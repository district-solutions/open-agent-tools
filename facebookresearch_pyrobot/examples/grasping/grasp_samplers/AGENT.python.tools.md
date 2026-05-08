# Agent Python Tools

- repo: facebookresearch/pyrobot
- repo_uri: https://github.com/facebookresearch/pyrobot

## File: facebookresearch_pyrobot/examples/grasping/grasp_samplers/deeper_models.py

Prompts

```
['build a ResNet-based grasp sampler model with IfullRobHWNet for robot grasping angle and noise prediction', 'create an IfullRobHWNet instance with pretrained ResNet18 weights and configurable hidden layer size', 'run a forward pass on IfullRobHWNet with image input, robot labels, height, width, and full image', 'review the _one_forward method that extracts features through conv layers and average pooling', 'test the load_from_pretrained_resnet18 method to load pretrained ResNet18 weights from model zoo', 'download a grasp model file from a URL to a specified local path if not already present', 'draw a colored grasp rectangle on an image at a given height, width, and angle', 'initialize a GraspModel with configurable sample count, patch size, and importance sampling parameters', 'run grasp prediction on an image and return the selected grasp configuration with confidence score', 'save the scene image with the predicted grasp rectangle overlay to a file path', 'create a GraspTorchObj instance by loading a PyTorch grasp model from a file path', 'test a batch of image patches through the grasp model to get predictions', 'convert a list of OpenCV image patches into a stacked PyTorch tensor', 'convert a list of grasp angle labels into a one-hot encoded PyTorch tensor', 'get the default torchvision transform with resize, tensor conversion, and ImageNet normalization', 'create a Predictors instance with a scene image and optional grasp model object', 'run random_grasp on a Predictors object to sample a random grasp configuration tuple', 'run center_grasp on a Predictors object to get the center grasp configuration tuple', 'run graspNet_grasp on a Predictors object to select grasps using the grasp model', 'review the Predictors class and its grasp sampling methods for robotics applications']
```

Usage

```
{'build_grasp_model': 'build a ResNet-based grasp sampler model with IfullRobHWNet for robot grasping angle and noise prediction', 'create_ifullrobhw_net': 'create an IfullRobHWNet instance with pretrained ResNet18 weights and configurable hidden layer size', 'run_forward_pass': 'run a forward pass on IfullRobHWNet with image input, robot labels, height, width, and full image', 'review_one_forward': 'review the _one_forward method that extracts features through conv layers and average pooling', 'test_pretrained_loading': 'test the load_from_pretrained_resnet18 method to load pretrained ResNet18 weights from model zoo'}
```

## File: facebookresearch_pyrobot/examples/grasping/grasp_samplers/grasp_model.py

Prompts

```
['build a ResNet-based grasp sampler model with IfullRobHWNet for robot grasping angle and noise prediction', 'create an IfullRobHWNet instance with pretrained ResNet18 weights and configurable hidden layer size', 'run a forward pass on IfullRobHWNet with image input, robot labels, height, width, and full image', 'review the _one_forward method that extracts features through conv layers and average pooling', 'test the load_from_pretrained_resnet18 method to load pretrained ResNet18 weights from model zoo', 'download a grasp model file from a URL to a specified local path if not already present', 'draw a colored grasp rectangle on an image at a given height, width, and angle', 'initialize a GraspModel with configurable sample count, patch size, and importance sampling parameters', 'run grasp prediction on an image and return the selected grasp configuration with confidence score', 'save the scene image with the predicted grasp rectangle overlay to a file path', 'create a GraspTorchObj instance by loading a PyTorch grasp model from a file path', 'test a batch of image patches through the grasp model to get predictions', 'convert a list of OpenCV image patches into a stacked PyTorch tensor', 'convert a list of grasp angle labels into a one-hot encoded PyTorch tensor', 'get the default torchvision transform with resize, tensor conversion, and ImageNet normalization', 'create a Predictors instance with a scene image and optional grasp model object', 'run random_grasp on a Predictors object to sample a random grasp configuration tuple', 'run center_grasp on a Predictors object to get the center grasp configuration tuple', 'run graspNet_grasp on a Predictors object to select grasps using the grasp model', 'review the Predictors class and its grasp sampling methods for robotics applications']
```

Usage

```
{'download_grasp_model': 'download a grasp model file from a URL to a specified local path if not already present', 'draw_grasp_rectangle': 'draw a colored grasp rectangle on an image at a given height, width, and angle', 'init_grasp_model': 'initialize a GraspModel with configurable sample count, patch size, and importance sampling parameters', 'predict_grasp': 'run grasp prediction on an image and return the selected grasp configuration with confidence score', 'save_predicted_grasp_image': 'save the scene image with the predicted grasp rectangle overlay to a file path'}
```

