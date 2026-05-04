# Agent Python Tools

- repo: facebookresearch/eai-vc
- repo_uri: https://github.com/facebookresearch/eai-vc

## File: facebookresearch_eai-vc/third_party/habitat2/habitat-baselines/habitat_baselines/il/trainers/eqa_cnn_pretrain_trainer.py

Prompts

```
['train the EQACNNPretrainTrainer to pre-train a MultitaskCNN encoder-decoder for EQA feature extraction', 'evaluate an EQACNNPretrainTrainer checkpoint on the validation set and log loss metrics to TensorBoard', 'save EQA-CNN reconstruction results including RGB, segmentation, and depth map outputs to disk', 'create result directories for RGB, segmentation, and depth outputs for EQA-CNN pretrain evaluation', 'review the EQACNNPretrainTrainer multitask loss computation combining segmentation, autoencoder, and depth losses', 'train the PACMAN navigation model for EmbodiedQA with planner and controller loss over multiple epochs', 'evaluate a PACMAN checkpoint by running navigation episodes and computing distance metrics', 'save navigation evaluation results as videos with question text overlaid on frames', 'review the PACMANTrainer init method to understand device setup and config handling', 'summarize the PACMANTrainer class for training EmbodiedQA navigation models with hierarchical planner and controller', 'train a VQA model using VQATrainer.train() with an EQADataset and VqaLstmCnnAttentionModel', 'evaluate a VQA model checkpoint using VQATrainer._eval_checkpoint() with a TensorboardWriter', 'save VQA evaluation results as images using VQATrainer._save_vqa_results() with episode data', 'create a VQATrainer instance with a config to set up device and logging', 'review the VQATrainer class and its supported_tasks for VQA-v0 embodied question answering']
```

Usage

```
{'train_EQACNNPretrainTrainer': 'train the EQACNNPretrainTrainer to pre-train a MultitaskCNN encoder-decoder for EQA feature extraction', 'eval_EQACNNPretrainTrainer_checkpoint': 'evaluate an EQACNNPretrainTrainer checkpoint on the validation set and log loss metrics to TensorBoard', 'save_EQACNNPretrainTrainer_results': 'save EQA-CNN reconstruction results including RGB, segmentation, and depth map outputs to disk', 'create_EQACNNPretrainTrainer_results_dir': 'create result directories for RGB, segmentation, and depth outputs for EQA-CNN pretrain evaluation', 'review_EQACNNPretrainTrainer_multitask_loss': 'review the EQACNNPretrainTrainer multitask loss computation combining segmentation, autoencoder, and depth losses'}
```

## File: facebookresearch_eai-vc/third_party/habitat2/habitat-baselines/habitat_baselines/il/trainers/pacman_trainer.py

Prompts

```
['train the EQACNNPretrainTrainer to pre-train a MultitaskCNN encoder-decoder for EQA feature extraction', 'evaluate an EQACNNPretrainTrainer checkpoint on the validation set and log loss metrics to TensorBoard', 'save EQA-CNN reconstruction results including RGB, segmentation, and depth map outputs to disk', 'create result directories for RGB, segmentation, and depth outputs for EQA-CNN pretrain evaluation', 'review the EQACNNPretrainTrainer multitask loss computation combining segmentation, autoencoder, and depth losses', 'train the PACMAN navigation model for EmbodiedQA with planner and controller loss over multiple epochs', 'evaluate a PACMAN checkpoint by running navigation episodes and computing distance metrics', 'save navigation evaluation results as videos with question text overlaid on frames', 'review the PACMANTrainer init method to understand device setup and config handling', 'summarize the PACMANTrainer class for training EmbodiedQA navigation models with hierarchical planner and controller', 'train a VQA model using VQATrainer.train() with an EQADataset and VqaLstmCnnAttentionModel', 'evaluate a VQA model checkpoint using VQATrainer._eval_checkpoint() with a TensorboardWriter', 'save VQA evaluation results as images using VQATrainer._save_vqa_results() with episode data', 'create a VQATrainer instance with a config to set up device and logging', 'review the VQATrainer class and its supported_tasks for VQA-v0 embodied question answering']
```

Usage

```
{'train_PACMANTrainer': 'train the PACMAN navigation model for EmbodiedQA with planner and controller loss over multiple epochs', 'eval_checkpoint_PACMANTrainer': 'evaluate a PACMAN checkpoint by running navigation episodes and computing distance metrics', 'save_nav_results_PACMANTrainer': 'save navigation evaluation results as videos with question text overlaid on frames', 'review_PACMANTrainer_init': 'review the PACMANTrainer init method to understand device setup and config handling', 'summarize_PACMANTrainer': 'summarize the PACMANTrainer class for training EmbodiedQA navigation models with hierarchical planner and controller'}
```

## File: facebookresearch_eai-vc/third_party/habitat2/habitat-baselines/habitat_baselines/il/trainers/vqa_trainer.py

Prompts

```
['train the EQACNNPretrainTrainer to pre-train a MultitaskCNN encoder-decoder for EQA feature extraction', 'evaluate an EQACNNPretrainTrainer checkpoint on the validation set and log loss metrics to TensorBoard', 'save EQA-CNN reconstruction results including RGB, segmentation, and depth map outputs to disk', 'create result directories for RGB, segmentation, and depth outputs for EQA-CNN pretrain evaluation', 'review the EQACNNPretrainTrainer multitask loss computation combining segmentation, autoencoder, and depth losses', 'train the PACMAN navigation model for EmbodiedQA with planner and controller loss over multiple epochs', 'evaluate a PACMAN checkpoint by running navigation episodes and computing distance metrics', 'save navigation evaluation results as videos with question text overlaid on frames', 'review the PACMANTrainer init method to understand device setup and config handling', 'summarize the PACMANTrainer class for training EmbodiedQA navigation models with hierarchical planner and controller', 'train a VQA model using VQATrainer.train() with an EQADataset and VqaLstmCnnAttentionModel', 'evaluate a VQA model checkpoint using VQATrainer._eval_checkpoint() with a TensorboardWriter', 'save VQA evaluation results as images using VQATrainer._save_vqa_results() with episode data', 'create a VQATrainer instance with a config to set up device and logging', 'review the VQATrainer class and its supported_tasks for VQA-v0 embodied question answering']
```

Usage

```
{'train_VQATrainer': 'train a VQA model using VQATrainer.train() with an EQADataset and VqaLstmCnnAttentionModel', 'eval_VQATrainer_checkpoint': 'evaluate a VQA model checkpoint using VQATrainer._eval_checkpoint() with a TensorboardWriter', 'save_VQATrainer_vqa_results': 'save VQA evaluation results as images using VQATrainer._save_vqa_results() with episode data', 'create_VQATrainer_instance': 'create a VQATrainer instance with a config to set up device and logging', 'review_VQATrainer_class': 'review the VQATrainer class and its supported_tasks for VQA-v0 embodied question answering'}
```

