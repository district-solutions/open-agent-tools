# Agent Python Tools

- repo: facebookresearch/sam3
- repo_uri: https://github.com/facebookresearch/sam3

## File: facebookresearch_sam3/sam3/agent/agent_core.py

Prompts

```
['run the SAM3 agent inference loop to segment objects in an image given an initial text prompt', 'save conversation messages to a debug jsonl file when debug mode is enabled', 'count the total number of image content items in a list of conversation messages', 'remove debug jsonl file and debug folder after successful agent execution', 'prune conversation messages to keep only the first two messages and the latest tool call segment', 'run send_generate_request to send multimodal messages to an OpenAI-compatible LLM API endpoint', 'run send_direct_request to perform local vLLM inference on a list of multimodal messages', 'create a base64-encoded image string and MIME type from an image file path', 'test send_generate_request with image-containing messages against a server URL', 'test send_direct_request with a vLLM instance and sampling params for local inference', 'run SAM 3 image inference with a processor, image path, and text prompt to get normalized boxes, masks, and scores', 'call the SAM 3 service with an image and text prompt to produce sorted JSON results and a visualization image', 'remove overlapping masks from SAM 3 inference outputs to deduplicate predictions', 'visualize SAM 3 inference results by rendering bounding boxes and masks onto the original image', 'normalize SAM 3 predicted bounding boxes from pixel coordinates to [0, 1] range and convert to xywh format', 'run single image inference with SAM 3 agent using an image path, text prompt, LLM config, and callbacks for LLM generation and SAM service calls', 'visualize all predicted masks on an image from a result JSON without zoom-in', 'visualize a single mask with zoom-in view and overlay using the computed color', 'visualize segmentation masks with a custom transparency alpha value', 'visualize segmentation masks with a specified label mode and font size', 'visualize a mask instance pair returning both zoomed overlay and full-scene render']
```

Usage

```
{'run_agent_inference': 'run the SAM3 agent inference loop to segment objects in an image given an initial text prompt', 'save_debug_messages': 'save conversation messages to a debug jsonl file when debug mode is enabled', 'count_images': 'count the total number of image content items in a list of conversation messages', 'cleanup_debug_files': 'remove debug jsonl file and debug folder after successful agent execution', 'prune_messages': 'prune conversation messages to keep only the first two messages and the latest tool call segment'}
```

## File: facebookresearch_sam3/sam3/agent/client_llm.py

Prompts

```
['run the SAM3 agent inference loop to segment objects in an image given an initial text prompt', 'save conversation messages to a debug jsonl file when debug mode is enabled', 'count the total number of image content items in a list of conversation messages', 'remove debug jsonl file and debug folder after successful agent execution', 'prune conversation messages to keep only the first two messages and the latest tool call segment', 'run send_generate_request to send multimodal messages to an OpenAI-compatible LLM API endpoint', 'run send_direct_request to perform local vLLM inference on a list of multimodal messages', 'create a base64-encoded image string and MIME type from an image file path', 'test send_generate_request with image-containing messages against a server URL', 'test send_direct_request with a vLLM instance and sampling params for local inference', 'run SAM 3 image inference with a processor, image path, and text prompt to get normalized boxes, masks, and scores', 'call the SAM 3 service with an image and text prompt to produce sorted JSON results and a visualization image', 'remove overlapping masks from SAM 3 inference outputs to deduplicate predictions', 'visualize SAM 3 inference results by rendering bounding boxes and masks onto the original image', 'normalize SAM 3 predicted bounding boxes from pixel coordinates to [0, 1] range and convert to xywh format', 'run single image inference with SAM 3 agent using an image path, text prompt, LLM config, and callbacks for LLM generation and SAM service calls', 'visualize all predicted masks on an image from a result JSON without zoom-in', 'visualize a single mask with zoom-in view and overlay using the computed color', 'visualize segmentation masks with a custom transparency alpha value', 'visualize segmentation masks with a specified label mode and font size', 'visualize a mask instance pair returning both zoomed overlay and full-scene render']
```

Usage

```
{'run_send_generate_request': 'run send_generate_request to send multimodal messages to an OpenAI-compatible LLM API endpoint', 'run_send_direct_request': 'run send_direct_request to perform local vLLM inference on a list of multimodal messages', 'create_get_image_base64_and_mime': 'create a base64-encoded image string and MIME type from an image file path', 'test_send_generate_request': 'test send_generate_request with image-containing messages against a server URL', 'test_send_direct_request': 'test send_direct_request with a vLLM instance and sampling params for local inference'}
```

## File: facebookresearch_sam3/sam3/agent/client_sam3.py

Prompts

```
['run the SAM3 agent inference loop to segment objects in an image given an initial text prompt', 'save conversation messages to a debug jsonl file when debug mode is enabled', 'count the total number of image content items in a list of conversation messages', 'remove debug jsonl file and debug folder after successful agent execution', 'prune conversation messages to keep only the first two messages and the latest tool call segment', 'run send_generate_request to send multimodal messages to an OpenAI-compatible LLM API endpoint', 'run send_direct_request to perform local vLLM inference on a list of multimodal messages', 'create a base64-encoded image string and MIME type from an image file path', 'test send_generate_request with image-containing messages against a server URL', 'test send_direct_request with a vLLM instance and sampling params for local inference', 'run SAM 3 image inference with a processor, image path, and text prompt to get normalized boxes, masks, and scores', 'call the SAM 3 service with an image and text prompt to produce sorted JSON results and a visualization image', 'remove overlapping masks from SAM 3 inference outputs to deduplicate predictions', 'visualize SAM 3 inference results by rendering bounding boxes and masks onto the original image', 'normalize SAM 3 predicted bounding boxes from pixel coordinates to [0, 1] range and convert to xywh format', 'run single image inference with SAM 3 agent using an image path, text prompt, LLM config, and callbacks for LLM generation and SAM service calls', 'visualize all predicted masks on an image from a result JSON without zoom-in', 'visualize a single mask with zoom-in view and overlay using the computed color', 'visualize segmentation masks with a custom transparency alpha value', 'visualize segmentation masks with a specified label mode and font size', 'visualize a mask instance pair returning both zoomed overlay and full-scene render']
```

