# Agent Python Tools

- repo: berriai/litellm
- repo_uri: https://github.com/berriai/litellm

## File: berriai_litellm/tests/llm_translation/test_skills_data/slack-gif-creator/core/easing.py

Prompts

```
['interpolate between two numeric values using a named easing function like bounce or elastic', 'get an easing function by name from the EASING_FUNCTIONS dictionary for animation timing', 'calculate a position along a parabolic arc between two points with a given height', 'apply squash and stretch scaling to animation dimensions with configurable intensity and direction', 'use back easing functions to create overshoot and anticipate effects in animations', 'create a blank PIL Image frame with a solid white background at a given width and height', 'draw a filled or outlined circle on a PIL Image frame at a specified center position and radius', 'draw text on a PIL Image frame at a given position with optional centering and custom color', 'create a vertical gradient background image that interpolates between a top and bottom RGB color', 'draw a 5-pointed star on a PIL Image frame at a specified center with a given size and fill color', 'create a GIFBuilder instance with custom width, height, and fps for building animated GIFs', 'add numpy array or PIL Image frames to the GIFBuilder using add_frame or add_frames', 'optimize GIF frame colors using global palette quantization with a target number of colors', 'remove near-duplicate consecutive frames from the GIFBuilder to reduce file size', 'save the GIFBuilder frames as an optimized GIF with optional emoji sizing and duplicate removal', 'validate a GIF file for Slack emoji requirements checking dimensions size and frame count', 'validate a GIF file for Slack message requirements checking aspect ratio and dimensions', 'check if a GIF file is ready for Slack with a quick boolean pass or fail', 'review the validate_gif function to understand Slack dimension and size validation logic', 'refactor the is_slack_ready function to add custom validation rules for GIF files']
```

Usage

```
{'interpolate_values_with_easing': 'interpolate between two numeric values using a named easing function like bounce or elastic', 'get_easing_function_by_name': 'get an easing function by name from the EASING_FUNCTIONS dictionary for animation timing', 'calculate_arc_motion': 'calculate a position along a parabolic arc between two points with a given height', 'apply_squash_stretch': 'apply squash and stretch scaling to animation dimensions with configurable intensity and direction', 'use_back_easing_overshoot': 'use back easing functions to create overshoot and anticipate effects in animations'}
```

## File: berriai_litellm/tests/llm_translation/test_skills_data/slack-gif-creator/core/frame_composer.py

Prompts

```
['interpolate between two numeric values using a named easing function like bounce or elastic', 'get an easing function by name from the EASING_FUNCTIONS dictionary for animation timing', 'calculate a position along a parabolic arc between two points with a given height', 'apply squash and stretch scaling to animation dimensions with configurable intensity and direction', 'use back easing functions to create overshoot and anticipate effects in animations', 'create a blank PIL Image frame with a solid white background at a given width and height', 'draw a filled or outlined circle on a PIL Image frame at a specified center position and radius', 'draw text on a PIL Image frame at a given position with optional centering and custom color', 'create a vertical gradient background image that interpolates between a top and bottom RGB color', 'draw a 5-pointed star on a PIL Image frame at a specified center with a given size and fill color', 'create a GIFBuilder instance with custom width, height, and fps for building animated GIFs', 'add numpy array or PIL Image frames to the GIFBuilder using add_frame or add_frames', 'optimize GIF frame colors using global palette quantization with a target number of colors', 'remove near-duplicate consecutive frames from the GIFBuilder to reduce file size', 'save the GIFBuilder frames as an optimized GIF with optional emoji sizing and duplicate removal', 'validate a GIF file for Slack emoji requirements checking dimensions size and frame count', 'validate a GIF file for Slack message requirements checking aspect ratio and dimensions', 'check if a GIF file is ready for Slack with a quick boolean pass or fail', 'review the validate_gif function to understand Slack dimension and size validation logic', 'refactor the is_slack_ready function to add custom validation rules for GIF files']
```

Usage

```
{'create_blank_frame': 'create a blank PIL Image frame with a solid white background at a given width and height', 'draw_circle': 'draw a filled or outlined circle on a PIL Image frame at a specified center position and radius', 'draw_text': 'draw text on a PIL Image frame at a given position with optional centering and custom color', 'create_gradient_background': 'create a vertical gradient background image that interpolates between a top and bottom RGB color', 'draw_star': 'draw a 5-pointed star on a PIL Image frame at a specified center with a given size and fill color'}
```

