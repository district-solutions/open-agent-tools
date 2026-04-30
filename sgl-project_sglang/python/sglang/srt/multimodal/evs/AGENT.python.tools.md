# Agent Python Tools

- repo: sgl-project/sglang
- repo_uri: https://github.com/sgl-project/sglang

## File: sgl-project_sglang/python/sglang/srt/multimodal/evs/evs_core.py

Prompts

```
['compute the number of retained tokens for a video given tokens per frame, number of frames, and pruning rate', 'compute a retention mask for video embeddings using cosine similarity and pruning rate to select dissimilar tokens', 'generate a list of per-frame token counts that sum to the total retained tokens after EVS pruning', 'replace stale frame offsets in input_ids with new offsets matching post-EVS pruned token counts', 'test replace_offsets_with_tokens_per_frame with pre-chunked input ids, frame offsets, and filler token id', 'create an EVSConfig with video_pruning_rate and spatial_merge_size for video token pruning', 'build a VideoEVSDataItem with pre_chunked_input_ids and thw_grids for EVS video processing', 'test the EVS.evs_video method that applies EVS pruning to video embeddings and returns pruned results', 'refactor the EVSEmbeddingResult.redistribute_pruned_frames_placeholders method to adjust input_ids after pruning', 'review the EVS base class mixin that enables video pruning by wrapping get_video_feature', 'create an EVSProcessor instance with a HuggingFace config and a dict mapping config types to EVS model classes', 'build static-size data items for images and videos with a given frame count, rows, and columns', 'build non-EVS multimodal data items from image and video tensors with their offsets', 'test EVSProcessor initialization with a PretrainedConfig and config-to-model mapping', 'review EVSProcessor static_size_data_items method for generating token-per-frame counts and data items']
```

Usage

```
{'compute_retained_tokens_count': 'compute the number of retained tokens for a video given tokens per frame, number of frames, and pruning rate', 'compute_retention_mask': 'compute a retention mask for video embeddings using cosine similarity and pruning rate to select dissimilar tokens', 'tokens_per_frame': 'generate a list of per-frame token counts that sum to the total retained tokens after EVS pruning', 'replace_offsets_with_tokens_per_frame': 'replace stale frame offsets in input_ids with new offsets matching post-EVS pruned token counts', 'test_replace_offsets_with_tokens_per_frame': 'test replace_offsets_with_tokens_per_frame with pre-chunked input ids, frame offsets, and filler token id'}
```

## File: sgl-project_sglang/python/sglang/srt/multimodal/evs/evs_module.py

Prompts

```
['compute the number of retained tokens for a video given tokens per frame, number of frames, and pruning rate', 'compute a retention mask for video embeddings using cosine similarity and pruning rate to select dissimilar tokens', 'generate a list of per-frame token counts that sum to the total retained tokens after EVS pruning', 'replace stale frame offsets in input_ids with new offsets matching post-EVS pruned token counts', 'test replace_offsets_with_tokens_per_frame with pre-chunked input ids, frame offsets, and filler token id', 'create an EVSConfig with video_pruning_rate and spatial_merge_size for video token pruning', 'build a VideoEVSDataItem with pre_chunked_input_ids and thw_grids for EVS video processing', 'test the EVS.evs_video method that applies EVS pruning to video embeddings and returns pruned results', 'refactor the EVSEmbeddingResult.redistribute_pruned_frames_placeholders method to adjust input_ids after pruning', 'review the EVS base class mixin that enables video pruning by wrapping get_video_feature', 'create an EVSProcessor instance with a HuggingFace config and a dict mapping config types to EVS model classes', 'build static-size data items for images and videos with a given frame count, rows, and columns', 'build non-EVS multimodal data items from image and video tensors with their offsets', 'test EVSProcessor initialization with a PretrainedConfig and config-to-model mapping', 'review EVSProcessor static_size_data_items method for generating token-per-frame counts and data items']
```

Usage

```
{'create_evs_config': 'create an EVSConfig with video_pruning_rate and spatial_merge_size for video token pruning', 'build_evs_dataitem': 'build a VideoEVSDataItem with pre_chunked_input_ids and thw_grids for EVS video processing', 'test_evs_video': 'test the EVS.evs_video method that applies EVS pruning to video embeddings and returns pruned results', 'refactor_evs_embedding': 'refactor the EVSEmbeddingResult.redistribute_pruned_frames_placeholders method to adjust input_ids after pruning', 'review_evs_class': 'review the EVS base class mixin that enables video pruning by wrapping get_video_feature'}
```

## File: sgl-project_sglang/python/sglang/srt/multimodal/evs/evs_processor.py

Prompts

```
['compute the number of retained tokens for a video given tokens per frame, number of frames, and pruning rate', 'compute a retention mask for video embeddings using cosine similarity and pruning rate to select dissimilar tokens', 'generate a list of per-frame token counts that sum to the total retained tokens after EVS pruning', 'replace stale frame offsets in input_ids with new offsets matching post-EVS pruned token counts', 'test replace_offsets_with_tokens_per_frame with pre-chunked input ids, frame offsets, and filler token id', 'create an EVSConfig with video_pruning_rate and spatial_merge_size for video token pruning', 'build a VideoEVSDataItem with pre_chunked_input_ids and thw_grids for EVS video processing', 'test the EVS.evs_video method that applies EVS pruning to video embeddings and returns pruned results', 'refactor the EVSEmbeddingResult.redistribute_pruned_frames_placeholders method to adjust input_ids after pruning', 'review the EVS base class mixin that enables video pruning by wrapping get_video_feature', 'create an EVSProcessor instance with a HuggingFace config and a dict mapping config types to EVS model classes', 'build static-size data items for images and videos with a given frame count, rows, and columns', 'build non-EVS multimodal data items from image and video tensors with their offsets', 'test EVSProcessor initialization with a PretrainedConfig and config-to-model mapping', 'review EVSProcessor static_size_data_items method for generating token-per-frame counts and data items']
```

Usage

```
{'create_EVSProcessor': 'create an EVSProcessor instance with a HuggingFace config and a dict mapping config types to EVS model classes', 'build_EVSProcessor_static_size_data_items': 'build static-size data items for images and videos with a given frame count, rows, and columns', 'build__non_evs_data_items': 'build non-EVS multimodal data items from image and video tensors with their offsets', 'test_EVSProcessor_init': 'test EVSProcessor initialization with a PretrainedConfig and config-to-model mapping', 'review_EVSProcessor_static_size_data_items': 'review EVSProcessor static_size_data_items method for generating token-per-frame counts and data items'}
```

