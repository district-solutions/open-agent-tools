# Agent Python Tools

- repo: facebookresearch/cutler
- repo_uri: https://github.com/facebookresearch/cutler

## File: facebookresearch_cutler/videocutler/demo_video/colormap.py

Prompts

```
['get the full colormap as a numpy array of Nx3 colors scaled to 0-255 or 0-1 range', 'get a single random color from the colormap as an RGB or BGR vector', 'get N unique random colors sampled from the colormap for visualization', 'select specific colors from the colormap by providing explicit index values', 'run the module to display a grid preview of all colormap colors using OpenCV', 'run video segmentation on a list of image frames using the VideoCutLER demo with a config file', 'run video segmentation on a video file using the VideoCutLER demo and save visualization output', 'setup a detectron2 config by merging a YAML config file with command-line options and freezing it', 'save a list of segmentation masks as a palette-encoded PNG image using the PALETTE constant', 'test whether a given codec and file extension are supported by OpenCV VideoWriter', 'run the VisualizationDemo class on a list of video frames to get predictions and visualized output', 'create a VideoPredictor from a Detectron2 config to run inference on a sequence of video frames', 'run the AsyncPredictor class across multiple GPUs for asynchronous video frame prediction with ordered results', 'review the VisualizationDemo run_on_video method to understand how it filters predictions by confidence threshold', 'refactor the AsyncPredictor _PredictWorker subprocess class to customize the prediction loop or add logging', 'create a TrackVisualizer instance with an RGB image and optional metadata for video instance tracking', 'draw instance-level prediction results including boxes, masks, and labels on an image using TrackVisualizer', 'jitter an RGB color using a predefined ID jitter vector to produce a slightly different color', 'review the TrackVisualizer class that extends detectron2 Visualizer for video instance segmentation visualization', 'summarize the _ID_JITTERS constant list of 128 RGB jitter vectors used for color variation']
```

Usage

```
{'get_colormap_array': 'get the full colormap as a numpy array of Nx3 colors scaled to 0-255 or 0-1 range', 'get_random_color': 'get a single random color from the colormap as an RGB or BGR vector', 'get_random_colors': 'get N unique random colors sampled from the colormap for visualization', 'select_colors_by_index': 'select specific colors from the colormap by providing explicit index values', 'run_colormap_preview': 'run the module to display a grid preview of all colormap colors using OpenCV'}
```

## File: facebookresearch_cutler/videocutler/demo_video/demo.py

Prompts

```
['get the full colormap as a numpy array of Nx3 colors scaled to 0-255 or 0-1 range', 'get a single random color from the colormap as an RGB or BGR vector', 'get N unique random colors sampled from the colormap for visualization', 'select specific colors from the colormap by providing explicit index values', 'run the module to display a grid preview of all colormap colors using OpenCV', 'run video segmentation on a list of image frames using the VideoCutLER demo with a config file', 'run video segmentation on a video file using the VideoCutLER demo and save visualization output', 'setup a detectron2 config by merging a YAML config file with command-line options and freezing it', 'save a list of segmentation masks as a palette-encoded PNG image using the PALETTE constant', 'test whether a given codec and file extension are supported by OpenCV VideoWriter', 'run the VisualizationDemo class on a list of video frames to get predictions and visualized output', 'create a VideoPredictor from a Detectron2 config to run inference on a sequence of video frames', 'run the AsyncPredictor class across multiple GPUs for asynchronous video frame prediction with ordered results', 'review the VisualizationDemo run_on_video method to understand how it filters predictions by confidence threshold', 'refactor the AsyncPredictor _PredictWorker subprocess class to customize the prediction loop or add logging', 'create a TrackVisualizer instance with an RGB image and optional metadata for video instance tracking', 'draw instance-level prediction results including boxes, masks, and labels on an image using TrackVisualizer', 'jitter an RGB color using a predefined ID jitter vector to produce a slightly different color', 'review the TrackVisualizer class that extends detectron2 Visualizer for video instance segmentation visualization', 'summarize the _ID_JITTERS constant list of 128 RGB jitter vectors used for color variation']
```

Usage

```
{'run_video_segmentation_on_image_frames': 'run video segmentation on a list of image frames using the VideoCutLER demo with a config file', 'run_video_segmentation_on_video_file': 'run video segmentation on a video file using the VideoCutLER demo and save visualization output', 'setup_cfg_merge_config': 'setup a detectron2 config by merging a YAML config file with command-line options and freezing it', 'save_masks_palette_image': 'save a list of segmentation masks as a palette-encoded PNG image using the PALETTE constant', 'test_opencv_video_format': 'test whether a given codec and file extension are supported by OpenCV VideoWriter'}
```

## File: facebookresearch_cutler/videocutler/demo_video/predictor.py

