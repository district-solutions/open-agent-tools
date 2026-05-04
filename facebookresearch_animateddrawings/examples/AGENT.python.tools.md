# Agent Python Tools

- repo: facebookresearch/animateddrawings
- repo_uri: https://github.com/facebookresearch/animateddrawings

## File: facebookresearch_animateddrawings/examples/annotations_to_animation.py

Prompts

```
['run the script to convert character annotations into an animated GIF video', 'create an MVC configuration YAML file for rendering an animated drawing scene', 'render an animation video from character annotations using a motion and retarget config', 'build a dictionary with character, motion, and retarget config paths for animation', 'review the annotations_to_animation function to understand how it generates animated GIFs from character annotations', 'run a flask web server to fix character annotation YAML config files for animated drawings', 'load a character config YAML file from disk and return the parsed dictionary', 'write a character config dictionary to a YAML file on disk', 'process a POST request to parse skeleton joint data and save updated annotations', 'render the annotation fixer UI with the character texture image and config data', 'run the image_to_animation script with an image path and character annotation directory', 'run image_to_animation using default dab motion and fair1_ppf retarget config', 'run image_to_animation with a custom motion config like jesse_dance or zombie', 'run image_to_animation with a custom retarget config like mixamo_fff or four_legs', 'run image_to_animation with all four arguments: image, annotation dir, motion config, retarget config', 'run image_to_annotations to detect drawn humanoids and generate texture, mask, and skeleton config files', 'run segment to threshold, floodfill, and extract the largest contour mask from a cropped image', 'review image_to_annotations to understand how detection, segmentation, and pose estimation produce animation-ready outputs', 'refactor image_to_annotations to support a different torchserve endpoint or custom pose keypoint mapping', 'test segment with a cropped image to verify floodfill and contour extraction produce a valid binary mask']
```

Usage

```
{'run_annotations_to_animation': 'run the script to convert character annotations into an animated GIF video', 'create_mvc_config': 'create an MVC configuration YAML file for rendering an animated drawing scene', 'render_animation_video': 'render an animation video from character annotations using a motion and retarget config', 'build_animated_drawing_dict': 'build a dictionary with character, motion, and retarget config paths for animation', 'review_annotations_to_animation': 'review the annotations_to_animation function to understand how it generates animated GIFs from character annotations'}
```

## File: facebookresearch_animateddrawings/examples/fix_annotations.py

Prompts

```
['run the script to convert character annotations into an animated GIF video', 'create an MVC configuration YAML file for rendering an animated drawing scene', 'render an animation video from character annotations using a motion and retarget config', 'build a dictionary with character, motion, and retarget config paths for animation', 'review the annotations_to_animation function to understand how it generates animated GIFs from character annotations', 'run a flask web server to fix character annotation YAML config files for animated drawings', 'load a character config YAML file from disk and return the parsed dictionary', 'write a character config dictionary to a YAML file on disk', 'process a POST request to parse skeleton joint data and save updated annotations', 'render the annotation fixer UI with the character texture image and config data', 'run the image_to_animation script with an image path and character annotation directory', 'run image_to_animation using default dab motion and fair1_ppf retarget config', 'run image_to_animation with a custom motion config like jesse_dance or zombie', 'run image_to_animation with a custom retarget config like mixamo_fff or four_legs', 'run image_to_animation with all four arguments: image, annotation dir, motion config, retarget config', 'run image_to_annotations to detect drawn humanoids and generate texture, mask, and skeleton config files', 'run segment to threshold, floodfill, and extract the largest contour mask from a cropped image', 'review image_to_annotations to understand how detection, segmentation, and pose estimation produce animation-ready outputs', 'refactor image_to_annotations to support a different torchserve endpoint or custom pose keypoint mapping', 'test segment with a cropped image to verify floodfill and contour extraction produce a valid binary mask']
```

Usage

```
{'run_flask_app': 'run a flask web server to fix character annotation YAML config files for animated drawings', 'load_cfg_yaml': 'load a character config YAML file from disk and return the parsed dictionary', 'write_cfg_yaml': 'write a character config dictionary to a YAML file on disk', 'process_annotation_submission': 'process a POST request to parse skeleton joint data and save updated annotations', 'index_route_render': 'render the annotation fixer UI with the character texture image and config data'}
```

