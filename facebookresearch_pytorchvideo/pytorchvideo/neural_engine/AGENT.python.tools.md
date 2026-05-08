# Agent Python Tools

- repo: facebookresearch/pytorchvideo
- repo_uri: https://github.com/facebookresearch/pytorchvideo

## File: facebookresearch_pytorchvideo/pytorchvideo/neural_engine/detection_hook.py

Prompts

```
['generate a detectron2 DefaultPredictor from a model config dict with backend, model, and threshold keys', 'run the PeopleKeypointDetectionHook to detect human keypoints in a loaded image using detectron2', 'create an ImageLoadHook that loads an image from a file path using cv2.imread', 'run the Detectron2PeopleDetectionHook to detect people bounding boxes in a loaded image', 'run the people_detection_executor function to extract person bounding boxes from a detectron2 predictor output', 'run a NeuralEngine with a list of HookBase hooks and an OrderedDict status', 'create a topological sort of hooks based on their inputs and outputs using NeuralEngine', 'use NeuralEngine as a context manager to execute hooks in topological order', 'call NeuralEngine with a video file path string to process it through hooks', 'set a custom execution order function on NeuralEngine to replace topological sort', 'create a subclass of HookBase with custom executor, conditional execution, and exit functions', 'run a HookBase instance with an OrderedDict status to execute the hook pipeline', 'create a DecodeHook to decode video and audio from a file path using PYAV decoder', 'use full_decode to extract all video frames and audio from an encoded video file path', 'create an X3DClsHook to classify video actions using a pretrained X3D-S model from PyTorch Hub']
```

Usage

```
{'generate_detectron2_predictor': 'generate a detectron2 DefaultPredictor from a model config dict with backend, model, and threshold keys', 'run_people_keypoint_detection': 'run the PeopleKeypointDetectionHook to detect human keypoints in a loaded image using detectron2', 'load_image_with_opencv': 'create an ImageLoadHook that loads an image from a file path using cv2.imread', 'detect_people_bounding_boxes': 'run the Detectron2PeopleDetectionHook to detect people bounding boxes in a loaded image', 'run_people_detection_executor': 'run the people_detection_executor function to extract person bounding boxes from a detectron2 predictor output'}
```

## File: facebookresearch_pytorchvideo/pytorchvideo/neural_engine/engine.py

Prompts

```
['generate a detectron2 DefaultPredictor from a model config dict with backend, model, and threshold keys', 'run the PeopleKeypointDetectionHook to detect human keypoints in a loaded image using detectron2', 'create an ImageLoadHook that loads an image from a file path using cv2.imread', 'run the Detectron2PeopleDetectionHook to detect people bounding boxes in a loaded image', 'run the people_detection_executor function to extract person bounding boxes from a detectron2 predictor output', 'run a NeuralEngine with a list of HookBase hooks and an OrderedDict status', 'create a topological sort of hooks based on their inputs and outputs using NeuralEngine', 'use NeuralEngine as a context manager to execute hooks in topological order', 'call NeuralEngine with a video file path string to process it through hooks', 'set a custom execution order function on NeuralEngine to replace topological sort', 'create a subclass of HookBase with custom executor, conditional execution, and exit functions', 'run a HookBase instance with an OrderedDict status to execute the hook pipeline', 'create a DecodeHook to decode video and audio from a file path using PYAV decoder', 'use full_decode to extract all video frames and audio from an encoded video file path', 'create an X3DClsHook to classify video actions using a pretrained X3D-S model from PyTorch Hub']
```

Usage

```
{'run_NeuralEngine_with_hooks': 'run a NeuralEngine with a list of HookBase hooks and an OrderedDict status', 'create_NeuralEngine_topological_sort': 'create a topological sort of hooks based on their inputs and outputs using NeuralEngine', 'use_NeuralEngine_context_manager': 'use NeuralEngine as a context manager to execute hooks in topological order', 'call_NeuralEngine_with_video_path': 'call NeuralEngine with a video file path string to process it through hooks', 'set_NeuralEngine_execution_order': 'set a custom execution order function on NeuralEngine to replace topological sort'}
```

## File: facebookresearch_pytorchvideo/pytorchvideo/neural_engine/hook.py

Prompts

```
['generate a detectron2 DefaultPredictor from a model config dict with backend, model, and threshold keys', 'run the PeopleKeypointDetectionHook to detect human keypoints in a loaded image using detectron2', 'create an ImageLoadHook that loads an image from a file path using cv2.imread', 'run the Detectron2PeopleDetectionHook to detect people bounding boxes in a loaded image', 'run the people_detection_executor function to extract person bounding boxes from a detectron2 predictor output', 'run a NeuralEngine with a list of HookBase hooks and an OrderedDict status', 'create a topological sort of hooks based on their inputs and outputs using NeuralEngine', 'use NeuralEngine as a context manager to execute hooks in topological order', 'call NeuralEngine with a video file path string to process it through hooks', 'set a custom execution order function on NeuralEngine to replace topological sort', 'create a subclass of HookBase with custom executor, conditional execution, and exit functions', 'run a HookBase instance with an OrderedDict status to execute the hook pipeline', 'create a DecodeHook to decode video and audio from a file path using PYAV decoder', 'use full_decode to extract all video frames and audio from an encoded video file path', 'create an X3DClsHook to classify video actions using a pretrained X3D-S model from PyTorch Hub']
```

Usage

```
{'create_hookbase_subclass': 'create a subclass of HookBase with custom executor, conditional execution, and exit functions', 'run_hookbase': 'run a HookBase instance with an OrderedDict status to execute the hook pipeline', 'create_decodehook': 'create a DecodeHook to decode video and audio from a file path using PYAV decoder', 'full_decode_video': 'use full_decode to extract all video frames and audio from an encoded video file path', 'create_x3dclshook': 'create an X3DClsHook to classify video actions using a pretrained X3D-S model from PyTorch Hub'}
```

