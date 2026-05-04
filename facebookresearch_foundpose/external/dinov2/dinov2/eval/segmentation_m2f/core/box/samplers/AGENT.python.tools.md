# Agent Python Tools

- repo: facebookresearch/foundpose
- repo_uri: https://github.com/facebookresearch/foundpose

## File: facebookresearch_foundpose/external/dinov2/dinov2/eval/segmentation_m2f/core/box/samplers/base_sampler.py

Prompts

```
['sample positive and negative bounding boxes from candidates using assign results and ground truth bboxes', 'implement a subclass that overrides _sample_pos to define custom positive sample selection logic', 'implement a subclass that overrides _sample_neg to define custom negative sample selection logic', 'create a BaseSampler subclass with configurable num samples, pos fraction, and neg pos upper bound', 'review the BaseSampler class and its sample method that returns a SamplingResult object', 'build a MaskPseudoSampler instance to sample positive and negative mask indices without actual sampling', 'create a call to MaskPseudoSampler.sample with assign_result, masks, and gt_masks tensors', 'test the MaskPseudoSampler.sample method to verify it returns correct pos_inds and neg_inds', 'review the MaskSamplingResult object returned by MaskPseudoSampler.sample for correctness', 'refactor the MaskPseudoSampler to integrate with a custom assignment result pipeline', 'create a MaskSamplingResult instance with positive and negative mask indices, masks, and ground truth data', 'review the MaskSamplingResult constructor to understand how pos_masks and neg_masks are indexed from assign_result', 'use the masks property to get a concatenated tensor of all positive and negative masks', 'inspect the info property to retrieve a dictionary of all sampling result attributes and indices', 'debug the __nice__ method to get a formatted string representation of the sampling result with tensor shapes', 'create a SamplingResult from positive and negative bbox indices with ground truth boxes and assignment results', 'get the concatenated positive and negative bounding boxes as a single tensor via the bboxes property', 'move all tensor data in a SamplingResult to a specified GPU or CPU device inplace', 'get a dictionary of sampling result info including positive and negative indices and assigned ground truth indices', 'generate a random SamplingResult for testing with configurable number of predicted and ground truth boxes']
```

Usage

```
{'sample_bbox_positive_negative': 'sample positive and negative bounding boxes from candidates using assign results and ground truth bboxes', 'sample_pos_abstract': 'implement a subclass that overrides _sample_pos to define custom positive sample selection logic', 'sample_neg_abstract': 'implement a subclass that overrides _sample_neg to define custom negative sample selection logic', 'init_basesampler': 'create a BaseSampler subclass with configurable num samples, pos fraction, and neg pos upper bound', 'review_basesampler_sampling_result': 'review the BaseSampler class and its sample method that returns a SamplingResult object'}
```

## File: facebookresearch_foundpose/external/dinov2/dinov2/eval/segmentation_m2f/core/box/samplers/mask_pseudo_sampler.py

Prompts

```
['sample positive and negative bounding boxes from candidates using assign results and ground truth bboxes', 'implement a subclass that overrides _sample_pos to define custom positive sample selection logic', 'implement a subclass that overrides _sample_neg to define custom negative sample selection logic', 'create a BaseSampler subclass with configurable num samples, pos fraction, and neg pos upper bound', 'review the BaseSampler class and its sample method that returns a SamplingResult object', 'build a MaskPseudoSampler instance to sample positive and negative mask indices without actual sampling', 'create a call to MaskPseudoSampler.sample with assign_result, masks, and gt_masks tensors', 'test the MaskPseudoSampler.sample method to verify it returns correct pos_inds and neg_inds', 'review the MaskSamplingResult object returned by MaskPseudoSampler.sample for correctness', 'refactor the MaskPseudoSampler to integrate with a custom assignment result pipeline', 'create a MaskSamplingResult instance with positive and negative mask indices, masks, and ground truth data', 'review the MaskSamplingResult constructor to understand how pos_masks and neg_masks are indexed from assign_result', 'use the masks property to get a concatenated tensor of all positive and negative masks', 'inspect the info property to retrieve a dictionary of all sampling result attributes and indices', 'debug the __nice__ method to get a formatted string representation of the sampling result with tensor shapes', 'create a SamplingResult from positive and negative bbox indices with ground truth boxes and assignment results', 'get the concatenated positive and negative bounding boxes as a single tensor via the bboxes property', 'move all tensor data in a SamplingResult to a specified GPU or CPU device inplace', 'get a dictionary of sampling result info including positive and negative indices and assigned ground truth indices', 'generate a random SamplingResult for testing with configurable number of predicted and ground truth boxes']
```

Usage

```
{'build_mask_pseudo_sampler': 'build a MaskPseudoSampler instance to sample positive and negative mask indices without actual sampling', 'create_sample_call': 'create a call to MaskPseudoSampler.sample with assign_result, masks, and gt_masks tensors', 'test_sample_method': 'test the MaskPseudoSampler.sample method to verify it returns correct pos_inds and neg_inds', 'review_mask_sampling_result': 'review the MaskSamplingResult object returned by MaskPseudoSampler.sample for correctness', 'refactor_sampler_integration': 'refactor the MaskPseudoSampler to integrate with a custom assignment result pipeline'}
```

