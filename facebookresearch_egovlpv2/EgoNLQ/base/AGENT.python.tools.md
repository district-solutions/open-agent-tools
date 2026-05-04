# Agent Python Tools

- repo: facebookresearch/egovlpv2
- repo_uri: https://github.com/facebookresearch/egovlpv2

## File: facebookresearch_egovlpv2/EgoNLQ/base/base_dataset.py

Prompts

```
['create a subclass of TextVideoDataset implementing _load_metadata, _get_video_path, and _get_caption for custom video-text datasets', 'read frames from a video file using decord with random or uniform sampling and return normalized tensors', 'read frames from a video file using cv2 with configurable sampling strategy and return normalized tensors', 'sample frame indices from a video given the number of frames, video length, and sampling strategy', 'get the total frame count of a video file using cv2 and return the length as an integer', 'create a subclass of BaseModel that implements the forward method for a custom PyTorch model', 'review the BaseModel abstract forward method to understand the required interface for subclasses', 'summarize the BaseModel __str__ method that prints trainable parameter counts alongside the model structure', 'build a custom PyTorch model by subclassing BaseModel and implementing the abstract forward pass', 'test the BaseModel __str__ method to verify it correctly counts trainable parameters', 'create a torchvision transform dictionary with train, val, and test pipelines using default ImageNet normalization', 'create a transform dictionary with a custom input resolution and center crop size for image augmentation', 'create a transform dictionary with custom color jitter values for brightness, saturation, and hue augmentation', 'create a torchvision video transform dictionary with train, val, and test pipelines using default normalization', 'create a video transform dictionary with a custom random crop scale range for training augmentation']
```

Usage

```
{'create_TextVideoDataset_subclass': 'create a subclass of TextVideoDataset implementing _load_metadata, _get_video_path, and _get_caption for custom video-text datasets', 'read_frames_decord': 'read frames from a video file using decord with random or uniform sampling and return normalized tensors', 'read_frames_cv2': 'read frames from a video file using cv2 with configurable sampling strategy and return normalized tensors', 'sample_frames': 'sample frame indices from a video given the number of frames, video length, and sampling strategy', 'get_video_len': 'get the total frame count of a video file using cv2 and return the length as an integer'}
```

## File: facebookresearch_egovlpv2/EgoNLQ/base/base_model.py

Prompts

```
['create a subclass of TextVideoDataset implementing _load_metadata, _get_video_path, and _get_caption for custom video-text datasets', 'read frames from a video file using decord with random or uniform sampling and return normalized tensors', 'read frames from a video file using cv2 with configurable sampling strategy and return normalized tensors', 'sample frame indices from a video given the number of frames, video length, and sampling strategy', 'get the total frame count of a video file using cv2 and return the length as an integer', 'create a subclass of BaseModel that implements the forward method for a custom PyTorch model', 'review the BaseModel abstract forward method to understand the required interface for subclasses', 'summarize the BaseModel __str__ method that prints trainable parameter counts alongside the model structure', 'build a custom PyTorch model by subclassing BaseModel and implementing the abstract forward pass', 'test the BaseModel __str__ method to verify it correctly counts trainable parameters', 'create a torchvision transform dictionary with train, val, and test pipelines using default ImageNet normalization', 'create a transform dictionary with a custom input resolution and center crop size for image augmentation', 'create a transform dictionary with custom color jitter values for brightness, saturation, and hue augmentation', 'create a torchvision video transform dictionary with train, val, and test pipelines using default normalization', 'create a video transform dictionary with a custom random crop scale range for training augmentation']
```

Usage

```
{'create_subclass_with_forward': 'create a subclass of BaseModel that implements the forward method for a custom PyTorch model', 'review_base_model_forward': 'review the BaseModel abstract forward method to understand the required interface for subclasses', 'summarize_base_model_str': 'summarize the BaseModel __str__ method that prints trainable parameter counts alongside the model structure', 'build_custom_model_subclass': 'build a custom PyTorch model by subclassing BaseModel and implementing the abstract forward pass', 'test_base_model_parameter_count': 'test the BaseModel __str__ method to verify it correctly counts trainable parameters'}
```

## File: facebookresearch_egovlpv2/EgoNLQ/base/transforms.py

Prompts

```
['create a subclass of TextVideoDataset implementing _load_metadata, _get_video_path, and _get_caption for custom video-text datasets', 'read frames from a video file using decord with random or uniform sampling and return normalized tensors', 'read frames from a video file using cv2 with configurable sampling strategy and return normalized tensors', 'sample frame indices from a video given the number of frames, video length, and sampling strategy', 'get the total frame count of a video file using cv2 and return the length as an integer', 'create a subclass of BaseModel that implements the forward method for a custom PyTorch model', 'review the BaseModel abstract forward method to understand the required interface for subclasses', 'summarize the BaseModel __str__ method that prints trainable parameter counts alongside the model structure', 'build a custom PyTorch model by subclassing BaseModel and implementing the abstract forward pass', 'test the BaseModel __str__ method to verify it correctly counts trainable parameters', 'create a torchvision transform dictionary with train, val, and test pipelines using default ImageNet normalization', 'create a transform dictionary with a custom input resolution and center crop size for image augmentation', 'create a transform dictionary with custom color jitter values for brightness, saturation, and hue augmentation', 'create a torchvision video transform dictionary with train, val, and test pipelines using default normalization', 'create a video transform dictionary with a custom random crop scale range for training augmentation']
```

Usage

```
{'init_transform_dict_default': 'create a torchvision transform dictionary with train, val, and test pipelines using default ImageNet normalization', 'init_transform_dict_custom_resolution': 'create a transform dictionary with a custom input resolution and center crop size for image augmentation', 'init_transform_dict_color_jitter': 'create a transform dictionary with custom color jitter values for brightness, saturation, and hue augmentation', 'init_video_transform_dict_default': 'create a torchvision video transform dictionary with train, val, and test pipelines using default normalization', 'init_video_transform_dict_custom_randcrop': 'create a video transform dictionary with a custom random crop scale range for training augmentation'}
```

