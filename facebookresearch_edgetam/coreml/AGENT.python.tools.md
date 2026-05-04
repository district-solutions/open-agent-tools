# Agent Python Tools

- repo: facebookresearch/edgetam
- repo_uri: https://github.com/facebookresearch/edgetam

## File: facebookresearch_edgetam/coreml/benchmark_coreml.py

Prompts

```
['run the EdgeTAM benchmark comparing PyTorch and CoreML model performance with timing and quality metrics', 'load the PyTorch EdgeTAM model from a Hydra config and checkpoint file for CPU inference', 'load the CoreML image encoder, prompt encoder, and mask decoder models from mlpackage directories', 'benchmark the PyTorch EdgeTAM model by running multiple prediction passes and measuring latency in milliseconds', 'benchmark the CoreML EdgeTAM models by running prompt encoding and mask decoding and measuring latency', 'export the EdgeTAM image encoder to a CoreML mlpackage for iOS16 deployment', 'export the EdgeTAM prompt encoder to a CoreML mlpackage for iOS16 deployment', 'export the EdgeTAM mask decoder to a CoreML mlpackage for iOS16 deployment', 'run the CLI tool to export all EdgeTAM model components to CoreML format', 'review the EdgeTAMImageEncoder, EdgeTAMPromptEncoder, and EdgeTAMMaskDecoder wrapper classes for CoreML export', 'run the EdgeTAM CoreML demo to track an object in a video and save output', 'run the EdgeTAM segment example to segment a single image with point prompts', 'run the EdgeTAM track example for real-time video tracking with mouse clicks', 'review the EdgeTAMVideoTracker class that loads CoreML models and manages video frame encoding', 'review the segment_current_frame method that generates masks from tracking points and image embeddings']
```

Usage

```
{'run_benchmark': 'run the EdgeTAM benchmark comparing PyTorch and CoreML model performance with timing and quality metrics', 'load_pytorch_model': 'load the PyTorch EdgeTAM model from a Hydra config and checkpoint file for CPU inference', 'load_coreml_models': 'load the CoreML image encoder, prompt encoder, and mask decoder models from mlpackage directories', 'benchmark_pytorch': 'benchmark the PyTorch EdgeTAM model by running multiple prediction passes and measuring latency in milliseconds', 'benchmark_coreml': 'benchmark the CoreML EdgeTAM models by running prompt encoding and mask decoding and measuring latency'}
```

## File: facebookresearch_edgetam/coreml/export_to_coreml.py

Prompts

```
['run the EdgeTAM benchmark comparing PyTorch and CoreML model performance with timing and quality metrics', 'load the PyTorch EdgeTAM model from a Hydra config and checkpoint file for CPU inference', 'load the CoreML image encoder, prompt encoder, and mask decoder models from mlpackage directories', 'benchmark the PyTorch EdgeTAM model by running multiple prediction passes and measuring latency in milliseconds', 'benchmark the CoreML EdgeTAM models by running prompt encoding and mask decoding and measuring latency', 'export the EdgeTAM image encoder to a CoreML mlpackage for iOS16 deployment', 'export the EdgeTAM prompt encoder to a CoreML mlpackage for iOS16 deployment', 'export the EdgeTAM mask decoder to a CoreML mlpackage for iOS16 deployment', 'run the CLI tool to export all EdgeTAM model components to CoreML format', 'review the EdgeTAMImageEncoder, EdgeTAMPromptEncoder, and EdgeTAMMaskDecoder wrapper classes for CoreML export', 'run the EdgeTAM CoreML demo to track an object in a video and save output', 'run the EdgeTAM segment example to segment a single image with point prompts', 'run the EdgeTAM track example for real-time video tracking with mouse clicks', 'review the EdgeTAMVideoTracker class that loads CoreML models and manages video frame encoding', 'review the segment_current_frame method that generates masks from tracking points and image embeddings']
```

Usage

```
{'export_image_encoder_coreml': 'export the EdgeTAM image encoder to a CoreML mlpackage for iOS16 deployment', 'export_prompt_encoder_coreml': 'export the EdgeTAM prompt encoder to a CoreML mlpackage for iOS16 deployment', 'export_mask_decoder_coreml': 'export the EdgeTAM mask decoder to a CoreML mlpackage for iOS16 deployment', 'run_edgetam_coreml_export': 'run the CLI tool to export all EdgeTAM model components to CoreML format', 'review_edgetam_coreml_wrappers': 'review the EdgeTAMImageEncoder, EdgeTAMPromptEncoder, and EdgeTAMMaskDecoder wrapper classes for CoreML export'}
```

## File: facebookresearch_edgetam/coreml/inference_example.py

Prompts

```
['run the EdgeTAM benchmark comparing PyTorch and CoreML model performance with timing and quality metrics', 'load the PyTorch EdgeTAM model from a Hydra config and checkpoint file for CPU inference', 'load the CoreML image encoder, prompt encoder, and mask decoder models from mlpackage directories', 'benchmark the PyTorch EdgeTAM model by running multiple prediction passes and measuring latency in milliseconds', 'benchmark the CoreML EdgeTAM models by running prompt encoding and mask decoding and measuring latency', 'export the EdgeTAM image encoder to a CoreML mlpackage for iOS16 deployment', 'export the EdgeTAM prompt encoder to a CoreML mlpackage for iOS16 deployment', 'export the EdgeTAM mask decoder to a CoreML mlpackage for iOS16 deployment', 'run the CLI tool to export all EdgeTAM model components to CoreML format', 'review the EdgeTAMImageEncoder, EdgeTAMPromptEncoder, and EdgeTAMMaskDecoder wrapper classes for CoreML export', 'run the EdgeTAM CoreML demo to track an object in a video and save output', 'run the EdgeTAM segment example to segment a single image with point prompts', 'run the EdgeTAM track example for real-time video tracking with mouse clicks', 'review the EdgeTAMVideoTracker class that loads CoreML models and manages video frame encoding', 'review the segment_current_frame method that generates masks from tracking points and image embeddings']
```

Usage

```
{'run_edgeTAM_video_demo': 'run the EdgeTAM CoreML demo to track an object in a video and save output', 'run_edgeTAM_segment_example': 'run the EdgeTAM segment example to segment a single image with point prompts', 'run_edgeTAM_track_example': 'run the EdgeTAM track example for real-time video tracking with mouse clicks', 'review_edgetamvideotracker_class': 'review the EdgeTAMVideoTracker class that loads CoreML models and manages video frame encoding', 'review_segment_current_frame': 'review the segment_current_frame method that generates masks from tracking points and image embeddings'}
```

