# Agent Python Tools

- repo: facebookresearch/maskrcnn-benchmark
- repo_uri: https://github.com/facebookresearch/maskrcnn-benchmark

## File: facebookresearch_maskrcnn-benchmark/maskrcnn_benchmark/modeling/box_coder.py

Prompts

```
['encode a set of bounding box proposals relative to reference boxes using BoxCoder', 'decode relative box offsets back into predicted bounding boxes using BoxCoder', 'create a BoxCoder instance with custom weights and bbox_xform_clip for box regression', 'review the BoxCoder encode method to understand how proposals are transformed into regression targets', 'review the BoxCoder decode method to understand how relative codes are transformed into predicted boxes', 'create a 3x3 convolutional layer with optional GroupNorm and ReLU activation', 'create a fully connected layer with Kaiming uniform initialization and optional GroupNorm', 'create a GroupNorm layer using config-based group count and epsilon settings', 'create a convolution factory function that returns conv layers with Kaiming uniform init', 'calculate the number of GroupNorm groups from channel dim and dim-per-group config', 'create a Matcher instance with high and low threshold values for matching predictions to ground truth', 'run the Matcher on an MxN match quality matrix to get ground truth matches for each prediction', 'review the Matcher class BELOW_LOW_THRESHOLD and BETWEEN_THRESHOLDS constants for match quality stratification', 'test the set_low_quality_matches_ method to produce additional matches for predictions with only low-quality candidates', 'summarize the Matcher __call__ method that assigns ground truth elements to predicted elements using quality thresholds', 'create a LevelMapper to determine FPN levels for RoIs based on box area', 'create a Pooler module with ROIAlign for multi-level feature map pooling', 'test the Pooler forward method with feature maps and box lists', 'refactor convert_to_roi_format to support additional box list formats', 'build a Pooler instance from config using the make_pooler factory function', 'concatenate a list of torch tensors along a specified dimension using the cat utility', 'return a single tensor from a one-element list without an unnecessary copy', 'concatenate multiple torch tensors along dimension 0 by default', 'review the cat function to understand its optimization for single-element tensor lists', 'summarize the cat utility function that wraps torch.cat with a single-element shortcut']
```

Usage

```
{'encode_bounding_box_proposals': 'encode a set of bounding box proposals relative to reference boxes using BoxCoder', 'decode_bounding_box_offsets': 'decode relative box offsets back into predicted bounding boxes using BoxCoder', 'create_box_coder_instance': 'create a BoxCoder instance with custom weights and bbox_xform_clip for box regression', 'review_box_coder_encode': 'review the BoxCoder encode method to understand how proposals are transformed into regression targets', 'review_box_coder_decode': 'review the BoxCoder decode method to understand how relative codes are transformed into predicted boxes'}
```

## File: facebookresearch_maskrcnn-benchmark/maskrcnn_benchmark/modeling/make_layers.py

Prompts

```
['encode a set of bounding box proposals relative to reference boxes using BoxCoder', 'decode relative box offsets back into predicted bounding boxes using BoxCoder', 'create a BoxCoder instance with custom weights and bbox_xform_clip for box regression', 'review the BoxCoder encode method to understand how proposals are transformed into regression targets', 'review the BoxCoder decode method to understand how relative codes are transformed into predicted boxes', 'create a 3x3 convolutional layer with optional GroupNorm and ReLU activation', 'create a fully connected layer with Kaiming uniform initialization and optional GroupNorm', 'create a GroupNorm layer using config-based group count and epsilon settings', 'create a convolution factory function that returns conv layers with Kaiming uniform init', 'calculate the number of GroupNorm groups from channel dim and dim-per-group config', 'create a Matcher instance with high and low threshold values for matching predictions to ground truth', 'run the Matcher on an MxN match quality matrix to get ground truth matches for each prediction', 'review the Matcher class BELOW_LOW_THRESHOLD and BETWEEN_THRESHOLDS constants for match quality stratification', 'test the set_low_quality_matches_ method to produce additional matches for predictions with only low-quality candidates', 'summarize the Matcher __call__ method that assigns ground truth elements to predicted elements using quality thresholds', 'create a LevelMapper to determine FPN levels for RoIs based on box area', 'create a Pooler module with ROIAlign for multi-level feature map pooling', 'test the Pooler forward method with feature maps and box lists', 'refactor convert_to_roi_format to support additional box list formats', 'build a Pooler instance from config using the make_pooler factory function', 'concatenate a list of torch tensors along a specified dimension using the cat utility', 'return a single tensor from a one-element list without an unnecessary copy', 'concatenate multiple torch tensors along dimension 0 by default', 'review the cat function to understand its optimization for single-element tensor lists', 'summarize the cat utility function that wraps torch.cat with a single-element shortcut']
```

