# Agent Python Tools

- repo: facebookresearch/stablesignature
- repo_uri: https://github.com/facebookresearch/stable_signature

## File: facebookresearch_stablesignature/src/ldm/modules/image_degradation/bsrgan.py

Prompts

```
['build a python module to apply BSRGAN degradation model to an image and return low-quality and high-quality patches', 'create a function that applies BSRGAN variant degradation to an image and returns a dictionary with the degraded image', 'build a python module to apply the extended BSRGAN plus degradation model combining BSRGAN and Real-ESRGAN degradations', 'create a function that adds random anisotropic or Gaussian blur to an image based on scale factor', 'build a python module to add JPEG compression noise to an image with a random quality factor between 30 and 95', 'add random Gaussian noise to an image with configurable noise level range', 'generate an anisotropic Gaussian kernel with configurable size, rotation angle, and eigenvalue scaling', 'calculate the PSNR between two images with range 0-255 and an optional border to exclude', 'calculate the SSIM between two images with range 0-255 and an optional border to exclude', 'resize a numpy image array using bicubic interpolation with optional antialiasing at a given scale', 'apply one of eight flip and rotation augmentations to a numpy image by mode index', 'convert an RGB image to YCbCr color space returning only the Y channel or all three']
```

Usage

```
{'degradation_bsrgan': 'build a python module to apply BSRGAN degradation model to an image and return low-quality and high-quality patches', 'degradation_bsrgan_variant': 'create a function that applies BSRGAN variant degradation to an image and returns a dictionary with the degraded image', 'degradation_bsrgan_plus': 'build a python module to apply the extended BSRGAN plus degradation model combining BSRGAN and Real-ESRGAN degradations', 'add_blur': 'create a function that adds random anisotropic or Gaussian blur to an image based on scale factor', 'add_JPEG_noise': 'build a python module to add JPEG compression noise to an image with a random quality factor between 30 and 95'}
```

## File: facebookresearch_stablesignature/src/ldm/modules/image_degradation/bsrgan_light.py

Prompts

```
['build a python module to apply BSRGAN degradation model to an image and return low-quality and high-quality patches', 'create a function that applies BSRGAN variant degradation to an image and returns a dictionary with the degraded image', 'build a python module to apply the extended BSRGAN plus degradation model combining BSRGAN and Real-ESRGAN degradations', 'create a function that adds random anisotropic or Gaussian blur to an image based on scale factor', 'build a python module to add JPEG compression noise to an image with a random quality factor between 30 and 95', 'add random Gaussian noise to an image with configurable noise level range', 'generate an anisotropic Gaussian kernel with configurable size, rotation angle, and eigenvalue scaling', 'calculate the PSNR between two images with range 0-255 and an optional border to exclude', 'calculate the SSIM between two images with range 0-255 and an optional border to exclude', 'resize a numpy image array using bicubic interpolation with optional antialiasing at a given scale', 'apply one of eight flip and rotation augmentations to a numpy image by mode index', 'convert an RGB image to YCbCr color space returning only the Y channel or all three']
```

Usage

```
{'degradation_bsrgan': 'apply the BSRGAN degradation model to generate low-quality and high-quality image patches for super-resolution training', 'degradation_bsrgan_variant': 'apply the BSRGAN variant degradation model to produce a degraded low-quality image with JPEG noise', 'add_blur': 'apply random anisotropic or isotropic Gaussian blur to an image using a kernel', 'add_Gaussian_noise': 'add random Gaussian noise to an image with configurable noise level range', 'anisotropic_Gaussian': 'generate an anisotropic Gaussian kernel with configurable size, rotation angle, and eigenvalue scaling'}
```

## File: facebookresearch_stablesignature/src/ldm/modules/image_degradation/utils_image.py

Prompts

```
['build a python module to apply BSRGAN degradation model to an image and return low-quality and high-quality patches', 'create a function that applies BSRGAN variant degradation to an image and returns a dictionary with the degraded image', 'build a python module to apply the extended BSRGAN plus degradation model combining BSRGAN and Real-ESRGAN degradations', 'create a function that adds random anisotropic or Gaussian blur to an image based on scale factor', 'build a python module to add JPEG compression noise to an image with a random quality factor between 30 and 95', 'add random Gaussian noise to an image with configurable noise level range', 'generate an anisotropic Gaussian kernel with configurable size, rotation angle, and eigenvalue scaling', 'calculate the PSNR between two images with range 0-255 and an optional border to exclude', 'calculate the SSIM between two images with range 0-255 and an optional border to exclude', 'resize a numpy image array using bicubic interpolation with optional antialiasing at a given scale', 'apply one of eight flip and rotation augmentations to a numpy image by mode index', 'convert an RGB image to YCbCr color space returning only the Y channel or all three']
```

Usage

```
{'calculate_psnr': 'calculate the PSNR between two images with range 0-255 and an optional border to exclude', 'calculate_ssim': 'calculate the SSIM between two images with range 0-255 and an optional border to exclude', 'imresize_np': 'resize a numpy image array using bicubic interpolation with optional antialiasing at a given scale', 'augment_img': 'apply one of eight flip and rotation augmentations to a numpy image by mode index', 'rgb2ycbcr': 'convert an RGB image to YCbCr color space returning only the Y channel or all three'}
```

