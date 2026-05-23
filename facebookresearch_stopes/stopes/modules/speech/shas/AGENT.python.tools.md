# Agent Python Tools

- repo: facebookresearch/stopes
- repo_uri: https://github.com/facebookresearch/stopes

## File: facebookresearch_stopes/stopes/modules/speech/shas/data.py

Prompts

```
['create a Segment dataclass with start, end, probs, and properties for duration and offset', 'build a FixedSegmentationDatasetNoTarget to chunk an audio WAV file into fixed-length segments for SHAS inference', 'run fixed_length_segmentation on a FixedSegmentationDatasetNoTarget instance to generate segment start and end boundaries', 'test the segm_collate_fn collate function to pad, normalize, and mask a batch of audio segments', 'review the secs_to_inframes method to convert seconds to input sample frames at 16kHz', 'load a pretrained wav2vec 2.0 model and trim it to keep only the first N encoder layers', 'build a PyTorch SegmentationFrameClassifer module with configurable transformer layers and dropout for frame-level classification', 'run a forward pass through the SegmentationFrameClassifer with input features and an attention mask to get logits', 'review the SegmentationFrameClassifer transformer encoder configuration including nhead, activation, and norm_first settings', 'test the prepare_wav2vec function to verify it correctly prunes encoder layers and replaces the final layer norm with Identity', 'build a SHAS segmenter instance with a pretrained checkpoint path and GPU enabled', 'run the SHAS segment method on an audio WAV file path to get speech segments', 'run build_segments_dataset on an audio path to get a batch sampler and dataset', 'run the infer function with wav2vec and SFC models on a dataloader to get frame probabilities', 'run the pdac algorithm on frame probabilities with max and min segment length constraints']
```

Usage

```
{'create_segment_dataclass': 'create a Segment dataclass with start, end, probs, and properties for duration and offset', 'build_fixed_segmentation_dataset': 'build a FixedSegmentationDatasetNoTarget to chunk an audio WAV file into fixed-length segments for SHAS inference', 'run_fixed_length_segmentation': 'run fixed_length_segmentation on a FixedSegmentationDatasetNoTarget instance to generate segment start and end boundaries', 'test_segm_collate_fn': 'test the segm_collate_fn collate function to pad, normalize, and mask a batch of audio segments', 'review_secs_to_inframes': 'review the secs_to_inframes method to convert seconds to input sample frames at 16kHz'}
```

## File: facebookresearch_stopes/stopes/modules/speech/shas/models.py

Prompts

```
['create a Segment dataclass with start, end, probs, and properties for duration and offset', 'build a FixedSegmentationDatasetNoTarget to chunk an audio WAV file into fixed-length segments for SHAS inference', 'run fixed_length_segmentation on a FixedSegmentationDatasetNoTarget instance to generate segment start and end boundaries', 'test the segm_collate_fn collate function to pad, normalize, and mask a batch of audio segments', 'review the secs_to_inframes method to convert seconds to input sample frames at 16kHz', 'load a pretrained wav2vec 2.0 model and trim it to keep only the first N encoder layers', 'build a PyTorch SegmentationFrameClassifer module with configurable transformer layers and dropout for frame-level classification', 'run a forward pass through the SegmentationFrameClassifer with input features and an attention mask to get logits', 'review the SegmentationFrameClassifer transformer encoder configuration including nhead, activation, and norm_first settings', 'test the prepare_wav2vec function to verify it correctly prunes encoder layers and replaces the final layer norm with Identity', 'build a SHAS segmenter instance with a pretrained checkpoint path and GPU enabled', 'run the SHAS segment method on an audio WAV file path to get speech segments', 'run build_segments_dataset on an audio path to get a batch sampler and dataset', 'run the infer function with wav2vec and SFC models on a dataloader to get frame probabilities', 'run the pdac algorithm on frame probabilities with max and min segment length constraints']
```

Usage

```
{'build_wav2vec_feature_extractor': 'load a pretrained wav2vec 2.0 model and trim it to keep only the first N encoder layers', 'create_segmentation_classifier': 'build a PyTorch SegmentationFrameClassifer module with configurable transformer layers and dropout for frame-level classification', 'run_forward_pass': 'run a forward pass through the SegmentationFrameClassifer with input features and an attention mask to get logits', 'review_transformer_encoder_config': 'review the SegmentationFrameClassifer transformer encoder configuration including nhead, activation, and norm_first settings', 'test_wav2vec_layer_pruning': 'test the prepare_wav2vec function to verify it correctly prunes encoder layers and replaces the final layer norm with Identity'}
```

## File: facebookresearch_stopes/stopes/modules/speech/shas/shas.py

Prompts

```
['create a Segment dataclass with start, end, probs, and properties for duration and offset', 'build a FixedSegmentationDatasetNoTarget to chunk an audio WAV file into fixed-length segments for SHAS inference', 'run fixed_length_segmentation on a FixedSegmentationDatasetNoTarget instance to generate segment start and end boundaries', 'test the segm_collate_fn collate function to pad, normalize, and mask a batch of audio segments', 'review the secs_to_inframes method to convert seconds to input sample frames at 16kHz', 'load a pretrained wav2vec 2.0 model and trim it to keep only the first N encoder layers', 'build a PyTorch SegmentationFrameClassifer module with configurable transformer layers and dropout for frame-level classification', 'run a forward pass through the SegmentationFrameClassifer with input features and an attention mask to get logits', 'review the SegmentationFrameClassifer transformer encoder configuration including nhead, activation, and norm_first settings', 'test the prepare_wav2vec function to verify it correctly prunes encoder layers and replaces the final layer norm with Identity', 'build a SHAS segmenter instance with a pretrained checkpoint path and GPU enabled', 'run the SHAS segment method on an audio WAV file path to get speech segments', 'run build_segments_dataset on an audio path to get a batch sampler and dataset', 'run the infer function with wav2vec and SFC models on a dataloader to get frame probabilities', 'run the pdac algorithm on frame probabilities with max and min segment length constraints']
```

Usage

```
{'build_SHAS_segmenter': 'build a SHAS segmenter instance with a pretrained checkpoint path and GPU enabled', 'run_SHAS_segment': 'run the SHAS segment method on an audio WAV file path to get speech segments', 'run_SHAS_build_segments_dataset': 'run build_segments_dataset on an audio path to get a batch sampler and dataset', 'run_infer': 'run the infer function with wav2vec and SFC models on a dataloader to get frame probabilities', 'run_pdac': 'run the pdac algorithm on frame probabilities with max and min segment length constraints'}
```

