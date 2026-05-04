# Agent Python Tools

- repo: facebookresearch/augly
- repo_uri: https://github.com/facebookresearch/augly

## File: facebookresearch_augly/augly/video/augmenters/cv2/base_augmenter.py

Prompts

```
['create a subclass of BaseCV2Augmenter to augment video frames by adding distractors to each frame', 'build a custom apply_augmentation method in a BaseCV2Augmenter subclass to transform individual frames', 'create an iterator of random (x, y) origin coordinates within a specified bounding box range', 'build an iterator of horizontally moving origin coordinates that wrap around within a given x range', 'create an iterator that yields random RGB color tuples or randomly selects from a provided color list', 'create a VideoDistractorByDots instance with colored dot type to add colored circle distractors to video frames', 'create a VideoDistractorByDots instance with blur dot type to add Gaussian blurred dot distractors to video frames', 'apply the VideoDistractorByDots augmentation to an RGB frame to add random dot distractors in various positions', 'call add_blurred_dots on a VideoDistractorByDots instance to add Gaussian blurred dots to a single RGB frame', 'review the VideoDistractorByDots class to understand how it adds colored or blurred dot distractors to video frames', 'create a VideoDistractorByShapes instance with 5 random circles and rectangles on video frames', 'apply the VideoDistractorByShapes apply_augmentation method to draw colored shapes on a single RGB frame', 'augment a video file by adding random shape distractors to every extracted frame using the augment method', 'review the random_shape_type static method that yields circle or rectangle shape types as an iterator', 'test the random_radius static method that yields a fixed or random fractional radius for circles', 'create a VideoDistractorByText augmenter to overlay random text on video frames with configurable fonts and colors', 'apply the VideoDistractorByText apply_augmentation method to add random text overlays to a single RGB frame', 'configure the random_texts method to generate random text sequences with a specified length and change interval', 'configure the random_fonts method to cycle through CV2 or PIL fonts with optional custom character sets', 'configure the random_fontscales and random_thickness methods to control text size and stroke width on video frames']
```

Usage

```
{'augment_video_frames': 'create a subclass of BaseCV2Augmenter to augment video frames by adding distractors to each frame', 'apply_augmentation_override': 'build a custom apply_augmentation method in a BaseCV2Augmenter subclass to transform individual frames', 'random_origins_generator': 'create an iterator of random (x, y) origin coordinates within a specified bounding box range', 'moving_origins_generator': 'build an iterator of horizontally moving origin coordinates that wrap around within a given x range', 'random_colors_generator': 'create an iterator that yields random RGB color tuples or randomly selects from a provided color list'}
```

## File: facebookresearch_augly/augly/video/augmenters/cv2/dots.py

Prompts

```
['create a subclass of BaseCV2Augmenter to augment video frames by adding distractors to each frame', 'build a custom apply_augmentation method in a BaseCV2Augmenter subclass to transform individual frames', 'create an iterator of random (x, y) origin coordinates within a specified bounding box range', 'build an iterator of horizontally moving origin coordinates that wrap around within a given x range', 'create an iterator that yields random RGB color tuples or randomly selects from a provided color list', 'create a VideoDistractorByDots instance with colored dot type to add colored circle distractors to video frames', 'create a VideoDistractorByDots instance with blur dot type to add Gaussian blurred dot distractors to video frames', 'apply the VideoDistractorByDots augmentation to an RGB frame to add random dot distractors in various positions', 'call add_blurred_dots on a VideoDistractorByDots instance to add Gaussian blurred dots to a single RGB frame', 'review the VideoDistractorByDots class to understand how it adds colored or blurred dot distractors to video frames', 'create a VideoDistractorByShapes instance with 5 random circles and rectangles on video frames', 'apply the VideoDistractorByShapes apply_augmentation method to draw colored shapes on a single RGB frame', 'augment a video file by adding random shape distractors to every extracted frame using the augment method', 'review the random_shape_type static method that yields circle or rectangle shape types as an iterator', 'test the random_radius static method that yields a fixed or random fractional radius for circles', 'create a VideoDistractorByText augmenter to overlay random text on video frames with configurable fonts and colors', 'apply the VideoDistractorByText apply_augmentation method to add random text overlays to a single RGB frame', 'configure the random_texts method to generate random text sequences with a specified length and change interval', 'configure the random_fonts method to cycle through CV2 or PIL fonts with optional custom character sets', 'configure the random_fontscales and random_thickness methods to control text size and stroke width on video frames']
```

Usage

```
{'create_video_distractor_by_dots_colored': 'create a VideoDistractorByDots instance with colored dot type to add colored circle distractors to video frames', 'create_video_distractor_by_dots_blur': 'create a VideoDistractorByDots instance with blur dot type to add Gaussian blurred dot distractors to video frames', 'apply_augmentation_dots': 'apply the VideoDistractorByDots augmentation to an RGB frame to add random dot distractors in various positions', 'add_blurred_dots_to_frame': 'call add_blurred_dots on a VideoDistractorByDots instance to add Gaussian blurred dots to a single RGB frame', 'review_video_distractor_by_dots_class': 'review the VideoDistractorByDots class to understand how it adds colored or blurred dot distractors to video frames'}
```

