# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/videomt/convert_videomt_to_hf.py

Prompts

```
['convert an official VidEoMT checkpoint from tue-mps/VidEoMT to Hugging Face transformers format', 'verify a converted VidEoMT model matches the GitHub reference implementation within tolerance', 'build a reference VidEoMT model from the GitHub repository for forward-pass verification', 'rename and split state dict keys from the original VidEoMT checkpoint to Hugging Face format', "infer a VideomtConfig from a checkpoint's state dict including hidden size, layers, and attention heads", 'build a VideomtForUniversalSegmentation model from a VideomtConfig for universal video segmentation', 'run the forward pass of VideomtForUniversalSegmentation with 5D video tensor inputs', 'create VideomtEmbeddings with patch embeddings, mask tokens, and positional encodings for video frames', 'create a VideomtHungarianMatcher that computes bipartite matching between predictions and ground truth masks', 'compute the VideomtLoss with cross-entropy, mask, and dice losses using hungarian matching', 'initialize a VideomtConfig instance inheriting from EomtConfig for video transformer settings', 'get VideomtForUniversalSegmentationOutput containing class queries, mask queries, and hidden states', 'run post_process_semantic_segmentation on VideomtVideoProcessor to convert model outputs into semantic segmentation predictions per frame', 'run post_process_instance_segmentation on VideomtVideoProcessor to convert model outputs into instance segmentation predictions per frame', 'run post_process_panoptic_segmentation on VideomtVideoProcessor to convert model outputs into panoptic segmentation predictions per frame', 'test compute_segments function to convert per-query mask predictions into a panoptic segmentation map', 'test check_segment_validity function to validate whether a predicted query produces a valid panoptic segment']
```

Usage

```
{'convert_checkpoint': 'convert an official VidEoMT checkpoint from tue-mps/VidEoMT to Hugging Face transformers format', 'verify_conversion': 'verify a converted VidEoMT model matches the GitHub reference implementation within tolerance', 'build_reference_model': 'build a reference VidEoMT model from the GitHub repository for forward-pass verification', 'rename_state_dict_keys': 'rename and split state dict keys from the original VidEoMT checkpoint to Hugging Face format', 'infer_videomt_config': "infer a VideomtConfig from a checkpoint's state dict including hidden size, layers, and attention heads"}
```

## File: huggingface_transformers/src/transformers/models/videomt/modeling_videomt.py

Prompts

```
['convert an official VidEoMT checkpoint from tue-mps/VidEoMT to Hugging Face transformers format', 'verify a converted VidEoMT model matches the GitHub reference implementation within tolerance', 'build a reference VidEoMT model from the GitHub repository for forward-pass verification', 'rename and split state dict keys from the original VidEoMT checkpoint to Hugging Face format', "infer a VideomtConfig from a checkpoint's state dict including hidden size, layers, and attention heads", 'build a VideomtForUniversalSegmentation model from a VideomtConfig for universal video segmentation', 'run the forward pass of VideomtForUniversalSegmentation with 5D video tensor inputs', 'create VideomtEmbeddings with patch embeddings, mask tokens, and positional encodings for video frames', 'create a VideomtHungarianMatcher that computes bipartite matching between predictions and ground truth masks', 'compute the VideomtLoss with cross-entropy, mask, and dice losses using hungarian matching', 'initialize a VideomtConfig instance inheriting from EomtConfig for video transformer settings', 'get VideomtForUniversalSegmentationOutput containing class queries, mask queries, and hidden states', 'run post_process_semantic_segmentation on VideomtVideoProcessor to convert model outputs into semantic segmentation predictions per frame', 'run post_process_instance_segmentation on VideomtVideoProcessor to convert model outputs into instance segmentation predictions per frame', 'run post_process_panoptic_segmentation on VideomtVideoProcessor to convert model outputs into panoptic segmentation predictions per frame', 'test compute_segments function to convert per-query mask predictions into a panoptic segmentation map', 'test check_segment_validity function to validate whether a predicted query produces a valid panoptic segment']
```

Usage

```
{'build_VideomtForUniversalSegmentation': 'build a VideomtForUniversalSegmentation model from a VideomtConfig for universal video segmentation', 'run_Videomt_forward': 'run the forward pass of VideomtForUniversalSegmentation with 5D video tensor inputs', 'create_VideomtEmbeddings': 'create VideomtEmbeddings with patch embeddings, mask tokens, and positional encodings for video frames', 'create_VideomtHungarianMatcher': 'create a VideomtHungarianMatcher that computes bipartite matching between predictions and ground truth masks', 'compute_VideomtLoss': 'compute the VideomtLoss with cross-entropy, mask, and dice losses using hungarian matching'}
```

## File: huggingface_transformers/src/transformers/models/videomt/modular_videomt.py

