# Agent Python Tools

- repo: facebookresearch/denoisedmdp
- repo_uri: https://github.com/facebookresearch/denoised_mdp

## File: facebookresearch_denoisedmdp/denoised_mdp/envs/dmc/dmc2gym/natural_imgsource.py

Prompts

```
['create a subclass of ImageSource that returns RGB images with a fixed shape', 'build a ConcatImageSource to concatenate multiple ImageSource outputs along a specified axis', 'create a RandomVideoSource that loads video frames from a filelist and applies contrast and sharpen', 'test the RandomImageSource class to load and serve random images from a filelist', 'refactor the BackgroundMatting class to produce a color mask for a given image', 'create a DMCWrapper gym environment for a DM Control domain and task with configurable observation output', 'run a step on the DMCWrapper environment with a normalized action and collect observations and rewards', 'reset the DMCWrapper environment to its initial state and return the first observation', 'review the DMCWrapper seed method to understand how random states are split and assigned to the environment', 'refactor the DMCWrapper _convert_action method to normalize actions from the unit box to the true action space']
```

Usage

```
{'create_ImageSource_subclass': 'create a subclass of ImageSource that returns RGB images with a fixed shape', 'build_ConcatImageSource': 'build a ConcatImageSource to concatenate multiple ImageSource outputs along a specified axis', 'create_RandomVideoSource': 'create a RandomVideoSource that loads video frames from a filelist and applies contrast and sharpen', 'test_RandomImageSource': 'test the RandomImageSource class to load and serve random images from a filelist', 'refactor_BackgroundMatting': 'refactor the BackgroundMatting class to produce a color mask for a given image'}
```

## File: facebookresearch_denoisedmdp/denoised_mdp/envs/dmc/dmc2gym/wrappers.py

Prompts

```
['create a subclass of ImageSource that returns RGB images with a fixed shape', 'build a ConcatImageSource to concatenate multiple ImageSource outputs along a specified axis', 'create a RandomVideoSource that loads video frames from a filelist and applies contrast and sharpen', 'test the RandomImageSource class to load and serve random images from a filelist', 'refactor the BackgroundMatting class to produce a color mask for a given image', 'create a DMCWrapper gym environment for a DM Control domain and task with configurable observation output', 'run a step on the DMCWrapper environment with a normalized action and collect observations and rewards', 'reset the DMCWrapper environment to its initial state and return the first observation', 'review the DMCWrapper seed method to understand how random states are split and assigned to the environment', 'refactor the DMCWrapper _convert_action method to normalize actions from the unit box to the true action space']
```

Usage

```
{'create_DMCWrapper': 'create a DMCWrapper gym environment for a DM Control domain and task with configurable observation output', 'run_DMCWrapper_step': 'run a step on the DMCWrapper environment with a normalized action and collect observations and rewards', 'run_DMCWrapper_reset': 'reset the DMCWrapper environment to its initial state and return the first observation', 'review_DMCWrapper_seed': 'review the DMCWrapper seed method to understand how random states are split and assigned to the environment', 'refactor_DMCWrapper_convert_action': 'refactor the DMCWrapper _convert_action method to normalize actions from the unit box to the true action space'}
```