## File: facebookresearch_pyrobot/examples/grasping/grasp_samplers/grasp_object.py

Prompts

```
['build a ResNet-based grasp sampler model with IfullRobHWNet for robot grasping angle and noise prediction', 'create an IfullRobHWNet instance with pretrained ResNet18 weights and configurable hidden layer size', 'run a forward pass on IfullRobHWNet with image input, robot labels, height, width, and full image', 'review the _one_forward method that extracts features through conv layers and average pooling', 'test the load_from_pretrained_resnet18 method to load pretrained ResNet18 weights from model zoo', 'download a grasp model file from a URL to a specified local path if not already present', 'draw a colored grasp rectangle on an image at a given height, width, and angle', 'initialize a GraspModel with configurable sample count, patch size, and importance sampling parameters', 'run grasp prediction on an image and return the selected grasp configuration with confidence score', 'save the scene image with the predicted grasp rectangle overlay to a file path', 'create a GraspTorchObj instance by loading a PyTorch grasp model from a file path', 'test a batch of image patches through the grasp model to get predictions', 'convert a list of OpenCV image patches into a stacked PyTorch tensor', 'convert a list of grasp angle labels into a one-hot encoded PyTorch tensor', 'get the default torchvision transform with resize, tensor conversion, and ImageNet normalization', 'create a Predictors instance with a scene image and optional grasp model object', 'run random_grasp on a Predictors object to sample a random grasp configuration tuple', 'run center_grasp on a Predictors object to get the center grasp configuration tuple', 'run graspNet_grasp on a Predictors object to select grasps using the grasp model', 'review the Predictors class and its grasp sampling methods for robotics applications']
```

Usage

```
{'create_grasp_torch_obj': 'create a GraspTorchObj instance by loading a PyTorch grasp model from a file path', 'test_one_batch_predictions': 'test a batch of image patches through the grasp model to get predictions', 'convert_cv2_patches_to_tensor': 'convert a list of OpenCV image patches into a stacked PyTorch tensor', 'convert_angle_labels_one_hot': 'convert a list of grasp angle labels into a one-hot encoded PyTorch tensor', 'get_default_image_transform': 'get the default torchvision transform with resize, tensor conversion, and ImageNet normalization'}
```

## File: facebookresearch_pyrobot/examples/grasping/grasp_samplers/grasp_predictor.py

Prompts

```
['build a ResNet-based grasp sampler model with IfullRobHWNet for robot grasping angle and noise prediction', 'create an IfullRobHWNet instance with pretrained ResNet18 weights and configurable hidden layer size', 'run a forward pass on IfullRobHWNet with image input, robot labels, height, width, and full image', 'review the _one_forward method that extracts features through conv layers and average pooling', 'test the load_from_pretrained_resnet18 method to load pretrained ResNet18 weights from model zoo', 'download a grasp model file from a URL to a specified local path if not already present', 'draw a colored grasp rectangle on an image at a given height, width, and angle', 'initialize a GraspModel with configurable sample count, patch size, and importance sampling parameters', 'run grasp prediction on an image and return the selected grasp configuration with confidence score', 'save the scene image with the predicted grasp rectangle overlay to a file path', 'create a GraspTorchObj instance by loading a PyTorch grasp model from a file path', 'test a batch of image patches through the grasp model to get predictions', 'convert a list of OpenCV image patches into a stacked PyTorch tensor', 'convert a list of grasp angle labels into a one-hot encoded PyTorch tensor', 'get the default torchvision transform with resize, tensor conversion, and ImageNet normalization', 'create a Predictors instance with a scene image and optional grasp model object', 'run random_grasp on a Predictors object to sample a random grasp configuration tuple', 'run center_grasp on a Predictors object to get the center grasp configuration tuple', 'run graspNet_grasp on a Predictors object to select grasps using the grasp model', 'review the Predictors class and its grasp sampling methods for robotics applications']
```

Usage

```
{'create_Predictors_class': 'create a Predictors instance with a scene image and optional grasp model object', 'run_random_grasp': 'run random_grasp on a Predictors object to sample a random grasp configuration tuple', 'run_center_grasp': 'run center_grasp on a Predictors object to get the center grasp configuration tuple', 'run_graspNet_grasp': 'run graspNet_grasp on a Predictors object to select grasps using the grasp model', 'review_Predictors_class': 'review the Predictors class and its grasp sampling methods for robotics applications'}
```

