# Agent Python Tools

- repo: facebookresearch/eai-vc
- repo_uri: https://github.com/facebookresearch/eai-vc

## File: facebookresearch_eai-vc/third_party/habitat2/habitat-baselines/habitat_baselines/il/data/data.py

Prompts

```
['build a PyTorch dataset for Embodied Q&A tasks using webdataset with frame caching and tar archive creation', 'create an EQADataset instance with config, input type, and frame count for VQA or PACMAN model training', 'review the EQADataset group_by_keys_ method that groups episode info and images into webdataset samples', 'refactor the EQADataset calc_max_length method to compute max question and action sequence lengths for padding', 'summarize the EQADataset save_frame_queue method that renders and saves episode frames to disk as JPEG images', 'create an EQACNNPretrainDataset instance with a Habitat config for training or validation mode', 'save rgb, depth, and semantic segmentation frames from shortest path positions to an LMDB database', 'load a new scene into the Habitat simulator by reconfiguring the environment with the scene path', 'retrieve a batch of rgb, depth, and segmentation tensors from the LMDB cache by index', 'check if the EQA-CNN pretrain dataset cache directory exists and contains data', 'create a NavDataset instance from a DictConfig, habitat.Env, and torch device for PACMAN navigation training', 'build a function that converts flat navigation actions into hierarchical planner and controller action sequences', 'run the map_dataset_sample method to preprocess a webdataset sample into planner and controller features', 'review the preprocess_actions method that transforms raw navigation actions into padded planner and controller tensors', 'summarize the get_img_features method that extracts CNN image features from a numpy array using a pretrained MultitaskCNN']
```

Usage

```
{'build_EQADataset': 'build a PyTorch dataset for Embodied Q&A tasks using webdataset with frame caching and tar archive creation', 'create_EQADataset_init': 'create an EQADataset instance with config, input type, and frame count for VQA or PACMAN model training', 'review_group_by_keys': 'review the EQADataset group_by_keys_ method that groups episode info and images into webdataset samples', 'refactor_calc_max_length': 'refactor the EQADataset calc_max_length method to compute max question and action sequence lengths for padding', 'summarize_save_frame_queue': 'summarize the EQADataset save_frame_queue method that renders and saves episode frames to disk as JPEG images'}
```

## File: facebookresearch_eai-vc/third_party/habitat2/habitat-baselines/habitat_baselines/il/data/eqa_cnn_pretrain_data.py

Prompts

```
['build a PyTorch dataset for Embodied Q&A tasks using webdataset with frame caching and tar archive creation', 'create an EQADataset instance with config, input type, and frame count for VQA or PACMAN model training', 'review the EQADataset group_by_keys_ method that groups episode info and images into webdataset samples', 'refactor the EQADataset calc_max_length method to compute max question and action sequence lengths for padding', 'summarize the EQADataset save_frame_queue method that renders and saves episode frames to disk as JPEG images', 'create an EQACNNPretrainDataset instance with a Habitat config for training or validation mode', 'save rgb, depth, and semantic segmentation frames from shortest path positions to an LMDB database', 'load a new scene into the Habitat simulator by reconfiguring the environment with the scene path', 'retrieve a batch of rgb, depth, and segmentation tensors from the LMDB cache by index', 'check if the EQA-CNN pretrain dataset cache directory exists and contains data', 'create a NavDataset instance from a DictConfig, habitat.Env, and torch device for PACMAN navigation training', 'build a function that converts flat navigation actions into hierarchical planner and controller action sequences', 'run the map_dataset_sample method to preprocess a webdataset sample into planner and controller features', 'review the preprocess_actions method that transforms raw navigation actions into padded planner and controller tensors', 'summarize the get_img_features method that extracts CNN image features from a numpy array using a pretrained MultitaskCNN']
```

Usage

```
{'create_EQACNNPretrainDataset': 'create an EQACNNPretrainDataset instance with a Habitat config for training or validation mode', 'save_frames_to_lmdb': 'save rgb, depth, and semantic segmentation frames from shortest path positions to an LMDB database', 'load_scene_in_simulator': 'load a new scene into the Habitat simulator by reconfiguring the environment with the scene path', 'getitem_rgb_depth_seg': 'retrieve a batch of rgb, depth, and segmentation tensors from the LMDB cache by index', 'cache_exists_check': 'check if the EQA-CNN pretrain dataset cache directory exists and contains data'}
```

## File: facebookresearch_eai-vc/third_party/habitat2/habitat-baselines/habitat_baselines/il/data/nav_data.py

Prompts

```
['build a PyTorch dataset for Embodied Q&A tasks using webdataset with frame caching and tar archive creation', 'create an EQADataset instance with config, input type, and frame count for VQA or PACMAN model training', 'review the EQADataset group_by_keys_ method that groups episode info and images into webdataset samples', 'refactor the EQADataset calc_max_length method to compute max question and action sequence lengths for padding', 'summarize the EQADataset save_frame_queue method that renders and saves episode frames to disk as JPEG images', 'create an EQACNNPretrainDataset instance with a Habitat config for training or validation mode', 'save rgb, depth, and semantic segmentation frames from shortest path positions to an LMDB database', 'load a new scene into the Habitat simulator by reconfiguring the environment with the scene path', 'retrieve a batch of rgb, depth, and segmentation tensors from the LMDB cache by index', 'check if the EQA-CNN pretrain dataset cache directory exists and contains data', 'create a NavDataset instance from a DictConfig, habitat.Env, and torch device for PACMAN navigation training', 'build a function that converts flat navigation actions into hierarchical planner and controller action sequences', 'run the map_dataset_sample method to preprocess a webdataset sample into planner and controller features', 'review the preprocess_actions method that transforms raw navigation actions into padded planner and controller tensors', 'summarize the get_img_features method that extracts CNN image features from a numpy array using a pretrained MultitaskCNN']
```

Usage

```
{'create_NavDataset': 'create a NavDataset instance from a DictConfig, habitat.Env, and torch device for PACMAN navigation training', 'build_flat_to_hierarchical_actions': 'build a function that converts flat navigation actions into hierarchical planner and controller action sequences', 'run_map_dataset_sample': 'run the map_dataset_sample method to preprocess a webdataset sample into planner and controller features', 'review_preprocess_actions': 'review the preprocess_actions method that transforms raw navigation actions into padded planner and controller tensors', 'summarize_get_img_features': 'summarize the get_img_features method that extracts CNN image features from a numpy array using a pretrained MultitaskCNN'}
```

