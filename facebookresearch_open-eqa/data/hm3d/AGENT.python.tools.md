# Agent Python Tools

- repo: facebookresearch/open-eqa
- repo_uri: https://github.com/facebookresearch/open-eqa

## File: facebookresearch_open-eqa/data/hm3d/config.py

Prompts

```
['create a habitat-sim simulator configuration with rgb, depth, and semantic sensors using make_cfg', 'create a camera sensor specification with a given uuid, type, hfov, resolution, position, and pitch', 'add six movement actions including forward, backward, left, right, up, and down to an action space', 'add turn left and turn right actions with a specified rotation amount to an action space', 'add look up and look down actions with a specified pitch amount to an action space', 'extract rgb and depth frames from HM3D pickle files using Habitat-Sim simulator', 'compute and save camera intrinsic matrices from HM3D pickle scene data', 'save the camera pose transformation matrix from a Habitat-Sim simulator instance', 'save depth observations as 16-bit PNG images from a Habitat-Sim simulator', 'save RGB color observations as PNG images from a Habitat-Sim simulator']
```

Usage

```
{'create_habitat_sim_config': 'create a habitat-sim simulator configuration with rgb, depth, and semantic sensors using make_cfg', 'create_sensor_spec': 'create a camera sensor specification with a given uuid, type, hfov, resolution, position, and pitch', 'add_move_actions': 'add six movement actions including forward, backward, left, right, up, and down to an action space', 'add_turn_actions': 'add turn left and turn right actions with a specified rotation amount to an action space', 'add_look_actions': 'add look up and look down actions with a specified pitch amount to an action space'}
```

## File: facebookresearch_open-eqa/data/hm3d/extract-frames.py

Prompts

```
['create a habitat-sim simulator configuration with rgb, depth, and semantic sensors using make_cfg', 'create a camera sensor specification with a given uuid, type, hfov, resolution, position, and pitch', 'add six movement actions including forward, backward, left, right, up, and down to an action space', 'add turn left and turn right actions with a specified rotation amount to an action space', 'add look up and look down actions with a specified pitch amount to an action space', 'extract rgb and depth frames from HM3D pickle files using Habitat-Sim simulator', 'compute and save camera intrinsic matrices from HM3D pickle scene data', 'save the camera pose transformation matrix from a Habitat-Sim simulator instance', 'save depth observations as 16-bit PNG images from a Habitat-Sim simulator', 'save RGB color observations as PNG images from a Habitat-Sim simulator']
```

Usage

```
{'extract_frames_from_hm3d_pickles': 'extract rgb and depth frames from HM3D pickle files using Habitat-Sim simulator', 'save_intrinsics_from_pickle': 'compute and save camera intrinsic matrices from HM3D pickle scene data', 'save_pose_from_simulator': 'save the camera pose transformation matrix from a Habitat-Sim simulator instance', 'save_depth_from_simulator': 'save depth observations as 16-bit PNG images from a Habitat-Sim simulator', 'save_color_from_simulator': 'save RGB color observations as PNG images from a Habitat-Sim simulator'}
```

