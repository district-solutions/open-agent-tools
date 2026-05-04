# Agent Python Tools

- repo: facebookresearch/animateddrawings
- repo_uri: https://github.com/facebookresearch/animateddrawings

## File: facebookresearch_animateddrawings/animated_drawings/config.py

Prompts

```
['build a Config instance from a user MVC YAML config file to load view, scene, and controller settings', 'create a CharacterConfig from a character YAML file to validate skeleton joints, mask, and texture paths', 'create a MotionConfig from a motion YAML file to validate BVH filepath, frame indices, scale, and up axis', 'create a RetargetConfig from a retarget YAML file to validate bodypart groups, joint mappings, and runtime checks', 'review RetargetConfig validate_char_and_bvh_joint_names method to verify character and BVH joint name cross-references', 'run the animated drawings render pipeline with a user-specified MVC configuration file path', 'start the render loop by loading an MVC config and creating the view, scene, and controller', 'create a view, scene, and controller from an MVC config and start the run loop', 'review the start function that orchestrates config loading, view creation, scene setup, and controller execution', 'refactor the render entry point to support additional command-line arguments beyond the config file path', 'resolve a file path by searching relative, absolute, and package resource locations', 'read a background image file and return it as an RGBA numpy array with EXIF orientation applied', 'test the resolve_ad_filepath function to verify it finds files across multiple search paths', 'review the read_background_image function to understand EXIF handling and RGBA conversion logic', 'refactor the read_background_image function to support additional image formats or color space conversions']
```

Usage

```
{'build_Config': 'build a Config instance from a user MVC YAML config file to load view, scene, and controller settings', 'create_CharacterConfig': 'create a CharacterConfig from a character YAML file to validate skeleton joints, mask, and texture paths', 'create_MotionConfig': 'create a MotionConfig from a motion YAML file to validate BVH filepath, frame indices, scale, and up axis', 'create_RetargetConfig': 'create a RetargetConfig from a retarget YAML file to validate bodypart groups, joint mappings, and runtime checks', 'review_RetargetConfig_validate_char_and_bvh_joint_names': 'review RetargetConfig validate_char_and_bvh_joint_names method to verify character and BVH joint name cross-references'}
```

## File: facebookresearch_animateddrawings/animated_drawings/render.py

Prompts

```
['build a Config instance from a user MVC YAML config file to load view, scene, and controller settings', 'create a CharacterConfig from a character YAML file to validate skeleton joints, mask, and texture paths', 'create a MotionConfig from a motion YAML file to validate BVH filepath, frame indices, scale, and up axis', 'create a RetargetConfig from a retarget YAML file to validate bodypart groups, joint mappings, and runtime checks', 'review RetargetConfig validate_char_and_bvh_joint_names method to verify character and BVH joint name cross-references', 'run the animated drawings render pipeline with a user-specified MVC configuration file path', 'start the render loop by loading an MVC config and creating the view, scene, and controller', 'create a view, scene, and controller from an MVC config and start the run loop', 'review the start function that orchestrates config loading, view creation, scene setup, and controller execution', 'refactor the render entry point to support additional command-line arguments beyond the config file path', 'resolve a file path by searching relative, absolute, and package resource locations', 'read a background image file and return it as an RGBA numpy array with EXIF orientation applied', 'test the resolve_ad_filepath function to verify it finds files across multiple search paths', 'review the read_background_image function to understand EXIF handling and RGBA conversion logic', 'refactor the read_background_image function to support additional image formats or color space conversions']
```

Usage

```
{'run_render_pipeline': 'run the animated drawings render pipeline with a user-specified MVC configuration file path', 'start_render_with_config': 'start the render loop by loading an MVC config and creating the view, scene, and controller', 'create_view_scene_controller': 'create a view, scene, and controller from an MVC config and start the run loop', 'review_start_function': 'review the start function that orchestrates config loading, view creation, scene setup, and controller execution', 'refactor_render_entry': 'refactor the render entry point to support additional command-line arguments beyond the config file path'}
```

## File: facebookresearch_animateddrawings/animated_drawings/utils.py

Prompts

```
['build a Config instance from a user MVC YAML config file to load view, scene, and controller settings', 'create a CharacterConfig from a character YAML file to validate skeleton joints, mask, and texture paths', 'create a MotionConfig from a motion YAML file to validate BVH filepath, frame indices, scale, and up axis', 'create a RetargetConfig from a retarget YAML file to validate bodypart groups, joint mappings, and runtime checks', 'review RetargetConfig validate_char_and_bvh_joint_names method to verify character and BVH joint name cross-references', 'run the animated drawings render pipeline with a user-specified MVC configuration file path', 'start the render loop by loading an MVC config and creating the view, scene, and controller', 'create a view, scene, and controller from an MVC config and start the run loop', 'review the start function that orchestrates config loading, view creation, scene setup, and controller execution', 'refactor the render entry point to support additional command-line arguments beyond the config file path', 'resolve a file path by searching relative, absolute, and package resource locations', 'read a background image file and return it as an RGBA numpy array with EXIF orientation applied', 'test the resolve_ad_filepath function to verify it finds files across multiple search paths', 'review the read_background_image function to understand EXIF handling and RGBA conversion logic', 'refactor the read_background_image function to support additional image formats or color space conversions']
```

Usage

```
{'resolve_ad_filepath': 'resolve a file path by searching relative, absolute, and package resource locations', 'read_background_image': 'read a background image file and return it as an RGBA numpy array with EXIF orientation applied', 'test_resolve_ad_filepath': 'test the resolve_ad_filepath function to verify it finds files across multiple search paths', 'review_read_background_image': 'review the read_background_image function to understand EXIF handling and RGBA conversion logic', 'refactor_read_background_image': 'refactor the read_background_image function to support additional image formats or color space conversions'}
```