Prompts

```
['get the full colormap as a numpy array of Nx3 colors scaled to 0-255 or 0-1 range', 'get a single random color from the colormap as an RGB or BGR vector', 'get N unique random colors sampled from the colormap for visualization', 'select specific colors from the colormap by providing explicit index values', 'run the module to display a grid preview of all colormap colors using OpenCV', 'run video segmentation on a list of image frames using the VideoCutLER demo with a config file', 'run video segmentation on a video file using the VideoCutLER demo and save visualization output', 'setup a detectron2 config by merging a YAML config file with command-line options and freezing it', 'save a list of segmentation masks as a palette-encoded PNG image using the PALETTE constant', 'test whether a given codec and file extension are supported by OpenCV VideoWriter', 'run the VisualizationDemo class on a list of video frames to get predictions and visualized output', 'create a VideoPredictor from a Detectron2 config to run inference on a sequence of video frames', 'run the AsyncPredictor class across multiple GPUs for asynchronous video frame prediction with ordered results', 'review the VisualizationDemo run_on_video method to understand how it filters predictions by confidence threshold', 'refactor the AsyncPredictor _PredictWorker subprocess class to customize the prediction loop or add logging', 'create a TrackVisualizer instance with an RGB image and optional metadata for video instance tracking', 'draw instance-level prediction results including boxes, masks, and labels on an image using TrackVisualizer', 'jitter an RGB color using a predefined ID jitter vector to produce a slightly different color', 'review the TrackVisualizer class that extends detectron2 Visualizer for video instance segmentation visualization', 'summarize the _ID_JITTERS constant list of 128 RGB jitter vectors used for color variation']
```

Usage

```
{'run_VisualizationDemo_on_video': 'run the VisualizationDemo class on a list of video frames to get predictions and visualized output', 'create_VideoPredictor_for_frames': 'create a VideoPredictor from a Detectron2 config to run inference on a sequence of video frames', 'run_AsyncPredictor_multi_gpu': 'run the AsyncPredictor class across multiple GPUs for asynchronous video frame prediction with ordered results', 'review_VisualizationDemo_run_on_video': 'review the VisualizationDemo run_on_video method to understand how it filters predictions by confidence threshold', 'refactor_AsyncPredictor_PredictWorker': 'refactor the AsyncPredictor _PredictWorker subprocess class to customize the prediction loop or add logging'}
```

## File: facebookresearch_cutler/videocutler/demo_video/visualizer.py

Prompts

```
['get the full colormap as a numpy array of Nx3 colors scaled to 0-255 or 0-1 range', 'get a single random color from the colormap as an RGB or BGR vector', 'get N unique random colors sampled from the colormap for visualization', 'select specific colors from the colormap by providing explicit index values', 'run the module to display a grid preview of all colormap colors using OpenCV', 'run video segmentation on a list of image frames using the VideoCutLER demo with a config file', 'run video segmentation on a video file using the VideoCutLER demo and save visualization output', 'setup a detectron2 config by merging a YAML config file with command-line options and freezing it', 'save a list of segmentation masks as a palette-encoded PNG image using the PALETTE constant', 'test whether a given codec and file extension are supported by OpenCV VideoWriter', 'run the VisualizationDemo class on a list of video frames to get predictions and visualized output', 'create a VideoPredictor from a Detectron2 config to run inference on a sequence of video frames', 'run the AsyncPredictor class across multiple GPUs for asynchronous video frame prediction with ordered results', 'review the VisualizationDemo run_on_video method to understand how it filters predictions by confidence threshold', 'refactor the AsyncPredictor _PredictWorker subprocess class to customize the prediction loop or add logging', 'create a TrackVisualizer instance with an RGB image and optional metadata for video instance tracking', 'draw instance-level prediction results including boxes, masks, and labels on an image using TrackVisualizer', 'jitter an RGB color using a predefined ID jitter vector to produce a slightly different color', 'review the TrackVisualizer class that extends detectron2 Visualizer for video instance segmentation visualization', 'summarize the _ID_JITTERS constant list of 128 RGB jitter vectors used for color variation']
```

Usage

```
{'create_track_visualizer': 'create a TrackVisualizer instance with an RGB image and optional metadata for video instance tracking', 'draw_instance_predictions': 'draw instance-level prediction results including boxes, masks, and labels on an image using TrackVisualizer', 'jitter_color': 'jitter an RGB color using a predefined ID jitter vector to produce a slightly different color', 'review_track_visualizer_class': 'review the TrackVisualizer class that extends detectron2 Visualizer for video instance segmentation visualization', 'summarize_id_jitters_constant': 'summarize the _ID_JITTERS constant list of 128 RGB jitter vectors used for color variation'}
```

