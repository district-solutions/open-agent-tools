# Agent Python Tools

- repo: facebookresearch/pytouch
- repo_uri: https://github.com/facebookresearch/pytouch

## File: facebookresearch_pytouch/examples/contact_area.py

Prompts

```
['run the extract_surface_contact function to compute major and minor axis of surface contact area from images', 'run the extract_surface_contact_real_time function to display real-time object contact area with a DIGIT sensor', 'build a PyTouch instance with DigitSensor and ContactArea task to analyze surface contact from images', 'create a ContactArea task with custom base image and contour threshold to extract contact ellipse axes', 'use ImageHandler to load images as numpy arrays and save annotated contact area results to PNG files', 'run a PyTouch instance with DigitSensor and ContactArea plus TouchDetect tasks on sample images', 'run the ContactArea task on a sample image with a base image to get major and minor axis', 'run the TouchDetect task on a sample image to determine if touching is detected', 'create a ContactArea task with a custom base image and contour threshold of 10', 'create a TouchDetect task with DigitSensor and a touchdetect_resnet18 zoo model', 'run the visualize_surface_3d function to render 3D point clouds from touch sensor image sequences', 'create an ImageSequenceDataset to load touch image sequences from a dataset path', 'create Visualizer3DViewParams to define a custom 3D camera view with fov, lookat, and zoom', 'create a Visualizer3D instance to render 3D point clouds with custom view parameters', 'run Surface3D point_cloud_3d to generate 3D points, depth, and normals from a color image', 'run the touch_detect function to detect if a hand is touching using PyTouch with DigitSensor', 'create an ImageHandler to load an image from a file path for touch detection input', 'build a PyTouch instance with DigitSensor and TouchDetect task for default touch detection', 'run TouchDetect with a custom zoo model like touchdetect_resnet18 for touch classification', 'test touch detection by calling TouchDetect on an image and checking is_touching and certainty values']
```

Usage

```
{'extract_surface_contact': 'run the extract_surface_contact function to compute major and minor axis of surface contact area from images', 'extract_surface_contact_real_time': 'run the extract_surface_contact_real_time function to display real-time object contact area with a DIGIT sensor', 'pytouch_PyTouch_init': 'build a PyTouch instance with DigitSensor and ContactArea task to analyze surface contact from images', 'contact_area_custom_config': 'create a ContactArea task with custom base image and contour threshold to extract contact ellipse axes', 'imagehandler_load_and_save': 'use ImageHandler to load images as numpy arrays and save annotated contact area results to PNG files'}
```

## File: facebookresearch_pytouch/examples/multi_task.py

Prompts

```
['run the extract_surface_contact function to compute major and minor axis of surface contact area from images', 'run the extract_surface_contact_real_time function to display real-time object contact area with a DIGIT sensor', 'build a PyTouch instance with DigitSensor and ContactArea task to analyze surface contact from images', 'create a ContactArea task with custom base image and contour threshold to extract contact ellipse axes', 'use ImageHandler to load images as numpy arrays and save annotated contact area results to PNG files', 'run a PyTouch instance with DigitSensor and ContactArea plus TouchDetect tasks on sample images', 'run the ContactArea task on a sample image with a base image to get major and minor axis', 'run the TouchDetect task on a sample image to determine if touching is detected', 'create a ContactArea task with a custom base image and contour threshold of 10', 'create a TouchDetect task with DigitSensor and a touchdetect_resnet18 zoo model', 'run the visualize_surface_3d function to render 3D point clouds from touch sensor image sequences', 'create an ImageSequenceDataset to load touch image sequences from a dataset path', 'create Visualizer3DViewParams to define a custom 3D camera view with fov, lookat, and zoom', 'create a Visualizer3D instance to render 3D point clouds with custom view parameters', 'run Surface3D point_cloud_3d to generate 3D points, depth, and normals from a color image', 'run the touch_detect function to detect if a hand is touching using PyTouch with DigitSensor', 'create an ImageHandler to load an image from a file path for touch detection input', 'build a PyTouch instance with DigitSensor and TouchDetect task for default touch detection', 'run TouchDetect with a custom zoo model like touchdetect_resnet18 for touch classification', 'test touch detection by calling TouchDetect on an image and checking is_touching and certainty values']
```

Usage

```
{'run_PyTouch_multi_task': 'run a PyTouch instance with DigitSensor and ContactArea plus TouchDetect tasks on sample images', 'run_ContactArea_task': 'run the ContactArea task on a sample image with a base image to get major and minor axis', 'run_TouchDetect_task': 'run the TouchDetect task on a sample image to determine if touching is detected', 'create_ContactArea_custom': 'create a ContactArea task with a custom base image and contour threshold of 10', 'create_TouchDetect_custom': 'create a TouchDetect task with DigitSensor and a touchdetect_resnet18 zoo model'}
```

