# Agent Python Tools

- repo: facebookresearch/neural-light-fields
- repo_uri: https://github.com/facebookresearch/neural-light-fields

## File: facebookresearch_neural-light-fields/baselines/third_party/evaluation/lpips_tf.py

Prompts

```
['compute the LPIPS perceptual distance between two image tensors using a pretrained AlexNet model', 'run the LPIPS metric on two images using the VGG network instead of AlexNet', 'test the LPIPS function with a batch of image tensors and verify distance output shape', 'review the lpips function to understand how input tensors are normalized from [0,1] to [-1,1]', 'summarize how the lpips function loads a frozen TensorFlow graph from a .pb file', 'run the evaluation script comparing ground truth and predicted images using PSNR, SSIM, and LPIPS metrics', 'run the evaluation in lightfield mode to compare 17x17 lightfield view images excluding every 4th row and column', 'run the evaluation with gamma correction applied to both ground truth and predicted images before computing metrics', 'run the evaluation using E-LPIPS instead of standard LPIPS for perceptual image quality comparison', 'run the evaluation in same_dir mode to compare ground truth and predicted images from a single directory']
```

Usage

```
{'compute_lpips_distance': 'compute the LPIPS perceptual distance between two image tensors using a pretrained AlexNet model', 'run_lpips_with_vgg': 'run the LPIPS metric on two images using the VGG network instead of AlexNet', 'test_lpips_batch': 'test the LPIPS function with a batch of image tensors and verify distance output shape', 'review_lpips_normalization': 'review the lpips function to understand how input tensors are normalized from [0,1] to [-1,1]', 'summarize_lpips_graph_loading': 'summarize how the lpips function loads a frozen TensorFlow graph from a .pb file'}
```

## File: facebookresearch_neural-light-fields/baselines/third_party/evaluation/run_evaluation.py

Prompts

```
['compute the LPIPS perceptual distance between two image tensors using a pretrained AlexNet model', 'run the LPIPS metric on two images using the VGG network instead of AlexNet', 'test the LPIPS function with a batch of image tensors and verify distance output shape', 'review the lpips function to understand how input tensors are normalized from [0,1] to [-1,1]', 'summarize how the lpips function loads a frozen TensorFlow graph from a .pb file', 'run the evaluation script comparing ground truth and predicted images using PSNR, SSIM, and LPIPS metrics', 'run the evaluation in lightfield mode to compare 17x17 lightfield view images excluding every 4th row and column', 'run the evaluation with gamma correction applied to both ground truth and predicted images before computing metrics', 'run the evaluation using E-LPIPS instead of standard LPIPS for perceptual image quality comparison', 'run the evaluation in same_dir mode to compare ground truth and predicted images from a single directory']
```

Usage

```
{'run_evaluation_cli': 'run the evaluation script comparing ground truth and predicted images using PSNR, SSIM, and LPIPS metrics', 'run_lightfield_evaluation': 'run the evaluation in lightfield mode to compare 17x17 lightfield view images excluding every 4th row and column', 'run_gamma_corrected_evaluation': 'run the evaluation with gamma correction applied to both ground truth and predicted images before computing metrics', 'run_elpips_evaluation': 'run the evaluation using E-LPIPS instead of standard LPIPS for perceptual image quality comparison', 'run_same_dir_evaluation': 'run the evaluation in same_dir mode to compare ground truth and predicted images from a single directory'}
```

