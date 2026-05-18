# Agent Python Tools

- repo: facebookresearch/motif
- repo_uri: https://github.com/facebookresearch/motif

## File: facebookresearch_motif/rl_baseline/encoders_nle.py

Prompts

```
['create a Crop module that calculates centered crops around given x,y coordinates using grid sampling', 'create an NLEMainEncoder that combines CNN image encoding with vector observations and message heads', 'create a TorchBeastEncoder that processes glyphs, crops, blstats, and messages through configurable CNN heads', 'calculate the output spatial size of a convolutional network given kernel, stride, padding, and layer count', 'register a custom encoder class with the sample_factory framework using register_custom_encoder', 'create a RootNLEWrapper instance wrapping a gym NLE environment with custom observation spaces', 'test the RootNLEWrapper step method by passing an action and verifying observation reward and done', 'test the RootNLEWrapper reset method to verify it returns the initial observation from the wrapped env', 'build a custom NLE environment using make_custom_env_func with a config and env name prefix', 'review the global_env_registry registration to confirm nle_ prefix envs are properly registered', 'create a VectorFeaturesWrapper to normalize NetHack blstats into network-friendly vector observations clipped to [-5, 5]', 'create a RenderCharImagesWithNumpyWrapper to render NetHack terminal characters as RGB images using cached PIL glyphs', 'call initialize_char_array to pre-render all 256 printable characters in 16 colors into a cached NumPy array', 'use tile_characters_to_image to composite cached character tiles into an output image with optional viewport offsets', 'create a MessageWrapper to track and count repeated NetHack messages for LLM-based reward shaping', 'create a NetHackScore gym environment with configurable time penalty mode for RL training', 'run a NetHackStaircase environment where the agent must descend stairs to level 2', 'create a NetHackOracle environment where the agent must navigate to stand next to the Oracle', 'run a NetHackStaircaseContinual environment that only terminates on agent death not goal reach', 'review the NetHackScore class _get_time_penalty method to understand constant exp square linear and always modes']
```

Usage

```
{'create_crop_module': 'create a Crop module that calculates centered crops around given x,y coordinates using grid sampling', 'create_nle_main_encoder': 'create an NLEMainEncoder that combines CNN image encoding with vector observations and message heads', 'create_torchbeast_encoder': 'create a TorchBeastEncoder that processes glyphs, crops, blstats, and messages through configurable CNN heads', 'calculate_conv_output_size': 'calculate the output spatial size of a convolutional network given kernel, stride, padding, and layer count', 'register_custom_encoder': 'register a custom encoder class with the sample_factory framework using register_custom_encoder'}
```

## File: facebookresearch_motif/rl_baseline/env_nle.py

Prompts

```
['create a Crop module that calculates centered crops around given x,y coordinates using grid sampling', 'create an NLEMainEncoder that combines CNN image encoding with vector observations and message heads', 'create a TorchBeastEncoder that processes glyphs, crops, blstats, and messages through configurable CNN heads', 'calculate the output spatial size of a convolutional network given kernel, stride, padding, and layer count', 'register a custom encoder class with the sample_factory framework using register_custom_encoder', 'create a RootNLEWrapper instance wrapping a gym NLE environment with custom observation spaces', 'test the RootNLEWrapper step method by passing an action and verifying observation reward and done', 'test the RootNLEWrapper reset method to verify it returns the initial observation from the wrapped env', 'build a custom NLE environment using make_custom_env_func with a config and env name prefix', 'review the global_env_registry registration to confirm nle_ prefix envs are properly registered', 'create a VectorFeaturesWrapper to normalize NetHack blstats into network-friendly vector observations clipped to [-5, 5]', 'create a RenderCharImagesWithNumpyWrapper to render NetHack terminal characters as RGB images using cached PIL glyphs', 'call initialize_char_array to pre-render all 256 printable characters in 16 colors into a cached NumPy array', 'use tile_characters_to_image to composite cached character tiles into an output image with optional viewport offsets', 'create a MessageWrapper to track and count repeated NetHack messages for LLM-based reward shaping', 'create a NetHackScore gym environment with configurable time penalty mode for RL training', 'run a NetHackStaircase environment where the agent must descend stairs to level 2', 'create a NetHackOracle environment where the agent must navigate to stand next to the Oracle', 'run a NetHackStaircaseContinual environment that only terminates on agent death not goal reach', 'review the NetHackScore class _get_time_penalty method to understand constant exp square linear and always modes']
```

Usage

```
{'create_RootNLEWrapper': 'create a RootNLEWrapper instance wrapping a gym NLE environment with custom observation spaces', 'test_RootNLEWrapper_step': 'test the RootNLEWrapper step method by passing an action and verifying observation reward and done', 'test_RootNLEWrapper_reset': 'test the RootNLEWrapper reset method to verify it returns the initial observation from the wrapped env', 'build_make_custom_env_func': 'build a custom NLE environment using make_custom_env_func with a config and env name prefix', 'review_global_env_registry': 'review the global_env_registry registration to confirm nle_ prefix envs are properly registered'}
```

