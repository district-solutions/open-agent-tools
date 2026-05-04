# Agent Python Tools

- repo: facebookresearch/eai-vc
- repo_uri: https://github.com/facebookresearch/eai-vc

## File: facebookresearch_eai-vc/cortexbench/habitat_vc/habitat_vc/config.py

Prompts

```
['get a Habitat task config object with optional YAML file paths and override options', 'get a full Habitat baselines training config with merged YAML files and command line options', 'customize the SimpleReward parameters like success_reward and slack_penalty in the task config', 'configure the RGB encoder backbone, image size, and augmentation settings in the model config', 'set PPO hyperparameters like learning rate, clip param, and gamma in the RL config', 'initialize a wandb run with config settings for training or evaluation mode', 'list and return the next checkpoint file from a folder sorted by modification time', 'convert habitat environment observation dicts and info into a single rendered image frame', 'create a video from a list of image frames and log it to disk or wandb', 'overlay navigation metrics like distance to goal and success rate onto an image frame', 'create a VisualEncoder with a ResNet backbone config and default 128x128 image size', 'create a VisualEncoder with a ViT or BEiT backbone config and global pooling enabled', 'run the VisualEncoder forward pass on a torch tensor to get compressed visual features', 'get the backbone model, embedding dimension, and visual transform from an existing VisualEncoder instance', 'review the VisualEncoder init to understand ResNet vs ViT backbone branching and compression layer setup']
```

Usage

```
{'get_task_config': 'get a Habitat task config object with optional YAML file paths and override options', 'get_config': 'get a full Habitat baselines training config with merged YAML files and command line options', 'customize_task_reward': 'customize the SimpleReward parameters like success_reward and slack_penalty in the task config', 'configure_rgb_encoder': 'configure the RGB encoder backbone, image size, and augmentation settings in the model config', 'set_ppo_hyperparams': 'set PPO hyperparameters like learning rate, clip param, and gamma in the RL config'}
```

## File: facebookresearch_eai-vc/cortexbench/habitat_vc/habitat_vc/utils.py

Prompts

```
['get a Habitat task config object with optional YAML file paths and override options', 'get a full Habitat baselines training config with merged YAML files and command line options', 'customize the SimpleReward parameters like success_reward and slack_penalty in the task config', 'configure the RGB encoder backbone, image size, and augmentation settings in the model config', 'set PPO hyperparameters like learning rate, clip param, and gamma in the RL config', 'initialize a wandb run with config settings for training or evaluation mode', 'list and return the next checkpoint file from a folder sorted by modification time', 'convert habitat environment observation dicts and info into a single rendered image frame', 'create a video from a list of image frames and log it to disk or wandb', 'overlay navigation metrics like distance to goal and success rate onto an image frame', 'create a VisualEncoder with a ResNet backbone config and default 128x128 image size', 'create a VisualEncoder with a ViT or BEiT backbone config and global pooling enabled', 'run the VisualEncoder forward pass on a torch tensor to get compressed visual features', 'get the backbone model, embedding dimension, and visual transform from an existing VisualEncoder instance', 'review the VisualEncoder init to understand ResNet vs ViT backbone branching and compression layer setup']
```

Usage

```
{'setup_wandb': 'initialize a wandb run with config settings for training or evaluation mode', 'poll_checkpoint_folder': 'list and return the next checkpoint file from a folder sorted by modification time', 'observations_to_image': 'convert habitat environment observation dicts and info into a single rendered image frame', 'generate_video': 'create a video from a list of image frames and log it to disk or wandb', 'add_info_to_image': 'overlay navigation metrics like distance to goal and success rate onto an image frame'}
```

## File: facebookresearch_eai-vc/cortexbench/habitat_vc/habitat_vc/visual_encoder.py

Prompts

```
['get a Habitat task config object with optional YAML file paths and override options', 'get a full Habitat baselines training config with merged YAML files and command line options', 'customize the SimpleReward parameters like success_reward and slack_penalty in the task config', 'configure the RGB encoder backbone, image size, and augmentation settings in the model config', 'set PPO hyperparameters like learning rate, clip param, and gamma in the RL config', 'initialize a wandb run with config settings for training or evaluation mode', 'list and return the next checkpoint file from a folder sorted by modification time', 'convert habitat environment observation dicts and info into a single rendered image frame', 'create a video from a list of image frames and log it to disk or wandb', 'overlay navigation metrics like distance to goal and success rate onto an image frame', 'create a VisualEncoder with a ResNet backbone config and default 128x128 image size', 'create a VisualEncoder with a ViT or BEiT backbone config and global pooling enabled', 'run the VisualEncoder forward pass on a torch tensor to get compressed visual features', 'get the backbone model, embedding dimension, and visual transform from an existing VisualEncoder instance', 'review the VisualEncoder init to understand ResNet vs ViT backbone branching and compression layer setup']
```

Usage

```
{'create_visual_encoder_with_resnet': 'create a VisualEncoder with a ResNet backbone config and default 128x128 image size', 'create_visual_encoder_with_vit': 'create a VisualEncoder with a ViT or BEiT backbone config and global pooling enabled', 'run_visual_encoder_forward': 'run the VisualEncoder forward pass on a torch tensor to get compressed visual features', 'get_loaded_backbone_data': 'get the backbone model, embedding dimension, and visual transform from an existing VisualEncoder instance', 'review_visual_encoder_init': 'review the VisualEncoder init to understand ResNet vs ViT backbone branching and compression layer setup'}
```

