# Agent Python Tools

- repo: facebookresearch/sapiens
- repo_uri: https://github.com/facebookresearch/sapiens

## File: facebookresearch_sapiens/seg/mmseg/structures/sampler/base_pixel_sampler.py

Prompts

```
['review the BasePixelSampler abstract base class and its sample method signature', 'summarize the BasePixelSampler class which defines the interface for pixel samplers', 'create a subclass of BasePixelSampler that implements the abstract sample method', 'test that BasePixelSampler cannot be instantiated directly due to the abstract sample method', 'refactor a BasePixelSampler subclass to accept seg_logit and seg_label in the sample method', 'build a pixel sampler for segmentation map using a config dict and default arguments', 'review the build_pixel_sampler function which is deprecated and delegates to TASK_UTILS.build', 'summarize the build_pixel_sampler function that constructs pixel samplers via the TASK_UTILS registry', 'refactor code that uses build_pixel_sampler to use mmseg.registry.TASK_UTILS.build directly instead', 'review the PIXEL_SAMPLERS variable which is an alias for the TASK_UTILS registry', 'create an OHEMPixelSampler instance with a decode head context and threshold for hard example mining', 'sample pixels with high loss or low prediction confidence using the OHEMPixelSampler sample method', 'configure OHEMPixelSampler with a threshold value to select low-confidence predictions for mining', 'configure OHEMPixelSampler with min_kept to keep top loss pixels when no threshold is set', 'review the OHEMPixelSampler class and its sample method for online hard example mining in segmentation']
```

Usage

```
{'review_BasePixelSampler': 'review the BasePixelSampler abstract base class and its sample method signature', 'summarize_BasePixelSampler': 'summarize the BasePixelSampler class which defines the interface for pixel samplers', 'create_subclass_BasePixelSampler': 'create a subclass of BasePixelSampler that implements the abstract sample method', 'test_BasePixelSampler_instantiation': 'test that BasePixelSampler cannot be instantiated directly due to the abstract sample method', 'refactor_BasePixelSampler_sample': 'refactor a BasePixelSampler subclass to accept seg_logit and seg_label in the sample method'}
```

## File: facebookresearch_sapiens/seg/mmseg/structures/sampler/builder.py

Prompts

```
['review the BasePixelSampler abstract base class and its sample method signature', 'summarize the BasePixelSampler class which defines the interface for pixel samplers', 'create a subclass of BasePixelSampler that implements the abstract sample method', 'test that BasePixelSampler cannot be instantiated directly due to the abstract sample method', 'refactor a BasePixelSampler subclass to accept seg_logit and seg_label in the sample method', 'build a pixel sampler for segmentation map using a config dict and default arguments', 'review the build_pixel_sampler function which is deprecated and delegates to TASK_UTILS.build', 'summarize the build_pixel_sampler function that constructs pixel samplers via the TASK_UTILS registry', 'refactor code that uses build_pixel_sampler to use mmseg.registry.TASK_UTILS.build directly instead', 'review the PIXEL_SAMPLERS variable which is an alias for the TASK_UTILS registry', 'create an OHEMPixelSampler instance with a decode head context and threshold for hard example mining', 'sample pixels with high loss or low prediction confidence using the OHEMPixelSampler sample method', 'configure OHEMPixelSampler with a threshold value to select low-confidence predictions for mining', 'configure OHEMPixelSampler with min_kept to keep top loss pixels when no threshold is set', 'review the OHEMPixelSampler class and its sample method for online hard example mining in segmentation']
```

Usage

```
{'build_pixel_sampler': 'build a pixel sampler for segmentation map using a config dict and default arguments', 'review_build_pixel_sampler': 'review the build_pixel_sampler function which is deprecated and delegates to TASK_UTILS.build', 'summarize_build_pixel_sampler': 'summarize the build_pixel_sampler function that constructs pixel samplers via the TASK_UTILS registry', 'refactor_build_pixel_sampler': 'refactor code that uses build_pixel_sampler to use mmseg.registry.TASK_UTILS.build directly instead', 'review_PIXEL_SAMPLERS': 'review the PIXEL_SAMPLERS variable which is an alias for the TASK_UTILS registry'}
```

## File: facebookresearch_sapiens/seg/mmseg/structures/sampler/ohem_pixel_sampler.py

Prompts

```
['review the BasePixelSampler abstract base class and its sample method signature', 'summarize the BasePixelSampler class which defines the interface for pixel samplers', 'create a subclass of BasePixelSampler that implements the abstract sample method', 'test that BasePixelSampler cannot be instantiated directly due to the abstract sample method', 'refactor a BasePixelSampler subclass to accept seg_logit and seg_label in the sample method', 'build a pixel sampler for segmentation map using a config dict and default arguments', 'review the build_pixel_sampler function which is deprecated and delegates to TASK_UTILS.build', 'summarize the build_pixel_sampler function that constructs pixel samplers via the TASK_UTILS registry', 'refactor code that uses build_pixel_sampler to use mmseg.registry.TASK_UTILS.build directly instead', 'review the PIXEL_SAMPLERS variable which is an alias for the TASK_UTILS registry', 'create an OHEMPixelSampler instance with a decode head context and threshold for hard example mining', 'sample pixels with high loss or low prediction confidence using the OHEMPixelSampler sample method', 'configure OHEMPixelSampler with a threshold value to select low-confidence predictions for mining', 'configure OHEMPixelSampler with min_kept to keep top loss pixels when no threshold is set', 'review the OHEMPixelSampler class and its sample method for online hard example mining in segmentation']
```

Usage

```
{'create_ohem_sampler': 'create an OHEMPixelSampler instance with a decode head context and threshold for hard example mining', 'sample_hard_pixels': 'sample pixels with high loss or low prediction confidence using the OHEMPixelSampler sample method', 'configure_threshold_sampling': 'configure OHEMPixelSampler with a threshold value to select low-confidence predictions for mining', 'configure_min_kept_sampling': 'configure OHEMPixelSampler with min_kept to keep top loss pixels when no threshold is set', 'review_ohem_sampler': 'review the OHEMPixelSampler class and its sample method for online hard example mining in segmentation'}
```

