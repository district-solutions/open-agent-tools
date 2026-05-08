# Agent Python Tools

- repo: facebookresearch/imagebind
- repo_uri: https://github.com/facebookresearch/imagebind

## File: facebookresearch_imagebind/imagebind/models/helpers.py

Prompts

```
['create a Normalize layer that L2-normalizes tensors along a specified dimension', 'create a LearnableLogitScaling module to scale logits with a learnable temperature parameter', 'create an EinOpsRearrange layer to reshape tensors using einops rearrange expressions', 'create a QuickGELU activation function as a fast approximation of GELU', 'create a SelectEOSAndProject module to extract EOS token features and project them', 'create an ImageBindModel instance with custom modality embedding dimensions and transformer block counts', 'run the ImageBindModel forward pass with a dictionary of modality inputs to get embeddings', 'create a pretrained ImageBind huge model by calling imagebind_huge with pretrained set to true', 'review the ImageBindModel modality preprocessors for vision text audio depth thermal and imu', 'review the ImageBindModel modality trunks transformer architecture for each modality type', 'build an RGBDTPreprocessor module to tokenize vision and depth inputs into multimodal tokens with positional embeddings', 'build a TextPreprocessor module to embed text tokens with positional encoding and optional causal attention masking', 'build a SimpleTokenizer to encode and decode text using BPE tokenization with a given merges file', 'build an IMUPreprocessor module to patchify and tokenize IMU sensor data into embedding tokens', 'build an AudioPreprocessor module to tokenize audio inputs into multimodal tokens using a patch embedding stem', 'build a SimpleTransformer with configurable blocks, drop path rate, and layer scale for multi-modal token processing', 'create an Attention module with multi-head self-attention, QKV projections, and configurable dropout rates', 'create a BlockWithMasking transformer block with attention, MLP, normalization, and optional layer scaling', 'test the Mlp feed-forward network with configurable hidden features, activation layer, and dropout', 'review the ViTAttention class that extends Attention with mask assertion for vision transformer use']
```

Usage

```
{'create_normalize_layer': 'create a Normalize layer that L2-normalizes tensors along a specified dimension', 'create_learnable_logit_scaling': 'create a LearnableLogitScaling module to scale logits with a learnable temperature parameter', 'create_einops_rearrange_layer': 'create an EinOpsRearrange layer to reshape tensors using einops rearrange expressions', 'create_quick_gelu_activation': 'create a QuickGELU activation function as a fast approximation of GELU', 'create_select_eos_and_project': 'create a SelectEOSAndProject module to extract EOS token features and project them'}
```

## File: facebookresearch_imagebind/imagebind/models/imagebind_model.py

Prompts

```
['create a Normalize layer that L2-normalizes tensors along a specified dimension', 'create a LearnableLogitScaling module to scale logits with a learnable temperature parameter', 'create an EinOpsRearrange layer to reshape tensors using einops rearrange expressions', 'create a QuickGELU activation function as a fast approximation of GELU', 'create a SelectEOSAndProject module to extract EOS token features and project them', 'create an ImageBindModel instance with custom modality embedding dimensions and transformer block counts', 'run the ImageBindModel forward pass with a dictionary of modality inputs to get embeddings', 'create a pretrained ImageBind huge model by calling imagebind_huge with pretrained set to true', 'review the ImageBindModel modality preprocessors for vision text audio depth thermal and imu', 'review the ImageBindModel modality trunks transformer architecture for each modality type', 'build an RGBDTPreprocessor module to tokenize vision and depth inputs into multimodal tokens with positional embeddings', 'build a TextPreprocessor module to embed text tokens with positional encoding and optional causal attention masking', 'build a SimpleTokenizer to encode and decode text using BPE tokenization with a given merges file', 'build an IMUPreprocessor module to patchify and tokenize IMU sensor data into embedding tokens', 'build an AudioPreprocessor module to tokenize audio inputs into multimodal tokens using a patch embedding stem', 'build a SimpleTransformer with configurable blocks, drop path rate, and layer scale for multi-modal token processing', 'create an Attention module with multi-head self-attention, QKV projections, and configurable dropout rates', 'create a BlockWithMasking transformer block with attention, MLP, normalization, and optional layer scaling', 'test the Mlp feed-forward network with configurable hidden features, activation layer, and dropout', 'review the ViTAttention class that extends Attention with mask assertion for vision transformer use']
```

Usage

```
{'create_imagebind_model': 'create an ImageBindModel instance with custom modality embedding dimensions and transformer block counts', 'run_imagebind_forward': 'run the ImageBindModel forward pass with a dictionary of modality inputs to get embeddings', 'create_imagebind_huge': 'create a pretrained ImageBind huge model by calling imagebind_huge with pretrained set to true', 'review_modality_preprocessors': 'review the ImageBindModel modality preprocessors for vision text audio depth thermal and imu', 'review_modality_trunks': 'review the ImageBindModel modality trunks transformer architecture for each modality type'}
```

