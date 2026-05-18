# Agent Python Tools

- repo: facebookresearch/mils
- repo_uri: https://github.com/facebookresearch/mils

## File: facebookresearch_mils/task_utils/style_transfer.py

Prompts

```
['build a VGG19-based model with style and content loss layers for neural style transfer', 'create a normalized Gram matrix from a 4D feature tensor for style representation', 'create a StyleLoss module that computes MSE between input and target Gram matrices', 'create a ContentLoss module that computes MSE between input and target feature maps', 'load an image file, resize to 256x256, and convert to a PyTorch tensor', 'read frames from a video file using decord or torchvision decoder with configurable sampling', 'sample uniformly spaced frame indices from a video given fps and length range', 'stack video frames into a grid layout with configurable rows and columns', 'subsample elements from an iterator to a bounded max size using exponential frequency', 'convert all mp4 videos in a directory to individual png frame images']
```

Usage

```
{'build_style_transfer_model': 'build a VGG19-based model with style and content loss layers for neural style transfer', 'create_gram_matrix': 'create a normalized Gram matrix from a 4D feature tensor for style representation', 'create_style_loss_module': 'create a StyleLoss module that computes MSE between input and target Gram matrices', 'create_content_loss_module': 'create a ContentLoss module that computes MSE between input and target feature maps', 'load_image_for_transfer': 'load an image file, resize to 256x256, and convert to a PyTorch tensor'}
```

## File: facebookresearch_mils/task_utils/video_analysis.py

Prompts

```
['build a VGG19-based model with style and content loss layers for neural style transfer', 'create a normalized Gram matrix from a 4D feature tensor for style representation', 'create a StyleLoss module that computes MSE between input and target Gram matrices', 'create a ContentLoss module that computes MSE between input and target feature maps', 'load an image file, resize to 256x256, and convert to a PyTorch tensor', 'read frames from a video file using decord or torchvision decoder with configurable sampling', 'sample uniformly spaced frame indices from a video given fps and length range', 'stack video frames into a grid layout with configurable rows and columns', 'subsample elements from an iterator to a bounded max size using exponential frequency', 'convert all mp4 videos in a directory to individual png frame images']
```

Usage

```
{'read_frames_from_video': 'read frames from a video file using decord or torchvision decoder with configurable sampling', 'sample_frame_ids': 'sample uniformly spaced frame indices from a video given fps and length range', 'stack_frames_grid': 'stack video frames into a grid layout with configurable rows and columns', 'subsample_iterator': 'subsample elements from an iterator to a bounded max size using exponential frequency', 'convert_videos_to_images': 'convert all mp4 videos in a directory to individual png frame images'}
```

