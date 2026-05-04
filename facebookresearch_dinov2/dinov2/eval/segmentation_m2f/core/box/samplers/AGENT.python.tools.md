# Agent Python Tools

- repo: facebookresearch/dinov2
- repo_uri: https://github.com/facebookresearch/dinov2.git

## File: facebookresearch_dinov2/dinov2/eval/segmentation_m2f/core/box/samplers/base_sampler.py

Prompts

```
['sample positive and negative bounding boxes from candidates using assign results and ground truth bboxes', 'implement a subclass that overrides the abstract _sample_pos method to sample positive bounding box indices', 'implement a subclass that overrides the abstract _sample_neg method to sample negative bounding box indices', 'create a BaseSampler subclass with configurable num samples, pos fraction, neg pos upper bound, and add gt proposals flag', 'review the BaseSampler sample method logic for bbox sampling with ground truth flag handling and duplicate index removal', 'build a MaskPseudoSampler instance to sample positive and negative mask indices from assignment results', 'create a MaskSamplingResult with positive and negative indices using MaskPseudoSampler sample method', 'sample positive and negative mask indices directly from assign_result gt_inds without actual sampling', 'review the MaskPseudoSampler class that extends BaseSampler for mask-based pseudo sampling in segmentation', 'refactor the MaskPseudoSampler sample method to customize how positive and negative mask indices are extracted', 'create a MaskSamplingResult instance with positive and negative mask indices, masks, and assignment results', 'review the MaskSamplingResult masks property that concatenates positive and negative masks into a single tensor', 'summarize the MaskSamplingResult info property that returns a dictionary of sampling result metadata', 'test the MaskSamplingResult constructor to verify it correctly assigns positive and negative mask tensors', 'refactor the MaskSamplingResult __nice__ method to customize the string representation of sampling result data', 'generate a random SamplingResult using the class method with an optional RNG seed', 'move all tensors in a SamplingResult to a specified device like GPU', 'get a dictionary of info about a SamplingResult including indices and bboxes', 'concatenate positive and negative bounding boxes from a SamplingResult into one tensor']
```

Usage

```
{'sample_bboxes': 'sample positive and negative bounding boxes from candidates using assign results and ground truth bboxes', 'sample_pos_abstract': 'implement a subclass that overrides the abstract _sample_pos method to sample positive bounding box indices', 'sample_neg_abstract': 'implement a subclass that overrides the abstract _sample_neg method to sample negative bounding box indices', 'init_basesampler': 'create a BaseSampler subclass with configurable num samples, pos fraction, neg pos upper bound, and add gt proposals flag', 'review_basesampler_sample': 'review the BaseSampler sample method logic for bbox sampling with ground truth flag handling and duplicate index removal'}
```

## File: facebookresearch_dinov2/dinov2/eval/segmentation_m2f/core/box/samplers/mask_pseudo_sampler.py

Prompts

```
['sample positive and negative bounding boxes from candidates using assign results and ground truth bboxes', 'implement a subclass that overrides the abstract _sample_pos method to sample positive bounding box indices', 'implement a subclass that overrides the abstract _sample_neg method to sample negative bounding box indices', 'create a BaseSampler subclass with configurable num samples, pos fraction, neg pos upper bound, and add gt proposals flag', 'review the BaseSampler sample method logic for bbox sampling with ground truth flag handling and duplicate index removal', 'build a MaskPseudoSampler instance to sample positive and negative mask indices from assignment results', 'create a MaskSamplingResult with positive and negative indices using MaskPseudoSampler sample method', 'sample positive and negative mask indices directly from assign_result gt_inds without actual sampling', 'review the MaskPseudoSampler class that extends BaseSampler for mask-based pseudo sampling in segmentation', 'refactor the MaskPseudoSampler sample method to customize how positive and negative mask indices are extracted', 'create a MaskSamplingResult instance with positive and negative mask indices, masks, and assignment results', 'review the MaskSamplingResult masks property that concatenates positive and negative masks into a single tensor', 'summarize the MaskSamplingResult info property that returns a dictionary of sampling result metadata', 'test the MaskSamplingResult constructor to verify it correctly assigns positive and negative mask tensors', 'refactor the MaskSamplingResult __nice__ method to customize the string representation of sampling result data', 'generate a random SamplingResult using the class method with an optional RNG seed', 'move all tensors in a SamplingResult to a specified device like GPU', 'get a dictionary of info about a SamplingResult including indices and bboxes', 'concatenate positive and negative bounding boxes from a SamplingResult into one tensor']
```

Usage

```
{'build_mask_pseudo_sampler': 'build a MaskPseudoSampler instance to sample positive and negative mask indices from assignment results', 'create_sampling_result': 'create a MaskSamplingResult with positive and negative indices using MaskPseudoSampler sample method', 'sample_positive_negative_masks': 'sample positive and negative mask indices directly from assign_result gt_inds without actual sampling', 'review_mask_pseudo_sampler_class': 'review the MaskPseudoSampler class that extends BaseSampler for mask-based pseudo sampling in segmentation', 'refactor_mask_sampling_logic': 'refactor the MaskPseudoSampler sample method to customize how positive and negative mask indices are extracted'}
```

