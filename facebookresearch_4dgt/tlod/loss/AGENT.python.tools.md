# Agent Python Tools

- repo: facebookresearch/4dgt
- repo_uri: https://github.com/facebookresearch/4dgt

## File: facebookresearch_4dgt/tlod/loss/perc_loss.py

Prompts

```
['create a PerceptualLoss with loss_type zhang using LPIPS VGG for image comparison', 'create a PerceptualLoss with loss_type chen using VGG19 feature extractor for image comparison', 'compute the perceptual loss between two normalized image tensors with an optional mask', 'create a Vgg19FeatureExtractor with shift_scale normalization to extract weighted multi-layer features', 'extract weighted convolutional features from conv1_2 through conv5_2 layers of a VGG19 network', 'run the render_loss forward_and_backward method to compute supervision and regularization loss then backpropagate gradients', 'run the render_loss supervision method to compute per-key weighted loss values between predictions and ground truth', 'run the render_loss regularization method to compute non-pixel-wise regularization loss terms from predictions and ground truth', 'review the render_loss class and its supervision, regularization, and forward_and_backward methods for 4D Gaussian Splatting training', 'refactor the render_loss forward_and_backward PSNR clipping logic to handle divergent gradients across GPU ranks', 'run scale_ls to compute a least-squares optimal scale factor between prediction and ground truth tensors', 'create a scaled prediction tensor from predictions and ground truth using least-squares scaling', 'test scale_ls to verify the scale factor is clamped between scale_min and scale_max', 'review scale_ls to understand how optional masks are applied to predictions and ground truth', 'summarize scale_ls which returns a scaled prediction tensor and its detached scale factor']
```

Usage

```
{'create_perceptual_loss_zhang': 'create a PerceptualLoss with loss_type zhang using LPIPS VGG for image comparison', 'create_perceptual_loss_chen': 'create a PerceptualLoss with loss_type chen using VGG19 feature extractor for image comparison', 'compute_perceptual_loss_forward': 'compute the perceptual loss between two normalized image tensors with an optional mask', 'create_vgg19_feature_extractor': 'create a Vgg19FeatureExtractor with shift_scale normalization to extract weighted multi-layer features', 'extract_vgg19_features': 'extract weighted convolutional features from conv1_2 through conv5_2 layers of a VGG19 network'}
```

## File: facebookresearch_4dgt/tlod/loss/render_loss.py

Prompts

```
['create a PerceptualLoss with loss_type zhang using LPIPS VGG for image comparison', 'create a PerceptualLoss with loss_type chen using VGG19 feature extractor for image comparison', 'compute the perceptual loss between two normalized image tensors with an optional mask', 'create a Vgg19FeatureExtractor with shift_scale normalization to extract weighted multi-layer features', 'extract weighted convolutional features from conv1_2 through conv5_2 layers of a VGG19 network', 'run the render_loss forward_and_backward method to compute supervision and regularization loss then backpropagate gradients', 'run the render_loss supervision method to compute per-key weighted loss values between predictions and ground truth', 'run the render_loss regularization method to compute non-pixel-wise regularization loss terms from predictions and ground truth', 'review the render_loss class and its supervision, regularization, and forward_and_backward methods for 4D Gaussian Splatting training', 'refactor the render_loss forward_and_backward PSNR clipping logic to handle divergent gradients across GPU ranks', 'run scale_ls to compute a least-squares optimal scale factor between prediction and ground truth tensors', 'create a scaled prediction tensor from predictions and ground truth using least-squares scaling', 'test scale_ls to verify the scale factor is clamped between scale_min and scale_max', 'review scale_ls to understand how optional masks are applied to predictions and ground truth', 'summarize scale_ls which returns a scaled prediction tensor and its detached scale factor']
```

Usage

```
{'run_render_loss_forward_and_backward': 'run the render_loss forward_and_backward method to compute supervision and regularization loss then backpropagate gradients', 'run_render_loss_supervision': 'run the render_loss supervision method to compute per-key weighted loss values between predictions and ground truth', 'run_render_loss_regularization': 'run the render_loss regularization method to compute non-pixel-wise regularization loss terms from predictions and ground truth', 'review_render_loss_class': 'review the render_loss class and its supervision, regularization, and forward_and_backward methods for 4D Gaussian Splatting training', 'refactor_render_loss_psnr_clipping': 'refactor the render_loss forward_and_backward PSNR clipping logic to handle divergent gradients across GPU ranks'}
```

## File: facebookresearch_4dgt/tlod/loss/utils.py

Prompts

```
['create a PerceptualLoss with loss_type zhang using LPIPS VGG for image comparison', 'create a PerceptualLoss with loss_type chen using VGG19 feature extractor for image comparison', 'compute the perceptual loss between two normalized image tensors with an optional mask', 'create a Vgg19FeatureExtractor with shift_scale normalization to extract weighted multi-layer features', 'extract weighted convolutional features from conv1_2 through conv5_2 layers of a VGG19 network', 'run the render_loss forward_and_backward method to compute supervision and regularization loss then backpropagate gradients', 'run the render_loss supervision method to compute per-key weighted loss values between predictions and ground truth', 'run the render_loss regularization method to compute non-pixel-wise regularization loss terms from predictions and ground truth', 'review the render_loss class and its supervision, regularization, and forward_and_backward methods for 4D Gaussian Splatting training', 'refactor the render_loss forward_and_backward PSNR clipping logic to handle divergent gradients across GPU ranks', 'run scale_ls to compute a least-squares optimal scale factor between prediction and ground truth tensors', 'create a scaled prediction tensor from predictions and ground truth using least-squares scaling', 'test scale_ls to verify the scale factor is clamped between scale_min and scale_max', 'review scale_ls to understand how optional masks are applied to predictions and ground truth', 'summarize scale_ls which returns a scaled prediction tensor and its detached scale factor']
```

Usage

```
{'run_scale_ls': 'run scale_ls to compute a least-squares optimal scale factor between prediction and ground truth tensors', 'create_scaled_prediction': 'create a scaled prediction tensor from predictions and ground truth using least-squares scaling', 'test_scale_ls_clamping': 'test scale_ls to verify the scale factor is clamped between scale_min and scale_max', 'review_scale_ls_masking': 'review scale_ls to understand how optional masks are applied to predictions and ground truth', 'summarize_scale_ls': 'summarize scale_ls which returns a scaled prediction tensor and its detached scale factor'}
```

