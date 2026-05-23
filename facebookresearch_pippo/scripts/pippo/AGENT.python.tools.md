# Agent Python Tools

- repo: facebookresearch/pippo
- repo_uri: https://github.com/facebookresearch/pippo

## File: facebookresearch_pippo/scripts/pippo/generate_ref.py

Prompts

```
['create an InferenceSampler wrapping a DDIM sampler with configurable conditioning and unconditional sampling parameters', 'run the InferenceSampler to generate multiview images from a batch of reference images and camera poses', 'run generate_and_save to iterate over a dataloader, generate samples via the sampler, and save image grids to disk', 'review the save_image function that assembles generated samples, ground truth, and reference images into a composite grid for saving', 'refactor the InferenceSampler cond_fn method to customize how conditioning tensors are passed to the model during inference', 'run the reprojection error script to compute L2 reprojection metrics on generated samples', 'match features between two images using LightGlue and DISK to find corresponding keypoints', 'load the LightGlue matcher and DISK feature extractor models onto a GPU device', 'compute the L2 reprojection error for generated views using camera intrinsics and extrinsics', 'review the match_features function that uses DISK keypoints and LightGlue matching for image pairs']
```

Usage

```
{'create_InferenceSampler': 'create an InferenceSampler wrapping a DDIM sampler with configurable conditioning and unconditional sampling parameters', 'run_InferenceSampler_generate_image': 'run the InferenceSampler to generate multiview images from a batch of reference images and camera poses', 'run_generate_and_save': 'run generate_and_save to iterate over a dataloader, generate samples via the sampler, and save image grids to disk', 'review_save_image': 'review the save_image function that assembles generated samples, ground truth, and reference images into a composite grid for saving', 'refactor_InferenceSampler_cond_fn': 'refactor the InferenceSampler cond_fn method to customize how conditioning tensors are passed to the model during inference'}
```

## File: facebookresearch_pippo/scripts/pippo/reprojection_error.py

Prompts

```
['create an InferenceSampler wrapping a DDIM sampler with configurable conditioning and unconditional sampling parameters', 'run the InferenceSampler to generate multiview images from a batch of reference images and camera poses', 'run generate_and_save to iterate over a dataloader, generate samples via the sampler, and save image grids to disk', 'review the save_image function that assembles generated samples, ground truth, and reference images into a composite grid for saving', 'refactor the InferenceSampler cond_fn method to customize how conditioning tensors are passed to the model during inference', 'run the reprojection error script to compute L2 reprojection metrics on generated samples', 'match features between two images using LightGlue and DISK to find corresponding keypoints', 'load the LightGlue matcher and DISK feature extractor models onto a GPU device', 'compute the L2 reprojection error for generated views using camera intrinsics and extrinsics', 'review the match_features function that uses DISK keypoints and LightGlue matching for image pairs']
```

Usage

```
{'run_reprojection_error': 'run the reprojection error script to compute L2 reprojection metrics on generated samples', 'match_features_between_images': 'match features between two images using LightGlue and DISK to find corresponding keypoints', 'load_lightglue_model': 'load the LightGlue matcher and DISK feature extractor models onto a GPU device', 'compute_l2_reproj_error': 'compute the L2 reprojection error for generated views using camera intrinsics and extrinsics', 'review_match_features': 'review the match_features function that uses DISK keypoints and LightGlue matching for image pairs'}
```

