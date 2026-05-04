# Agent Python Tools

- repo: facebookresearch/avid-cma
- repo_uri: https://github.com/facebookresearch/avid-cma

## File: facebookresearch_avid-cma/utils/videotransforms/utils/functional.py

Prompts

```
['normalize a tensor by subtracting mean and dividing by std in place', 'normalize video frame tensors using provided mean and std values', 'normalize a batch of tensors with the same mean and std parameters', 'review the normalize function to understand its in-place tensor operations', 'test the normalize function with sample tensor mean and std values', 'convert a numpy image array from HWC format to CWH format using transpose', 'convert a 2D grayscale numpy image array to a single-channel CWH format', 'test the convert_img function with a 3D numpy array to verify HWC to CWH conversion', 'test the convert_img function with a 2D numpy array to verify grayscale channel expansion', 'refactor the convert_img function to add input shape validation and error handling']
```

Usage

```
{'normalize_tensor': 'normalize a tensor by subtracting mean and dividing by std in place', 'normalize_video_frames': 'normalize video frame tensors using provided mean and std values', 'normalize_batch': 'normalize a batch of tensors with the same mean and std parameters', 'review_normalize': 'review the normalize function to understand its in-place tensor operations', 'test_normalize': 'test the normalize function with sample tensor mean and std values'}
```

## File: facebookresearch_avid-cma/utils/videotransforms/utils/images.py

Prompts

```
['normalize a tensor by subtracting mean and dividing by std in place', 'normalize video frame tensors using provided mean and std values', 'normalize a batch of tensors with the same mean and std parameters', 'review the normalize function to understand its in-place tensor operations', 'test the normalize function with sample tensor mean and std values', 'convert a numpy image array from HWC format to CWH format using transpose', 'convert a 2D grayscale numpy image array to a single-channel CWH format', 'test the convert_img function with a 3D numpy array to verify HWC to CWH conversion', 'test the convert_img function with a 2D numpy array to verify grayscale channel expansion', 'refactor the convert_img function to add input shape validation and error handling']
```

Usage

```
{'convert_img_HWC_to_CWH': 'convert a numpy image array from HWC format to CWH format using transpose', 'convert_img_grayscale_to_channel_first': 'convert a 2D grayscale numpy image array to a single-channel CWH format', 'test_convert_img_3d_array': 'test the convert_img function with a 3D numpy array to verify HWC to CWH conversion', 'test_convert_img_2d_array': 'test the convert_img function with a 2D numpy array to verify grayscale channel expansion', 'refactor_convert_img_validation': 'refactor the convert_img function to add input shape validation and error handling'}
```