## File: facebookresearch_animateddrawings/examples/image_to_animation.py

Prompts

```
['run the script to convert character annotations into an animated GIF video', 'create an MVC configuration YAML file for rendering an animated drawing scene', 'render an animation video from character annotations using a motion and retarget config', 'build a dictionary with character, motion, and retarget config paths for animation', 'review the annotations_to_animation function to understand how it generates animated GIFs from character annotations', 'run a flask web server to fix character annotation YAML config files for animated drawings', 'load a character config YAML file from disk and return the parsed dictionary', 'write a character config dictionary to a YAML file on disk', 'process a POST request to parse skeleton joint data and save updated annotations', 'render the annotation fixer UI with the character texture image and config data', 'run the image_to_animation script with an image path and character annotation directory', 'run image_to_animation using default dab motion and fair1_ppf retarget config', 'run image_to_animation with a custom motion config like jesse_dance or zombie', 'run image_to_animation with a custom retarget config like mixamo_fff or four_legs', 'run image_to_animation with all four arguments: image, annotation dir, motion config, retarget config', 'run image_to_annotations to detect drawn humanoids and generate texture, mask, and skeleton config files', 'run segment to threshold, floodfill, and extract the largest contour mask from a cropped image', 'review image_to_annotations to understand how detection, segmentation, and pose estimation produce animation-ready outputs', 'refactor image_to_annotations to support a different torchserve endpoint or custom pose keypoint mapping', 'test segment with a cropped image to verify floodfill and contour extraction produce a valid binary mask']
```

Usage

```
{'run_image_to_animation_cli': 'run the image_to_animation script with an image path and character annotation directory', 'run_image_to_animation_with_defaults': 'run image_to_animation using default dab motion and fair1_ppf retarget config', 'run_image_to_animation_custom_motion': 'run image_to_animation with a custom motion config like jesse_dance or zombie', 'run_image_to_animation_custom_retarget': 'run image_to_animation with a custom retarget config like mixamo_fff or four_legs', 'run_image_to_animation_full_args': 'run image_to_animation with all four arguments: image, annotation dir, motion config, retarget config'}
```

## File: facebookresearch_animateddrawings/examples/image_to_annotations.py

Prompts

```
['run the script to convert character annotations into an animated GIF video', 'create an MVC configuration YAML file for rendering an animated drawing scene', 'render an animation video from character annotations using a motion and retarget config', 'build a dictionary with character, motion, and retarget config paths for animation', 'review the annotations_to_animation function to understand how it generates animated GIFs from character annotations', 'run a flask web server to fix character annotation YAML config files for animated drawings', 'load a character config YAML file from disk and return the parsed dictionary', 'write a character config dictionary to a YAML file on disk', 'process a POST request to parse skeleton joint data and save updated annotations', 'render the annotation fixer UI with the character texture image and config data', 'run the image_to_animation script with an image path and character annotation directory', 'run image_to_animation using default dab motion and fair1_ppf retarget config', 'run image_to_animation with a custom motion config like jesse_dance or zombie', 'run image_to_animation with a custom retarget config like mixamo_fff or four_legs', 'run image_to_animation with all four arguments: image, annotation dir, motion config, retarget config', 'run image_to_annotations to detect drawn humanoids and generate texture, mask, and skeleton config files', 'run segment to threshold, floodfill, and extract the largest contour mask from a cropped image', 'review image_to_annotations to understand how detection, segmentation, and pose estimation produce animation-ready outputs', 'refactor image_to_annotations to support a different torchserve endpoint or custom pose keypoint mapping', 'test segment with a cropped image to verify floodfill and contour extraction produce a valid binary mask']
```

Usage

```
{'run_image_to_annotations': 'run image_to_annotations to detect drawn humanoids and generate texture, mask, and skeleton config files', 'run_segment': 'run segment to threshold, floodfill, and extract the largest contour mask from a cropped image', 'review_image_to_annotations': 'review image_to_annotations to understand how detection, segmentation, and pose estimation produce animation-ready outputs', 'refactor_image_to_annotations': 'refactor image_to_annotations to support a different torchserve endpoint or custom pose keypoint mapping', 'test_segment': 'test segment with a cropped image to verify floodfill and contour extraction produce a valid binary mask'}
```

