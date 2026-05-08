# Agent Python Tools

- repo: facebookresearch/ijepa
- repo_uri: https://github.com/facebookresearch/ijepa

## File: facebookresearch_ijepa/src/masks/multiblock.py

Prompts

```
['create a MaskCollator instance with custom input_size, patch_size, and mask scale parameters for iMask generation', 'generate encoder masks by calling the MaskCollator on a batch of images to get visible patch indices', 'generate predictor masks by calling the MaskCollator on a batch of images to get masked patch indices', 'sample a random block height and width using _sample_block_size with a torch Generator and scale range', 'sample a random block mask with _sample_block_mask constrained to acceptable regions on the patch grid', 'call the MaskCollator on a batch to get collated data with encoder and predictor masks', 'step the MaskCollator iterator counter to get a new seed value for mask generation', 'review the MaskCollator __call__ method that generates encoder and predictor masks for each image in a batch', 'refactor the MaskCollator to support a fixed ratio instead of a random ratio range', 'apply masks to gather specific patches from a tensor using torch gather', 'apply masks to select context patches from a batch of patch tensors', 'apply masks to select target patches from a batch of patch tensors', 'review the apply_masks function that gathers patches from tensors using mask indices', 'summarize the apply_masks function for iJEPa mask-based patch selection']
```

Usage

```
{'create_mask_collator': 'create a MaskCollator instance with custom input_size, patch_size, and mask scale parameters for iMask generation', 'generate_encoder_masks': 'generate encoder masks by calling the MaskCollator on a batch of images to get visible patch indices', 'generate_predictor_masks': 'generate predictor masks by calling the MaskCollator on a batch of images to get masked patch indices', 'sample_block_size': 'sample a random block height and width using _sample_block_size with a torch Generator and scale range', 'sample_block_mask': 'sample a random block mask with _sample_block_mask constrained to acceptable regions on the patch grid'}
```

## File: facebookresearch_ijepa/src/masks/random.py

Prompts

```
['create a MaskCollator instance with custom input_size, patch_size, and mask scale parameters for iMask generation', 'generate encoder masks by calling the MaskCollator on a batch of images to get visible patch indices', 'generate predictor masks by calling the MaskCollator on a batch of images to get masked patch indices', 'sample a random block height and width using _sample_block_size with a torch Generator and scale range', 'sample a random block mask with _sample_block_mask constrained to acceptable regions on the patch grid', 'call the MaskCollator on a batch to get collated data with encoder and predictor masks', 'step the MaskCollator iterator counter to get a new seed value for mask generation', 'review the MaskCollator __call__ method that generates encoder and predictor masks for each image in a batch', 'refactor the MaskCollator to support a fixed ratio instead of a random ratio range', 'apply masks to gather specific patches from a tensor using torch gather', 'apply masks to select context patches from a batch of patch tensors', 'apply masks to select target patches from a batch of patch tensors', 'review the apply_masks function that gathers patches from tensors using mask indices', 'summarize the apply_masks function for iJEPa mask-based patch selection']
```

Usage

```
{'create_mask_collator': 'create a MaskCollator with ratio, input_size, and patch_size for masked image modeling', 'call_mask_collator_batch': 'call the MaskCollator on a batch to get collated data with encoder and predictor masks', 'step_mask_collator_counter': 'step the MaskCollator iterator counter to get a new seed value for mask generation', 'review_mask_collator_call': 'review the MaskCollator __call__ method that generates encoder and predictor masks for each image in a batch', 'refactor_mask_collator_ratio': 'refactor the MaskCollator to support a fixed ratio instead of a random ratio range'}
```

## File: facebookresearch_ijepa/src/masks/utils.py

Prompts

```
['create a MaskCollator instance with custom input_size, patch_size, and mask scale parameters for iMask generation', 'generate encoder masks by calling the MaskCollator on a batch of images to get visible patch indices', 'generate predictor masks by calling the MaskCollator on a batch of images to get masked patch indices', 'sample a random block height and width using _sample_block_size with a torch Generator and scale range', 'sample a random block mask with _sample_block_mask constrained to acceptable regions on the patch grid', 'call the MaskCollator on a batch to get collated data with encoder and predictor masks', 'step the MaskCollator iterator counter to get a new seed value for mask generation', 'review the MaskCollator __call__ method that generates encoder and predictor masks for each image in a batch', 'refactor the MaskCollator to support a fixed ratio instead of a random ratio range', 'apply masks to gather specific patches from a tensor using torch gather', 'apply masks to select context patches from a batch of patch tensors', 'apply masks to select target patches from a batch of patch tensors', 'review the apply_masks function that gathers patches from tensors using mask indices', 'summarize the apply_masks function for iJEPa mask-based patch selection']
```

Usage

```
{'apply_masks_gather_patches': 'apply masks to gather specific patches from a tensor using torch gather', 'apply_masks_select_context_patches': 'apply masks to select context patches from a batch of patch tensors', 'apply_masks_select_target_patches': 'apply masks to select target patches from a batch of patch tensors', 'review_apply_masks': 'review the apply_masks function that gathers patches from tensors using mask indices', 'summarize_apply_masks': 'summarize the apply_masks function for iJEPa mask-based patch selection'}
```

