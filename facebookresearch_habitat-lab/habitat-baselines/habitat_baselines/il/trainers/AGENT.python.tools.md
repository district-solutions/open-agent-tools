# Agent Python Tools

- repo: facebookresearch/habitat-lab
- repo_uri: https://github.com/facebookresearch/habitat-lab

## File: facebookresearch_habitat-lab/habitat-baselines/habitat_baselines/il/trainers/eqa_cnn_pretrain_trainer.py

Prompts

```
['run the EQACNNPretrainTrainer train method to pretrain the MultitaskCNN encoder-decoder model for EQA', 'run the EQACNNPretrainTrainer eval method to evaluate a saved checkpoint on the validation set', 'create an EQACNNPretrainTrainer instance with a Habitat config to setup the training device and logger', 'review the EQACNNPretrainTrainer _save_results method that saves RGB, segmentation, and depth reconstruction results', 'review the EQACNNPretrainTrainer _make_results_dir method that creates output directories for RGB, segmentation, and depth results', 'train the PACMAN navigation model for EmbodiedQA using the EQA-v0 task and Habitat environment', 'evaluate a PACMAN checkpoint on the validation split and log navigation metrics to TensorBoard', 'save navigation evaluation results as a video with question text overlaid on frames', 'review the PACMANTrainer planner and controller loss computation and backpropagation logic', 'summarize the PACMANTrainer hierarchical navigation loop with planner and controller action steps', 'train a VQA model using VQATrainer with an EQADataset and VqaLstmCnnAttentionModel', 'evaluate a VQA model checkpoint using VQATrainer._eval_checkpoint with tensorboard logging', 'save VQA evaluation results as images using VQATrainer._save_vqa_results with vocab dictionaries', 'create a results directory for VQA evaluation using VQATrainer._make_results_dir', 'review the VQATrainer class and its supported_tasks for VQA-v0 embodied question answering']
```

Usage

```
{'run_EQACNNPretrainTrainer_train': 'run the EQACNNPretrainTrainer train method to pretrain the MultitaskCNN encoder-decoder model for EQA', 'run_EQACNNPretrainTrainer_eval_checkpoint': 'run the EQACNNPretrainTrainer eval method to evaluate a saved checkpoint on the validation set', 'create_EQACNNPretrainTrainer': 'create an EQACNNPretrainTrainer instance with a Habitat config to setup the training device and logger', 'review_EQACNNPretrainTrainer_save_results': 'review the EQACNNPretrainTrainer _save_results method that saves RGB, segmentation, and depth reconstruction results', 'review_EQACNNPretrainTrainer_make_results_dir': 'review the EQACNNPretrainTrainer _make_results_dir method that creates output directories for RGB, segmentation, and depth results'}
```

## File: facebookresearch_habitat-lab/habitat-baselines/habitat_baselines/il/trainers/pacman_trainer.py

Prompts

```
['run the EQACNNPretrainTrainer train method to pretrain the MultitaskCNN encoder-decoder model for EQA', 'run the EQACNNPretrainTrainer eval method to evaluate a saved checkpoint on the validation set', 'create an EQACNNPretrainTrainer instance with a Habitat config to setup the training device and logger', 'review the EQACNNPretrainTrainer _save_results method that saves RGB, segmentation, and depth reconstruction results', 'review the EQACNNPretrainTrainer _make_results_dir method that creates output directories for RGB, segmentation, and depth results', 'train the PACMAN navigation model for EmbodiedQA using the EQA-v0 task and Habitat environment', 'evaluate a PACMAN checkpoint on the validation split and log navigation metrics to TensorBoard', 'save navigation evaluation results as a video with question text overlaid on frames', 'review the PACMANTrainer planner and controller loss computation and backpropagation logic', 'summarize the PACMANTrainer hierarchical navigation loop with planner and controller action steps', 'train a VQA model using VQATrainer with an EQADataset and VqaLstmCnnAttentionModel', 'evaluate a VQA model checkpoint using VQATrainer._eval_checkpoint with tensorboard logging', 'save VQA evaluation results as images using VQATrainer._save_vqa_results with vocab dictionaries', 'create a results directory for VQA evaluation using VQATrainer._make_results_dir', 'review the VQATrainer class and its supported_tasks for VQA-v0 embodied question answering']
```

Usage

```
{'train_PACMANTrainer': 'train the PACMAN navigation model for EmbodiedQA using the EQA-v0 task and Habitat environment', 'eval_PACMANTrainer_checkpoint': 'evaluate a PACMAN checkpoint on the validation split and log navigation metrics to TensorBoard', 'save_nav_results_video': 'save navigation evaluation results as a video with question text overlaid on frames', 'review_PACMANTrainer_planner_controller': 'review the PACMANTrainer planner and controller loss computation and backpropagation logic', 'summarize_PACMANTrainer_hierarchical_navigation': 'summarize the PACMANTrainer hierarchical navigation loop with planner and controller action steps'}
```

## File: facebookresearch_habitat-lab/habitat-baselines/habitat_baselines/il/trainers/vqa_trainer.py

Prompts

```
['run the EQACNNPretrainTrainer train method to pretrain the MultitaskCNN encoder-decoder model for EQA', 'run the EQACNNPretrainTrainer eval method to evaluate a saved checkpoint on the validation set', 'create an EQACNNPretrainTrainer instance with a Habitat config to setup the training device and logger', 'review the EQACNNPretrainTrainer _save_results method that saves RGB, segmentation, and depth reconstruction results', 'review the EQACNNPretrainTrainer _make_results_dir method that creates output directories for RGB, segmentation, and depth results', 'train the PACMAN navigation model for EmbodiedQA using the EQA-v0 task and Habitat environment', 'evaluate a PACMAN checkpoint on the validation split and log navigation metrics to TensorBoard', 'save navigation evaluation results as a video with question text overlaid on frames', 'review the PACMANTrainer planner and controller loss computation and backpropagation logic', 'summarize the PACMANTrainer hierarchical navigation loop with planner and controller action steps', 'train a VQA model using VQATrainer with an EQADataset and VqaLstmCnnAttentionModel', 'evaluate a VQA model checkpoint using VQATrainer._eval_checkpoint with tensorboard logging', 'save VQA evaluation results as images using VQATrainer._save_vqa_results with vocab dictionaries', 'create a results directory for VQA evaluation using VQATrainer._make_results_dir', 'review the VQATrainer class and its supported_tasks for VQA-v0 embodied question answering']
```

Usage

```
{'train_VQATrainer': 'train a VQA model using VQATrainer with an EQADataset and VqaLstmCnnAttentionModel', 'eval_VQATrainer_checkpoint': 'evaluate a VQA model checkpoint using VQATrainer._eval_checkpoint with tensorboard logging', 'save_VQATrainer_vqa_results': 'save VQA evaluation results as images using VQATrainer._save_vqa_results with vocab dictionaries', 'create_VQATrainer_results_dir': 'create a results directory for VQA evaluation using VQATrainer._make_results_dir', 'review_VQATrainer_class': 'review the VQATrainer class and its supported_tasks for VQA-v0 embodied question answering'}
```