## File: facebookresearch_imagebind/imagebind/models/multimodal_preprocessors.py

Prompts

```
['create a Normalize layer that L2-normalizes tensors along a specified dimension', 'create a LearnableLogitScaling module to scale logits with a learnable temperature parameter', 'create an EinOpsRearrange layer to reshape tensors using einops rearrange expressions', 'create a QuickGELU activation function as a fast approximation of GELU', 'create a SelectEOSAndProject module to extract EOS token features and project them', 'create an ImageBindModel instance with custom modality embedding dimensions and transformer block counts', 'run the ImageBindModel forward pass with a dictionary of modality inputs to get embeddings', 'create a pretrained ImageBind huge model by calling imagebind_huge with pretrained set to true', 'review the ImageBindModel modality preprocessors for vision text audio depth thermal and imu', 'review the ImageBindModel modality trunks transformer architecture for each modality type', 'build an RGBDTPreprocessor module to tokenize vision and depth inputs into multimodal tokens with positional embeddings', 'build a TextPreprocessor module to embed text tokens with positional encoding and optional causal attention masking', 'build a SimpleTokenizer to encode and decode text using BPE tokenization with a given merges file', 'build an IMUPreprocessor module to patchify and tokenize IMU sensor data into embedding tokens', 'build an AudioPreprocessor module to tokenize audio inputs into multimodal tokens using a patch embedding stem', 'build a SimpleTransformer with configurable blocks, drop path rate, and layer scale for multi-modal token processing', 'create an Attention module with multi-head self-attention, QKV projections, and configurable dropout rates', 'create a BlockWithMasking transformer block with attention, MLP, normalization, and optional layer scaling', 'test the Mlp feed-forward network with configurable hidden features, activation layer, and dropout', 'review the ViTAttention class that extends Attention with mask assertion for vision transformer use']
```

Usage

```
{'build_RGBDTPreprocessor': 'build an RGBDTPreprocessor module to tokenize vision and depth inputs into multimodal tokens with positional embeddings', 'build_TextPreprocessor': 'build a TextPreprocessor module to embed text tokens with positional encoding and optional causal attention masking', 'build_SimpleTokenizer': 'build a SimpleTokenizer to encode and decode text using BPE tokenization with a given merges file', 'build_IMUPreprocessor': 'build an IMUPreprocessor module to patchify and tokenize IMU sensor data into embedding tokens', 'build_AudioPreprocessor': 'build an AudioPreprocessor module to tokenize audio inputs into multimodal tokens using a patch embedding stem'}
```

## File: facebookresearch_imagebind/imagebind/models/transformer.py

Prompts

```
['create a Normalize layer that L2-normalizes tensors along a specified dimension', 'create a LearnableLogitScaling module to scale logits with a learnable temperature parameter', 'create an EinOpsRearrange layer to reshape tensors using einops rearrange expressions', 'create a QuickGELU activation function as a fast approximation of GELU', 'create a SelectEOSAndProject module to extract EOS token features and project them', 'create an ImageBindModel instance with custom modality embedding dimensions and transformer block counts', 'run the ImageBindModel forward pass with a dictionary of modality inputs to get embeddings', 'create a pretrained ImageBind huge model by calling imagebind_huge with pretrained set to true', 'review the ImageBindModel modality preprocessors for vision text audio depth thermal and imu', 'review the ImageBindModel modality trunks transformer architecture for each modality type', 'build an RGBDTPreprocessor module to tokenize vision and depth inputs into multimodal tokens with positional embeddings', 'build a TextPreprocessor module to embed text tokens with positional encoding and optional causal attention masking', 'build a SimpleTokenizer to encode and decode text using BPE tokenization with a given merges file', 'build an IMUPreprocessor module to patchify and tokenize IMU sensor data into embedding tokens', 'build an AudioPreprocessor module to tokenize audio inputs into multimodal tokens using a patch embedding stem', 'build a SimpleTransformer with configurable blocks, drop path rate, and layer scale for multi-modal token processing', 'create an Attention module with multi-head self-attention, QKV projections, and configurable dropout rates', 'create a BlockWithMasking transformer block with attention, MLP, normalization, and optional layer scaling', 'test the Mlp feed-forward network with configurable hidden features, activation layer, and dropout', 'review the ViTAttention class that extends Attention with mask assertion for vision transformer use']
```

Usage

```
{'build_SimpleTransformer': 'build a SimpleTransformer with configurable blocks, drop path rate, and layer scale for multi-modal token processing', 'create_Attention_module': 'create an Attention module with multi-head self-attention, QKV projections, and configurable dropout rates', 'create_BlockWithMasking': 'create a BlockWithMasking transformer block with attention, MLP, normalization, and optional layer scaling', 'test_Mlp_forward': 'test the Mlp feed-forward network with configurable hidden features, activation layer, and dropout', 'review_ViTAttention': 'review the ViTAttention class that extends Attention with mask assertion for vision transformer use'}
```

