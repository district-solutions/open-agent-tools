# Agent Python Tools

- repo: facebookresearch/sapiens
- repo_uri: https://github.com/facebookresearch/sapiens

## File: facebookresearch_sapiens/engine/mmengine/model/base_model/base_model.py

Prompts

```
['build a python module that subclasses BaseModel to implement a custom algorithmic model with forward method', 'run the train_step method of BaseModel to preprocess data, calculate loss, and update model parameters', 'run the val_step method of BaseModel to get predictions on validation data for evaluation', 'parse the raw loss dict from the network into a total loss tensor and logging variables', 'move the BaseModel and its data preprocessor to a target device like cuda, cpu, mlu, or npu', 'build a BaseDataPreprocessor module to copy dataloader data to the target device', 'build an ImgDataPreprocessor to normalize, pad, and convert BGR to RGB image inputs', 'test the cast_data method to recursively move tensors and nested data to target device', 'test the ImgDataPreprocessor forward method to normalize and pad a batch of image tensors', 'review the to, cuda, npu, mlu, and cpu device transfer methods in BaseDataPreprocessor']
```

Usage

```
{'build_BaseModel_subclass': 'build a python module that subclasses BaseModel to implement a custom algorithmic model with forward method', 'run_train_step': 'run the train_step method of BaseModel to preprocess data, calculate loss, and update model parameters', 'run_val_step': 'run the val_step method of BaseModel to get predictions on validation data for evaluation', 'parse_losses': 'parse the raw loss dict from the network into a total loss tensor and logging variables', 'move_model_to_device': 'move the BaseModel and its data preprocessor to a target device like cuda, cpu, mlu, or npu'}
```

## File: facebookresearch_sapiens/engine/mmengine/model/base_model/data_preprocessor.py

Prompts

```
['build a python module that subclasses BaseModel to implement a custom algorithmic model with forward method', 'run the train_step method of BaseModel to preprocess data, calculate loss, and update model parameters', 'run the val_step method of BaseModel to get predictions on validation data for evaluation', 'parse the raw loss dict from the network into a total loss tensor and logging variables', 'move the BaseModel and its data preprocessor to a target device like cuda, cpu, mlu, or npu', 'build a BaseDataPreprocessor module to copy dataloader data to the target device', 'build an ImgDataPreprocessor to normalize, pad, and convert BGR to RGB image inputs', 'test the cast_data method to recursively move tensors and nested data to target device', 'test the ImgDataPreprocessor forward method to normalize and pad a batch of image tensors', 'review the to, cuda, npu, mlu, and cpu device transfer methods in BaseDataPreprocessor']
```

Usage

```
{'build_base_data_preprocessor': 'build a BaseDataPreprocessor module to copy dataloader data to the target device', 'build_img_data_preprocessor': 'build an ImgDataPreprocessor to normalize, pad, and convert BGR to RGB image inputs', 'test_cast_data': 'test the cast_data method to recursively move tensors and nested data to target device', 'test_img_forward': 'test the ImgDataPreprocessor forward method to normalize and pad a batch of image tensors', 'review_device_methods': 'review the to, cuda, npu, mlu, and cpu device transfer methods in BaseDataPreprocessor'}
```

