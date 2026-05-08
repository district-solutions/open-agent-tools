# Agent Python Tools

- repo: facebookresearch/jepa-intuitive-physics
- repo_uri: https://github.com/facebookresearch/jepa-intuitive-physics

## File: facebookresearch_jepa-intuitive-physics/evaluation_code/src/masks/causal.py

Prompts

```
['create a MaskCollator with mask config list, crop size, num frames, patch size, and tubelet size', 'call the MaskCollator on a batch to get collated batch, encoder masks, and predictor masks', 'step all mask generators in the MaskCollator to advance their internal iteration counters', 'create a _MaskGenerator with crop size, num frames, spatial and temporal patch sizes, and context ratio', 'call the _MaskGenerator with a batch size to generate encoder and predictor mask tensors', 'sample a 3D block size with temporal, spatial, and aspect ratio scales using a torch Generator', 'create a MaskCollator with configurable ratio, input_size, and patch_size for random masking', 'call the MaskCollator on a batch to get collated data with encoder and predictor masks', 'step the MaskCollator iteration counter to get a unique seed for mask generation', 'review the MaskCollator __init__ to understand patch grid and ratio configuration', 'refactor the MaskCollator __call__ to customize mask generation logic for batches', 'create a _MaskGenerator with crop size, num frames, spatial and temporal patch sizes, and masking ratio', 'call the _MaskGenerator with a batch size to generate encoder and predictor mask tensors', 'apply masks to gather selected patches from a tensor and concatenate results along dimension 0', 'apply masks to gather selected patches from a tensor and return a list of separate tensors', 'review the apply_masks function that gathers patches from a tensor using index masks', 'summarize the apply_masks function for gathering K patches from N patches in a batch tensor', 'test the apply_masks function with a batch tensor and list of index masks']
```

Usage

```
{'create_MaskCollator': 'create a MaskCollator with mask config list, crop size, num frames, patch size, and tubelet size', 'call_MaskCollator': 'call the MaskCollator on a batch to get collated batch, encoder masks, and predictor masks', 'step_MaskCollator': 'step all mask generators in the MaskCollator to advance their internal iteration counters', 'create_MaskGenerator': 'create a _MaskGenerator with crop size, num frames, spatial and temporal patch sizes, and context ratio', 'call_MaskGenerator': 'call the _MaskGenerator with a batch size to generate encoder and predictor mask tensors'}
```

## File: facebookresearch_jepa-intuitive-physics/evaluation_code/src/masks/multiblock3d.py

Prompts

```
['create a MaskCollator with mask config list, crop size, num frames, patch size, and tubelet size', 'call the MaskCollator on a batch to get collated batch, encoder masks, and predictor masks', 'step all mask generators in the MaskCollator to advance their internal iteration counters', 'create a _MaskGenerator with crop size, num frames, spatial and temporal patch sizes, and context ratio', 'call the _MaskGenerator with a batch size to generate encoder and predictor mask tensors', 'sample a 3D block size with temporal, spatial, and aspect ratio scales using a torch Generator', 'create a MaskCollator with configurable ratio, input_size, and patch_size for random masking', 'call the MaskCollator on a batch to get collated data with encoder and predictor masks', 'step the MaskCollator iteration counter to get a unique seed for mask generation', 'review the MaskCollator __init__ to understand patch grid and ratio configuration', 'refactor the MaskCollator __call__ to customize mask generation logic for batches', 'create a _MaskGenerator with crop size, num frames, spatial and temporal patch sizes, and masking ratio', 'call the _MaskGenerator with a batch size to generate encoder and predictor mask tensors', 'apply masks to gather selected patches from a tensor and concatenate results along dimension 0', 'apply masks to gather selected patches from a tensor and return a list of separate tensors', 'review the apply_masks function that gathers patches from a tensor using index masks', 'summarize the apply_masks function for gathering K patches from N patches in a batch tensor', 'test the apply_masks function with a batch tensor and list of index masks']
```

Usage

```
{'create_MaskCollator': 'create a MaskCollator with mask config dicts, crop size, num frames, patch size, and tubelet size', 'call_MaskCollator': 'call the MaskCollator on a batch to get collated batch, encoder masks, and predictor masks', 'create_MaskGenerator': 'create a _MaskGenerator with crop size, num frames, spatial and temporal patch sizes, and mask scales', 'call_MaskGenerator': 'call the _MaskGenerator with a batch size to generate encoder and predictor mask tensors', 'sample_block_size_MaskGenerator': 'sample a 3D block size with temporal, spatial, and aspect ratio scales using a torch Generator'}
```

## File: facebookresearch_jepa-intuitive-physics/evaluation_code/src/masks/random.py

Prompts

```
['create a MaskCollator with mask config list, crop size, num frames, patch size, and tubelet size', 'call the MaskCollator on a batch to get collated batch, encoder masks, and predictor masks', 'step all mask generators in the MaskCollator to advance their internal iteration counters', 'create a _MaskGenerator with crop size, num frames, spatial and temporal patch sizes, and context ratio', 'call the _MaskGenerator with a batch size to generate encoder and predictor mask tensors', 'sample a 3D block size with temporal, spatial, and aspect ratio scales using a torch Generator', 'create a MaskCollator with configurable ratio, input_size, and patch_size for random masking', 'call the MaskCollator on a batch to get collated data with encoder and predictor masks', 'step the MaskCollator iteration counter to get a unique seed for mask generation', 'review the MaskCollator __init__ to understand patch grid and ratio configuration', 'refactor the MaskCollator __call__ to customize mask generation logic for batches', 'create a _MaskGenerator with crop size, num frames, spatial and temporal patch sizes, and masking ratio', 'call the _MaskGenerator with a batch size to generate encoder and predictor mask tensors', 'apply masks to gather selected patches from a tensor and concatenate results along dimension 0', 'apply masks to gather selected patches from a tensor and return a list of separate tensors', 'review the apply_masks function that gathers patches from a tensor using index masks', 'summarize the apply_masks function for gathering K patches from N patches in a batch tensor', 'test the apply_masks function with a batch tensor and list of index masks']
```

