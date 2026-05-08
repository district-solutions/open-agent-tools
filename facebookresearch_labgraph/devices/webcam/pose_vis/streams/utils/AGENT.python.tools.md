# Agent Python Tools

- repo: facebookresearch/labgraph
- repo_uri: https://github.com/facebookresearch/labgraph

## File: facebookresearch_labgraph/devices/webcam/pose_vis/streams/utils/capture_handler.py

Prompts

```
['create a CaptureHandler instance with video sources, resolutions, and PoseVisExtension objects', 'start all CaptureWorker processes in the CaptureHandler to begin capturing video frames', 'get captured frames from all active workers as a list of Capture tuples with metadata', 'cleanup the CaptureHandler by stopping workers, joining processes, and unlinking shared memory', 'handle the AllCapturesFinished exception when all video sources have completed capturing', 'create a CaptureWorker subprocess to handle CV2 VideoCapture frame reading and shared memory communication', 'open a camera or video source using the appropriate CV2 backend like V4L2 or GStreamer', 'read and process a frame from the capture source with resize, flip, and BGR to RGB conversion', 'setup a capture worker with shared memory, blank frame, and PoseVisExtension instances', 'cleanup and release the capture worker resources including VideoCapture and extensions']
```

Usage

```
{'create_capture_handler': 'create a CaptureHandler instance with video sources, resolutions, and PoseVisExtension objects', 'start_capture_workers': 'start all CaptureWorker processes in the CaptureHandler to begin capturing video frames', 'get_captures': 'get captured frames from all active workers as a list of Capture tuples with metadata', 'cleanup_capture_handler': 'cleanup the CaptureHandler by stopping workers, joining processes, and unlinking shared memory', 'handle_all_captures_finished': 'handle the AllCapturesFinished exception when all video sources have completed capturing'}
```

## File: facebookresearch_labgraph/devices/webcam/pose_vis/streams/utils/capture_worker.py

Prompts

```
['create a CaptureHandler instance with video sources, resolutions, and PoseVisExtension objects', 'start all CaptureWorker processes in the CaptureHandler to begin capturing video frames', 'get captured frames from all active workers as a list of Capture tuples with metadata', 'cleanup the CaptureHandler by stopping workers, joining processes, and unlinking shared memory', 'handle the AllCapturesFinished exception when all video sources have completed capturing', 'create a CaptureWorker subprocess to handle CV2 VideoCapture frame reading and shared memory communication', 'open a camera or video source using the appropriate CV2 backend like V4L2 or GStreamer', 'read and process a frame from the capture source with resize, flip, and BGR to RGB conversion', 'setup a capture worker with shared memory, blank frame, and PoseVisExtension instances', 'cleanup and release the capture worker resources including VideoCapture and extensions']
```

Usage

```
{'create_capture_worker_process': 'create a CaptureWorker subprocess to handle CV2 VideoCapture frame reading and shared memory communication', 'open_capture_with_backend': 'open a camera or video source using the appropriate CV2 backend like V4L2 or GStreamer', 'read_capture_frame': 'read and process a frame from the capture source with resize, flip, and BGR to RGB conversion', 'setup_worker_with_extensions': 'setup a capture worker with shared memory, blank frame, and PoseVisExtension instances', 'cleanup_capture_worker': 'cleanup and release the capture worker resources including VideoCapture and extensions'}
```