## File: facebookresearch_motif/rl_baseline/obs_wrappers.py

Prompts

```
['create a Crop module that calculates centered crops around given x,y coordinates using grid sampling', 'create an NLEMainEncoder that combines CNN image encoding with vector observations and message heads', 'create a TorchBeastEncoder that processes glyphs, crops, blstats, and messages through configurable CNN heads', 'calculate the output spatial size of a convolutional network given kernel, stride, padding, and layer count', 'register a custom encoder class with the sample_factory framework using register_custom_encoder', 'create a RootNLEWrapper instance wrapping a gym NLE environment with custom observation spaces', 'test the RootNLEWrapper step method by passing an action and verifying observation reward and done', 'test the RootNLEWrapper reset method to verify it returns the initial observation from the wrapped env', 'build a custom NLE environment using make_custom_env_func with a config and env name prefix', 'review the global_env_registry registration to confirm nle_ prefix envs are properly registered', 'create a VectorFeaturesWrapper to normalize NetHack blstats into network-friendly vector observations clipped to [-5, 5]', 'create a RenderCharImagesWithNumpyWrapper to render NetHack terminal characters as RGB images using cached PIL glyphs', 'call initialize_char_array to pre-render all 256 printable characters in 16 colors into a cached NumPy array', 'use tile_characters_to_image to composite cached character tiles into an output image with optional viewport offsets', 'create a MessageWrapper to track and count repeated NetHack messages for LLM-based reward shaping', 'create a NetHackScore gym environment with configurable time penalty mode for RL training', 'run a NetHackStaircase environment where the agent must descend stairs to level 2', 'create a NetHackOracle environment where the agent must navigate to stand next to the Oracle', 'run a NetHackStaircaseContinual environment that only terminates on agent death not goal reach', 'review the NetHackScore class _get_time_penalty method to understand constant exp square linear and always modes']
```

Usage

```
{'create_vector_features_wrapper': 'create a VectorFeaturesWrapper to normalize NetHack blstats into network-friendly vector observations clipped to [-5, 5]', 'render_char_images_wrapper': 'create a RenderCharImagesWithNumpyWrapper to render NetHack terminal characters as RGB images using cached PIL glyphs', 'initialize_char_array': 'call initialize_char_array to pre-render all 256 printable characters in 16 colors into a cached NumPy array', 'tile_characters_to_image': 'use tile_characters_to_image to composite cached character tiles into an output image with optional viewport offsets', 'create_message_wrapper': 'create a MessageWrapper to track and count repeated NetHack messages for LLM-based reward shaping'}
```

## File: facebookresearch_motif/rl_baseline/tasks_nle.py

Prompts

```
['create a Crop module that calculates centered crops around given x,y coordinates using grid sampling', 'create an NLEMainEncoder that combines CNN image encoding with vector observations and message heads', 'create a TorchBeastEncoder that processes glyphs, crops, blstats, and messages through configurable CNN heads', 'calculate the output spatial size of a convolutional network given kernel, stride, padding, and layer count', 'register a custom encoder class with the sample_factory framework using register_custom_encoder', 'create a RootNLEWrapper instance wrapping a gym NLE environment with custom observation spaces', 'test the RootNLEWrapper step method by passing an action and verifying observation reward and done', 'test the RootNLEWrapper reset method to verify it returns the initial observation from the wrapped env', 'build a custom NLE environment using make_custom_env_func with a config and env name prefix', 'review the global_env_registry registration to confirm nle_ prefix envs are properly registered', 'create a VectorFeaturesWrapper to normalize NetHack blstats into network-friendly vector observations clipped to [-5, 5]', 'create a RenderCharImagesWithNumpyWrapper to render NetHack terminal characters as RGB images using cached PIL glyphs', 'call initialize_char_array to pre-render all 256 printable characters in 16 colors into a cached NumPy array', 'use tile_characters_to_image to composite cached character tiles into an output image with optional viewport offsets', 'create a MessageWrapper to track and count repeated NetHack messages for LLM-based reward shaping', 'create a NetHackScore gym environment with configurable time penalty mode for RL training', 'run a NetHackStaircase environment where the agent must descend stairs to level 2', 'create a NetHackOracle environment where the agent must navigate to stand next to the Oracle', 'run a NetHackStaircaseContinual environment that only terminates on agent death not goal reach', 'review the NetHackScore class _get_time_penalty method to understand constant exp square linear and always modes']
```

Usage

```
{'create_nethack_score_env': 'create a NetHackScore gym environment with configurable time penalty mode for RL training', 'run_nethack_staircase_task': 'run a NetHackStaircase environment where the agent must descend stairs to level 2', 'create_oracle_env': 'create a NetHackOracle environment where the agent must navigate to stand next to the Oracle', 'run_continual_staircase': 'run a NetHackStaircaseContinual environment that only terminates on agent death not goal reach', 'review_time_penalty_modes': 'review the NetHackScore class _get_time_penalty method to understand constant exp square linear and always modes'}
```

