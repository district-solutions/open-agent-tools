# Agent Python Tools

- repo: facebookresearch/multimodal
- repo_uri: https://github.com/facebookresearch/multimodal

## File: facebookresearch_multimodal/examples/flava/native/data.py

Prompts

```
['create an ImageDataModule LightningDataModule for image pretraining with configurable transforms and batch size', 'create a TextDataModule LightningDataModule for text data with BERT tokenizer and configurable max length', 'create an MLMDataModule for masked language modeling with configurable MLM probability and ignore index', 'create a VLDataModule for vision-language pretraining with image fetching and whole word masking', 'create a TorchVisionDataModule for torchvision datasets with automatic download and split configuration', 'create an AdamW optimizer with cosine warmup schedule for a PyTorch model', 'build a FLAVA pretraining module with bf16 support and custom model kwargs', 'run a forward pass on a batch containing image and text data', 'encode text input using the FLAVA model encode_text method', 'encode image input using the FLAVA model forward method with encode_image action', 'run the FLAVA multimodal model training loop with torchrun using a YAML config file', 'create a Trainer instance with a DictConfig to set up distributed training and data modules', 'build a FLAVAPreTrainModule wrapped with DDP or FSDP using the create_model method', 'calculate the total pretraining loss from a FLAVAPretrainingLossOutput across all loss keys', 'run ImageNet zero-shot validation on the trained FLAVA model using imagenet_validate', 'build a config by loading a YAML file and merging CLI arguments with OmegaConf', 'move a nested dict or list of tensors to a specified CUDA or CPU device', 'get the total number of parameters in a PyTorch model module', 'setup a distributed training device using NCCL and return the correct CUDA device', 'run a zero-shot ImageNet evaluation on a FLAVA model and return top1 and top5 accuracy']
```

Usage

```
{'create_imagemodule': 'create an ImageDataModule LightningDataModule for image pretraining with configurable transforms and batch size', 'create_textmodule': 'create a TextDataModule LightningDataModule for text data with BERT tokenizer and configurable max length', 'create_mlmmodule': 'create an MLMDataModule for masked language modeling with configurable MLM probability and ignore index', 'create_vlmodule': 'create a VLDataModule for vision-language pretraining with image fetching and whole word masking', 'create_torchvisionmodule': 'create a TorchVisionDataModule for torchvision datasets with automatic download and split configuration'}
```

## File: facebookresearch_multimodal/examples/flava/native/model.py

Prompts

```
['create an ImageDataModule LightningDataModule for image pretraining with configurable transforms and batch size', 'create a TextDataModule LightningDataModule for text data with BERT tokenizer and configurable max length', 'create an MLMDataModule for masked language modeling with configurable MLM probability and ignore index', 'create a VLDataModule for vision-language pretraining with image fetching and whole word masking', 'create a TorchVisionDataModule for torchvision datasets with automatic download and split configuration', 'create an AdamW optimizer with cosine warmup schedule for a PyTorch model', 'build a FLAVA pretraining module with bf16 support and custom model kwargs', 'run a forward pass on a batch containing image and text data', 'encode text input using the FLAVA model encode_text method', 'encode image input using the FLAVA model forward method with encode_image action', 'run the FLAVA multimodal model training loop with torchrun using a YAML config file', 'create a Trainer instance with a DictConfig to set up distributed training and data modules', 'build a FLAVAPreTrainModule wrapped with DDP or FSDP using the create_model method', 'calculate the total pretraining loss from a FLAVAPretrainingLossOutput across all loss keys', 'run ImageNet zero-shot validation on the trained FLAVA model using imagenet_validate', 'build a config by loading a YAML file and merging CLI arguments with OmegaConf', 'move a nested dict or list of tensors to a specified CUDA or CPU device', 'get the total number of parameters in a PyTorch model module', 'setup a distributed training device using NCCL and return the correct CUDA device', 'run a zero-shot ImageNet evaluation on a FLAVA model and return top1 and top5 accuracy']
```

Usage

```
{'create_optimizer_and_scheduler': 'create an AdamW optimizer with cosine warmup schedule for a PyTorch model', 'build_flava_pretrain_module': 'build a FLAVA pretraining module with bf16 support and custom model kwargs', 'run_flava_forward_pass': 'run a forward pass on a batch containing image and text data', 'encode_text_with_flava': 'encode text input using the FLAVA model encode_text method', 'encode_image_with_flava': 'encode image input using the FLAVA model forward method with encode_image action'}
```