## File: berriai_litellm/tests/llm_translation/test_skills_data/slack-gif-creator/core/gif_builder.py

Prompts

```
['interpolate between two numeric values using a named easing function like bounce or elastic', 'get an easing function by name from the EASING_FUNCTIONS dictionary for animation timing', 'calculate a position along a parabolic arc between two points with a given height', 'apply squash and stretch scaling to animation dimensions with configurable intensity and direction', 'use back easing functions to create overshoot and anticipate effects in animations', 'create a blank PIL Image frame with a solid white background at a given width and height', 'draw a filled or outlined circle on a PIL Image frame at a specified center position and radius', 'draw text on a PIL Image frame at a given position with optional centering and custom color', 'create a vertical gradient background image that interpolates between a top and bottom RGB color', 'draw a 5-pointed star on a PIL Image frame at a specified center with a given size and fill color', 'create a GIFBuilder instance with custom width, height, and fps for building animated GIFs', 'add numpy array or PIL Image frames to the GIFBuilder using add_frame or add_frames', 'optimize GIF frame colors using global palette quantization with a target number of colors', 'remove near-duplicate consecutive frames from the GIFBuilder to reduce file size', 'save the GIFBuilder frames as an optimized GIF with optional emoji sizing and duplicate removal', 'validate a GIF file for Slack emoji requirements checking dimensions size and frame count', 'validate a GIF file for Slack message requirements checking aspect ratio and dimensions', 'check if a GIF file is ready for Slack with a quick boolean pass or fail', 'review the validate_gif function to understand Slack dimension and size validation logic', 'refactor the is_slack_ready function to add custom validation rules for GIF files']
```

Usage

```
{'create_gif_builder': 'create a GIFBuilder instance with custom width, height, and fps for building animated GIFs', 'add_frames_to_gif': 'add numpy array or PIL Image frames to the GIFBuilder using add_frame or add_frames', 'optimize_gif_colors': 'optimize GIF frame colors using global palette quantization with a target number of colors', 'deduplicate_gif_frames': 'remove near-duplicate consecutive frames from the GIFBuilder to reduce file size', 'save_optimized_gif': 'save the GIFBuilder frames as an optimized GIF with optional emoji sizing and duplicate removal'}
```

## File: berriai_litellm/tests/llm_translation/test_skills_data/slack-gif-creator/core/validators.py

Prompts

```
['interpolate between two numeric values using a named easing function like bounce or elastic', 'get an easing function by name from the EASING_FUNCTIONS dictionary for animation timing', 'calculate a position along a parabolic arc between two points with a given height', 'apply squash and stretch scaling to animation dimensions with configurable intensity and direction', 'use back easing functions to create overshoot and anticipate effects in animations', 'create a blank PIL Image frame with a solid white background at a given width and height', 'draw a filled or outlined circle on a PIL Image frame at a specified center position and radius', 'draw text on a PIL Image frame at a given position with optional centering and custom color', 'create a vertical gradient background image that interpolates between a top and bottom RGB color', 'draw a 5-pointed star on a PIL Image frame at a specified center with a given size and fill color', 'create a GIFBuilder instance with custom width, height, and fps for building animated GIFs', 'add numpy array or PIL Image frames to the GIFBuilder using add_frame or add_frames', 'optimize GIF frame colors using global palette quantization with a target number of colors', 'remove near-duplicate consecutive frames from the GIFBuilder to reduce file size', 'save the GIFBuilder frames as an optimized GIF with optional emoji sizing and duplicate removal', 'validate a GIF file for Slack emoji requirements checking dimensions size and frame count', 'validate a GIF file for Slack message requirements checking aspect ratio and dimensions', 'check if a GIF file is ready for Slack with a quick boolean pass or fail', 'review the validate_gif function to understand Slack dimension and size validation logic', 'refactor the is_slack_ready function to add custom validation rules for GIF files']
```

Usage

```
{'validate_gif_for_slack_emoji': 'validate a GIF file for Slack emoji requirements checking dimensions size and frame count', 'validate_gif_for_slack_message': 'validate a GIF file for Slack message requirements checking aspect ratio and dimensions', 'check_gif_slack_ready': 'check if a GIF file is ready for Slack with a quick boolean pass or fail', 'review_validate_gif_function': 'review the validate_gif function to understand Slack dimension and size validation logic', 'refactor_is_slack_ready': 'refactor the is_slack_ready function to add custom validation rules for GIF files'}
```

