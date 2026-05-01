# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/eomt/test_image_processing_eomt.py

Prompts

```
['test the EomtImageProcessingTester class that prepares image processor configs and fake EoMT model outputs', 'test the EomtImageProcessingTest to verify numpy image inputs are processed into correct tensor shapes', 'test the backends equivalence method to ensure slow and fast image processors produce matching outputs', 'test the post_process_semantic_segmentation method to verify segmentation output matches original image dimensions', 'test the post_process_panoptic_segmentation method to verify batched panoptic segmentation returns correct segments_info', 'run the EoMT model tester to generate config and input tensors for segmentation tests', 'test the EoMT universal segmentation model using the ModelTesterMixin and PipelineTesterMixin classes', 'test EoMT inference on pretrained models for panoptic, semantic, and instance segmentation tasks', 'run EoMT panoptic segmentation inference on a COCO image with a pretrained large model', 'run the HuggingFace pipeline for panoptic segmentation using the EoMT model']
```

Usage

```
{'test_EomtImageProcessingTester': 'test the EomtImageProcessingTester class that prepares image processor configs and fake EoMT model outputs', 'test_EomtImageProcessingTest_call_numpy': 'test the EomtImageProcessingTest to verify numpy image inputs are processed into correct tensor shapes', 'test_EomtImageProcessingTest_backends_equivalence': 'test the backends equivalence method to ensure slow and fast image processors produce matching outputs', 'test_post_process_semantic_segmentation': 'test the post_process_semantic_segmentation method to verify segmentation output matches original image dimensions', 'test_post_process_panoptic_segmentation': 'test the post_process_panoptic_segmentation method to verify batched panoptic segmentation returns correct segments_info'}
```

## File: huggingface_transformers/tests/models/eomt/test_modeling_eomt.py

Prompts

```
['test the EomtImageProcessingTester class that prepares image processor configs and fake EoMT model outputs', 'test the EomtImageProcessingTest to verify numpy image inputs are processed into correct tensor shapes', 'test the backends equivalence method to ensure slow and fast image processors produce matching outputs', 'test the post_process_semantic_segmentation method to verify segmentation output matches original image dimensions', 'test the post_process_panoptic_segmentation method to verify batched panoptic segmentation returns correct segments_info', 'run the EoMT model tester to generate config and input tensors for segmentation tests', 'test the EoMT universal segmentation model using the ModelTesterMixin and PipelineTesterMixin classes', 'test EoMT inference on pretrained models for panoptic, semantic, and instance segmentation tasks', 'run EoMT panoptic segmentation inference on a COCO image with a pretrained large model', 'run the HuggingFace pipeline for panoptic segmentation using the EoMT model']
```

Usage

```
{'run_EomtForUniversalSegmentationTester': 'run the EoMT model tester to generate config and input tensors for segmentation tests', 'test_EomtForUniversalSegmentationTest': 'test the EoMT universal segmentation model using the ModelTesterMixin and PipelineTesterMixin classes', 'test_EomtForUniversalSegmentationIntegrationTest': 'test EoMT inference on pretrained models for panoptic, semantic, and instance segmentation tasks', 'run_test_inference': 'run EoMT panoptic segmentation inference on a COCO image with a pretrained large model', 'run_test_segmentation_pipeline': 'run the HuggingFace pipeline for panoptic segmentation using the EoMT model'}
```

