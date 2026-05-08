# Agent Python Tools

- repo: facebookresearch/maskrcnn-benchmark
- repo_uri: https://github.com/facebookresearch/maskrcnn-benchmark

## File: facebookresearch_maskrcnn-benchmark/maskrcnn_benchmark/data/datasets/evaluation/coco/abs_to_coco.py

Prompts

```
['convert an AbstractDataset-derived dataset to COCO-style annotation format for pycocotools evaluation', 'process a single image from an AbstractDataset and extract COCO-style image and annotation data', 'convert a tensor of binary instance masks to COCO-compatible RLE encoded segmentation format', 'review the convert_abstract_to_coco function for multiprocessing dataset conversion to COCO format', 'summarize the masks_to_rles function that encodes binary mask tensors into RLE format', 'run COCO evaluation on model predictions for bbox, segmentation, and keypoints', 'create COCO detection results from model predictions with bounding boxes and scores', 'build COCO segmentation results from model predictions with RLE-encoded masks', 'test detection proposal recall metrics by evaluating IoU overlap against ground truth boxes', 'review the COCOResults class that stores and formats COCO evaluation metrics like AP and AR', 'run COCO-style evaluation on a custom AbstractDataset by converting annotations to COCO format', "convert an AbstractDataset's annotations to COCO JSON format and save to output folder", 'wrap the original COCO evaluation function to auto-convert custom dataset annotations before evaluating', 'review the do_coco_evaluation wrapper function that bridges AbstractDataset and COCO evaluation', 'refactor the coco_eval_wrapper to support additional dataset formats beyond AbstractDataset']
```

Usage

```
{'convert_abstract_to_coco': 'convert an AbstractDataset-derived dataset to COCO-style annotation format for pycocotools evaluation', 'process_single_image': 'process a single image from an AbstractDataset and extract COCO-style image and annotation data', 'masks_to_rles': 'convert a tensor of binary instance masks to COCO-compatible RLE encoded segmentation format', 'review_convert_abstract_to_coco': 'review the convert_abstract_to_coco function for multiprocessing dataset conversion to COCO format', 'summarize_masks_to_rles': 'summarize the masks_to_rles function that encodes binary mask tensors into RLE format'}
```

## File: facebookresearch_maskrcnn-benchmark/maskrcnn_benchmark/data/datasets/evaluation/coco/coco_eval.py

Prompts

```
['convert an AbstractDataset-derived dataset to COCO-style annotation format for pycocotools evaluation', 'process a single image from an AbstractDataset and extract COCO-style image and annotation data', 'convert a tensor of binary instance masks to COCO-compatible RLE encoded segmentation format', 'review the convert_abstract_to_coco function for multiprocessing dataset conversion to COCO format', 'summarize the masks_to_rles function that encodes binary mask tensors into RLE format', 'run COCO evaluation on model predictions for bbox, segmentation, and keypoints', 'create COCO detection results from model predictions with bounding boxes and scores', 'build COCO segmentation results from model predictions with RLE-encoded masks', 'test detection proposal recall metrics by evaluating IoU overlap against ground truth boxes', 'review the COCOResults class that stores and formats COCO evaluation metrics like AP and AR', 'run COCO-style evaluation on a custom AbstractDataset by converting annotations to COCO format', "convert an AbstractDataset's annotations to COCO JSON format and save to output folder", 'wrap the original COCO evaluation function to auto-convert custom dataset annotations before evaluating', 'review the do_coco_evaluation wrapper function that bridges AbstractDataset and COCO evaluation', 'refactor the coco_eval_wrapper to support additional dataset formats beyond AbstractDataset']
```

Usage

```
{'run_do_coco_evaluation': 'run COCO evaluation on model predictions for bbox, segmentation, and keypoints', 'create_prepare_for_coco_detection': 'create COCO detection results from model predictions with bounding boxes and scores', 'build_prepare_for_coco_segmentation': 'build COCO segmentation results from model predictions with RLE-encoded masks', 'test_evaluate_box_proposals': 'test detection proposal recall metrics by evaluating IoU overlap against ground truth boxes', 'review_COCOResults_class': 'review the COCOResults class that stores and formats COCO evaluation metrics like AP and AR'}
```

## File: facebookresearch_maskrcnn-benchmark/maskrcnn_benchmark/data/datasets/evaluation/coco/coco_eval_wrapper.py

Prompts

```
['convert an AbstractDataset-derived dataset to COCO-style annotation format for pycocotools evaluation', 'process a single image from an AbstractDataset and extract COCO-style image and annotation data', 'convert a tensor of binary instance masks to COCO-compatible RLE encoded segmentation format', 'review the convert_abstract_to_coco function for multiprocessing dataset conversion to COCO format', 'summarize the masks_to_rles function that encodes binary mask tensors into RLE format', 'run COCO evaluation on model predictions for bbox, segmentation, and keypoints', 'create COCO detection results from model predictions with bounding boxes and scores', 'build COCO segmentation results from model predictions with RLE-encoded masks', 'test detection proposal recall metrics by evaluating IoU overlap against ground truth boxes', 'review the COCOResults class that stores and formats COCO evaluation metrics like AP and AR', 'run COCO-style evaluation on a custom AbstractDataset by converting annotations to COCO format', "convert an AbstractDataset's annotations to COCO JSON format and save to output folder", 'wrap the original COCO evaluation function to auto-convert custom dataset annotations before evaluating', 'review the do_coco_evaluation wrapper function that bridges AbstractDataset and COCO evaluation', 'refactor the coco_eval_wrapper to support additional dataset formats beyond AbstractDataset']
```

Usage

```
{'run_coco_evaluation_on_custom_dataset': 'run COCO-style evaluation on a custom AbstractDataset by converting annotations to COCO format', 'convert_abstract_to_coco_annotations': "convert an AbstractDataset's annotations to COCO JSON format and save to output folder", 'wrap_evaluation_with_coco_conversion': 'wrap the original COCO evaluation function to auto-convert custom dataset annotations before evaluating', 'review_do_coco_evaluation': 'review the do_coco_evaluation wrapper function that bridges AbstractDataset and COCO evaluation', 'refactor_coco_eval_wrapper': 'refactor the coco_eval_wrapper to support additional dataset formats beyond AbstractDataset'}
```