Usage

```
{'create_mask_collator': 'create a MaskCollator with configurable ratio, input_size, and patch_size for random masking', 'call_mask_collator': 'call the MaskCollator on a batch to get collated data with encoder and predictor masks', 'step_mask_collator': 'step the MaskCollator iteration counter to get a unique seed for mask generation', 'review_mask_collator_init': 'review the MaskCollator __init__ to understand patch grid and ratio configuration', 'refactor_mask_collator_call': 'refactor the MaskCollator __call__ to customize mask generation logic for batches'}
```

## File: facebookresearch_jepa-intuitive-physics/evaluation_code/src/masks/random_tube.py

Prompts

```
['create a MaskCollator with mask config list, crop size, num frames, patch size, and tubelet size', 'call the MaskCollator on a batch to get collated batch, encoder masks, and predictor masks', 'step all mask generators in the MaskCollator to advance their internal iteration counters', 'create a _MaskGenerator with crop size, num frames, spatial and temporal patch sizes, and context ratio', 'call the _MaskGenerator with a batch size to generate encoder and predictor mask tensors', 'sample a 3D block size with temporal, spatial, and aspect ratio scales using a torch Generator', 'create a MaskCollator with configurable ratio, input_size, and patch_size for random masking', 'call the MaskCollator on a batch to get collated data with encoder and predictor masks', 'step the MaskCollator iteration counter to get a unique seed for mask generation', 'review the MaskCollator __init__ to understand patch grid and ratio configuration', 'refactor the MaskCollator __call__ to customize mask generation logic for batches', 'create a _MaskGenerator with crop size, num frames, spatial and temporal patch sizes, and masking ratio', 'call the _MaskGenerator with a batch size to generate encoder and predictor mask tensors', 'apply masks to gather selected patches from a tensor and concatenate results along dimension 0', 'apply masks to gather selected patches from a tensor and return a list of separate tensors', 'review the apply_masks function that gathers patches from a tensor using index masks', 'summarize the apply_masks function for gathering K patches from N patches in a batch tensor', 'test the apply_masks function with a batch tensor and list of index masks']
```

Usage

```
{'create_mask_collator': 'create a MaskCollator with mask config list, crop size, num frames, patch size, and tubelet size', 'call_mask_collator': 'call the MaskCollator on a batch to get collated batch, encoder masks, and predictor masks', 'step_mask_collator': 'step the MaskCollator to increment iteration counters across all mask generators', 'create_mask_generator': 'create a _MaskGenerator with crop size, num frames, spatial and temporal patch sizes, and masking ratio', 'call_mask_generator': 'call the _MaskGenerator with a batch size to generate encoder and predictor mask tensors'}
```

## File: facebookresearch_jepa-intuitive-physics/evaluation_code/src/masks/utils.py

Prompts

```
['create a MaskCollator with mask config list, crop size, num frames, patch size, and tubelet size', 'call the MaskCollator on a batch to get collated batch, encoder masks, and predictor masks', 'step all mask generators in the MaskCollator to advance their internal iteration counters', 'create a _MaskGenerator with crop size, num frames, spatial and temporal patch sizes, and context ratio', 'call the _MaskGenerator with a batch size to generate encoder and predictor mask tensors', 'sample a 3D block size with temporal, spatial, and aspect ratio scales using a torch Generator', 'create a MaskCollator with configurable ratio, input_size, and patch_size for random masking', 'call the MaskCollator on a batch to get collated data with encoder and predictor masks', 'step the MaskCollator iteration counter to get a unique seed for mask generation', 'review the MaskCollator __init__ to understand patch grid and ratio configuration', 'refactor the MaskCollator __call__ to customize mask generation logic for batches', 'create a _MaskGenerator with crop size, num frames, spatial and temporal patch sizes, and masking ratio', 'call the _MaskGenerator with a batch size to generate encoder and predictor mask tensors', 'apply masks to gather selected patches from a tensor and concatenate results along dimension 0', 'apply masks to gather selected patches from a tensor and return a list of separate tensors', 'review the apply_masks function that gathers patches from a tensor using index masks', 'summarize the apply_masks function for gathering K patches from N patches in a batch tensor', 'test the apply_masks function with a batch tensor and list of index masks']
```

Usage

```
{'apply_masks_concat': 'apply masks to gather selected patches from a tensor and concatenate results along dimension 0', 'apply_masks_no_concat': 'apply masks to gather selected patches from a tensor and return a list of separate tensors', 'review_apply_masks': 'review the apply_masks function that gathers patches from a tensor using index masks', 'summarize_apply_masks': 'summarize the apply_masks function for gathering K patches from N patches in a batch tensor', 'test_apply_masks': 'test the apply_masks function with a batch tensor and list of index masks'}
```

