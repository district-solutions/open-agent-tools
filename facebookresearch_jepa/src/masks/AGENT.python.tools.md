# Agent Python Tools

- repo: facebookresearch/jepa
- repo_uri: https://github.com/facebookresearch/jepa

## File: facebookresearch_jepa/src/masks/multiblock3d.py

Prompts

```
['create a MaskCollator with mask config dicts, crop size, num frames, patch size, and tubelet size', 'call the MaskCollator on a batch to get collated batch, encoder masks, and predictor masks', 'create a _MaskGenerator with crop size, num frames, spatial and temporal patch sizes, and mask scales', 'sample a 3D block mask with random temporal, spatial, and aspect ratio dimensions for masking', 'step the _MaskGenerator iteration counter to advance the seed for deterministic mask generation', 'step the MaskCollator to increment iteration counters across all mask generators', 'call the _MaskGenerator with a batch size to generate encoder and predictor mask tensors', 'apply masks to a tensor and concatenate the masked patch selections along dimension 0', 'apply masks to a tensor and return a list of separately masked patch selections', 'gather specific patch indices from a batched tensor using mask index tensors', 'unsqueeze and repeat a mask tensor to match the feature dimension for gathering', 'apply multiple mask tensors to a single batched tensor and collect results']
```

Usage

```
{'create_mask_collator': 'create a MaskCollator with mask config dicts, crop size, num frames, patch size, and tubelet size', 'call_mask_collator': 'call the MaskCollator on a batch to get collated batch, encoder masks, and predictor masks', 'create_mask_generator': 'create a _MaskGenerator with crop size, num frames, spatial and temporal patch sizes, and mask scales', 'sample_block_mask': 'sample a 3D block mask with random temporal, spatial, and aspect ratio dimensions for masking', 'step_mask_generator': 'step the _MaskGenerator iteration counter to advance the seed for deterministic mask generation'}
```

## File: facebookresearch_jepa/src/masks/random_tube.py

Prompts

```
['create a MaskCollator with mask config dicts, crop size, num frames, patch size, and tubelet size', 'call the MaskCollator on a batch to get collated batch, encoder masks, and predictor masks', 'create a _MaskGenerator with crop size, num frames, spatial and temporal patch sizes, and mask scales', 'sample a 3D block mask with random temporal, spatial, and aspect ratio dimensions for masking', 'step the _MaskGenerator iteration counter to advance the seed for deterministic mask generation', 'step the MaskCollator to increment iteration counters across all mask generators', 'call the _MaskGenerator with a batch size to generate encoder and predictor mask tensors', 'apply masks to a tensor and concatenate the masked patch selections along dimension 0', 'apply masks to a tensor and return a list of separately masked patch selections', 'gather specific patch indices from a batched tensor using mask index tensors', 'unsqueeze and repeat a mask tensor to match the feature dimension for gathering', 'apply multiple mask tensors to a single batched tensor and collect results']
```

Usage

```
{'create_mask_collator': 'create a MaskCollator with mask config list, crop size, num frames, patch size, and tubelet size', 'call_mask_collator': 'call the MaskCollator on a batch to get collated batch, encoder masks, and predictor masks', 'step_mask_collator': 'step the MaskCollator to increment iteration counters across all mask generators', 'create_mask_generator': 'create a _MaskGenerator with crop size, num frames, spatial and temporal patch sizes, and masking ratio', 'call_mask_generator': 'call the _MaskGenerator with a batch size to generate encoder and predictor mask tensors'}
```

## File: facebookresearch_jepa/src/masks/utils.py

Prompts

```
['create a MaskCollator with mask config dicts, crop size, num frames, patch size, and tubelet size', 'call the MaskCollator on a batch to get collated batch, encoder masks, and predictor masks', 'create a _MaskGenerator with crop size, num frames, spatial and temporal patch sizes, and mask scales', 'sample a 3D block mask with random temporal, spatial, and aspect ratio dimensions for masking', 'step the _MaskGenerator iteration counter to advance the seed for deterministic mask generation', 'step the MaskCollator to increment iteration counters across all mask generators', 'call the _MaskGenerator with a batch size to generate encoder and predictor mask tensors', 'apply masks to a tensor and concatenate the masked patch selections along dimension 0', 'apply masks to a tensor and return a list of separately masked patch selections', 'gather specific patch indices from a batched tensor using mask index tensors', 'unsqueeze and repeat a mask tensor to match the feature dimension for gathering', 'apply multiple mask tensors to a single batched tensor and collect results']
```

Usage

```
{'apply_masks_concat': 'apply masks to a tensor and concatenate the masked patch selections along dimension 0', 'apply_masks_no_concat': 'apply masks to a tensor and return a list of separately masked patch selections', 'apply_masks_gather_patches': 'gather specific patch indices from a batched tensor using mask index tensors', 'apply_masks_repeat_mask': 'unsqueeze and repeat a mask tensor to match the feature dimension for gathering', 'apply_masks_batched_tensor': 'apply multiple mask tensors to a single batched tensor and collect results'}
```

