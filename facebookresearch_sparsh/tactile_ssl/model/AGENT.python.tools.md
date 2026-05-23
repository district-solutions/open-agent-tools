# Agent Python Tools

- repo: facebookresearch/sparsh
- repo_uri: https://github.com/facebookresearch/sparsh

## File: facebookresearch_sparsh/tactile_ssl/model/custom_scheduler.py

Prompts

```
['create a WarmupCosineScheduler instance with an optimizer, steps per epoch, start learning rate, and T_max', 'call get_lr on a WarmupCosineScheduler to compute the current learning rate based on warmup or cosine decay', 'create a CosineWDSchedule instance with an optimizer, reference weight decay, and total steps for cosine weight decay scheduling', 'call step on a CosineWDSchedule to update the optimizer weight decay using a cosine annealing schedule', 'review the WarmupCosineScheduler and CosineWDSchedule classes for learning rate and weight decay scheduling strategies', 'build a MultimodalTransformer with modal dims, lengths, embed dim, and depth for multi-modal feature extraction', 'build a MultimodalMAEDecoder with modal channels and shared mask tokens for masked autoencoding', 'run forward_features on a list of modality tensors with optional masks to get normalized patch tokens', 'test the apply_mask method with tube or block mask types on multi-modal tensor inputs', 'review the transcode method to understand shared versus per-modality attention block processing', 'build a ResNet-18 encoder with default pretrained weights and no final classification layer', 'build an AlexNet encoder with default pretrained weights and no final classification layer', 'create an AlexnetWrapper module that wraps a pretrained AlexNet encoder for feature extraction', 'test the AlexnetWrapper get_intermediate_layers method to extract features from specified layer indices', 'review the AlexnetWrapper _register_hooks method that attaches forward hooks to capture intermediate layer outputs', 'build a ViT-base vision transformer model with 768 embed dim and 12 attention heads', 'build a ViT-large vision transformer model with 1024 embed dim and 24 transformer blocks', 'build a VisionTransformerPredictor model for masked image modeling with sinusoidal positional encoding', 'create a vision transformer with configurable register tokens for enhanced feature extraction', 'test the get_intermediate_layers method to extract normalized features from specific transformer blocks']
```

Usage

```
{'create_warmup_cosine_scheduler': 'create a WarmupCosineScheduler instance with an optimizer, steps per epoch, start learning rate, and T_max', 'get_lr_warmup_cosine': 'call get_lr on a WarmupCosineScheduler to compute the current learning rate based on warmup or cosine decay', 'create_cosine_wd_schedule': 'create a CosineWDSchedule instance with an optimizer, reference weight decay, and total steps for cosine weight decay scheduling', 'step_cosine_wd_schedule': 'call step on a CosineWDSchedule to update the optimizer weight decay using a cosine annealing schedule', 'review_custom_scheduler_classes': 'review the WarmupCosineScheduler and CosineWDSchedule classes for learning rate and weight decay scheduling strategies'}
```

## File: facebookresearch_sparsh/tactile_ssl/model/multimodal_transformer.py

Prompts

```
['create a WarmupCosineScheduler instance with an optimizer, steps per epoch, start learning rate, and T_max', 'call get_lr on a WarmupCosineScheduler to compute the current learning rate based on warmup or cosine decay', 'create a CosineWDSchedule instance with an optimizer, reference weight decay, and total steps for cosine weight decay scheduling', 'call step on a CosineWDSchedule to update the optimizer weight decay using a cosine annealing schedule', 'review the WarmupCosineScheduler and CosineWDSchedule classes for learning rate and weight decay scheduling strategies', 'build a MultimodalTransformer with modal dims, lengths, embed dim, and depth for multi-modal feature extraction', 'build a MultimodalMAEDecoder with modal channels and shared mask tokens for masked autoencoding', 'run forward_features on a list of modality tensors with optional masks to get normalized patch tokens', 'test the apply_mask method with tube or block mask types on multi-modal tensor inputs', 'review the transcode method to understand shared versus per-modality attention block processing', 'build a ResNet-18 encoder with default pretrained weights and no final classification layer', 'build an AlexNet encoder with default pretrained weights and no final classification layer', 'create an AlexnetWrapper module that wraps a pretrained AlexNet encoder for feature extraction', 'test the AlexnetWrapper get_intermediate_layers method to extract features from specified layer indices', 'review the AlexnetWrapper _register_hooks method that attaches forward hooks to capture intermediate layer outputs', 'build a ViT-base vision transformer model with 768 embed dim and 12 attention heads', 'build a ViT-large vision transformer model with 1024 embed dim and 24 transformer blocks', 'build a VisionTransformerPredictor model for masked image modeling with sinusoidal positional encoding', 'create a vision transformer with configurable register tokens for enhanced feature extraction', 'test the get_intermediate_layers method to extract normalized features from specific transformer blocks']
```

Usage

```
{'build_multimodal_transformer': 'build a MultimodalTransformer with modal dims, lengths, embed dim, and depth for multi-modal feature extraction', 'build_multimodal_mae_decoder': 'build a MultimodalMAEDecoder with modal channels and shared mask tokens for masked autoencoding', 'run_forward_features': 'run forward_features on a list of modality tensors with optional masks to get normalized patch tokens', 'test_apply_mask': 'test the apply_mask method with tube or block mask types on multi-modal tensor inputs', 'review_transcode': 'review the transcode method to understand shared versus per-modality attention block processing'}
```

