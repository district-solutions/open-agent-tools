# Agent Python Tools

- repo: facebookresearch/frankmocap
- repo_uri: https://github.com/facebookresearch/frankmocap

## File: facebookresearch_frankmocap/demo/demo_bodymocap.py

Prompts

```
['run the body mocap demo on a video or webcam input with 3D mesh visualization', 'run body mocap regression on video frames to extract 3D body mesh predictions', 'run body mocap in real time from a webcam feed with live mesh rendering', 'run body mocap using pre-computed bounding boxes from a JSON directory input', 'run body mocap in single person mode to track only the largest detected body', 'run the FRANKMocap demo on an image directory, video, or webcam input with GPU', 'run the FRANKMocap main loop to process frames and visualize body and hand meshes', 'run body and hand pose regression on an image using bounding boxes and mocap models', 'review the filter_bbox_list function that sorts bounding boxes by size and filters for single person', 'run the copy-and-paste integration to combine predicted body and hand mesh outputs', 'run the hand mocap demo on images, video, or webcam input with GPU', 'run the hand mocap loop to detect hands and regress 3D pose from frames', 'review the main entry point that sets up HandBboxDetector, HandMocap, and Visualizer', 'refactor run_hand_mocap to support additional input types beyond image_dir, video, and webcam', 'summarize the run_hand_mocap function that processes frames through detection, regression, and visualization', 'parse command line arguments for FrankMocap demo using DemoOptions parse method', 'configure SMPL and SMPLX pretrained checkpoint paths for body motion capture', 'set input video path and output directory for mocap predictions', 'configure hand mocap view type and crop type for hand pose estimation', 'set renderer type and display options for visualizing mocap results', 'run the demo to visualize SMPL/SMPLX body and hand mesh predictions from pickle files', 'run the hand mesh calculation using SMPLX pose parameters and betas for left or right hand', 'run the body mesh calculation using SMPL or SMPLX model with body pose and betas', 'run the SMPL model loader to create SMPL, SMPLX, or neutral SMPLX models for demo type', 'run the visualization pipeline to render predicted meshes onto original images and save results']
```

Usage

```
{'run_body_mocap_demo': 'run the body mocap demo on a video or webcam input with 3D mesh visualization', 'run_body_mocap_on_video': 'run body mocap regression on video frames to extract 3D body mesh predictions', 'run_body_mocap_on_webcam': 'run body mocap in real time from a webcam feed with live mesh rendering', 'run_body_mocap_with_precomputed_bboxes': 'run body mocap using pre-computed bounding boxes from a JSON directory input', 'run_body_mocap_single_person': 'run body mocap in single person mode to track only the largest detected body'}
```

## File: facebookresearch_frankmocap/demo/demo_frankmocap.py

Prompts

```
['run the body mocap demo on a video or webcam input with 3D mesh visualization', 'run body mocap regression on video frames to extract 3D body mesh predictions', 'run body mocap in real time from a webcam feed with live mesh rendering', 'run body mocap using pre-computed bounding boxes from a JSON directory input', 'run body mocap in single person mode to track only the largest detected body', 'run the FRANKMocap demo on an image directory, video, or webcam input with GPU', 'run the FRANKMocap main loop to process frames and visualize body and hand meshes', 'run body and hand pose regression on an image using bounding boxes and mocap models', 'review the filter_bbox_list function that sorts bounding boxes by size and filters for single person', 'run the copy-and-paste integration to combine predicted body and hand mesh outputs', 'run the hand mocap demo on images, video, or webcam input with GPU', 'run the hand mocap loop to detect hands and regress 3D pose from frames', 'review the main entry point that sets up HandBboxDetector, HandMocap, and Visualizer', 'refactor run_hand_mocap to support additional input types beyond image_dir, video, and webcam', 'summarize the run_hand_mocap function that processes frames through detection, regression, and visualization', 'parse command line arguments for FrankMocap demo using DemoOptions parse method', 'configure SMPL and SMPLX pretrained checkpoint paths for body motion capture', 'set input video path and output directory for mocap predictions', 'configure hand mocap view type and crop type for hand pose estimation', 'set renderer type and display options for visualizing mocap results', 'run the demo to visualize SMPL/SMPLX body and hand mesh predictions from pickle files', 'run the hand mesh calculation using SMPLX pose parameters and betas for left or right hand', 'run the body mesh calculation using SMPL or SMPLX model with body pose and betas', 'run the SMPL model loader to create SMPL, SMPLX, or neutral SMPLX models for demo type', 'run the visualization pipeline to render predicted meshes onto original images and save results']
```

