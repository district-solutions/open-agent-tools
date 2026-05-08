# Agent Python Tools

- repo: facebookresearch/mask2former
- repo_uri: https://github.com/facebookresearch/mask2former

## File: facebookresearch_mask2former/demo_video/demo.py

Prompts

```
['run mask2former video segmentation on a list of input image frames and save visualized output', 'run mask2former video segmentation on a video file and save the visualization as an MP4', 'setup a detectron2 config object by merging a YAML config file with command-line options', 'get an argparse parser with arguments for config file, video input, image input, output, and confidence threshold', 'test whether a given codec and file extension are supported by OpenCV VideoWriter', 'run the VisualizationDemo class to predict and visualize instance segmentation on a list of video frames', 'create a VideoPredictor from a Detectron2 config to run inference on a sequence of BGR frames', 'run the AsyncPredictor class to perform asynchronous multi-GPU inference on video frames using multiprocessing', 'review the VideoPredictor __call__ method that preprocesses frames and runs the model with torch.no_grad', 'refactor the AsyncPredictor get method that retrieves results in order using bisect insertion', 'create a TrackVisualizer instance from an RGB image with optional metadata and scale', 'draw instance-level prediction results with boxes, masks, and labels on an image', 'jitter a given RGB color using a deterministic ID-based jitter vector', 'review the TrackVisualizer class that extends detectron2 Visualizer for tracking visualization', 'summarize the _ID_JITTERS constant list of 100 RGB jitter vectors for color variation']
```

Usage

```
{'run_video_segmentation_from_images': 'run mask2former video segmentation on a list of input image frames and save visualized output', 'run_video_segmentation_from_video': 'run mask2former video segmentation on a video file and save the visualization as an MP4', 'setup_cfg': 'setup a detectron2 config object by merging a YAML config file with command-line options', 'get_parser': 'get an argparse parser with arguments for config file, video input, image input, output, and confidence threshold', 'test_opencv_video_format': 'test whether a given codec and file extension are supported by OpenCV VideoWriter'}
```

## File: facebookresearch_mask2former/demo_video/predictor.py

Prompts

```
['run mask2former video segmentation on a list of input image frames and save visualized output', 'run mask2former video segmentation on a video file and save the visualization as an MP4', 'setup a detectron2 config object by merging a YAML config file with command-line options', 'get an argparse parser with arguments for config file, video input, image input, output, and confidence threshold', 'test whether a given codec and file extension are supported by OpenCV VideoWriter', 'run the VisualizationDemo class to predict and visualize instance segmentation on a list of video frames', 'create a VideoPredictor from a Detectron2 config to run inference on a sequence of BGR frames', 'run the AsyncPredictor class to perform asynchronous multi-GPU inference on video frames using multiprocessing', 'review the VideoPredictor __call__ method that preprocesses frames and runs the model with torch.no_grad', 'refactor the AsyncPredictor get method that retrieves results in order using bisect insertion', 'create a TrackVisualizer instance from an RGB image with optional metadata and scale', 'draw instance-level prediction results with boxes, masks, and labels on an image', 'jitter a given RGB color using a deterministic ID-based jitter vector', 'review the TrackVisualizer class that extends detectron2 Visualizer for tracking visualization', 'summarize the _ID_JITTERS constant list of 100 RGB jitter vectors for color variation']
```

Usage

```
{'run_visualization_demo_on_video': 'run the VisualizationDemo class to predict and visualize instance segmentation on a list of video frames', 'create_video_predictor': 'create a VideoPredictor from a Detectron2 config to run inference on a sequence of BGR frames', 'run_async_predictor': 'run the AsyncPredictor class to perform asynchronous multi-GPU inference on video frames using multiprocessing', 'review_video_predictor_call': 'review the VideoPredictor __call__ method that preprocesses frames and runs the model with torch.no_grad', 'refactor_async_predictor_get': 'refactor the AsyncPredictor get method that retrieves results in order using bisect insertion'}
```

## File: facebookresearch_mask2former/demo_video/visualizer.py

Prompts

```
['run mask2former video segmentation on a list of input image frames and save visualized output', 'run mask2former video segmentation on a video file and save the visualization as an MP4', 'setup a detectron2 config object by merging a YAML config file with command-line options', 'get an argparse parser with arguments for config file, video input, image input, output, and confidence threshold', 'test whether a given codec and file extension are supported by OpenCV VideoWriter', 'run the VisualizationDemo class to predict and visualize instance segmentation on a list of video frames', 'create a VideoPredictor from a Detectron2 config to run inference on a sequence of BGR frames', 'run the AsyncPredictor class to perform asynchronous multi-GPU inference on video frames using multiprocessing', 'review the VideoPredictor __call__ method that preprocesses frames and runs the model with torch.no_grad', 'refactor the AsyncPredictor get method that retrieves results in order using bisect insertion', 'create a TrackVisualizer instance from an RGB image with optional metadata and scale', 'draw instance-level prediction results with boxes, masks, and labels on an image', 'jitter a given RGB color using a deterministic ID-based jitter vector', 'review the TrackVisualizer class that extends detectron2 Visualizer for tracking visualization', 'summarize the _ID_JITTERS constant list of 100 RGB jitter vectors for color variation']
```

Usage

```
{'create_track_visualizer': 'create a TrackVisualizer instance from an RGB image with optional metadata and scale', 'draw_instance_predictions': 'draw instance-level prediction results with boxes, masks, and labels on an image', 'jitter_color_by_id': 'jitter a given RGB color using a deterministic ID-based jitter vector', 'review_track_visualizer_class': 'review the TrackVisualizer class that extends detectron2 Visualizer for tracking visualization', 'summarize_id_jitters_constant': 'summarize the _ID_JITTERS constant list of 100 RGB jitter vectors for color variation'}
```