## File: facebookresearch_dinov2/dinov2/eval/segmentation_m2f/core/box/samplers/mask_sampling_result.py

Prompts

```
['sample positive and negative bounding boxes from candidates using assign results and ground truth bboxes', 'implement a subclass that overrides the abstract _sample_pos method to sample positive bounding box indices', 'implement a subclass that overrides the abstract _sample_neg method to sample negative bounding box indices', 'create a BaseSampler subclass with configurable num samples, pos fraction, neg pos upper bound, and add gt proposals flag', 'review the BaseSampler sample method logic for bbox sampling with ground truth flag handling and duplicate index removal', 'build a MaskPseudoSampler instance to sample positive and negative mask indices from assignment results', 'create a MaskSamplingResult with positive and negative indices using MaskPseudoSampler sample method', 'sample positive and negative mask indices directly from assign_result gt_inds without actual sampling', 'review the MaskPseudoSampler class that extends BaseSampler for mask-based pseudo sampling in segmentation', 'refactor the MaskPseudoSampler sample method to customize how positive and negative mask indices are extracted', 'create a MaskSamplingResult instance with positive and negative mask indices, masks, and assignment results', 'review the MaskSamplingResult masks property that concatenates positive and negative masks into a single tensor', 'summarize the MaskSamplingResult info property that returns a dictionary of sampling result metadata', 'test the MaskSamplingResult constructor to verify it correctly assigns positive and negative mask tensors', 'refactor the MaskSamplingResult __nice__ method to customize the string representation of sampling result data', 'generate a random SamplingResult using the class method with an optional RNG seed', 'move all tensors in a SamplingResult to a specified device like GPU', 'get a dictionary of info about a SamplingResult including indices and bboxes', 'concatenate positive and negative bounding boxes from a SamplingResult into one tensor']
```

Usage

```
{'create_MaskSamplingResult': 'create a MaskSamplingResult instance with positive and negative mask indices, masks, and assignment results', 'review_MaskSamplingResult_masks_property': 'review the MaskSamplingResult masks property that concatenates positive and negative masks into a single tensor', 'summarize_MaskSamplingResult_info_property': 'summarize the MaskSamplingResult info property that returns a dictionary of sampling result metadata', 'test_MaskSamplingResult_init': 'test the MaskSamplingResult constructor to verify it correctly assigns positive and negative mask tensors', 'refactor_MaskSamplingResult_nice_method': 'refactor the MaskSamplingResult __nice__ method to customize the string representation of sampling result data'}
```

## File: facebookresearch_dinov2/dinov2/eval/segmentation_m2f/core/box/samplers/sampling_result.py

Prompts

```
['sample positive and negative bounding boxes from candidates using assign results and ground truth bboxes', 'implement a subclass that overrides the abstract _sample_pos method to sample positive bounding box indices', 'implement a subclass that overrides the abstract _sample_neg method to sample negative bounding box indices', 'create a BaseSampler subclass with configurable num samples, pos fraction, neg pos upper bound, and add gt proposals flag', 'review the BaseSampler sample method logic for bbox sampling with ground truth flag handling and duplicate index removal', 'build a MaskPseudoSampler instance to sample positive and negative mask indices from assignment results', 'create a MaskSamplingResult with positive and negative indices using MaskPseudoSampler sample method', 'sample positive and negative mask indices directly from assign_result gt_inds without actual sampling', 'review the MaskPseudoSampler class that extends BaseSampler for mask-based pseudo sampling in segmentation', 'refactor the MaskPseudoSampler sample method to customize how positive and negative mask indices are extracted', 'create a MaskSamplingResult instance with positive and negative mask indices, masks, and assignment results', 'review the MaskSamplingResult masks property that concatenates positive and negative masks into a single tensor', 'summarize the MaskSamplingResult info property that returns a dictionary of sampling result metadata', 'test the MaskSamplingResult constructor to verify it correctly assigns positive and negative mask tensors', 'refactor the MaskSamplingResult __nice__ method to customize the string representation of sampling result data', 'generate a random SamplingResult using the class method with an optional RNG seed', 'move all tensors in a SamplingResult to a specified device like GPU', 'get a dictionary of info about a SamplingResult including indices and bboxes', 'concatenate positive and negative bounding boxes from a SamplingResult into one tensor']
```

Usage

```
{'create_sampling_result': 'create a SamplingResult from positive and negative indices with bboxes and assignment results', 'generate_random_sampling_result': 'generate a random SamplingResult using the class method with an optional RNG seed', 'move_sampling_result_to_device': 'move all tensors in a SamplingResult to a specified device like GPU', 'get_sampling_result_info': 'get a dictionary of info about a SamplingResult including indices and bboxes', 'concatenate_sampling_bboxes': 'concatenate positive and negative bounding boxes from a SamplingResult into one tensor'}
```

