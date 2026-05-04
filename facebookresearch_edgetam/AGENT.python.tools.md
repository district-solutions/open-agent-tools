# Agent Python Tools

- repo: facebookresearch/edgetam
- repo_uri: https://github.com/facebookresearch/edgetam

## File: facebookresearch_edgetam/gradio_app.py

Prompts

```
['run the EdgeTAM gradio demo app for video object segmentation and tracking', 'create a function that reads a video file and returns its frames per second using OpenCV', 'build a function that loads all frames from a video and initializes the SAM2 predictor state', 'create a function that adds include or exclude points to segment an object on the first frame', 'build a function that propagates segmentation masks across all video frames and exports an MP4', 'build the EdgeTAM package with pip install -e . including all required dependencies', 'build the SAM 2 CUDA extension by running python setup.py build_ext with SAM2_BUILD_CUDA=1', 'install EdgeTAM with optional extras like gradio or coreml using pip install -e .[gradio]', 'review the get_extensions function that conditionally creates a CUDAExtension for sam2._C from connected_components.cu', 'review the BuildExtensionIgnoreErrors class that extends BuildExtension to gracefully handle CUDA build failures']
```

Usage

```
{'run_gradio_app': 'run the EdgeTAM gradio demo app for video object segmentation and tracking', 'get_video_fps': 'create a function that reads a video file and returns its frames per second using OpenCV', 'preprocess_video_in': 'build a function that loads all frames from a video and initializes the SAM2 predictor state', 'segment_with_points': 'create a function that adds include or exclude points to segment an object on the first frame', 'propagate_to_all': 'build a function that propagates segmentation masks across all video frames and exports an MP4'}
```

## File: facebookresearch_edgetam/setup.py

Prompts

```
['run the EdgeTAM gradio demo app for video object segmentation and tracking', 'create a function that reads a video file and returns its frames per second using OpenCV', 'build a function that loads all frames from a video and initializes the SAM2 predictor state', 'create a function that adds include or exclude points to segment an object on the first frame', 'build a function that propagates segmentation masks across all video frames and exports an MP4', 'build the EdgeTAM package with pip install -e . including all required dependencies', 'build the SAM 2 CUDA extension by running python setup.py build_ext with SAM2_BUILD_CUDA=1', 'install EdgeTAM with optional extras like gradio or coreml using pip install -e .[gradio]', 'review the get_extensions function that conditionally creates a CUDAExtension for sam2._C from connected_components.cu', 'review the BuildExtensionIgnoreErrors class that extends BuildExtension to gracefully handle CUDA build failures']
```

Usage

```
{'build_edgetam_package': 'build the EdgeTAM package with pip install -e . including all required dependencies', 'build_cuda_extension': 'build the SAM 2 CUDA extension by running python setup.py build_ext with SAM2_BUILD_CUDA=1', 'install_edgetam_with_extras': 'install EdgeTAM with optional extras like gradio or coreml using pip install -e .[gradio]', 'review_get_extensions': 'review the get_extensions function that conditionally creates a CUDAExtension for sam2._C from connected_components.cu', 'review_BuildExtensionIgnoreErrors': 'review the BuildExtensionIgnoreErrors class that extends BuildExtension to gracefully handle CUDA build failures'}
```

