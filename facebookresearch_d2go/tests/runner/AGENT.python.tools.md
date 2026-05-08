# Agent Python Tools

- repo: facebookresearch/d2go
- repo_uri: https://github.com/facebookresearch/d2go

## File: facebookresearch_d2go/tests/runner/test_runner_default_runner.py

Prompts

```
['build a Detectron2Go model from config using Detectron2GoRunner build_model method', 'train a Detectron2Go model with do_train and resume support for checkpointing', 'test a trained Detectron2Go model and get COCO AP evaluation results', 'run Detectron2Go training with exponential moving average model weights enabled', 'run Detectron2Go quantization aware training with fbgemm or qnnpack backend', 'use rsetattr, rgetattr, and rhasattr to get, set, and check deeply nested object attributes by dot-path string', 'create a ModelTransform that runs a function on the model at a specific training step', 'create a ModelTransform that runs a function on the model at a fixed training interval', 'run QuantizationAwareTraining as a PyTorch Lightning callback to quantize a model during training with configurable start and freeze steps', 'run PostTrainingQuantization with static qconfig to quantize a trained model after fitting with calibration', 'create a GeneralizedRCNNTask instance from a CfgNode config for training with PyTorch Lightning', 'load a GeneralizedRCNNTask from a saved checkpoint file and compare model state dicts', 'build a detection model from config in eval-only mode with optional EMA weights', 'create a runner class dynamically from its fully qualified module path string', 'test quantization-aware training with a custom meta architecture using prepare_qat_fx and convert_fx']
```

Usage

```
{'build_d2go_model': 'build a Detectron2Go model from config using Detectron2GoRunner build_model method', 'train_d2go_model': 'train a Detectron2Go model with do_train and resume support for checkpointing', 'test_d2go_model': 'test a trained Detectron2Go model and get COCO AP evaluation results', 'run_d2go_ema_training': 'run Detectron2Go training with exponential moving average model weights enabled', 'run_d2go_qat_training': 'run Detectron2Go quantization aware training with fbgemm or qnnpack backend'}
```

## File: facebookresearch_d2go/tests/runner/test_runner_lightning_quantization.py

Prompts

```
['build a Detectron2Go model from config using Detectron2GoRunner build_model method', 'train a Detectron2Go model with do_train and resume support for checkpointing', 'test a trained Detectron2Go model and get COCO AP evaluation results', 'run Detectron2Go training with exponential moving average model weights enabled', 'run Detectron2Go quantization aware training with fbgemm or qnnpack backend', 'use rsetattr, rgetattr, and rhasattr to get, set, and check deeply nested object attributes by dot-path string', 'create a ModelTransform that runs a function on the model at a specific training step', 'create a ModelTransform that runs a function on the model at a fixed training interval', 'run QuantizationAwareTraining as a PyTorch Lightning callback to quantize a model during training with configurable start and freeze steps', 'run PostTrainingQuantization with static qconfig to quantize a trained model after fitting with calibration', 'create a GeneralizedRCNNTask instance from a CfgNode config for training with PyTorch Lightning', 'load a GeneralizedRCNNTask from a saved checkpoint file and compare model state dicts', 'build a detection model from config in eval-only mode with optional EMA weights', 'create a runner class dynamically from its fully qualified module path string', 'test quantization-aware training with a custom meta architecture using prepare_qat_fx and convert_fx']
```

Usage

```
{'use_rsetattr_rgetattr_rhasattr': 'use rsetattr, rgetattr, and rhasattr to get, set, and check deeply nested object attributes by dot-path string', 'create_ModelTransform_with_step': 'create a ModelTransform that runs a function on the model at a specific training step', 'create_ModelTransform_with_interval': 'create a ModelTransform that runs a function on the model at a fixed training interval', 'run_QuantizationAwareTraining_callback': 'run QuantizationAwareTraining as a PyTorch Lightning callback to quantize a model during training with configurable start and freeze steps', 'run_PostTrainingQuantization_static': 'run PostTrainingQuantization with static qconfig to quantize a trained model after fitting with calibration'}
```

## File: facebookresearch_d2go/tests/runner/test_runner_lightning_task.py

Prompts

```
['build a Detectron2Go model from config using Detectron2GoRunner build_model method', 'train a Detectron2Go model with do_train and resume support for checkpointing', 'test a trained Detectron2Go model and get COCO AP evaluation results', 'run Detectron2Go training with exponential moving average model weights enabled', 'run Detectron2Go quantization aware training with fbgemm or qnnpack backend', 'use rsetattr, rgetattr, and rhasattr to get, set, and check deeply nested object attributes by dot-path string', 'create a ModelTransform that runs a function on the model at a specific training step', 'create a ModelTransform that runs a function on the model at a fixed training interval', 'run QuantizationAwareTraining as a PyTorch Lightning callback to quantize a model during training with configurable start and freeze steps', 'run PostTrainingQuantization with static qconfig to quantize a trained model after fitting with calibration', 'create a GeneralizedRCNNTask instance from a CfgNode config for training with PyTorch Lightning', 'load a GeneralizedRCNNTask from a saved checkpoint file and compare model state dicts', 'build a detection model from config in eval-only mode with optional EMA weights', 'create a runner class dynamically from its fully qualified module path string', 'test quantization-aware training with a custom meta architecture using prepare_qat_fx and convert_fx']
```

Usage

```
{'create_GeneralizedRCNNTask_from_cfg': 'create a GeneralizedRCNNTask instance from a CfgNode config for training with PyTorch Lightning', 'load_GeneralizedRCNNTask_from_checkpoint': 'load a GeneralizedRCNNTask from a saved checkpoint file and compare model state dicts', 'build_model_eval_only': 'build a detection model from config in eval-only mode with optional EMA weights', 'create_runner_from_module_path': 'create a runner class dynamically from its fully qualified module path string', 'test_quantization_aware_training': 'test quantization-aware training with a custom meta architecture using prepare_qat_fx and convert_fx'}
```

