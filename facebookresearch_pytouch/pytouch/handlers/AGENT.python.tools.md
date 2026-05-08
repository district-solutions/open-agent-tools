# Agent Python Tools

- repo: facebookresearch/pytouch
- repo_uri: https://github.com/facebookresearch/pytouch

## File: facebookresearch_pytouch/pytouch/handlers/image.py

Prompts

```
['create an ImageHandler instance from an image file path with optional color space conversion', 'convert a PyTorch tensor back to a PIL Image using the tensor_to_PIL static method', 'get a PyTorch tensor representation of the loaded image via the tensor property', 'get a numpy array representation of the loaded image via the nparray property', 'save a PIL or OpenCV image to disk using the save static method', 'create a SensorHandler instance that opens a cv2.VideoCapture device and raises IOError on failure', 'call get_frame on a SensorHandler to read and return the next camera frame as a numpy array', 'access the dev property of SensorHandler to retrieve the underlying cv2.VideoCapture object', 'review the SensorHandler class to understand how it wraps cv2.VideoCapture for frame capture', 'refactor SensorHandler to add frame rate control or resolution settings to the capture device', 'create a VideoHandler instance that loads a video file from a given path', 'get the next frame and its position from a VideoHandler using get_frame', 'resize video frames to a specific width and height tuple or scaling factor', 'seek to a specific frame position in the video using set_frame_pos', 'review the VideoHandler class and its frame reading and resizing capabilities']
```

Usage

```
{'init_ImageHandler': 'create an ImageHandler instance from an image file path with optional color space conversion', 'tensor_to_PIL': 'convert a PyTorch tensor back to a PIL Image using the tensor_to_PIL static method', 'ImageHandler_tensor': 'get a PyTorch tensor representation of the loaded image via the tensor property', 'ImageHandler_nparray': 'get a numpy array representation of the loaded image via the nparray property', 'ImageHandler_save': 'save a PIL or OpenCV image to disk using the save static method'}
```

## File: facebookresearch_pytouch/pytouch/handlers/sensor.py

Prompts

```
['create an ImageHandler instance from an image file path with optional color space conversion', 'convert a PyTorch tensor back to a PIL Image using the tensor_to_PIL static method', 'get a PyTorch tensor representation of the loaded image via the tensor property', 'get a numpy array representation of the loaded image via the nparray property', 'save a PIL or OpenCV image to disk using the save static method', 'create a SensorHandler instance that opens a cv2.VideoCapture device and raises IOError on failure', 'call get_frame on a SensorHandler to read and return the next camera frame as a numpy array', 'access the dev property of SensorHandler to retrieve the underlying cv2.VideoCapture object', 'review the SensorHandler class to understand how it wraps cv2.VideoCapture for frame capture', 'refactor SensorHandler to add frame rate control or resolution settings to the capture device', 'create a VideoHandler instance that loads a video file from a given path', 'get the next frame and its position from a VideoHandler using get_frame', 'resize video frames to a specific width and height tuple or scaling factor', 'seek to a specific frame position in the video using set_frame_pos', 'review the VideoHandler class and its frame reading and resizing capabilities']
```

Usage

```
{'init_sensor_handler': 'create a SensorHandler instance that opens a cv2.VideoCapture device and raises IOError on failure', 'get_frame': 'call get_frame on a SensorHandler to read and return the next camera frame as a numpy array', 'dev_property': 'access the dev property of SensorHandler to retrieve the underlying cv2.VideoCapture object', 'review_sensor_handler': 'review the SensorHandler class to understand how it wraps cv2.VideoCapture for frame capture', 'refactor_sensor_handler': 'refactor SensorHandler to add frame rate control or resolution settings to the capture device'}
```

## File: facebookresearch_pytouch/pytouch/handlers/video.py

Prompts

```
['create an ImageHandler instance from an image file path with optional color space conversion', 'convert a PyTorch tensor back to a PIL Image using the tensor_to_PIL static method', 'get a PyTorch tensor representation of the loaded image via the tensor property', 'get a numpy array representation of the loaded image via the nparray property', 'save a PIL or OpenCV image to disk using the save static method', 'create a SensorHandler instance that opens a cv2.VideoCapture device and raises IOError on failure', 'call get_frame on a SensorHandler to read and return the next camera frame as a numpy array', 'access the dev property of SensorHandler to retrieve the underlying cv2.VideoCapture object', 'review the SensorHandler class to understand how it wraps cv2.VideoCapture for frame capture', 'refactor SensorHandler to add frame rate control or resolution settings to the capture device', 'create a VideoHandler instance that loads a video file from a given path', 'get the next frame and its position from a VideoHandler using get_frame', 'resize video frames to a specific width and height tuple or scaling factor', 'seek to a specific frame position in the video using set_frame_pos', 'review the VideoHandler class and its frame reading and resizing capabilities']
```

Usage

```
{'create_video_handler': 'create a VideoHandler instance that loads a video file from a given path', 'get_frame_from_video': 'get the next frame and its position from a VideoHandler using get_frame', 'resize_video_frames': 'resize video frames to a specific width and height tuple or scaling factor', 'seek_video_frame': 'seek to a specific frame position in the video using set_frame_pos', 'review_video_handler_class': 'review the VideoHandler class and its frame reading and resizing capabilities'}
```