## File: facebookresearch_pytouch/examples/surface_3d.py

Prompts

```
['run the extract_surface_contact function to compute major and minor axis of surface contact area from images', 'run the extract_surface_contact_real_time function to display real-time object contact area with a DIGIT sensor', 'build a PyTouch instance with DigitSensor and ContactArea task to analyze surface contact from images', 'create a ContactArea task with custom base image and contour threshold to extract contact ellipse axes', 'use ImageHandler to load images as numpy arrays and save annotated contact area results to PNG files', 'run a PyTouch instance with DigitSensor and ContactArea plus TouchDetect tasks on sample images', 'run the ContactArea task on a sample image with a base image to get major and minor axis', 'run the TouchDetect task on a sample image to determine if touching is detected', 'create a ContactArea task with a custom base image and contour threshold of 10', 'create a TouchDetect task with DigitSensor and a touchdetect_resnet18 zoo model', 'run the visualize_surface_3d function to render 3D point clouds from touch sensor image sequences', 'create an ImageSequenceDataset to load touch image sequences from a dataset path', 'create Visualizer3DViewParams to define a custom 3D camera view with fov, lookat, and zoom', 'create a Visualizer3D instance to render 3D point clouds with custom view parameters', 'run Surface3D point_cloud_3d to generate 3D points, depth, and normals from a color image', 'run the touch_detect function to detect if a hand is touching using PyTouch with DigitSensor', 'create an ImageHandler to load an image from a file path for touch detection input', 'build a PyTouch instance with DigitSensor and TouchDetect task for default touch detection', 'run TouchDetect with a custom zoo model like touchdetect_resnet18 for touch classification', 'test touch detection by calling TouchDetect on an image and checking is_touching and certainty values']
```

Usage

```
{'run_visualize_surface_3d': 'run the visualize_surface_3d function to render 3D point clouds from touch sensor image sequences', 'create_ImageSequenceDataset': 'create an ImageSequenceDataset to load touch image sequences from a dataset path', 'create_Visualizer3DViewParams': 'create Visualizer3DViewParams to define a custom 3D camera view with fov, lookat, and zoom', 'create_Visualizer3D': 'create a Visualizer3D instance to render 3D point clouds with custom view parameters', 'run_Surface3D_point_cloud_3d': 'run Surface3D point_cloud_3d to generate 3D points, depth, and normals from a color image'}
```

## File: facebookresearch_pytouch/examples/touch_detect.py

Prompts

```
['run the extract_surface_contact function to compute major and minor axis of surface contact area from images', 'run the extract_surface_contact_real_time function to display real-time object contact area with a DIGIT sensor', 'build a PyTouch instance with DigitSensor and ContactArea task to analyze surface contact from images', 'create a ContactArea task with custom base image and contour threshold to extract contact ellipse axes', 'use ImageHandler to load images as numpy arrays and save annotated contact area results to PNG files', 'run a PyTouch instance with DigitSensor and ContactArea plus TouchDetect tasks on sample images', 'run the ContactArea task on a sample image with a base image to get major and minor axis', 'run the TouchDetect task on a sample image to determine if touching is detected', 'create a ContactArea task with a custom base image and contour threshold of 10', 'create a TouchDetect task with DigitSensor and a touchdetect_resnet18 zoo model', 'run the visualize_surface_3d function to render 3D point clouds from touch sensor image sequences', 'create an ImageSequenceDataset to load touch image sequences from a dataset path', 'create Visualizer3DViewParams to define a custom 3D camera view with fov, lookat, and zoom', 'create a Visualizer3D instance to render 3D point clouds with custom view parameters', 'run Surface3D point_cloud_3d to generate 3D points, depth, and normals from a color image', 'run the touch_detect function to detect if a hand is touching using PyTouch with DigitSensor', 'create an ImageHandler to load an image from a file path for touch detection input', 'build a PyTouch instance with DigitSensor and TouchDetect task for default touch detection', 'run TouchDetect with a custom zoo model like touchdetect_resnet18 for touch classification', 'test touch detection by calling TouchDetect on an image and checking is_touching and certainty values']
```

Usage

```
{'run_touch_detect': 'run the touch_detect function to detect if a hand is touching using PyTouch with DigitSensor', 'create_ImageHandler': 'create an ImageHandler to load an image from a file path for touch detection input', 'build_PyTouch_with_TouchDetect': 'build a PyTouch instance with DigitSensor and TouchDetect task for default touch detection', 'run_TouchDetect_custom_model': 'run TouchDetect with a custom zoo model like touchdetect_resnet18 for touch classification', 'test_touch_detection_certainty': 'test touch detection by calling TouchDetect on an image and checking is_touching and certainty values'}
```