## File: facebookresearch_multimodal/examples/flava/native/train.py

Prompts

```
['create an ImageDataModule LightningDataModule for image pretraining with configurable transforms and batch size', 'create a TextDataModule LightningDataModule for text data with BERT tokenizer and configurable max length', 'create an MLMDataModule for masked language modeling with configurable MLM probability and ignore index', 'create a VLDataModule for vision-language pretraining with image fetching and whole word masking', 'create a TorchVisionDataModule for torchvision datasets with automatic download and split configuration', 'create an AdamW optimizer with cosine warmup schedule for a PyTorch model', 'build a FLAVA pretraining module with bf16 support and custom model kwargs', 'run a forward pass on a batch containing image and text data', 'encode text input using the FLAVA model encode_text method', 'encode image input using the FLAVA model forward method with encode_image action', 'run the FLAVA multimodal model training loop with torchrun using a YAML config file', 'create a Trainer instance with a DictConfig to set up distributed training and data modules', 'build a FLAVAPreTrainModule wrapped with DDP or FSDP using the create_model method', 'calculate the total pretraining loss from a FLAVAPretrainingLossOutput across all loss keys', 'run ImageNet zero-shot validation on the trained FLAVA model using imagenet_validate', 'build a config by loading a YAML file and merging CLI arguments with OmegaConf', 'move a nested dict or list of tensors to a specified CUDA or CPU device', 'get the total number of parameters in a PyTorch model module', 'setup a distributed training device using NCCL and return the correct CUDA device', 'run a zero-shot ImageNet evaluation on a FLAVA model and return top1 and top5 accuracy']
```

Usage

```
{'run_FLAVA_training': 'run the FLAVA multimodal model training loop with torchrun using a YAML config file', 'create_Trainer': 'create a Trainer instance with a DictConfig to set up distributed training and data modules', 'build_FLAVA_model': 'build a FLAVAPreTrainModule wrapped with DDP or FSDP using the create_model method', 'calculate_loss_FLAVA': 'calculate the total pretraining loss from a FLAVAPretrainingLossOutput across all loss keys', 'validate_imagenet_zero_shot': 'run ImageNet zero-shot validation on the trained FLAVA model using imagenet_validate'}
```

## File: facebookresearch_multimodal/examples/flava/native/utils.py

Prompts

```
['create an ImageDataModule LightningDataModule for image pretraining with configurable transforms and batch size', 'create a TextDataModule LightningDataModule for text data with BERT tokenizer and configurable max length', 'create an MLMDataModule for masked language modeling with configurable MLM probability and ignore index', 'create a VLDataModule for vision-language pretraining with image fetching and whole word masking', 'create a TorchVisionDataModule for torchvision datasets with automatic download and split configuration', 'create an AdamW optimizer with cosine warmup schedule for a PyTorch model', 'build a FLAVA pretraining module with bf16 support and custom model kwargs', 'run a forward pass on a batch containing image and text data', 'encode text input using the FLAVA model encode_text method', 'encode image input using the FLAVA model forward method with encode_image action', 'run the FLAVA multimodal model training loop with torchrun using a YAML config file', 'create a Trainer instance with a DictConfig to set up distributed training and data modules', 'build a FLAVAPreTrainModule wrapped with DDP or FSDP using the create_model method', 'calculate the total pretraining loss from a FLAVAPretrainingLossOutput across all loss keys', 'run ImageNet zero-shot validation on the trained FLAVA model using imagenet_validate', 'build a config by loading a YAML file and merging CLI arguments with OmegaConf', 'move a nested dict or list of tensors to a specified CUDA or CPU device', 'get the total number of parameters in a PyTorch model module', 'setup a distributed training device using NCCL and return the correct CUDA device', 'run a zero-shot ImageNet evaluation on a FLAVA model and return top1 and top5 accuracy']
```

Usage

```
{'build_config_from_yaml': 'build a config by loading a YAML file and merging CLI arguments with OmegaConf', 'move_tensors_to_device': 'move a nested dict or list of tensors to a specified CUDA or CPU device', 'get_model_parameters': 'get the total number of parameters in a PyTorch model module', 'setup_distributed_device': 'setup a distributed training device using NCCL and return the correct CUDA device', 'run_imagenet_zero_shot': 'run a zero-shot ImageNet evaluation on a FLAVA model and return top1 and top5 accuracy'}
```