Usage

```
{'create_conv3x3_layer': 'create a 3x3 convolutional layer with optional GroupNorm and ReLU activation', 'create_fc_layer': 'create a fully connected layer with Kaiming uniform initialization and optional GroupNorm', 'create_group_norm_layer': 'create a GroupNorm layer using config-based group count and epsilon settings', 'create_conv_factory': 'create a convolution factory function that returns conv layers with Kaiming uniform init', 'calculate_groupnorm_groups': 'calculate the number of GroupNorm groups from channel dim and dim-per-group config'}
```

## File: facebookresearch_maskrcnn-benchmark/maskrcnn_benchmark/modeling/matcher.py

Prompts

```
['encode a set of bounding box proposals relative to reference boxes using BoxCoder', 'decode relative box offsets back into predicted bounding boxes using BoxCoder', 'create a BoxCoder instance with custom weights and bbox_xform_clip for box regression', 'review the BoxCoder encode method to understand how proposals are transformed into regression targets', 'review the BoxCoder decode method to understand how relative codes are transformed into predicted boxes', 'create a 3x3 convolutional layer with optional GroupNorm and ReLU activation', 'create a fully connected layer with Kaiming uniform initialization and optional GroupNorm', 'create a GroupNorm layer using config-based group count and epsilon settings', 'create a convolution factory function that returns conv layers with Kaiming uniform init', 'calculate the number of GroupNorm groups from channel dim and dim-per-group config', 'create a Matcher instance with high and low threshold values for matching predictions to ground truth', 'run the Matcher on an MxN match quality matrix to get ground truth matches for each prediction', 'review the Matcher class BELOW_LOW_THRESHOLD and BETWEEN_THRESHOLDS constants for match quality stratification', 'test the set_low_quality_matches_ method to produce additional matches for predictions with only low-quality candidates', 'summarize the Matcher __call__ method that assigns ground truth elements to predicted elements using quality thresholds', 'create a LevelMapper to determine FPN levels for RoIs based on box area', 'create a Pooler module with ROIAlign for multi-level feature map pooling', 'test the Pooler forward method with feature maps and box lists', 'refactor convert_to_roi_format to support additional box list formats', 'build a Pooler instance from config using the make_pooler factory function', 'concatenate a list of torch tensors along a specified dimension using the cat utility', 'return a single tensor from a one-element list without an unnecessary copy', 'concatenate multiple torch tensors along dimension 0 by default', 'review the cat function to understand its optimization for single-element tensor lists', 'summarize the cat utility function that wraps torch.cat with a single-element shortcut']
```

Usage

```
{'create_matcher_instance': 'create a Matcher instance with high and low threshold values for matching predictions to ground truth', 'call_matcher_on_quality_matrix': 'run the Matcher on an MxN match quality matrix to get ground truth matches for each prediction', 'review_matcher_thresholds': 'review the Matcher class BELOW_LOW_THRESHOLD and BETWEEN_THRESHOLDS constants for match quality stratification', 'test_set_low_quality_matches': 'test the set_low_quality_matches_ method to produce additional matches for predictions with only low-quality candidates', 'summarize_matcher_call': 'summarize the Matcher __call__ method that assigns ground truth elements to predicted elements using quality thresholds'}
```

## File: facebookresearch_maskrcnn-benchmark/maskrcnn_benchmark/modeling/poolers.py

Prompts