Usage

```
{'run_frankmocap_demo': 'run the FRANKMocap demo on an image directory, video, or webcam input with GPU', 'run_run_frank_mocap': 'run the FRANKMocap main loop to process frames and visualize body and hand meshes', 'run_run_regress': 'run body and hand pose regression on an image using bounding boxes and mocap models', 'review_filter_bbox_list': 'review the filter_bbox_list function that sorts bounding boxes by size and filters for single person', 'run_integration_copy_paste': 'run the copy-and-paste integration to combine predicted body and hand mesh outputs'}
```

## File: facebookresearch_frankmocap/demo/demo_handmocap.py

Prompts

```
['run the body mocap demo on a video or webcam input with 3D mesh visualization', 'run body mocap regression on video frames to extract 3D body mesh predictions', 'run body mocap in real time from a webcam feed with live mesh rendering', 'run body mocap using pre-computed bounding boxes from a JSON directory input', 'run body mocap in single person mode to track only the largest detected body', 'run the FRANKMocap demo on an image directory, video, or webcam input with GPU', 'run the FRANKMocap main loop to process frames and visualize body and hand meshes', 'run body and hand pose regression on an image using bounding boxes and mocap models', 'review the filter_bbox_list function that sorts bounding boxes by size and filters for single person', 'run the copy-and-paste integration to combine predicted body and hand mesh outputs', 'run the hand mocap demo on images, video, or webcam input with GPU', 'run the hand mocap loop to detect hands and regress 3D pose from frames', 'review the main entry point that sets up HandBboxDetector, HandMocap, and Visualizer', 'refactor run_hand_mocap to support additional input types beyond image_dir, video, and webcam', 'summarize the run_hand_mocap function that processes frames through detection, regression, and visualization', 'parse command line arguments for FrankMocap demo using DemoOptions parse method', 'configure SMPL and SMPLX pretrained checkpoint paths for body motion capture', 'set input video path and output directory for mocap predictions', 'configure hand mocap view type and crop type for hand pose estimation', 'set renderer type and display options for visualizing mocap results', 'run the demo to visualize SMPL/SMPLX body and hand mesh predictions from pickle files', 'run the hand mesh calculation using SMPLX pose parameters and betas for left or right hand', 'run the body mesh calculation using SMPL or SMPLX model with body pose and betas', 'run the SMPL model loader to create SMPL, SMPLX, or neutral SMPLX models for demo type', 'run the visualization pipeline to render predicted meshes onto original images and save results']
```

Usage

```
{'run_hand_mocap_demo': 'run the hand mocap demo on images, video, or webcam input with GPU', 'run_run_hand_mocap': 'run the hand mocap loop to detect hands and regress 3D pose from frames', 'review_main': 'review the main entry point that sets up HandBboxDetector, HandMocap, and Visualizer', 'refactor_run_hand_mocap': 'refactor run_hand_mocap to support additional input types beyond image_dir, video, and webcam', 'summarize_run_hand_mocap': 'summarize the run_hand_mocap function that processes frames through detection, regression, and visualization'}
```

## File: facebookresearch_frankmocap/demo/demo_options.py

Prompts

