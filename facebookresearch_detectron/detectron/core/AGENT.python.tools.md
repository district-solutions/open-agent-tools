# Agent Python Tools

- repo: facebookresearch/detectron
- repo_uri: https://github.com/facebookresearch/detectron

## File: facebookresearch_detectron/detectron/core/config.py

Prompts

```
['merge a yaml config file into the global Detectron cfg object to override default options', 'merge a list of key value pairs from the command line into the global Detectron cfg', 'assert and infer derived config values then optionally make the global cfg immutable', 'get the output directory path for training or testing based on datasets and model type', 'load and parse a yaml config file with backward compatibility for renamed modules', 'run RPN inference on a dataset using a single or multi GPU to generate region proposals', 'run parallel multi-GPU RPN inference on a dataset by spawning subprocesses and collating results', 'run RPN inference on a range of images in a dataset using a single GPU', 'generate RPN region proposals and scores on a single image using a loaded model', 'evaluate box proposal average recall from a saved RPN proposal file and log results', 'run full object detection with bbox, mask, and keypoint inference on an image using the model', 'run bounding box detection on an image with given box proposals and return class scores and boxes', 'run bounding box detection with test-time augmentations including flips, scales, and aspect ratios', 'run instance segmentation mask inference on detected bounding boxes using the mask network', 'run keypoint pose inference on detected bounding boxes using the keypoint network and heatmaps', 'run inference on a Detectron network across all configured test datasets using a weights file', 'test a Detectron model on a single dataset and return evaluation results for boxes, masks, and keypoints', 'test a Detectron model on all images in a dataset using a single GPU and save detections', 'initialize a Detectron model from the global config by loading test-time weights and creating Caffe2 networks', 'get the roidb for a dataset optionally restricted to a range of image indices', 'create cell anchors for all FPN levels, scales, and aspect ratios for RetinaNet inference', 'test the im_detect_bbox function by running RetinaNet detection on a sample image', 'review the im_detect_bbox function to understand how NMS and box transformation are applied', 'refactor the _create_cell_anchors function to cache anchors and avoid recomputation per image']
```

Usage

```
{'merge_cfg_from_file': 'merge a yaml config file into the global Detectron cfg object to override default options', 'merge_cfg_from_list': 'merge a list of key value pairs from the command line into the global Detectron cfg', 'assert_and_infer_cfg': 'assert and infer derived config values then optionally make the global cfg immutable', 'get_output_dir': 'get the output directory path for training or testing based on datasets and model type', 'load_cfg': 'load and parse a yaml config file with backward compatibility for renamed modules'}
```

## File: facebookresearch_detectron/detectron/core/rpn_generator.py

Prompts

```
['merge a yaml config file into the global Detectron cfg object to override default options', 'merge a list of key value pairs from the command line into the global Detectron cfg', 'assert and infer derived config values then optionally make the global cfg immutable', 'get the output directory path for training or testing based on datasets and model type', 'load and parse a yaml config file with backward compatibility for renamed modules', 'run RPN inference on a dataset using a single or multi GPU to generate region proposals', 'run parallel multi-GPU RPN inference on a dataset by spawning subprocesses and collating results', 'run RPN inference on a range of images in a dataset using a single GPU', 'generate RPN region proposals and scores on a single image using a loaded model', 'evaluate box proposal average recall from a saved RPN proposal file and log results', 'run full object detection with bbox, mask, and keypoint inference on an image using the model', 'run bounding box detection on an image with given box proposals and return class scores and boxes', 'run bounding box detection with test-time augmentations including flips, scales, and aspect ratios', 'run instance segmentation mask inference on detected bounding boxes using the mask network', 'run keypoint pose inference on detected bounding boxes using the keypoint network and heatmaps', 'run inference on a Detectron network across all configured test datasets using a weights file', 'test a Detectron model on a single dataset and return evaluation results for boxes, masks, and keypoints', 'test a Detectron model on all images in a dataset using a single GPU and save detections', 'initialize a Detectron model from the global config by loading test-time weights and creating Caffe2 networks', 'get the roidb for a dataset optionally restricted to a range of image indices', 'create cell anchors for all FPN levels, scales, and aspect ratios for RetinaNet inference', 'test the im_detect_bbox function by running RetinaNet detection on a sample image', 'review the im_detect_bbox function to understand how NMS and box transformation are applied', 'refactor the _create_cell_anchors function to cache anchors and avoid recomputation per image']
```

