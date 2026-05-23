# Agent Python Tools

- repo: facebookresearch/partnr-planner
- repo_uri: https://github.com/facebookresearch/partnr-planner

## File: facebookresearch_partnr-planner/third_party/habitat-lab/habitat-baselines/habitat_baselines/il/data/data.py

Prompts

```
['create an EQADataset instance with config and input_type for embodied Q&A training', 'build a webdataset pipeline using group_by_keys_ to group episode info and images', 'run calc_max_length to calculate max question and action lengths for padding', 'save an episode frame queue to disk using save_frame_queue with position data', 'fetch frames from disk using get_frames with a frames path and num parameter', 'create an EQACNNPretrainDataset instance with a Habitat config to cache RGB, depth, and segmentation frames in LMDB', 'save RGB, depth, and semantic segmentation frames from shortest path positions into an LMDB database', 'load a Habitat scene by reconfiguring the simulator with a new scene path for episode processing', 'retrieve a dataset sample by index returning RGB, depth, and segmentation tensors from the LMDB cache', 'check if the EQA-CNN pretrain dataset cache directory exists and contains entries before building', 'create a NavDataset instance with config, habitat environment, and device for PACMAN navigation training', 'build a function that converts flat action sequences into hierarchical planner and controller actions', 'test the get_img_features method to extract CNN features from navigation observation images', 'refactor the preprocess_actions method to transform episode actions into padded planner and controller tensors', 'review the map_dataset_sample method that preprocesses webdataset samples with image features and action sequences']
```

Usage

```
{'create_EQADataset': 'create an EQADataset instance with config and input_type for embodied Q&A training', 'build_group_by_keys_pipeline': 'build a webdataset pipeline using group_by_keys_ to group episode info and images', 'run_calc_max_length': 'run calc_max_length to calculate max question and action lengths for padding', 'save_frame_queue': 'save an episode frame queue to disk using save_frame_queue with position data', 'fetch_frames_with_get_frames': 'fetch frames from disk using get_frames with a frames path and num parameter'}
```

## File: facebookresearch_partnr-planner/third_party/habitat-lab/habitat-baselines/habitat_baselines/il/data/eqa_cnn_pretrain_data.py

Prompts

```
['create an EQADataset instance with config and input_type for embodied Q&A training', 'build a webdataset pipeline using group_by_keys_ to group episode info and images', 'run calc_max_length to calculate max question and action lengths for padding', 'save an episode frame queue to disk using save_frame_queue with position data', 'fetch frames from disk using get_frames with a frames path and num parameter', 'create an EQACNNPretrainDataset instance with a Habitat config to cache RGB, depth, and segmentation frames in LMDB', 'save RGB, depth, and semantic segmentation frames from shortest path positions into an LMDB database', 'load a Habitat scene by reconfiguring the simulator with a new scene path for episode processing', 'retrieve a dataset sample by index returning RGB, depth, and segmentation tensors from the LMDB cache', 'check if the EQA-CNN pretrain dataset cache directory exists and contains entries before building', 'create a NavDataset instance with config, habitat environment, and device for PACMAN navigation training', 'build a function that converts flat action sequences into hierarchical planner and controller actions', 'test the get_img_features method to extract CNN features from navigation observation images', 'refactor the preprocess_actions method to transform episode actions into padded planner and controller tensors', 'review the map_dataset_sample method that preprocesses webdataset samples with image features and action sequences']
```

Usage

```
{'create_EQACNNPretrainDataset': 'create an EQACNNPretrainDataset instance with a Habitat config to cache RGB, depth, and segmentation frames in LMDB', 'save_frames_to_lmdb': 'save RGB, depth, and semantic segmentation frames from shortest path positions into an LMDB database', 'load_scene_for_episodes': 'load a Habitat scene by reconfiguring the simulator with a new scene path for episode processing', 'getitem_dataset_sample': 'retrieve a dataset sample by index returning RGB, depth, and segmentation tensors from the LMDB cache', 'check_cache_exists': 'check if the EQA-CNN pretrain dataset cache directory exists and contains entries before building'}
```

## File: facebookresearch_partnr-planner/third_party/habitat-lab/habitat-baselines/habitat_baselines/il/data/nav_data.py

Prompts

```
['create an EQADataset instance with config and input_type for embodied Q&A training', 'build a webdataset pipeline using group_by_keys_ to group episode info and images', 'run calc_max_length to calculate max question and action lengths for padding', 'save an episode frame queue to disk using save_frame_queue with position data', 'fetch frames from disk using get_frames with a frames path and num parameter', 'create an EQACNNPretrainDataset instance with a Habitat config to cache RGB, depth, and segmentation frames in LMDB', 'save RGB, depth, and semantic segmentation frames from shortest path positions into an LMDB database', 'load a Habitat scene by reconfiguring the simulator with a new scene path for episode processing', 'retrieve a dataset sample by index returning RGB, depth, and segmentation tensors from the LMDB cache', 'check if the EQA-CNN pretrain dataset cache directory exists and contains entries before building', 'create a NavDataset instance with config, habitat environment, and device for PACMAN navigation training', 'build a function that converts flat action sequences into hierarchical planner and controller actions', 'test the get_img_features method to extract CNN features from navigation observation images', 'refactor the preprocess_actions method to transform episode actions into padded planner and controller tensors', 'review the map_dataset_sample method that preprocesses webdataset samples with image features and action sequences']
```

Usage

```
{'create_NavDataset': 'create a NavDataset instance with config, habitat environment, and device for PACMAN navigation training', 'build_flat_to_hierarchical_actions': 'build a function that converts flat action sequences into hierarchical planner and controller actions', 'test_get_img_features': 'test the get_img_features method to extract CNN features from navigation observation images', 'refactor_preprocess_actions': 'refactor the preprocess_actions method to transform episode actions into padded planner and controller tensors', 'review_map_dataset_sample': 'review the map_dataset_sample method that preprocesses webdataset samples with image features and action sequences'}
```