```
['run the body mocap demo on a video or webcam input with 3D mesh visualization', 'run body mocap regression on video frames to extract 3D body mesh predictions', 'run body mocap in real time from a webcam feed with live mesh rendering', 'run body mocap using pre-computed bounding boxes from a JSON directory input', 'run body mocap in single person mode to track only the largest detected body', 'run the FRANKMocap demo on an image directory, video, or webcam input with GPU', 'run the FRANKMocap main loop to process frames and visualize body and hand meshes', 'run body and hand pose regression on an image using bounding boxes and mocap models', 'review the filter_bbox_list function that sorts bounding boxes by size and filters for single person', 'run the copy-and-paste integration to combine predicted body and hand mesh outputs', 'run the hand mocap demo on images, video, or webcam input with GPU', 'run the hand mocap loop to detect hands and regress 3D pose from frames', 'review the main entry point that sets up HandBboxDetector, HandMocap, and Visualizer', 'refactor run_hand_mocap to support additional input types beyond image_dir, video, and webcam', 'summarize the run_hand_mocap function that processes frames through detection, regression, and visualization', 'parse command line arguments for FrankMocap demo using DemoOptions parse method', 'configure SMPL and SMPLX pretrained checkpoint paths for body motion capture', 'set input video path and output directory for mocap predictions', 'configure hand mocap view type and crop type for hand pose estimation', 'set renderer type and display options for visualizing mocap results', 'run the demo to visualize SMPL/SMPLX body and hand mesh predictions from pickle files', 'run the hand mesh calculation using SMPLX pose parameters and betas for left or right hand', 'run the body mesh calculation using SMPL or SMPLX model with body pose and betas', 'run the SMPL model loader to create SMPL, SMPLX, or neutral SMPLX models for demo type', 'run the visualization pipeline to render predicted meshes onto original images and save results']
```

Usage

```
{'parse_demo_options': 'parse command line arguments for FrankMocap demo using DemoOptions parse method', 'configure_body_mocap_checkpoints': 'configure SMPL and SMPLX pretrained checkpoint paths for body motion capture', 'set_input_output_paths': 'set input video path and output directory for mocap predictions', 'configure_hand_mocap_options': 'configure hand mocap view type and crop type for hand pose estimation', 'set_renderer_and_display_options': 'set renderer type and display options for visualizing mocap results'}
```

## File: facebookresearch_frankmocap/demo/demo_visualize_prediction.py

Prompts

```
['run the body mocap demo on a video or webcam input with 3D mesh visualization', 'run body mocap regression on video frames to extract 3D body mesh predictions', 'run body mocap in real time from a webcam feed with live mesh rendering', 'run body mocap using pre-computed bounding boxes from a JSON directory input', 'run body mocap in single person mode to track only the largest detected body', 'run the FRANKMocap demo on an image directory, video, or webcam input with GPU', 'run the FRANKMocap main loop to process frames and visualize body and hand meshes', 'run body and hand pose regression on an image using bounding boxes and mocap models', 'review the filter_bbox_list function that sorts bounding boxes by size and filters for single person', 'run the copy-and-paste integration to combine predicted body and hand mesh outputs', 'run the hand mocap demo on images, video, or webcam input with GPU', 'run the hand mocap loop to detect hands and regress 3D pose from frames', 'review the main entry point that sets up HandBboxDetector, HandMocap, and Visualizer', 'refactor run_hand_mocap to support additional input types beyond image_dir, video, and webcam', 'summarize the run_hand_mocap function that processes frames through detection, regression, and visualization', 'parse command line arguments for FrankMocap demo using DemoOptions parse method', 'configure SMPL and SMPLX pretrained checkpoint paths for body motion capture', 'set input video path and output directory for mocap predictions', 'configure hand mocap view type and crop type for hand pose estimation', 'set renderer type and display options for visualizing mocap results', 'run the demo to visualize SMPL/SMPLX body and hand mesh predictions from pickle files', 'run the hand mesh calculation using SMPLX pose parameters and betas for left or right hand', 'run the body mesh calculation using SMPL or SMPLX model with body pose and betas', 'run the SMPL model loader to create SMPL, SMPLX, or neutral SMPLX models for demo type', 'run the visualization pipeline to render predicted meshes onto original images and save results']
```

Usage

```
{'run_visualize_predictions': 'run the demo to visualize SMPL/SMPLX body and hand mesh predictions from pickle files', 'run_calc_hand_mesh': 'run the hand mesh calculation using SMPLX pose parameters and betas for left or right hand', 'run_calc_body_mesh': 'run the body mesh calculation using SMPL or SMPLX model with body pose and betas', 'run_get_smpl_model': 'run the SMPL model loader to create SMPL, SMPLX, or neutral SMPLX models for demo type', 'run_visualize_prediction': 'run the visualization pipeline to render predicted meshes onto original images and save results'}
```

