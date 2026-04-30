# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/hiera/configuration_hiera.py

Prompts

```
['create a HieraConfig instance with custom patch size, depths, and number of heads', 'build a HieraConfig for a hiera-base-patch16-224 style model configuration', 'validate a HieraConfig architecture to check masked_unit_size and num_query_pool constraints', 'configure a HieraConfig with backbone output features and output indices for feature extraction', 'summarize a HieraConfig including embed_dim, depths, num_heads, and hidden_size attributes', 'convert a Hiera checkpoint from Facebook Research to Hugging Face format', 'get a HieraConfig object for a specified model name and model type', 'create a list of key renames from original Hiera checkpoint keys to Hugging Face keys', 'run the convert_hiera_to_hf CLI script to convert a Hiera model to Hugging Face format', 'push a converted Hiera model and image processor to the Hugging Face hub', 'create a Hiera model for image classification with a linear classifier head on top of pooled hidden states', 'run Hiera model for self-supervised pre-training using masked image modeling with a decoder and multi-scale fusion heads', 'build a Hiera backbone model to extract multi-scale feature maps for use with frameworks like DETR and MaskFormer', 'test the Hiera model forward pass with pixel values, optional noise, and output attention and hidden states flags', 'review the HieraEncoderOutput class that contains last hidden state, hidden states, attentions, and reshaped hidden states']
```

Usage

```
{'create_hiera_config': 'create a HieraConfig instance with custom patch size, depths, and number of heads', 'build_hiera_model_config': 'build a HieraConfig for a hiera-base-patch16-224 style model configuration', 'validate_hiera_architecture': 'validate a HieraConfig architecture to check masked_unit_size and num_query_pool constraints', 'configure_hiera_backbone': 'configure a HieraConfig with backbone output features and output indices for feature extraction', 'summarize_hiera_config': 'summarize a HieraConfig including embed_dim, depths, num_heads, and hidden_size attributes'}
```

## File: huggingface_transformers/src/transformers/models/hiera/convert_hiera_to_hf.py

Prompts

```
['create a HieraConfig instance with custom patch size, depths, and number of heads', 'build a HieraConfig for a hiera-base-patch16-224 style model configuration', 'validate a HieraConfig architecture to check masked_unit_size and num_query_pool constraints', 'configure a HieraConfig with backbone output features and output indices for feature extraction', 'summarize a HieraConfig including embed_dim, depths, num_heads, and hidden_size attributes', 'convert a Hiera checkpoint from Facebook Research to Hugging Face format', 'get a HieraConfig object for a specified model name and model type', 'create a list of key renames from original Hiera checkpoint keys to Hugging Face keys', 'run the convert_hiera_to_hf CLI script to convert a Hiera model to Hugging Face format', 'push a converted Hiera model and image processor to the Hugging Face hub', 'create a Hiera model for image classification with a linear classifier head on top of pooled hidden states', 'run Hiera model for self-supervised pre-training using masked image modeling with a decoder and multi-scale fusion heads', 'build a Hiera backbone model to extract multi-scale feature maps for use with frameworks like DETR and MaskFormer', 'test the Hiera model forward pass with pixel values, optional noise, and output attention and hidden states flags', 'review the HieraEncoderOutput class that contains last hidden state, hidden states, attentions, and reshaped hidden states']
```

Usage

```
{'convert_hiera_checkpoint': 'convert a Hiera checkpoint from Facebook Research to Hugging Face format', 'get_hiera_config': 'get a HieraConfig object for a specified model name and model type', 'create_rename_keys': 'create a list of key renames from original Hiera checkpoint keys to Hugging Face keys', 'run_convert_hiera_cli': 'run the convert_hiera_to_hf CLI script to convert a Hiera model to Hugging Face format', 'push_hiera_model_to_hub': 'push a converted Hiera model and image processor to the Hugging Face hub'}
```

## File: huggingface_transformers/src/transformers/models/hiera/modeling_hiera.py

Prompts

```
['create a HieraConfig instance with custom patch size, depths, and number of heads', 'build a HieraConfig for a hiera-base-patch16-224 style model configuration', 'validate a HieraConfig architecture to check masked_unit_size and num_query_pool constraints', 'configure a HieraConfig with backbone output features and output indices for feature extraction', 'summarize a HieraConfig including embed_dim, depths, num_heads, and hidden_size attributes', 'convert a Hiera checkpoint from Facebook Research to Hugging Face format', 'get a HieraConfig object for a specified model name and model type', 'create a list of key renames from original Hiera checkpoint keys to Hugging Face keys', 'run the convert_hiera_to_hf CLI script to convert a Hiera model to Hugging Face format', 'push a converted Hiera model and image processor to the Hugging Face hub', 'create a Hiera model for image classification with a linear classifier head on top of pooled hidden states', 'run Hiera model for self-supervised pre-training using masked image modeling with a decoder and multi-scale fusion heads', 'build a Hiera backbone model to extract multi-scale feature maps for use with frameworks like DETR and MaskFormer', 'test the Hiera model forward pass with pixel values, optional noise, and output attention and hidden states flags', 'review the HieraEncoderOutput class that contains last hidden state, hidden states, attentions, and reshaped hidden states']
```

Usage

```
{'create_model_hiera_for_image_classification': 'create a Hiera model for image classification with a linear classifier head on top of pooled hidden states', 'run_model_hiera_for_pretraining': 'run Hiera model for self-supervised pre-training using masked image modeling with a decoder and multi-scale fusion heads', 'build_backbone_hiera': 'build a Hiera backbone model to extract multi-scale feature maps for use with frameworks like DETR and MaskFormer', 'test_model_hiera_forward': 'test the Hiera model forward pass with pixel values, optional noise, and output attention and hidden states flags', 'review_hiera_encoder_output': 'review the HieraEncoderOutput class that contains last hidden state, hidden states, attentions, and reshaped hidden states'}
```

