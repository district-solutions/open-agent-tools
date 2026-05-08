# Agent Python Tools

- repo: facebookresearch/pytorch3d
- repo_uri: https://github.com/facebookresearch/pytorch3d.git

## File: facebookresearch_pytorch3d/tests/implicitron/models/test_overfit_model.py

Prompts

```
['test that OverfitModel produces the same outputs as GenericModel with batch size one', 'test that OverfitModel shares implicit function weights across rendering passes when enabled', 'test that OverfitModel uses separate implicit function weights when sharing is disabled', 'test that OverfitModel handles a None coarse implicit function without errors', 'generate fake camera and image inputs for OverfitModel training and evaluation tests', 'test preprocess_input raises ValueError when given unbatched 3D tensor inputs', 'test preprocess_input masks image tensor using foreground probability threshold', 'test preprocess_input masks depth map tensor using foreground probability threshold', 'test weighted_sum_losses computes correct weighted sum from predictions and weights dict', 'test weighted_sum_losses returns None when weight keys do not match prediction keys']
```

Usage

```
{'test_overfit_model_vs_generic_model': 'test that OverfitModel produces the same outputs as GenericModel with batch size one', 'test_overfit_model_share_weights': 'test that OverfitModel shares implicit function weights across rendering passes when enabled', 'test_overfit_model_no_share_weights': 'test that OverfitModel uses separate implicit function weights when sharing is disabled', 'test_overfit_model_coarse_function_none': 'test that OverfitModel handles a None coarse implicit function without errors', 'generate_fake_inputs': 'generate fake camera and image inputs for OverfitModel training and evaluation tests'}
```

## File: facebookresearch_pytorch3d/tests/implicitron/models/test_utils.py

Prompts

```
['test that OverfitModel produces the same outputs as GenericModel with batch size one', 'test that OverfitModel shares implicit function weights across rendering passes when enabled', 'test that OverfitModel uses separate implicit function weights when sharing is disabled', 'test that OverfitModel handles a None coarse implicit function without errors', 'generate fake camera and image inputs for OverfitModel training and evaluation tests', 'test preprocess_input raises ValueError when given unbatched 3D tensor inputs', 'test preprocess_input masks image tensor using foreground probability threshold', 'test preprocess_input masks depth map tensor using foreground probability threshold', 'test weighted_sum_losses computes correct weighted sum from predictions and weights dict', 'test weighted_sum_losses returns None when weight keys do not match prediction keys']
```

Usage

```
{'test_preprocess_input_wrong_dim': 'test preprocess_input raises ValueError when given unbatched 3D tensor inputs', 'test_preprocess_input_mask_image': 'test preprocess_input masks image tensor using foreground probability threshold', 'test_preprocess_input_mask_depth': 'test preprocess_input masks depth map tensor using foreground probability threshold', 'test_weighted_sum_losses': 'test weighted_sum_losses computes correct weighted sum from predictions and weights dict', 'test_weighted_sum_losses_no_match': 'test weighted_sum_losses returns None when weight keys do not match prediction keys'}
```

