# Agent Python Tools

- repo: OpenBMB/VoxCPM
- repo_uri: https://github.com/OpenBMB/VoxCPM

## File: OpenBMB_VoxCPM/src/voxcpm/modules/locenc/local_encoder.py

Prompts

```
['create a VoxCPMLocEnc module with MiniCPM4Config and input_dim 64 for encoding local voxel sequences', 'build a forward pass through VoxCPMLocEnc that projects input [B,T,P,D] through in_proj, prepends special tokens, and returns [B,T,hidden_size] via MiniCPMModel encoder', 'test VoxCPMLocEnc special token parameter initialized as trainable [1,1,1,hidden_size] and expanded across batch and time dimensions', 'refactor VoxCPMLocEnc in_proj linear layer to map input_dim to config.hidden_size with bias enabled', 'review VoxCPMLocEnc einops rearrange operations that flatten batch-time dimensions for encoder and restore them after cls_output extraction']
```

Usage

```
{'create_VoxCPMLocEnc': 'create a VoxCPMLocEnc module with MiniCPM4Config and input_dim 64 for encoding local voxel sequences', 'build_VoxCPMLocEnc_forward': 'build a forward pass through VoxCPMLocEnc that projects input [B,T,P,D] through in_proj, prepends special tokens, and returns [B,T,hidden_size] via MiniCPMModel encoder', 'test_VoxCPMLocEnc_special_token': 'test VoxCPMLocEnc special token parameter initialized as trainable [1,1,1,hidden_size] and expanded across batch and time dimensions', 'refactor_VoxCPMLocEnc_in_proj': 'refactor VoxCPMLocEnc in_proj linear layer to map input_dim to config.hidden_size with bias enabled', 'review_VoxCPMLocEnc_rearrange': 'review VoxCPMLocEnc einops rearrange operations that flatten batch-time dimensions for encoder and restore them after cls_output extraction'}
```

