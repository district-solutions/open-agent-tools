# Agent Python Tools

- repo: facebookresearch/neural-light-fields
- repo_uri: https://github.com/facebookresearch/neural-light-fields

## File: facebookresearch_neural-light-fields/nlf/visualizers/base.py

Prompts

```
['create a BaseVisualizer instance with a system object and configuration dict', 'get the stored system reference from a BaseVisualizer instance using get_system', 'implement validation_video in a subclass to return visualization data for a batch', 'implement validation_image in a subclass to return per-batch visualization images', 'review the BaseVisualizer base class and its stub methods for subclass extension', 'create a ClosestViewVisualizer instance with a system and config for nearest view rendering', 'run validation on a batch to retrieve the closest RGB image for a given pose', 'run validation_video on a batch to produce video outputs with closest view RGB frames', 'run validation_image on a batch to produce image outputs for the closest view visualizer', 'review the ClosestViewVisualizer class and its validation methods for nearest view visualization', 'create an EPIVisualizer instance with a system and config to visualize epipolar plane images', 'run the EPIVisualizer validation method to generate EPI rays and render RGB output', 'run the EPIVisualizer validation_image method to get prefixed epipolar image outputs for logging', 'review the EPIVisualizer init method to understand how v, t, near, far, st_scale, and uv_scale are configured', 'refactor the EPIVisualizer validation method to support additional warp visualization channels or subdivision modes', 'build a FocusVisualizer instance with a system and config to visualize lightfield focus', 'run the FocusVisualizer validation method to generate out-of-focus and in-focus RGB images', 'run the FocusVisualizer validation_image method to return focus images with prefixed keys', 'review the FocusVisualizer constructor to understand how focus parameters s, t, ds, dt, near, far, and focal are configured', 'refactor the FocusVisualizer validation method to customize positional encoding weight calculation for frequency bands']
```

Usage

```
{'create_BaseVisualizer': 'create a BaseVisualizer instance with a system object and configuration dict', 'get_system_BaseVisualizer': 'get the stored system reference from a BaseVisualizer instance using get_system', 'implement_validation_video': 'implement validation_video in a subclass to return visualization data for a batch', 'implement_validation_image': 'implement validation_image in a subclass to return per-batch visualization images', 'review_BaseVisualizer': 'review the BaseVisualizer base class and its stub methods for subclass extension'}
```

## File: facebookresearch_neural-light-fields/nlf/visualizers/closest_view.py

Prompts

```
['create a BaseVisualizer instance with a system object and configuration dict', 'get the stored system reference from a BaseVisualizer instance using get_system', 'implement validation_video in a subclass to return visualization data for a batch', 'implement validation_image in a subclass to return per-batch visualization images', 'review the BaseVisualizer base class and its stub methods for subclass extension', 'create a ClosestViewVisualizer instance with a system and config for nearest view rendering', 'run validation on a batch to retrieve the closest RGB image for a given pose', 'run validation_video on a batch to produce video outputs with closest view RGB frames', 'run validation_image on a batch to produce image outputs for the closest view visualizer', 'review the ClosestViewVisualizer class and its validation methods for nearest view visualization', 'create an EPIVisualizer instance with a system and config to visualize epipolar plane images', 'run the EPIVisualizer validation method to generate EPI rays and render RGB output', 'run the EPIVisualizer validation_image method to get prefixed epipolar image outputs for logging', 'review the EPIVisualizer init method to understand how v, t, near, far, st_scale, and uv_scale are configured', 'refactor the EPIVisualizer validation method to support additional warp visualization channels or subdivision modes', 'build a FocusVisualizer instance with a system and config to visualize lightfield focus', 'run the FocusVisualizer validation method to generate out-of-focus and in-focus RGB images', 'run the FocusVisualizer validation_image method to return focus images with prefixed keys', 'review the FocusVisualizer constructor to understand how focus parameters s, t, ds, dt, near, far, and focal are configured', 'refactor the FocusVisualizer validation method to customize positional encoding weight calculation for frequency bands']
```

Usage

```
{'create_ClosestViewVisualizer': 'create a ClosestViewVisualizer instance with a system and config for nearest view rendering', 'run_validation': 'run validation on a batch to retrieve the closest RGB image for a given pose', 'run_validation_video': 'run validation_video on a batch to produce video outputs with closest view RGB frames', 'run_validation_image': 'run validation_image on a batch to produce image outputs for the closest view visualizer', 'review_ClosestViewVisualizer': 'review the ClosestViewVisualizer class and its validation methods for nearest view visualization'}
```

## File: facebookresearch_neural-light-fields/nlf/visualizers/epipolar.py

