# Agent Python Tools

- repo: facebookresearch/pyrobot
- repo_uri: https://github.com/facebookresearch/pyrobot

## File: facebookresearch_pyrobot/examples/crash_detection/crash_utils/model.py

Prompts

```
['build a CrashDetectorNet model with pretrained ResNet18 weights for binary crash classification', 'run forward inference on input tensor x through the CrashDetectorNet model to get crash probabilities', 'create a CrashDetectorNet model without pretrained weights by setting pretrained_resnet18 to False', 'review the CrashDetectorNet forward pass that extracts features and applies softmax for crash prediction', 'summarize the CrashDetectorNet architecture using ResNet18 backbone with a custom two-layer classifier head', 'run the crash detection model on an image using --model_path and --image_path CLI arguments', 'test a PyTorch model on an image using the Tester class test method', 'convert a raw image to PIL crops and PyTorch tensors using Tester convert_to_PIL method', 'review the torchvision transform pipeline that resizes to 224x224 and normalizes with ImageNet stats', 'refactor the Tester convert_to_PIL method to crop center, left, right regions and stack as a batch tensor', 'run the Trainer class to train a CrashDetectorNet model for N epochs with TensorBoard logging', 'run the main CLI to train a drone crash detection model with configurable epochs and train fraction', 'create a Trainer instance with a CSV filename and train/test split fraction for drone crash data', 'test the Trainer create_model method to instantiate and optionally move CrashDetectorNet to GPU', 'review the train_model method that performs training and testing loops with checkpoint saving and metrics tracking']
```

Usage

```
{'build_crash_detector_model': 'build a CrashDetectorNet model with pretrained ResNet18 weights for binary crash classification', 'run_crash_detection_inference': 'run forward inference on input tensor x through the CrashDetectorNet model to get crash probabilities', 'create_crash_detector_without_pretrained': 'create a CrashDetectorNet model without pretrained weights by setting pretrained_resnet18 to False', 'review_crash_detector_forward_pass': 'review the CrashDetectorNet forward pass that extracts features and applies softmax for crash prediction', 'summarize_crash_detector_architecture': 'summarize the CrashDetectorNet architecture using ResNet18 backbone with a custom two-layer classifier head'}
```

## File: facebookresearch_pyrobot/examples/crash_detection/crash_utils/test.py

Prompts

```
['build a CrashDetectorNet model with pretrained ResNet18 weights for binary crash classification', 'run forward inference on input tensor x through the CrashDetectorNet model to get crash probabilities', 'create a CrashDetectorNet model without pretrained weights by setting pretrained_resnet18 to False', 'review the CrashDetectorNet forward pass that extracts features and applies softmax for crash prediction', 'summarize the CrashDetectorNet architecture using ResNet18 backbone with a custom two-layer classifier head', 'run the crash detection model on an image using --model_path and --image_path CLI arguments', 'test a PyTorch model on an image using the Tester class test method', 'convert a raw image to PIL crops and PyTorch tensors using Tester convert_to_PIL method', 'review the torchvision transform pipeline that resizes to 224x224 and normalizes with ImageNet stats', 'refactor the Tester convert_to_PIL method to crop center, left, right regions and stack as a batch tensor', 'run the Trainer class to train a CrashDetectorNet model for N epochs with TensorBoard logging', 'run the main CLI to train a drone crash detection model with configurable epochs and train fraction', 'create a Trainer instance with a CSV filename and train/test split fraction for drone crash data', 'test the Trainer create_model method to instantiate and optionally move CrashDetectorNet to GPU', 'review the train_model method that performs training and testing loops with checkpoint saving and metrics tracking']
```

Usage

```
{'run_crash_detection_model': 'run the crash detection model on an image using --model_path and --image_path CLI arguments', 'test_Tester_class': 'test a PyTorch model on an image using the Tester class test method', 'convert_image_to_PIL_tensors': 'convert a raw image to PIL crops and PyTorch tensors using Tester convert_to_PIL method', 'review_PYTORCH_TRANSFORM': 'review the torchvision transform pipeline that resizes to 224x224 and normalizes with ImageNet stats', 'refactor_Tester_convert_to_PIL': 'refactor the Tester convert_to_PIL method to crop center, left, right regions and stack as a batch tensor'}
```

## File: facebookresearch_pyrobot/examples/crash_detection/crash_utils/train.py

Prompts

```
['build a CrashDetectorNet model with pretrained ResNet18 weights for binary crash classification', 'run forward inference on input tensor x through the CrashDetectorNet model to get crash probabilities', 'create a CrashDetectorNet model without pretrained weights by setting pretrained_resnet18 to False', 'review the CrashDetectorNet forward pass that extracts features and applies softmax for crash prediction', 'summarize the CrashDetectorNet architecture using ResNet18 backbone with a custom two-layer classifier head', 'run the crash detection model on an image using --model_path and --image_path CLI arguments', 'test a PyTorch model on an image using the Tester class test method', 'convert a raw image to PIL crops and PyTorch tensors using Tester convert_to_PIL method', 'review the torchvision transform pipeline that resizes to 224x224 and normalizes with ImageNet stats', 'refactor the Tester convert_to_PIL method to crop center, left, right regions and stack as a batch tensor', 'run the Trainer class to train a CrashDetectorNet model for N epochs with TensorBoard logging', 'run the main CLI to train a drone crash detection model with configurable epochs and train fraction', 'create a Trainer instance with a CSV filename and train/test split fraction for drone crash data', 'test the Trainer create_model method to instantiate and optionally move CrashDetectorNet to GPU', 'review the train_model method that performs training and testing loops with checkpoint saving and metrics tracking']
```

Usage

```
{'run_Trainer_train_model': 'run the Trainer class to train a CrashDetectorNet model for N epochs with TensorBoard logging', 'run_main_cli': 'run the main CLI to train a drone crash detection model with configurable epochs and train fraction', 'create_Trainer': 'create a Trainer instance with a CSV filename and train/test split fraction for drone crash data', 'test_Trainer_create_model': 'test the Trainer create_model method to instantiate and optionally move CrashDetectorNet to GPU', 'review_Trainer_train_model': 'review the train_model method that performs training and testing loops with checkpoint saving and metrics tracking'}
```

