# Agent Python Tools

- repo: facebookresearch/sapiens
- repo_uri: https://github.com/facebookresearch/sapiens

## File: facebookresearch_sapiens/cv/mmcv/visualization/color.py

Prompts

```
["convert a color string like 'red' to a BGR tuple using color_val", 'convert a Color enum member to its BGR tuple value using color_val', 'validate and return a 3-element BGR tuple via color_val with range checks', 'convert a single grayscale int to a BGR tuple using color_val', 'convert a numpy array of 3 values to a BGR tuple using color_val', 'display an image from a file path or numpy array in an OpenCV window with optional wait time', 'draw bounding box rectangles on an image with configurable colors, thickness, and optional top-k filtering', 'draw detection bounding boxes with class labels and confidence scores on an image with score thresholding', 'convert a color specification string, tuple, int, or Color enum into a BGR tuple for OpenCV drawing', "save a numpy array image to disk using mmcv's imwrite utility function", 'build a python module to display optical flow from a numpy array or file path using flowshow', 'create a function that converts an optical flow array to a colorized RGB image using flow2rgb', 'build a python module to generate a color wheel for optical flow visualization using make_color_wheel', 'test the flow2rgb function by passing a custom color wheel and unknown threshold', 'review the flowshow function to understand how it reads flow data and displays it in a window']
```

Usage

```
{'convert_string_to_bgr_tuple': "convert a color string like 'red' to a BGR tuple using color_val", 'convert_enum_to_bgr_tuple': 'convert a Color enum member to its BGR tuple value using color_val', 'convert_tuple_to_bgr_tuple': 'validate and return a 3-element BGR tuple via color_val with range checks', 'convert_int_to_bgr_tuple': 'convert a single grayscale int to a BGR tuple using color_val', 'convert_ndarray_to_bgr_tuple': 'convert a numpy array of 3 values to a BGR tuple using color_val'}
```

## File: facebookresearch_sapiens/cv/mmcv/visualization/image.py

Prompts

```
["convert a color string like 'red' to a BGR tuple using color_val", 'convert a Color enum member to its BGR tuple value using color_val', 'validate and return a 3-element BGR tuple via color_val with range checks', 'convert a single grayscale int to a BGR tuple using color_val', 'convert a numpy array of 3 values to a BGR tuple using color_val', 'display an image from a file path or numpy array in an OpenCV window with optional wait time', 'draw bounding box rectangles on an image with configurable colors, thickness, and optional top-k filtering', 'draw detection bounding boxes with class labels and confidence scores on an image with score thresholding', 'convert a color specification string, tuple, int, or Color enum into a BGR tuple for OpenCV drawing', "save a numpy array image to disk using mmcv's imwrite utility function", 'build a python module to display optical flow from a numpy array or file path using flowshow', 'create a function that converts an optical flow array to a colorized RGB image using flow2rgb', 'build a python module to generate a color wheel for optical flow visualization using make_color_wheel', 'test the flow2rgb function by passing a custom color wheel and unknown threshold', 'review the flowshow function to understand how it reads flow data and displays it in a window']
```

Usage

```
{'imshow_display_image': 'display an image from a file path or numpy array in an OpenCV window with optional wait time', 'imshow_bboxes_draw_rectangles': 'draw bounding box rectangles on an image with configurable colors, thickness, and optional top-k filtering', 'imshow_det_bboxes_draw_labels': 'draw detection bounding boxes with class labels and confidence scores on an image with score thresholding', 'color_val_convert_color': 'convert a color specification string, tuple, int, or Color enum into a BGR tuple for OpenCV drawing', 'imwrite_save_image': "save a numpy array image to disk using mmcv's imwrite utility function"}
```

## File: facebookresearch_sapiens/cv/mmcv/visualization/optflow.py

Prompts

```
["convert a color string like 'red' to a BGR tuple using color_val", 'convert a Color enum member to its BGR tuple value using color_val', 'validate and return a 3-element BGR tuple via color_val with range checks', 'convert a single grayscale int to a BGR tuple using color_val', 'convert a numpy array of 3 values to a BGR tuple using color_val', 'display an image from a file path or numpy array in an OpenCV window with optional wait time', 'draw bounding box rectangles on an image with configurable colors, thickness, and optional top-k filtering', 'draw detection bounding boxes with class labels and confidence scores on an image with score thresholding', 'convert a color specification string, tuple, int, or Color enum into a BGR tuple for OpenCV drawing', "save a numpy array image to disk using mmcv's imwrite utility function", 'build a python module to display optical flow from a numpy array or file path using flowshow', 'create a function that converts an optical flow array to a colorized RGB image using flow2rgb', 'build a python module to generate a color wheel for optical flow visualization using make_color_wheel', 'test the flow2rgb function by passing a custom color wheel and unknown threshold', 'review the flowshow function to understand how it reads flow data and displays it in a window']
```

Usage

```
{'build_optical_flow_visualizer': 'build a python module to display optical flow from a numpy array or file path using flowshow', 'create_flow_to_rgb_converter': 'create a function that converts an optical flow array to a colorized RGB image using flow2rgb', 'build_color_wheel_generator': 'build a python module to generate a color wheel for optical flow visualization using make_color_wheel', 'test_flow2rgb_with_custom_wheel': 'test the flow2rgb function by passing a custom color wheel and unknown threshold', 'review_flowshow_display': 'review the flowshow function to understand how it reads flow data and displays it in a window'}
```

