# Agent Python Tools

- repo: facebookresearch/habitat-lab
- repo_uri: https://github.com/facebookresearch/habitat-lab

## File: facebookresearch_habitat-lab/habitat-baselines/habitat_baselines/il/data/data.py

Prompts

```
['build a python module to create an EQADataset for embodied QA with VQA or PACMAN input types', 'review the EQADataset group_by_keys_ method that groups episode info and images into webdataset samples', 'test the EQADataset calc_max_length method to verify it calculates max question and action lengths for padding', 'refactor the EQADataset save_frame_queue method to render and save episode frames as JPEG images to disk', 'summarize the EQADataset get_frames method that reads frames from disk and returns normalized numpy arrays', 'create an EQACNNPretrainDataset instance with a Habitat config to cache RGB, depth, and segmentation frames into LMDB', 'build the EQACNNPretrainDataset cache by loading scenes and saving observation frames for each episode into an LMDB database', 'test the EQACNNPretrainDataset __getitem__ method to retrieve RGB, depth, and segmentation tensors by index from the LMDB cache', 'review the EQACNNPretrainDataset save_frames method that writes RGB, depth, and semantic segmentation frames to LMDB for each position', 'refactor the EQACNNPretrainDataset load_scene method to dynamically reconfigure the Habitat simulator with a new scene path', 'create a NavDataset instance from a DictConfig, habitat.Env, and torch device for PACMAN navigation', 'build a function to convert flat navigation actions into hierarchical planner and controller actions', 'extract image features from a numpy array using a pre-trained MultitaskCNN encoder', 'run preprocessing on navigation episodes to pad actions and compute hierarchical planner and controller sequences', 'review the map_dataset_sample method that preprocesses webdataset samples with image features and planner controller actions']
```

Usage

```
{'build_EQADataset': 'build a python module to create an EQADataset for embodied QA with VQA or PACMAN input types', 'review_EQADataset_group_by_keys': 'review the EQADataset group_by_keys_ method that groups episode info and images into webdataset samples', 'test_EQADataset_calc_max_length': 'test the EQADataset calc_max_length method to verify it calculates max question and action lengths for padding', 'refactor_EQADataset_save_frame_queue': 'refactor the EQADataset save_frame_queue method to render and save episode frames as JPEG images to disk', 'summarize_EQADataset_get_frames': 'summarize the EQADataset get_frames method that reads frames from disk and returns normalized numpy arrays'}
```

## File: facebookresearch_habitat-lab/habitat-baselines/habitat_baselines/il/data/eqa_cnn_pretrain_data.py

Prompts

```
['build a python module to create an EQADataset for embodied QA with VQA or PACMAN input types', 'review the EQADataset group_by_keys_ method that groups episode info and images into webdataset samples', 'test the EQADataset calc_max_length method to verify it calculates max question and action lengths for padding', 'refactor the EQADataset save_frame_queue method to render and save episode frames as JPEG images to disk', 'summarize the EQADataset get_frames method that reads frames from disk and returns normalized numpy arrays', 'create an EQACNNPretrainDataset instance with a Habitat config to cache RGB, depth, and segmentation frames into LMDB', 'build the EQACNNPretrainDataset cache by loading scenes and saving observation frames for each episode into an LMDB database', 'test the EQACNNPretrainDataset __getitem__ method to retrieve RGB, depth, and segmentation tensors by index from the LMDB cache', 'review the EQACNNPretrainDataset save_frames method that writes RGB, depth, and semantic segmentation frames to LMDB for each position', 'refactor the EQACNNPretrainDataset load_scene method to dynamically reconfigure the Habitat simulator with a new scene path', 'create a NavDataset instance from a DictConfig, habitat.Env, and torch device for PACMAN navigation', 'build a function to convert flat navigation actions into hierarchical planner and controller actions', 'extract image features from a numpy array using a pre-trained MultitaskCNN encoder', 'run preprocessing on navigation episodes to pad actions and compute hierarchical planner and controller sequences', 'review the map_dataset_sample method that preprocesses webdataset samples with image features and planner controller actions']
```

Usage

```
{'create_EQACNNPretrainDataset': 'create an EQACNNPretrainDataset instance with a Habitat config to cache RGB, depth, and segmentation frames into LMDB', 'build_EQACNNPretrainDataset_cache': 'build the EQACNNPretrainDataset cache by loading scenes and saving observation frames for each episode into an LMDB database', 'test_EQACNNPretrainDataset_getitem': 'test the EQACNNPretrainDataset __getitem__ method to retrieve RGB, depth, and segmentation tensors by index from the LMDB cache', 'review_EQACNNPretrainDataset_save_frames': 'review the EQACNNPretrainDataset save_frames method that writes RGB, depth, and semantic segmentation frames to LMDB for each position', 'refactor_EQACNNPretrainDataset_load_scene': 'refactor the EQACNNPretrainDataset load_scene method to dynamically reconfigure the Habitat simulator with a new scene path'}
```

## File: facebookresearch_habitat-lab/habitat-baselines/habitat_baselines/il/data/nav_data.py

Prompts

```
['build a python module to create an EQADataset for embodied QA with VQA or PACMAN input types', 'review the EQADataset group_by_keys_ method that groups episode info and images into webdataset samples', 'test the EQADataset calc_max_length method to verify it calculates max question and action lengths for padding', 'refactor the EQADataset save_frame_queue method to render and save episode frames as JPEG images to disk', 'summarize the EQADataset get_frames method that reads frames from disk and returns normalized numpy arrays', 'create an EQACNNPretrainDataset instance with a Habitat config to cache RGB, depth, and segmentation frames into LMDB', 'build the EQACNNPretrainDataset cache by loading scenes and saving observation frames for each episode into an LMDB database', 'test the EQACNNPretrainDataset __getitem__ method to retrieve RGB, depth, and segmentation tensors by index from the LMDB cache', 'review the EQACNNPretrainDataset save_frames method that writes RGB, depth, and semantic segmentation frames to LMDB for each position', 'refactor the EQACNNPretrainDataset load_scene method to dynamically reconfigure the Habitat simulator with a new scene path', 'create a NavDataset instance from a DictConfig, habitat.Env, and torch device for PACMAN navigation', 'build a function to convert flat navigation actions into hierarchical planner and controller actions', 'extract image features from a numpy array using a pre-trained MultitaskCNN encoder', 'run preprocessing on navigation episodes to pad actions and compute hierarchical planner and controller sequences', 'review the map_dataset_sample method that preprocesses webdataset samples with image features and planner controller actions']
```

Usage

```
{'create_NavDataset': 'create a NavDataset instance from a DictConfig, habitat.Env, and torch device for PACMAN navigation', 'build_flat_to_hierarchical_actions': 'build a function to convert flat navigation actions into hierarchical planner and controller actions', 'extract_get_img_features': 'extract image features from a numpy array using a pre-trained MultitaskCNN encoder', 'run_preprocess_actions': 'run preprocessing on navigation episodes to pad actions and compute hierarchical planner and controller sequences', 'review_map_dataset_sample': 'review the map_dataset_sample method that preprocesses webdataset samples with image features and planner controller actions'}
```