## File: facebookresearch_foundpose/external/dinov2/dinov2/eval/segmentation_m2f/core/box/samplers/mask_sampling_result.py

Prompts

```
['sample positive and negative bounding boxes from candidates using assign results and ground truth bboxes', 'implement a subclass that overrides _sample_pos to define custom positive sample selection logic', 'implement a subclass that overrides _sample_neg to define custom negative sample selection logic', 'create a BaseSampler subclass with configurable num samples, pos fraction, and neg pos upper bound', 'review the BaseSampler class and its sample method that returns a SamplingResult object', 'build a MaskPseudoSampler instance to sample positive and negative mask indices without actual sampling', 'create a call to MaskPseudoSampler.sample with assign_result, masks, and gt_masks tensors', 'test the MaskPseudoSampler.sample method to verify it returns correct pos_inds and neg_inds', 'review the MaskSamplingResult object returned by MaskPseudoSampler.sample for correctness', 'refactor the MaskPseudoSampler to integrate with a custom assignment result pipeline', 'create a MaskSamplingResult instance with positive and negative mask indices, masks, and ground truth data', 'review the MaskSamplingResult constructor to understand how pos_masks and neg_masks are indexed from assign_result', 'use the masks property to get a concatenated tensor of all positive and negative masks', 'inspect the info property to retrieve a dictionary of all sampling result attributes and indices', 'debug the __nice__ method to get a formatted string representation of the sampling result with tensor shapes', 'create a SamplingResult from positive and negative bbox indices with ground truth boxes and assignment results', 'get the concatenated positive and negative bounding boxes as a single tensor via the bboxes property', 'move all tensor data in a SamplingResult to a specified GPU or CPU device inplace', 'get a dictionary of sampling result info including positive and negative indices and assigned ground truth indices', 'generate a random SamplingResult for testing with configurable number of predicted and ground truth boxes']
```

Usage

```
{'create_MaskSamplingResult': 'create a MaskSamplingResult instance with positive and negative mask indices, masks, and ground truth data', 'review_MaskSamplingResult_init': 'review the MaskSamplingResult constructor to understand how pos_masks and neg_masks are indexed from assign_result', 'use_MaskSamplingResult_masks_property': 'use the masks property to get a concatenated tensor of all positive and negative masks', 'inspect_MaskSamplingResult_info': 'inspect the info property to retrieve a dictionary of all sampling result attributes and indices', 'debug_MaskSamplingResult_nice': 'debug the __nice__ method to get a formatted string representation of the sampling result with tensor shapes'}
```

## File: facebookresearch_foundpose/external/dinov2/dinov2/eval/segmentation_m2f/core/box/samplers/sampling_result.py

Prompts

```
['sample positive and negative bounding boxes from candidates using assign results and ground truth bboxes', 'implement a subclass that overrides _sample_pos to define custom positive sample selection logic', 'implement a subclass that overrides _sample_neg to define custom negative sample selection logic', 'create a BaseSampler subclass with configurable num samples, pos fraction, and neg pos upper bound', 'review the BaseSampler class and its sample method that returns a SamplingResult object', 'build a MaskPseudoSampler instance to sample positive and negative mask indices without actual sampling', 'create a call to MaskPseudoSampler.sample with assign_result, masks, and gt_masks tensors', 'test the MaskPseudoSampler.sample method to verify it returns correct pos_inds and neg_inds', 'review the MaskSamplingResult object returned by MaskPseudoSampler.sample for correctness', 'refactor the MaskPseudoSampler to integrate with a custom assignment result pipeline', 'create a MaskSamplingResult instance with positive and negative mask indices, masks, and ground truth data', 'review the MaskSamplingResult constructor to understand how pos_masks and neg_masks are indexed from assign_result', 'use the masks property to get a concatenated tensor of all positive and negative masks', 'inspect the info property to retrieve a dictionary of all sampling result attributes and indices', 'debug the __nice__ method to get a formatted string representation of the sampling result with tensor shapes', 'create a SamplingResult from positive and negative bbox indices with ground truth boxes and assignment results', 'get the concatenated positive and negative bounding boxes as a single tensor via the bboxes property', 'move all tensor data in a SamplingResult to a specified GPU or CPU device inplace', 'get a dictionary of sampling result info including positive and negative indices and assigned ground truth indices', 'generate a random SamplingResult for testing with configurable number of predicted and ground truth boxes']
```

Usage

```
{'create_sampling_result': 'create a SamplingResult from positive and negative bbox indices with ground truth boxes and assignment results', 'get_concatenated_bboxes': 'get the concatenated positive and negative bounding boxes as a single tensor via the bboxes property', 'move_sampling_result_to_device': 'move all tensor data in a SamplingResult to a specified GPU or CPU device inplace', 'get_sampling_result_info': 'get a dictionary of sampling result info including positive and negative indices and assigned ground truth indices', 'generate_random_sampling_result': 'generate a random SamplingResult for testing with configurable number of predicted and ground truth boxes'}
```