## File: facebookresearch_sparsh/tactile_ssl/model/pretrained.py

Prompts

```
['create a WarmupCosineScheduler instance with an optimizer, steps per epoch, start learning rate, and T_max', 'call get_lr on a WarmupCosineScheduler to compute the current learning rate based on warmup or cosine decay', 'create a CosineWDSchedule instance with an optimizer, reference weight decay, and total steps for cosine weight decay scheduling', 'call step on a CosineWDSchedule to update the optimizer weight decay using a cosine annealing schedule', 'review the WarmupCosineScheduler and CosineWDSchedule classes for learning rate and weight decay scheduling strategies', 'build a MultimodalTransformer with modal dims, lengths, embed dim, and depth for multi-modal feature extraction', 'build a MultimodalMAEDecoder with modal channels and shared mask tokens for masked autoencoding', 'run forward_features on a list of modality tensors with optional masks to get normalized patch tokens', 'test the apply_mask method with tube or block mask types on multi-modal tensor inputs', 'review the transcode method to understand shared versus per-modality attention block processing', 'build a ResNet-18 encoder with default pretrained weights and no final classification layer', 'build an AlexNet encoder with default pretrained weights and no final classification layer', 'create an AlexnetWrapper module that wraps a pretrained AlexNet encoder for feature extraction', 'test the AlexnetWrapper get_intermediate_layers method to extract features from specified layer indices', 'review the AlexnetWrapper _register_hooks method that attaches forward hooks to capture intermediate layer outputs', 'build a ViT-base vision transformer model with 768 embed dim and 12 attention heads', 'build a ViT-large vision transformer model with 1024 embed dim and 24 transformer blocks', 'build a VisionTransformerPredictor model for masked image modeling with sinusoidal positional encoding', 'create a vision transformer with configurable register tokens for enhanced feature extraction', 'test the get_intermediate_layers method to extract normalized features from specific transformer blocks']
```

Usage

```
{'build_resnet18_encoder': 'build a ResNet-18 encoder with default pretrained weights and no final classification layer', 'build_alexnet_encoder': 'build an AlexNet encoder with default pretrained weights and no final classification layer', 'create_AlexnetWrapper': 'create an AlexnetWrapper module that wraps a pretrained AlexNet encoder for feature extraction', 'test_get_intermediate_layers': 'test the AlexnetWrapper get_intermediate_layers method to extract features from specified layer indices', 'review_AlexnetWrapper_register_hooks': 'review the AlexnetWrapper _register_hooks method that attaches forward hooks to capture intermediate layer outputs'}
```

## File: facebookresearch_sparsh/tactile_ssl/model/vision_transformer.py

Prompts

```
['create a WarmupCosineScheduler instance with an optimizer, steps per epoch, start learning rate, and T_max', 'call get_lr on a WarmupCosineScheduler to compute the current learning rate based on warmup or cosine decay', 'create a CosineWDSchedule instance with an optimizer, reference weight decay, and total steps for cosine weight decay scheduling', 'call step on a CosineWDSchedule to update the optimizer weight decay using a cosine annealing schedule', 'review the WarmupCosineScheduler and CosineWDSchedule classes for learning rate and weight decay scheduling strategies', 'build a MultimodalTransformer with modal dims, lengths, embed dim, and depth for multi-modal feature extraction', 'build a MultimodalMAEDecoder with modal channels and shared mask tokens for masked autoencoding', 'run forward_features on a list of modality tensors with optional masks to get normalized patch tokens', 'test the apply_mask method with tube or block mask types on multi-modal tensor inputs', 'review the transcode method to understand shared versus per-modality attention block processing', 'build a ResNet-18 encoder with default pretrained weights and no final classification layer', 'build an AlexNet encoder with default pretrained weights and no final classification layer', 'create an AlexnetWrapper module that wraps a pretrained AlexNet encoder for feature extraction', 'test the AlexnetWrapper get_intermediate_layers method to extract features from specified layer indices', 'review the AlexnetWrapper _register_hooks method that attaches forward hooks to capture intermediate layer outputs', 'build a ViT-base vision transformer model with 768 embed dim and 12 attention heads', 'build a ViT-large vision transformer model with 1024 embed dim and 24 transformer blocks', 'build a VisionTransformerPredictor model for masked image modeling with sinusoidal positional encoding', 'create a vision transformer with configurable register tokens for enhanced feature extraction', 'test the get_intermediate_layers method to extract normalized features from specific transformer blocks']
```

Usage

```
{'build_vit_base_model': 'build a ViT-base vision transformer model with 768 embed dim and 12 attention heads', 'build_vit_large_model': 'build a ViT-large vision transformer model with 1024 embed dim and 24 transformer blocks', 'build_vit_predictor_model': 'build a VisionTransformerPredictor model for masked image modeling with sinusoidal positional encoding', 'create_vit_with_registers': 'create a vision transformer with configurable register tokens for enhanced feature extraction', 'test_vit_intermediate_layers': 'test the get_intermediate_layers method to extract normalized features from specific transformer blocks'}
```