Prompts

```
['convert an official VidEoMT checkpoint from tue-mps/VidEoMT to Hugging Face transformers format', 'verify a converted VidEoMT model matches the GitHub reference implementation within tolerance', 'build a reference VidEoMT model from the GitHub repository for forward-pass verification', 'rename and split state dict keys from the original VidEoMT checkpoint to Hugging Face format', "infer a VideomtConfig from a checkpoint's state dict including hidden size, layers, and attention heads", 'build a VideomtForUniversalSegmentation model from a VideomtConfig for universal video segmentation', 'run the forward pass of VideomtForUniversalSegmentation with 5D video tensor inputs', 'create VideomtEmbeddings with patch embeddings, mask tokens, and positional encodings for video frames', 'create a VideomtHungarianMatcher that computes bipartite matching between predictions and ground truth masks', 'compute the VideomtLoss with cross-entropy, mask, and dice losses using hungarian matching', 'initialize a VideomtConfig instance inheriting from EomtConfig for video transformer settings', 'get VideomtForUniversalSegmentationOutput containing class queries, mask queries, and hidden states', 'run post_process_semantic_segmentation on VideomtVideoProcessor to convert model outputs into semantic segmentation predictions per frame', 'run post_process_instance_segmentation on VideomtVideoProcessor to convert model outputs into instance segmentation predictions per frame', 'run post_process_panoptic_segmentation on VideomtVideoProcessor to convert model outputs into panoptic segmentation predictions per frame', 'test compute_segments function to convert per-query mask predictions into a panoptic segmentation map', 'test check_segment_validity function to validate whether a predicted query produces a valid panoptic segment']
```

Usage

```
{'initialize_VideomtConfig': 'initialize a VideomtConfig instance inheriting from EomtConfig for video transformer settings', 'build_VideomtForUniversalSegmentation': 'build a VideomtForUniversalSegmentation model from a VideomtConfig for universal video segmentation', 'run_Videomt_forward': 'run the forward pass of VideomtForUniversalSegmentation with 5D video tensor inputs', 'create_VideomtEmbeddings': 'create VideomtEmbeddings with patch embeddings, mask tokens, and positional encodings for video frames', 'get_Videomt_segmentation_output': 'get VideomtForUniversalSegmentationOutput containing class queries, mask queries, and hidden states'}
```

## File: huggingface_transformers/src/transformers/models/videomt/video_processing_videomt.py

Prompts

```
['convert an official VidEoMT checkpoint from tue-mps/VidEoMT to Hugging Face transformers format', 'verify a converted VidEoMT model matches the GitHub reference implementation within tolerance', 'build a reference VidEoMT model from the GitHub repository for forward-pass verification', 'rename and split state dict keys from the original VidEoMT checkpoint to Hugging Face format', "infer a VideomtConfig from a checkpoint's state dict including hidden size, layers, and attention heads", 'build a VideomtForUniversalSegmentation model from a VideomtConfig for universal video segmentation', 'run the forward pass of VideomtForUniversalSegmentation with 5D video tensor inputs', 'create VideomtEmbeddings with patch embeddings, mask tokens, and positional encodings for video frames', 'create a VideomtHungarianMatcher that computes bipartite matching between predictions and ground truth masks', 'compute the VideomtLoss with cross-entropy, mask, and dice losses using hungarian matching', 'initialize a VideomtConfig instance inheriting from EomtConfig for video transformer settings', 'get VideomtForUniversalSegmentationOutput containing class queries, mask queries, and hidden states', 'run post_process_semantic_segmentation on VideomtVideoProcessor to convert model outputs into semantic segmentation predictions per frame', 'run post_process_instance_segmentation on VideomtVideoProcessor to convert model outputs into instance segmentation predictions per frame', 'run post_process_panoptic_segmentation on VideomtVideoProcessor to convert model outputs into panoptic segmentation predictions per frame', 'test compute_segments function to convert per-query mask predictions into a panoptic segmentation map', 'test check_segment_validity function to validate whether a predicted query produces a valid panoptic segment']
```

Usage

```
{'run_post_process_semantic_segmentation': 'run post_process_semantic_segmentation on VideomtVideoProcessor to convert model outputs into semantic segmentation predictions per frame', 'run_post_process_instance_segmentation': 'run post_process_instance_segmentation on VideomtVideoProcessor to convert model outputs into instance segmentation predictions per frame', 'run_post_process_panoptic_segmentation': 'run post_process_panoptic_segmentation on VideomtVideoProcessor to convert model outputs into panoptic segmentation predictions per frame', 'test_compute_segments': 'test compute_segments function to convert per-query mask predictions into a panoptic segmentation map', 'test_check_segment_validity': 'test check_segment_validity function to validate whether a predicted query produces a valid panoptic segment'}
```

