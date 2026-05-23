# Agent Python Tools

- repo: facebookresearch/synsin
- repo_uri: https://github.com/facebookresearch/synsin

## File: facebookresearch_synsin/evaluation/eval.py

Prompts

```
['run the evaluation script to compute PSNR, SSIM, and perceptual similarity metrics on a trained model', 'run the psnr_mask function to compute masked PSNR between output and sampled images', 'run the ssim_mask function to compute masked SSIM between output and sampled images', 'run the perceptual_sim_mask function to compute masked perceptual similarity using a VGG16 network', 'run the check_initial_batch function to validate camera parameters match cached evaluation values', 'run the KITTI dataset evaluation script to predict new views and save rendered images', 'create a PyTorch Dataset class that loads KITTI image pairs with camera intrinsics and poses', 'review the Dataset load_image method that normalizes RGB images to [-1, 1] tensors', 'review the Dataset __getitem__ method that returns image pairs with camera projection matrices', 'refactor the model loading logic to handle sync batch norm and flexible image sizes', 'run the CLI to compute perceptual similarity, PSNR, and SSIM metrics for predicted vs target images in a folder', 'compute perceptual similarity, PSNR, and SSIM metrics by comparing predicted images against target images across subfolders', 'load an image file as a PyTorch tensor on GPU with optional resizing to a specified dimension', 'run the evaluation CLI with the take_every_other flag to pair and aggregate results from consecutive subfolders', 'review the compute_perceptual_similarity function that uses VGG16 via PNet to calculate perceptual similarity across image pairs', 'calculate the SSIM similarity score between two image tensors with an optional mask', 'calculate the PSNR value between two image tensors with an optional mask', 'calculate the perceptual similarity distance between two images using a VGG16 model', 'calculate the SSIM metric between two masked image tensors for region-specific comparison', 'calculate the PSNR metric between two masked image tensors for region-specific comparison']
```

Usage

```
{'run_evaluation': 'run the evaluation script to compute PSNR, SSIM, and perceptual similarity metrics on a trained model', 'run_psnr_mask': 'run the psnr_mask function to compute masked PSNR between output and sampled images', 'run_ssim_mask': 'run the ssim_mask function to compute masked SSIM between output and sampled images', 'run_perceptual_sim_mask': 'run the perceptual_sim_mask function to compute masked perceptual similarity using a VGG16 network', 'run_check_initial_batch': 'run the check_initial_batch function to validate camera parameters match cached evaluation values'}
```

## File: facebookresearch_synsin/evaluation/eval_kitti.py

Prompts

```
['run the evaluation script to compute PSNR, SSIM, and perceptual similarity metrics on a trained model', 'run the psnr_mask function to compute masked PSNR between output and sampled images', 'run the ssim_mask function to compute masked SSIM between output and sampled images', 'run the perceptual_sim_mask function to compute masked perceptual similarity using a VGG16 network', 'run the check_initial_batch function to validate camera parameters match cached evaluation values', 'run the KITTI dataset evaluation script to predict new views and save rendered images', 'create a PyTorch Dataset class that loads KITTI image pairs with camera intrinsics and poses', 'review the Dataset load_image method that normalizes RGB images to [-1, 1] tensors', 'review the Dataset __getitem__ method that returns image pairs with camera projection matrices', 'refactor the model loading logic to handle sync batch norm and flexible image sizes', 'run the CLI to compute perceptual similarity, PSNR, and SSIM metrics for predicted vs target images in a folder', 'compute perceptual similarity, PSNR, and SSIM metrics by comparing predicted images against target images across subfolders', 'load an image file as a PyTorch tensor on GPU with optional resizing to a specified dimension', 'run the evaluation CLI with the take_every_other flag to pair and aggregate results from consecutive subfolders', 'review the compute_perceptual_similarity function that uses VGG16 via PNet to calculate perceptual similarity across image pairs', 'calculate the SSIM similarity score between two image tensors with an optional mask', 'calculate the PSNR value between two image tensors with an optional mask', 'calculate the perceptual similarity distance between two images using a VGG16 model', 'calculate the SSIM metric between two masked image tensors for region-specific comparison', 'calculate the PSNR metric between two masked image tensors for region-specific comparison']
```

Usage

```
{'run_kitti_evaluation': 'run the KITTI dataset evaluation script to predict new views and save rendered images', 'create_Dataset_class': 'create a PyTorch Dataset class that loads KITTI image pairs with camera intrinsics and poses', 'review_Dataset_load_image': 'review the Dataset load_image method that normalizes RGB images to [-1, 1] tensors', 'review_Dataset_getitem': 'review the Dataset __getitem__ method that returns image pairs with camera projection matrices', 'refactor_model_loading': 'refactor the model loading logic to handle sync batch norm and flexible image sizes'}
```