```
['encode a set of bounding box proposals relative to reference boxes using BoxCoder', 'decode relative box offsets back into predicted bounding boxes using BoxCoder', 'create a BoxCoder instance with custom weights and bbox_xform_clip for box regression', 'review the BoxCoder encode method to understand how proposals are transformed into regression targets', 'review the BoxCoder decode method to understand how relative codes are transformed into predicted boxes', 'create a 3x3 convolutional layer with optional GroupNorm and ReLU activation', 'create a fully connected layer with Kaiming uniform initialization and optional GroupNorm', 'create a GroupNorm layer using config-based group count and epsilon settings', 'create a convolution factory function that returns conv layers with Kaiming uniform init', 'calculate the number of GroupNorm groups from channel dim and dim-per-group config', 'create a Matcher instance with high and low threshold values for matching predictions to ground truth', 'run the Matcher on an MxN match quality matrix to get ground truth matches for each prediction', 'review the Matcher class BELOW_LOW_THRESHOLD and BETWEEN_THRESHOLDS constants for match quality stratification', 'test the set_low_quality_matches_ method to produce additional matches for predictions with only low-quality candidates', 'summarize the Matcher __call__ method that assigns ground truth elements to predicted elements using quality thresholds', 'create a LevelMapper to determine FPN levels for RoIs based on box area', 'create a Pooler module with ROIAlign for multi-level feature map pooling', 'test the Pooler forward method with feature maps and box lists', 'refactor convert_to_roi_format to support additional box list formats', 'build a Pooler instance from config using the make_pooler factory function', 'concatenate a list of torch tensors along a specified dimension using the cat utility', 'return a single tensor from a one-element list without an unnecessary copy', 'concatenate multiple torch tensors along dimension 0 by default', 'review the cat function to understand its optimization for single-element tensor lists', 'summarize the cat utility function that wraps torch.cat with a single-element shortcut']
```

Usage

```
{'create_LevelMapper': 'create a LevelMapper to determine FPN levels for RoIs based on box area', 'create_Pooler': 'create a Pooler module with ROIAlign for multi-level feature map pooling', 'test_Pooler_forward': 'test the Pooler forward method with feature maps and box lists', 'refactor_convert_to_roi_format': 'refactor convert_to_roi_format to support additional box list formats', 'build_make_pooler': 'build a Pooler instance from config using the make_pooler factory function'}
```

## File: facebookresearch_maskrcnn-benchmark/maskrcnn_benchmark/modeling/utils.py

Prompts

```
['encode a set of bounding box proposals relative to reference boxes using BoxCoder', 'decode relative box offsets back into predicted bounding boxes using BoxCoder', 'create a BoxCoder instance with custom weights and bbox_xform_clip for box regression', 'review the BoxCoder encode method to understand how proposals are transformed into regression targets', 'review the BoxCoder decode method to understand how relative codes are transformed into predicted boxes', 'create a 3x3 convolutional layer with optional GroupNorm and ReLU activation', 'create a fully connected layer with Kaiming uniform initialization and optional GroupNorm', 'create a GroupNorm layer using config-based group count and epsilon settings', 'create a convolution factory function that returns conv layers with Kaiming uniform init', 'calculate the number of GroupNorm groups from channel dim and dim-per-group config', 'create a Matcher instance with high and low threshold values for matching predictions to ground truth', 'run the Matcher on an MxN match quality matrix to get ground truth matches for each prediction', 'review the Matcher class BELOW_LOW_THRESHOLD and BETWEEN_THRESHOLDS constants for match quality stratification', 'test the set_low_quality_matches_ method to produce additional matches for predictions with only low-quality candidates', 'summarize the Matcher __call__ method that assigns ground truth elements to predicted elements using quality thresholds', 'create a LevelMapper to determine FPN levels for RoIs based on box area', 'create a Pooler module with ROIAlign for multi-level feature map pooling', 'test the Pooler forward method with feature maps and box lists', 'refactor convert_to_roi_format to support additional box list formats', 'build a Pooler instance from config using the make_pooler factory function', 'concatenate a list of torch tensors along a specified dimension using the cat utility', 'return a single tensor from a one-element list without an unnecessary copy', 'concatenate multiple torch tensors along dimension 0 by default', 'review the cat function to understand its optimization for single-element tensor lists', 'summarize the cat utility function that wraps torch.cat with a single-element shortcut']
```

Usage

```
{'cat_tensors_along_dim': 'concatenate a list of torch tensors along a specified dimension using the cat utility', 'cat_single_tensor_no_copy': 'return a single tensor from a one-element list without an unnecessary copy', 'cat_tensors_default_dim': 'concatenate multiple torch tensors along dimension 0 by default', 'review_cat_function': 'review the cat function to understand its optimization for single-element tensor lists', 'summarize_cat_function': 'summarize the cat utility function that wraps torch.cat with a single-element shortcut'}
```