Usage

```
{'generate_rpn_on_dataset': 'run RPN inference on a dataset using a single or multi GPU to generate region proposals', 'multi_gpu_generate_rpn_on_dataset': 'run parallel multi-GPU RPN inference on a dataset by spawning subprocesses and collating results', 'generate_rpn_on_range': 'run RPN inference on a range of images in a dataset using a single GPU', 'im_proposals': 'generate RPN region proposals and scores on a single image using a loaded model', 'evaluate_proposal_file': 'evaluate box proposal average recall from a saved RPN proposal file and log results'}
```

## File: facebookresearch_detectron/detectron/core/test.py

Prompts

```
['merge a yaml config file into the global Detectron cfg object to override default options', 'merge a list of key value pairs from the command line into the global Detectron cfg', 'assert and infer derived config values then optionally make the global cfg immutable', 'get the output directory path for training or testing based on datasets and model type', 'load and parse a yaml config file with backward compatibility for renamed modules', 'run RPN inference on a dataset using a single or multi GPU to generate region proposals', 'run parallel multi-GPU RPN inference on a dataset by spawning subprocesses and collating results', 'run RPN inference on a range of images in a dataset using a single GPU', 'generate RPN region proposals and scores on a single image using a loaded model', 'evaluate box proposal average recall from a saved RPN proposal file and log results', 'run full object detection with bbox, mask, and keypoint inference on an image using the model', 'run bounding box detection on an image with given box proposals and return class scores and boxes', 'run bounding box detection with test-time augmentations including flips, scales, and aspect ratios', 'run instance segmentation mask inference on detected bounding boxes using the mask network', 'run keypoint pose inference on detected bounding boxes using the keypoint network and heatmaps', 'run inference on a Detectron network across all configured test datasets using a weights file', 'test a Detectron model on a single dataset and return evaluation results for boxes, masks, and keypoints', 'test a Detectron model on all images in a dataset using a single GPU and save detections', 'initialize a Detectron model from the global config by loading test-time weights and creating Caffe2 networks', 'get the roidb for a dataset optionally restricted to a range of image indices', 'create cell anchors for all FPN levels, scales, and aspect ratios for RetinaNet inference', 'test the im_detect_bbox function by running RetinaNet detection on a sample image', 'review the im_detect_bbox function to understand how NMS and box transformation are applied', 'refactor the _create_cell_anchors function to cache anchors and avoid recomputation per image']
```

Usage

```
{'run_im_detect_all': 'run full object detection with bbox, mask, and keypoint inference on an image using the model', 'run_im_detect_bbox': 'run bounding box detection on an image with given box proposals and return class scores and boxes', 'run_im_detect_bbox_aug': 'run bounding box detection with test-time augmentations including flips, scales, and aspect ratios', 'run_im_detect_mask': 'run instance segmentation mask inference on detected bounding boxes using the mask network', 'run_im_detect_keypoints': 'run keypoint pose inference on detected bounding boxes using the keypoint network and heatmaps'}
```

## File: facebookresearch_detectron/detectron/core/test_engine.py

Prompts