## File: facebookresearch_synsin/evaluation/evaluate_perceptualsim.py

Prompts

```
['run the evaluation script to compute PSNR, SSIM, and perceptual similarity metrics on a trained model', 'run the psnr_mask function to compute masked PSNR between output and sampled images', 'run the ssim_mask function to compute masked SSIM between output and sampled images', 'run the perceptual_sim_mask function to compute masked perceptual similarity using a VGG16 network', 'run the check_initial_batch function to validate camera parameters match cached evaluation values', 'run the KITTI dataset evaluation script to predict new views and save rendered images', 'create a PyTorch Dataset class that loads KITTI image pairs with camera intrinsics and poses', 'review the Dataset load_image method that normalizes RGB images to [-1, 1] tensors', 'review the Dataset __getitem__ method that returns image pairs with camera projection matrices', 'refactor the model loading logic to handle sync batch norm and flexible image sizes', 'run the CLI to compute perceptual similarity, PSNR, and SSIM metrics for predicted vs target images in a folder', 'compute perceptual similarity, PSNR, and SSIM metrics by comparing predicted images against target images across subfolders', 'load an image file as a PyTorch tensor on GPU with optional resizing to a specified dimension', 'run the evaluation CLI with the take_every_other flag to pair and aggregate results from consecutive subfolders', 'review the compute_perceptual_similarity function that uses VGG16 via PNet to calculate perceptual similarity across image pairs', 'calculate the SSIM similarity score between two image tensors with an optional mask', 'calculate the PSNR value between two image tensors with an optional mask', 'calculate the perceptual similarity distance between two images using a VGG16 model', 'calculate the SSIM metric between two masked image tensors for region-specific comparison', 'calculate the PSNR metric between two masked image tensors for region-specific comparison']
```

Usage

```
{'run_perceptual_similarity_evaluation': 'run the CLI to compute perceptual similarity, PSNR, and SSIM metrics for predicted vs target images in a folder', 'compute_perceptual_similarity_function': 'compute perceptual similarity, PSNR, and SSIM metrics by comparing predicted images against target images across subfolders', 'load_img_function': 'load an image file as a PyTorch tensor on GPU with optional resizing to a specified dimension', 'run_evaluation_with_take_every_other': 'run the evaluation CLI with the take_every_other flag to pair and aggregate results from consecutive subfolders', 'review_compute_perceptual_similarity': 'review the compute_perceptual_similarity function that uses VGG16 via PNet to calculate perceptual similarity across image pairs'}
```

## File: facebookresearch_synsin/evaluation/metrics.py

Prompts

```
['run the evaluation script to compute PSNR, SSIM, and perceptual similarity metrics on a trained model', 'run the psnr_mask function to compute masked PSNR between output and sampled images', 'run the ssim_mask function to compute masked SSIM between output and sampled images', 'run the perceptual_sim_mask function to compute masked perceptual similarity using a VGG16 network', 'run the check_initial_batch function to validate camera parameters match cached evaluation values', 'run the KITTI dataset evaluation script to predict new views and save rendered images', 'create a PyTorch Dataset class that loads KITTI image pairs with camera intrinsics and poses', 'review the Dataset load_image method that normalizes RGB images to [-1, 1] tensors', 'review the Dataset __getitem__ method that returns image pairs with camera projection matrices', 'refactor the model loading logic to handle sync batch norm and flexible image sizes', 'run the CLI to compute perceptual similarity, PSNR, and SSIM metrics for predicted vs target images in a folder', 'compute perceptual similarity, PSNR, and SSIM metrics by comparing predicted images against target images across subfolders', 'load an image file as a PyTorch tensor on GPU with optional resizing to a specified dimension', 'run the evaluation CLI with the take_every_other flag to pair and aggregate results from consecutive subfolders', 'review the compute_perceptual_similarity function that uses VGG16 via PNet to calculate perceptual similarity across image pairs', 'calculate the SSIM similarity score between two image tensors with an optional mask', 'calculate the PSNR value between two image tensors with an optional mask', 'calculate the perceptual similarity distance between two images using a VGG16 model', 'calculate the SSIM metric between two masked image tensors for region-specific comparison', 'calculate the PSNR metric between two masked image tensors for region-specific comparison']
```

Usage

```
{'calculate_ssim_metric': 'calculate the SSIM similarity score between two image tensors with an optional mask', 'calculate_psnr': 'calculate the PSNR value between two image tensors with an optional mask', 'calculate_perceptual_similarity': 'calculate the perceptual similarity distance between two images using a VGG16 model', 'calculate_ssim_with_mask': 'calculate the SSIM metric between two masked image tensors for region-specific comparison', 'calculate_psnr_with_mask': 'calculate the PSNR metric between two masked image tensors for region-specific comparison'}
```

