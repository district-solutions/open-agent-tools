# Agent Python Tools

- repo: facebookresearch/imvotenet
- repo_uri: https://github.com/facebookresearch/imvotenet

## File: facebookresearch_imvotenet/eval.py

Prompts

```
['run the VoteNet 3D object detection evaluation on SUN RGB-D validation set with a checkpoint', 'run the ImVoteNet evaluation with RGB image votes on SUN RGB-D validation set', 'evaluate one epoch of 3D object detection predictions and compute average precision metrics', 'run faster evaluation by skipping empty bounding box removal during 3D detection', 'run evaluation with 3D NMS and configurable IoU threshold for object detection', 'run the ImVoteNet training routine on SUN RGB-D with python train.py --use_imvotenet --log_dir log_imvotenet', 'run the VoteNet training routine on SUN RGB-D with python train.py --log_dir log_votenet', 'resume training from a checkpoint with python train.py --checkpoint_path checkpoint.tar --log_dir log', 'run training and monitor with tensorboard using python train.py --use_imvotenet --log_dir log_imvotenet', 'run training with custom batch size, learning rate, and max epochs via argparse flags']
```

Usage

```
{'run_evaluation_votenet': 'run the VoteNet 3D object detection evaluation on SUN RGB-D validation set with a checkpoint', 'run_evaluation_imvotenet': 'run the ImVoteNet evaluation with RGB image votes on SUN RGB-D validation set', 'evaluate_one_epoch': 'evaluate one epoch of 3D object detection predictions and compute average precision metrics', 'run_faster_evaluation': 'run faster evaluation by skipping empty bounding box removal during 3D detection', 'run_evaluation_with_nms': 'run evaluation with 3D NMS and configurable IoU threshold for object detection'}
```

## File: facebookresearch_imvotenet/train.py

Prompts

```
['run the VoteNet 3D object detection evaluation on SUN RGB-D validation set with a checkpoint', 'run the ImVoteNet evaluation with RGB image votes on SUN RGB-D validation set', 'evaluate one epoch of 3D object detection predictions and compute average precision metrics', 'run faster evaluation by skipping empty bounding box removal during 3D detection', 'run evaluation with 3D NMS and configurable IoU threshold for object detection', 'run the ImVoteNet training routine on SUN RGB-D with python train.py --use_imvotenet --log_dir log_imvotenet', 'run the VoteNet training routine on SUN RGB-D with python train.py --log_dir log_votenet', 'resume training from a checkpoint with python train.py --checkpoint_path checkpoint.tar --log_dir log', 'run training and monitor with tensorboard using python train.py --use_imvotenet --log_dir log_imvotenet', 'run training with custom batch size, learning rate, and max epochs via argparse flags']
```

Usage

```
{'run_train_imvotenet': 'run the ImVoteNet training routine on SUN RGB-D with python train.py --use_imvotenet --log_dir log_imvotenet', 'run_train_votenet': 'run the VoteNet training routine on SUN RGB-D with python train.py --log_dir log_votenet', 'run_train_resume_checkpoint': 'resume training from a checkpoint with python train.py --checkpoint_path checkpoint.tar --log_dir log', 'run_train_with_tensorboard': 'run training and monitor with tensorboard using python train.py --use_imvotenet --log_dir log_imvotenet', 'run_train_custom_config': 'run training with custom batch size, learning rate, and max epochs via argparse flags'}
```