## File: facebookresearch_augly/augly/video/augmenters/cv2/shapes.py

Prompts

```
['create a subclass of BaseCV2Augmenter to augment video frames by adding distractors to each frame', 'build a custom apply_augmentation method in a BaseCV2Augmenter subclass to transform individual frames', 'create an iterator of random (x, y) origin coordinates within a specified bounding box range', 'build an iterator of horizontally moving origin coordinates that wrap around within a given x range', 'create an iterator that yields random RGB color tuples or randomly selects from a provided color list', 'create a VideoDistractorByDots instance with colored dot type to add colored circle distractors to video frames', 'create a VideoDistractorByDots instance with blur dot type to add Gaussian blurred dot distractors to video frames', 'apply the VideoDistractorByDots augmentation to an RGB frame to add random dot distractors in various positions', 'call add_blurred_dots on a VideoDistractorByDots instance to add Gaussian blurred dots to a single RGB frame', 'review the VideoDistractorByDots class to understand how it adds colored or blurred dot distractors to video frames', 'create a VideoDistractorByShapes instance with 5 random circles and rectangles on video frames', 'apply the VideoDistractorByShapes apply_augmentation method to draw colored shapes on a single RGB frame', 'augment a video file by adding random shape distractors to every extracted frame using the augment method', 'review the random_shape_type static method that yields circle or rectangle shape types as an iterator', 'test the random_radius static method that yields a fixed or random fractional radius for circles', 'create a VideoDistractorByText augmenter to overlay random text on video frames with configurable fonts and colors', 'apply the VideoDistractorByText apply_augmentation method to add random text overlays to a single RGB frame', 'configure the random_texts method to generate random text sequences with a specified length and change interval', 'configure the random_fonts method to cycle through CV2 or PIL fonts with optional custom character sets', 'configure the random_fontscales and random_thickness methods to control text size and stroke width on video frames']
```

Usage

```
{'create_video_distractor_shapes': 'create a VideoDistractorByShapes instance with 5 random circles and rectangles on video frames', 'apply_augmentation_draw_shapes': 'apply the VideoDistractorByShapes apply_augmentation method to draw colored shapes on a single RGB frame', 'augment_video_with_shapes': 'augment a video file by adding random shape distractors to every extracted frame using the augment method', 'review_random_shape_type': 'review the random_shape_type static method that yields circle or rectangle shape types as an iterator', 'test_random_radius': 'test the random_radius static method that yields a fixed or random fractional radius for circles'}
```

## File: facebookresearch_augly/augly/video/augmenters/cv2/text.py

Prompts

```
['create a subclass of BaseCV2Augmenter to augment video frames by adding distractors to each frame', 'build a custom apply_augmentation method in a BaseCV2Augmenter subclass to transform individual frames', 'create an iterator of random (x, y) origin coordinates within a specified bounding box range', 'build an iterator of horizontally moving origin coordinates that wrap around within a given x range', 'create an iterator that yields random RGB color tuples or randomly selects from a provided color list', 'create a VideoDistractorByDots instance with colored dot type to add colored circle distractors to video frames', 'create a VideoDistractorByDots instance with blur dot type to add Gaussian blurred dot distractors to video frames', 'apply the VideoDistractorByDots augmentation to an RGB frame to add random dot distractors in various positions', 'call add_blurred_dots on a VideoDistractorByDots instance to add Gaussian blurred dots to a single RGB frame', 'review the VideoDistractorByDots class to understand how it adds colored or blurred dot distractors to video frames', 'create a VideoDistractorByShapes instance with 5 random circles and rectangles on video frames', 'apply the VideoDistractorByShapes apply_augmentation method to draw colored shapes on a single RGB frame', 'augment a video file by adding random shape distractors to every extracted frame using the augment method', 'review the random_shape_type static method that yields circle or rectangle shape types as an iterator', 'test the random_radius static method that yields a fixed or random fractional radius for circles', 'create a VideoDistractorByText augmenter to overlay random text on video frames with configurable fonts and colors', 'apply the VideoDistractorByText apply_augmentation method to add random text overlays to a single RGB frame', 'configure the random_texts method to generate random text sequences with a specified length and change interval', 'configure the random_fonts method to cycle through CV2 or PIL fonts with optional custom character sets', 'configure the random_fontscales and random_thickness methods to control text size and stroke width on video frames']
```

Usage

```
{'create_video_text_distractor': 'create a VideoDistractorByText augmenter to overlay random text on video frames with configurable fonts and colors', 'apply_text_augmentation_to_frame': 'apply the VideoDistractorByText apply_augmentation method to add random text overlays to a single RGB frame', 'configure_random_text_generator': 'configure the random_texts method to generate random text sequences with a specified length and change interval', 'configure_random_font_selection': 'configure the random_fonts method to cycle through CV2 or PIL fonts with optional custom character sets', 'configure_font_scale_and_thickness': 'configure the random_fontscales and random_thickness methods to control text size and stroke width on video frames'}
```