Prompts

```
['create a BaseVisualizer instance with a system object and configuration dict', 'get the stored system reference from a BaseVisualizer instance using get_system', 'implement validation_video in a subclass to return visualization data for a batch', 'implement validation_image in a subclass to return per-batch visualization images', 'review the BaseVisualizer base class and its stub methods for subclass extension', 'create a ClosestViewVisualizer instance with a system and config for nearest view rendering', 'run validation on a batch to retrieve the closest RGB image for a given pose', 'run validation_video on a batch to produce video outputs with closest view RGB frames', 'run validation_image on a batch to produce image outputs for the closest view visualizer', 'review the ClosestViewVisualizer class and its validation methods for nearest view visualization', 'create an EPIVisualizer instance with a system and config to visualize epipolar plane images', 'run the EPIVisualizer validation method to generate EPI rays and render RGB output', 'run the EPIVisualizer validation_image method to get prefixed epipolar image outputs for logging', 'review the EPIVisualizer init method to understand how v, t, near, far, st_scale, and uv_scale are configured', 'refactor the EPIVisualizer validation method to support additional warp visualization channels or subdivision modes', 'build a FocusVisualizer instance with a system and config to visualize lightfield focus', 'run the FocusVisualizer validation method to generate out-of-focus and in-focus RGB images', 'run the FocusVisualizer validation_image method to return focus images with prefixed keys', 'review the FocusVisualizer constructor to understand how focus parameters s, t, ds, dt, near, far, and focal are configured', 'refactor the FocusVisualizer validation method to customize positional encoding weight calculation for frequency bands']
```

Usage

```
{'create_EPIVisualizer': 'create an EPIVisualizer instance with a system and config to visualize epipolar plane images', 'run_EPIVisualizer_validation': 'run the EPIVisualizer validation method to generate EPI rays and render RGB output', 'run_EPIVisualizer_validation_image': 'run the EPIVisualizer validation_image method to get prefixed epipolar image outputs for logging', 'review_EPIVisualizer_init': 'review the EPIVisualizer init method to understand how v, t, near, far, st_scale, and uv_scale are configured', 'refactor_EPIVisualizer_validation': 'refactor the EPIVisualizer validation method to support additional warp visualization channels or subdivision modes'}
```

## File: facebookresearch_neural-light-fields/nlf/visualizers/focus.py

Prompts

```
['create a BaseVisualizer instance with a system object and configuration dict', 'get the stored system reference from a BaseVisualizer instance using get_system', 'implement validation_video in a subclass to return visualization data for a batch', 'implement validation_image in a subclass to return per-batch visualization images', 'review the BaseVisualizer base class and its stub methods for subclass extension', 'create a ClosestViewVisualizer instance with a system and config for nearest view rendering', 'run validation on a batch to retrieve the closest RGB image for a given pose', 'run validation_video on a batch to produce video outputs with closest view RGB frames', 'run validation_image on a batch to produce image outputs for the closest view visualizer', 'review the ClosestViewVisualizer class and its validation methods for nearest view visualization', 'create an EPIVisualizer instance with a system and config to visualize epipolar plane images', 'run the EPIVisualizer validation method to generate EPI rays and render RGB output', 'run the EPIVisualizer validation_image method to get prefixed epipolar image outputs for logging', 'review the EPIVisualizer init method to understand how v, t, near, far, st_scale, and uv_scale are configured', 'refactor the EPIVisualizer validation method to support additional warp visualization channels or subdivision modes', 'build a FocusVisualizer instance with a system and config to visualize lightfield focus', 'run the FocusVisualizer validation method to generate out-of-focus and in-focus RGB images', 'run the FocusVisualizer validation_image method to return focus images with prefixed keys', 'review the FocusVisualizer constructor to understand how focus parameters s, t, ds, dt, near, far, and focal are configured', 'refactor the FocusVisualizer validation method to customize positional encoding weight calculation for frequency bands']
```

Usage

```
{'build_FocusVisualizer': 'build a FocusVisualizer instance with a system and config to visualize lightfield focus', 'run_FocusVisualizer_validation': 'run the FocusVisualizer validation method to generate out-of-focus and in-focus RGB images', 'run_FocusVisualizer_validation_image': 'run the FocusVisualizer validation_image method to return focus images with prefixed keys', 'review_FocusVisualizer_init': 'review the FocusVisualizer constructor to understand how focus parameters s, t, ds, dt, near, far, and focal are configured', 'refactor_FocusVisualizer_pe_weight': 'refactor the FocusVisualizer validation method to customize positional encoding weight calculation for frequency bands'}
```

