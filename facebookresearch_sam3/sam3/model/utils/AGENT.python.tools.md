# Agent Python Tools

- repo: facebookresearch/sam3
- repo_uri: https://github.com/facebookresearch/sam3

## File: facebookresearch_sam3/sam3/model/utils/misc.py

Prompts

```
['copy nested data structures including tensors, dicts, lists, dataclasses, and named tuples to a specified torch device', 'test copy_data_to_device handles named tuples, lists, tuples, default dicts, mappings, dataclasses, and _CopyableData protocols', 'test _is_named_tuple correctly identifies named tuples by checking tuple type, _asdict, and _fields attributes', 'test _CopyableData protocol detection for objects with a to method accepting torch.device arguments', 'summarize how copy_data_to_device recursively moves data to a torch device across nested containers and custom objects', 'create a SAM2Transforms instance for image preprocessing with configurable resolution and mask threshold', 'transform absolute image coordinates to normalized SAM2 model coordinates using SAM2Transforms', 'transform bounding box coordinates to normalized SAM2 model coordinates using SAM2Transforms', 'postprocess SAM2 output masks by filling holes and removing sprinkles then resize to original image dimensions', 'build a batch of preprocessed images by converting PIL images to normalized tensors resized to model resolution', 'load video frames from a directory of JPEG files resized to a given image size with optional async loading', 'load video frames from an MP4 video file using decord resized to a target image size', 'load video frames from either an MP4 file or a JPEG image directory with normalization and device placement', 'create an async video frame loader that loads frames lazily in a background thread without blocking', 'load a single image as a normalized PyTorch tensor resized to a target image size']
```

Usage

```
{'copy_data_to_device': 'copy nested data structures including tensors, dicts, lists, dataclasses, and named tuples to a specified torch device', 'test_copy_data_to_device': 'test copy_data_to_device handles named tuples, lists, tuples, default dicts, mappings, dataclasses, and _CopyableData protocols', 'test_is_named_tuple': 'test _is_named_tuple correctly identifies named tuples by checking tuple type, _asdict, and _fields attributes', 'test_copyable_data_protocol': 'test _CopyableData protocol detection for objects with a to method accepting torch.device arguments', 'summarize_copy_data_to_device': 'summarize how copy_data_to_device recursively moves data to a torch device across nested containers and custom objects'}
```

## File: facebookresearch_sam3/sam3/model/utils/sam1_utils.py

Prompts

```
['copy nested data structures including tensors, dicts, lists, dataclasses, and named tuples to a specified torch device', 'test copy_data_to_device handles named tuples, lists, tuples, default dicts, mappings, dataclasses, and _CopyableData protocols', 'test _is_named_tuple correctly identifies named tuples by checking tuple type, _asdict, and _fields attributes', 'test _CopyableData protocol detection for objects with a to method accepting torch.device arguments', 'summarize how copy_data_to_device recursively moves data to a torch device across nested containers and custom objects', 'create a SAM2Transforms instance for image preprocessing with configurable resolution and mask threshold', 'transform absolute image coordinates to normalized SAM2 model coordinates using SAM2Transforms', 'transform bounding box coordinates to normalized SAM2 model coordinates using SAM2Transforms', 'postprocess SAM2 output masks by filling holes and removing sprinkles then resize to original image dimensions', 'build a batch of preprocessed images by converting PIL images to normalized tensors resized to model resolution', 'load video frames from a directory of JPEG files resized to a given image size with optional async loading', 'load video frames from an MP4 video file using decord resized to a target image size', 'load video frames from either an MP4 file or a JPEG image directory with normalization and device placement', 'create an async video frame loader that loads frames lazily in a background thread without blocking', 'load a single image as a normalized PyTorch tensor resized to a target image size']
```

Usage

```
{'create_sam2_transforms': 'create a SAM2Transforms instance for image preprocessing with configurable resolution and mask threshold', 'transform_image_coords': 'transform absolute image coordinates to normalized SAM2 model coordinates using SAM2Transforms', 'transform_image_boxes': 'transform bounding box coordinates to normalized SAM2 model coordinates using SAM2Transforms', 'postprocess_segmentation_masks': 'postprocess SAM2 output masks by filling holes and removing sprinkles then resize to original image dimensions', 'build_image_batch_transform': 'build a batch of preprocessed images by converting PIL images to normalized tensors resized to model resolution'}
```

## File: facebookresearch_sam3/sam3/model/utils/sam2_utils.py

Prompts

```
['copy nested data structures including tensors, dicts, lists, dataclasses, and named tuples to a specified torch device', 'test copy_data_to_device handles named tuples, lists, tuples, default dicts, mappings, dataclasses, and _CopyableData protocols', 'test _is_named_tuple correctly identifies named tuples by checking tuple type, _asdict, and _fields attributes', 'test _CopyableData protocol detection for objects with a to method accepting torch.device arguments', 'summarize how copy_data_to_device recursively moves data to a torch device across nested containers and custom objects', 'create a SAM2Transforms instance for image preprocessing with configurable resolution and mask threshold', 'transform absolute image coordinates to normalized SAM2 model coordinates using SAM2Transforms', 'transform bounding box coordinates to normalized SAM2 model coordinates using SAM2Transforms', 'postprocess SAM2 output masks by filling holes and removing sprinkles then resize to original image dimensions', 'build a batch of preprocessed images by converting PIL images to normalized tensors resized to model resolution', 'load video frames from a directory of JPEG files resized to a given image size with optional async loading', 'load video frames from an MP4 video file using decord resized to a target image size', 'load video frames from either an MP4 file or a JPEG image directory with normalization and device placement', 'create an async video frame loader that loads frames lazily in a background thread without blocking', 'load a single image as a normalized PyTorch tensor resized to a target image size']
```

Usage

```
{'load_video_frames_from_jpg_images': 'load video frames from a directory of JPEG files resized to a given image size with optional async loading', 'load_video_frames_from_video_file': 'load video frames from an MP4 video file using decord resized to a target image size', 'load_video_frames': 'load video frames from either an MP4 file or a JPEG image directory with normalization and device placement', 'create_async_video_frame_loader': 'create an async video frame loader that loads frames lazily in a background thread without blocking', 'load_img_as_tensor': 'load a single image as a normalized PyTorch tensor resized to a target image size'}
```