Usage

```
{'run_sam3_inference': 'run SAM 3 image inference with a processor, image path, and text prompt to get normalized boxes, masks, and scores', 'call_sam_service': 'call the SAM 3 service with an image and text prompt to produce sorted JSON results and a visualization image', 'remove_overlapping_masks': 'remove overlapping masks from SAM 3 inference outputs to deduplicate predictions', 'visualize_sam3_results': 'visualize SAM 3 inference results by rendering bounding boxes and masks onto the original image', 'normalize_sam3_boxes': 'normalize SAM 3 predicted bounding boxes from pixel coordinates to [0, 1] range and convert to xywh format'}
```

## File: facebookresearch_sam3/sam3/agent/inference.py

Prompts

```
['run the SAM3 agent inference loop to segment objects in an image given an initial text prompt', 'save conversation messages to a debug jsonl file when debug mode is enabled', 'count the total number of image content items in a list of conversation messages', 'remove debug jsonl file and debug folder after successful agent execution', 'prune conversation messages to keep only the first two messages and the latest tool call segment', 'run send_generate_request to send multimodal messages to an OpenAI-compatible LLM API endpoint', 'run send_direct_request to perform local vLLM inference on a list of multimodal messages', 'create a base64-encoded image string and MIME type from an image file path', 'test send_generate_request with image-containing messages against a server URL', 'test send_direct_request with a vLLM instance and sampling params for local inference', 'run SAM 3 image inference with a processor, image path, and text prompt to get normalized boxes, masks, and scores', 'call the SAM 3 service with an image and text prompt to produce sorted JSON results and a visualization image', 'remove overlapping masks from SAM 3 inference outputs to deduplicate predictions', 'visualize SAM 3 inference results by rendering bounding boxes and masks onto the original image', 'normalize SAM 3 predicted bounding boxes from pixel coordinates to [0, 1] range and convert to xywh format', 'run single image inference with SAM 3 agent using an image path, text prompt, LLM config, and callbacks for LLM generation and SAM service calls', 'visualize all predicted masks on an image from a result JSON without zoom-in', 'visualize a single mask with zoom-in view and overlay using the computed color', 'visualize segmentation masks with a custom transparency alpha value', 'visualize segmentation masks with a specified label mode and font size', 'visualize a mask instance pair returning both zoomed overlay and full-scene render']
```

Usage

```
{'run_single_image_inference': 'run single image inference with SAM 3 agent using an image path, text prompt, LLM config, and callbacks for LLM generation and SAM service calls'}
```

## File: facebookresearch_sam3/sam3/agent/viz.py

Prompts

```
['run the SAM3 agent inference loop to segment objects in an image given an initial text prompt', 'save conversation messages to a debug jsonl file when debug mode is enabled', 'count the total number of image content items in a list of conversation messages', 'remove debug jsonl file and debug folder after successful agent execution', 'prune conversation messages to keep only the first two messages and the latest tool call segment', 'run send_generate_request to send multimodal messages to an OpenAI-compatible LLM API endpoint', 'run send_direct_request to perform local vLLM inference on a list of multimodal messages', 'create a base64-encoded image string and MIME type from an image file path', 'test send_generate_request with image-containing messages against a server URL', 'test send_direct_request with a vLLM instance and sampling params for local inference', 'run SAM 3 image inference with a processor, image path, and text prompt to get normalized boxes, masks, and scores', 'call the SAM 3 service with an image and text prompt to produce sorted JSON results and a visualization image', 'remove overlapping masks from SAM 3 inference outputs to deduplicate predictions', 'visualize SAM 3 inference results by rendering bounding boxes and masks onto the original image', 'normalize SAM 3 predicted bounding boxes from pixel coordinates to [0, 1] range and convert to xywh format', 'run single image inference with SAM 3 agent using an image path, text prompt, LLM config, and callbacks for LLM generation and SAM service calls', 'visualize all predicted masks on an image from a result JSON without zoom-in', 'visualize a single mask with zoom-in view and overlay using the computed color', 'visualize segmentation masks with a custom transparency alpha value', 'visualize segmentation masks with a specified label mode and font size', 'visualize a mask instance pair returning both zoomed overlay and full-scene render']
```

Usage

```
{'visualize_full_scene_masks': 'visualize all predicted masks on an image from a result JSON without zoom-in', 'visualize_single_mask_zoom_in': 'visualize a single mask with zoom-in view and overlay using the computed color', 'visualize_masks_with_custom_alpha': 'visualize segmentation masks with a custom transparency alpha value', 'visualize_masks_with_label_mode': 'visualize segmentation masks with a specified label mode and font size', 'visualize_masks_pair_output': 'visualize a mask instance pair returning both zoomed overlay and full-scene render'}
```