```
['merge a yaml config file into the global Detectron cfg object to override default options', 'merge a list of key value pairs from the command line into the global Detectron cfg', 'assert and infer derived config values then optionally make the global cfg immutable', 'get the output directory path for training or testing based on datasets and model type', 'load and parse a yaml config file with backward compatibility for renamed modules', 'run RPN inference on a dataset using a single or multi GPU to generate region proposals', 'run parallel multi-GPU RPN inference on a dataset by spawning subprocesses and collating results', 'run RPN inference on a range of images in a dataset using a single GPU', 'generate RPN region proposals and scores on a single image using a loaded model', 'evaluate box proposal average recall from a saved RPN proposal file and log results', 'run full object detection with bbox, mask, and keypoint inference on an image using the model', 'run bounding box detection on an image with given box proposals and return class scores and boxes', 'run bounding box detection with test-time augmentations including flips, scales, and aspect ratios', 'run instance segmentation mask inference on detected bounding boxes using the mask network', 'run keypoint pose inference on detected bounding boxes using the keypoint network and heatmaps', 'run inference on a Detectron network across all configured test datasets using a weights file', 'test a Detectron model on a single dataset and return evaluation results for boxes, masks, and keypoints', 'test a Detectron model on all images in a dataset using a single GPU and save detections', 'initialize a Detectron model from the global config by loading test-time weights and creating Caffe2 networks', 'get the roidb for a dataset optionally restricted to a range of image indices', 'create cell anchors for all FPN levels, scales, and aspect ratios for RetinaNet inference', 'test the im_detect_bbox function by running RetinaNet detection on a sample image', 'review the im_detect_bbox function to understand how NMS and box transformation are applied', 'refactor the _create_cell_anchors function to cache anchors and avoid recomputation per image']
```

Usage

```
{'run_inference_on_dataset': 'run inference on a Detectron network across all configured test datasets using a weights file', 'test_net_on_dataset': 'test a Detectron model on a single dataset and return evaluation results for boxes, masks, and keypoints', 'test_net_single_gpu': 'test a Detectron model on all images in a dataset using a single GPU and save detections', 'initialize_model_from_cfg': 'initialize a Detectron model from the global config by loading test-time weights and creating Caffe2 networks', 'get_roidb_and_dataset': 'get the roidb for a dataset optionally restricted to a range of image indices'}
```

## File: facebookresearch_detectron/detectron/core/test_retinanet.py

Prompts

```
['merge a yaml config file into the global Detectron cfg object to override default options', 'merge a list of key value pairs from the command line into the global Detectron cfg', 'assert and infer derived config values then optionally make the global cfg immutable', 'get the output directory path for training or testing based on datasets and model type', 'load and parse a yaml config file with backward compatibility for renamed modules', 'run RPN inference on a dataset using a single or multi GPU to generate region proposals', 'run parallel multi-GPU RPN inference on a dataset by spawning subprocesses and collating results', 'run RPN inference on a range of images in a dataset using a single GPU', 'generate RPN region proposals and scores on a single image using a loaded model', 'evaluate box proposal average recall from a saved RPN proposal file and log results', 'run full object detection with bbox, mask, and keypoint inference on an image using the model', 'run bounding box detection on an image with given box proposals and return class scores and boxes', 'run bounding box detection with test-time augmentations including flips, scales, and aspect ratios', 'run instance segmentation mask inference on detected bounding boxes using the mask network', 'run keypoint pose inference on detected bounding boxes using the keypoint network and heatmaps', 'run inference on a Detectron network across all configured test datasets using a weights file', 'test a Detectron model on a single dataset and return evaluation results for boxes, masks, and keypoints', 'test a Detectron model on all images in a dataset using a single GPU and save detections', 'initialize a Detectron model from the global config by loading test-time weights and creating Caffe2 networks', 'get the roidb for a dataset optionally restricted to a range of image indices', 'create cell anchors for all FPN levels, scales, and aspect ratios for RetinaNet inference', 'test the im_detect_bbox function by running RetinaNet detection on a sample image', 'review the im_detect_bbox function to understand how NMS and box transformation are applied', 'refactor the _create_cell_anchors function to cache anchors and avoid recomputation per image']
```

Usage

```
{'run_im_detect_bbox': 'run RetinaNet detection on a single image using a trained model and return bounding boxes', 'create_cell_anchors': 'create cell anchors for all FPN levels, scales, and aspect ratios for RetinaNet inference', 'test_im_detect_bbox': 'test the im_detect_bbox function by running RetinaNet detection on a sample image', 'review_im_detect_bbox': 'review the im_detect_bbox function to understand how NMS and box transformation are applied', 'refactor_create_cell_anchors': 'refactor the _create_cell_anchors function to cache anchors and avoid recomputation per image'}
```

