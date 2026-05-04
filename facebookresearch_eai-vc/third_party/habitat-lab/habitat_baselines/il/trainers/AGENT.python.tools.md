# Agent Python Tools

- repo: facebookresearch/eai-vc
- repo_uri: https://github.com/facebookresearch/eai-vc

## File: facebookresearch_eai-vc/third_party/habitat-lab/habitat_baselines/il/trainers/eqa_cnn_pretrain_trainer.py

Prompts

```
['run the EQACNNPretrainTrainer train method to pre-train the MultitaskCNN encoder-decoder model for EQA feature extraction', 'run the EQACNNPretrainTrainer _eval_checkpoint method to evaluate a saved checkpoint on the validation dataset', 'create an EQACNNPretrainTrainer instance with a config to set up the device and logging for EQA pre-training', 'review the EQACNNPretrainTrainer _save_results method that saves RGB, segmentation, and depth reconstruction results', 'review the EQACNNPretrainTrainer _make_results_dir method that creates output directories for RGB, segmentation, and depth results', 'train the PACMAN navigation model for EmbodiedQA using the EQA-v0 task and config', 'evaluate a PACMAN checkpoint on the validation split and log navigation metrics', 'save PACMAN navigation evaluation results as a video with question text overlaid on frames', 'review the PACMANTrainer planner and controller loss computation and backpropagation logic', 'refactor the PACMANTrainer eval loop to support custom action length thresholds and metrics', 'train a VQA model using VQATrainer.train() with an EQADataset and LSTM-CNN attention architecture', 'evaluate a VQA model checkpoint using VQATrainer._eval_checkpoint() and log metrics to TensorBoard', 'save VQA evaluation results as images using VQATrainer._save_vqa_results() with predicted and ground truth answers', 'create a results directory for VQA evaluation output using VQATrainer._make_results_dir()', 'review the VQATrainer class for VQA model training, evaluation, and result saving in Habitat Baselines']
```

Usage

```
{'run_EQACNNPretrainTrainer_train': 'run the EQACNNPretrainTrainer train method to pre-train the MultitaskCNN encoder-decoder model for EQA feature extraction', 'run_EQACNNPretrainTrainer_eval_checkpoint': 'run the EQACNNPretrainTrainer _eval_checkpoint method to evaluate a saved checkpoint on the validation dataset', 'create_EQACNNPretrainTrainer': 'create an EQACNNPretrainTrainer instance with a config to set up the device and logging for EQA pre-training', 'review_EQACNNPretrainTrainer_save_results': 'review the EQACNNPretrainTrainer _save_results method that saves RGB, segmentation, and depth reconstruction results', 'review_EQACNNPretrainTrainer_make_results_dir': 'review the EQACNNPretrainTrainer _make_results_dir method that creates output directories for RGB, segmentation, and depth results'}
```

## File: facebookresearch_eai-vc/third_party/habitat-lab/habitat_baselines/il/trainers/pacman_trainer.py

Prompts

```
['run the EQACNNPretrainTrainer train method to pre-train the MultitaskCNN encoder-decoder model for EQA feature extraction', 'run the EQACNNPretrainTrainer _eval_checkpoint method to evaluate a saved checkpoint on the validation dataset', 'create an EQACNNPretrainTrainer instance with a config to set up the device and logging for EQA pre-training', 'review the EQACNNPretrainTrainer _save_results method that saves RGB, segmentation, and depth reconstruction results', 'review the EQACNNPretrainTrainer _make_results_dir method that creates output directories for RGB, segmentation, and depth results', 'train the PACMAN navigation model for EmbodiedQA using the EQA-v0 task and config', 'evaluate a PACMAN checkpoint on the validation split and log navigation metrics', 'save PACMAN navigation evaluation results as a video with question text overlaid on frames', 'review the PACMANTrainer planner and controller loss computation and backpropagation logic', 'refactor the PACMANTrainer eval loop to support custom action length thresholds and metrics', 'train a VQA model using VQATrainer.train() with an EQADataset and LSTM-CNN attention architecture', 'evaluate a VQA model checkpoint using VQATrainer._eval_checkpoint() and log metrics to TensorBoard', 'save VQA evaluation results as images using VQATrainer._save_vqa_results() with predicted and ground truth answers', 'create a results directory for VQA evaluation output using VQATrainer._make_results_dir()', 'review the VQATrainer class for VQA model training, evaluation, and result saving in Habitat Baselines']
```

Usage

```
{'train_PACMANTrainer': 'train the PACMAN navigation model for EmbodiedQA using the EQA-v0 task and config', 'eval_PACMANTrainer_checkpoint': 'evaluate a PACMAN checkpoint on the validation split and log navigation metrics', 'save_nav_results_video': 'save PACMAN navigation evaluation results as a video with question text overlaid on frames', 'review_PACMANTrainer_planner_controller': 'review the PACMANTrainer planner and controller loss computation and backpropagation logic', 'refactor_PACMANTrainer_eval_loop': 'refactor the PACMANTrainer eval loop to support custom action length thresholds and metrics'}
```

## File: facebookresearch_eai-vc/third_party/habitat-lab/habitat_baselines/il/trainers/vqa_trainer.py

Prompts

```
['run the EQACNNPretrainTrainer train method to pre-train the MultitaskCNN encoder-decoder model for EQA feature extraction', 'run the EQACNNPretrainTrainer _eval_checkpoint method to evaluate a saved checkpoint on the validation dataset', 'create an EQACNNPretrainTrainer instance with a config to set up the device and logging for EQA pre-training', 'review the EQACNNPretrainTrainer _save_results method that saves RGB, segmentation, and depth reconstruction results', 'review the EQACNNPretrainTrainer _make_results_dir method that creates output directories for RGB, segmentation, and depth results', 'train the PACMAN navigation model for EmbodiedQA using the EQA-v0 task and config', 'evaluate a PACMAN checkpoint on the validation split and log navigation metrics', 'save PACMAN navigation evaluation results as a video with question text overlaid on frames', 'review the PACMANTrainer planner and controller loss computation and backpropagation logic', 'refactor the PACMANTrainer eval loop to support custom action length thresholds and metrics', 'train a VQA model using VQATrainer.train() with an EQADataset and LSTM-CNN attention architecture', 'evaluate a VQA model checkpoint using VQATrainer._eval_checkpoint() and log metrics to TensorBoard', 'save VQA evaluation results as images using VQATrainer._save_vqa_results() with predicted and ground truth answers', 'create a results directory for VQA evaluation output using VQATrainer._make_results_dir()', 'review the VQATrainer class for VQA model training, evaluation, and result saving in Habitat Baselines']
```

Usage

```
{'train_VQATrainer': 'train a VQA model using VQATrainer.train() with an EQADataset and LSTM-CNN attention architecture', 'eval_VQATrainer_checkpoint': 'evaluate a VQA model checkpoint using VQATrainer._eval_checkpoint() and log metrics to TensorBoard', 'save_VQATrainer_vqa_results': 'save VQA evaluation results as images using VQATrainer._save_vqa_results() with predicted and ground truth answers', 'create_VQATrainer_results_dir': 'create a results directory for VQA evaluation output using VQATrainer._make_results_dir()', 'review_VQATrainer_class': 'review the VQATrainer class for VQA model training, evaluation, and result saving in Habitat Baselines'}
```

