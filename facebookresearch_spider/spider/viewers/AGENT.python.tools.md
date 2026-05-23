# Agent Python Tools

- repo: facebookresearch/spider
- repo_uri: https://github.com/facebookresearch/spider

## File: facebookresearch_spider/spider/viewers/mj_dr_viewer.py

Prompts

```
['run the MuJoCo direct replay viewer to visualize robot hand trajectories from dataset files', 'run the MuJoCo simulation with retarget, noise, rect, or debug control modes for robot hand replay', 'run the MuJoCo direct replay viewer with video recording enabled to save MP4 output', 'run the MuJoCo simulation with external force applied to objects via PD position control', 'run the MuJoCo direct replay viewer in headless mode without launching the GUI window', 'run a MuJoCo CPU simulation of a robot hand grasping task with trajectory replay', 'run the MuJoCo viewer and save the simulation as an MP4 video recording', 'run the MuJoCo simulation with random noise applied to the control signals', 'run the MuJoCo simulation with external forces applied to objects via PD control', 'run the MuJoCo simulation and save simulation state info to an NPZ file', 'run the MuJoCo XML Rerun viewer CLI to visualize a scene XML and trajectory NPZ file', 'build a Rerun scene graph from a MuJoCo MJCF XML file and log static geometry', "export a MuJoCo scene's static geometry and local transforms to an NPZ file for offline use", 'play a MuJoCo trajectory from an NPZ file by logging per-body world transforms to Rerun', 'load a pre-baked scene NPZ file and log its geometry to a Rerun visualization session', 'initialize a Viser server for MuJoCo scene visualization with a custom app name', 'build and log a MuJoCo scene from an XML file into the Viser viewer', 'build and log a Viser scene directly from a MuJoCo MjSpec and compiled model', 'log a MuJoCo simulation frame to Viser with body positions and optional reference data', 'log optimization traces with optional reference traces and cost data to the Viser viewer']
```

Usage

```
{'run_mujoco_dr_visualization': 'run the MuJoCo direct replay viewer to visualize robot hand trajectories from dataset files', 'run_simulation_with_ctrl_modes': 'run the MuJoCo simulation with retarget, noise, rect, or debug control modes for robot hand replay', 'run_simulation_with_video_recording': 'run the MuJoCo direct replay viewer with video recording enabled to save MP4 output', 'run_simulation_with_external_forces': 'run the MuJoCo simulation with external force applied to objects via PD position control', 'run_simulation_headless': 'run the MuJoCo direct replay viewer in headless mode without launching the GUI window'}
```

## File: facebookresearch_spider/spider/viewers/mjcpu_viewer.py

Prompts

```
['run the MuJoCo direct replay viewer to visualize robot hand trajectories from dataset files', 'run the MuJoCo simulation with retarget, noise, rect, or debug control modes for robot hand replay', 'run the MuJoCo direct replay viewer with video recording enabled to save MP4 output', 'run the MuJoCo simulation with external force applied to objects via PD position control', 'run the MuJoCo direct replay viewer in headless mode without launching the GUI window', 'run a MuJoCo CPU simulation of a robot hand grasping task with trajectory replay', 'run the MuJoCo viewer and save the simulation as an MP4 video recording', 'run the MuJoCo simulation with random noise applied to the control signals', 'run the MuJoCo simulation with external forces applied to objects via PD control', 'run the MuJoCo simulation and save simulation state info to an NPZ file', 'run the MuJoCo XML Rerun viewer CLI to visualize a scene XML and trajectory NPZ file', 'build a Rerun scene graph from a MuJoCo MJCF XML file and log static geometry', "export a MuJoCo scene's static geometry and local transforms to an NPZ file for offline use", 'play a MuJoCo trajectory from an NPZ file by logging per-body world transforms to Rerun', 'load a pre-baked scene NPZ file and log its geometry to a Rerun visualization session', 'initialize a Viser server for MuJoCo scene visualization with a custom app name', 'build and log a MuJoCo scene from an XML file into the Viser viewer', 'build and log a Viser scene directly from a MuJoCo MjSpec and compiled model', 'log a MuJoCo simulation frame to Viser with body positions and optional reference data', 'log optimization traces with optional reference traces and cost data to the Viser viewer']
```

Usage

```
{'run_mjcpu_simulation': 'run a MuJoCo CPU simulation of a robot hand grasping task with trajectory replay', 'run_mjcpu_with_video': 'run the MuJoCo viewer and save the simulation as an MP4 video recording', 'run_mjcpu_with_noise': 'run the MuJoCo simulation with random noise applied to the control signals', 'run_mjcpu_with_xfrc': 'run the MuJoCo simulation with external forces applied to objects via PD control', 'run_mjcpu_save_info': 'run the MuJoCo simulation and save simulation state info to an NPZ file'}
```

## File: facebookresearch_spider/spider/viewers/rerun_viewer.py

Prompts

```
['run the MuJoCo direct replay viewer to visualize robot hand trajectories from dataset files', 'run the MuJoCo simulation with retarget, noise, rect, or debug control modes for robot hand replay', 'run the MuJoCo direct replay viewer with video recording enabled to save MP4 output', 'run the MuJoCo simulation with external force applied to objects via PD position control', 'run the MuJoCo direct replay viewer in headless mode without launching the GUI window', 'run a MuJoCo CPU simulation of a robot hand grasping task with trajectory replay', 'run the MuJoCo viewer and save the simulation as an MP4 video recording', 'run the MuJoCo simulation with random noise applied to the control signals', 'run the MuJoCo simulation with external forces applied to objects via PD control', 'run the MuJoCo simulation and save simulation state info to an NPZ file', 'run the MuJoCo XML Rerun viewer CLI to visualize a scene XML and trajectory NPZ file', 'build a Rerun scene graph from a MuJoCo MJCF XML file and log static geometry', "export a MuJoCo scene's static geometry and local transforms to an NPZ file for offline use", 'play a MuJoCo trajectory from an NPZ file by logging per-body world transforms to Rerun', 'load a pre-baked scene NPZ file and log its geometry to a Rerun visualization session', 'initialize a Viser server for MuJoCo scene visualization with a custom app name', 'build and log a MuJoCo scene from an XML file into the Viser viewer', 'build and log a Viser scene directly from a MuJoCo MjSpec and compiled model', 'log a MuJoCo simulation frame to Viser with body positions and optional reference data', 'log optimization traces with optional reference traces and cost data to the Viser viewer']
```

Usage

```
{'run_mujoco_rerun_viewer': 'run the MuJoCo XML Rerun viewer CLI to visualize a scene XML and trajectory NPZ file', 'build_and_log_scene': 'build a Rerun scene graph from a MuJoCo MJCF XML file and log static geometry', 'export_scene_to_npz': "export a MuJoCo scene's static geometry and local transforms to an NPZ file for offline use", 'play_trajectory': 'play a MuJoCo trajectory from an NPZ file by logging per-body world transforms to Rerun', 'log_scene_from_npz': 'load a pre-baked scene NPZ file and log its geometry to a Rerun visualization session'}
```

## File: facebookresearch_spider/spider/viewers/viser_viewer.py

Prompts

```
['run the MuJoCo direct replay viewer to visualize robot hand trajectories from dataset files', 'run the MuJoCo simulation with retarget, noise, rect, or debug control modes for robot hand replay', 'run the MuJoCo direct replay viewer with video recording enabled to save MP4 output', 'run the MuJoCo simulation with external force applied to objects via PD position control', 'run the MuJoCo direct replay viewer in headless mode without launching the GUI window', 'run a MuJoCo CPU simulation of a robot hand grasping task with trajectory replay', 'run the MuJoCo viewer and save the simulation as an MP4 video recording', 'run the MuJoCo simulation with random noise applied to the control signals', 'run the MuJoCo simulation with external forces applied to objects via PD control', 'run the MuJoCo simulation and save simulation state info to an NPZ file', 'run the MuJoCo XML Rerun viewer CLI to visualize a scene XML and trajectory NPZ file', 'build a Rerun scene graph from a MuJoCo MJCF XML file and log static geometry', "export a MuJoCo scene's static geometry and local transforms to an NPZ file for offline use", 'play a MuJoCo trajectory from an NPZ file by logging per-body world transforms to Rerun', 'load a pre-baked scene NPZ file and log its geometry to a Rerun visualization session', 'initialize a Viser server for MuJoCo scene visualization with a custom app name', 'build and log a MuJoCo scene from an XML file into the Viser viewer', 'build and log a Viser scene directly from a MuJoCo MjSpec and compiled model', 'log a MuJoCo simulation frame to Viser with body positions and optional reference data', 'log optimization traces with optional reference traces and cost data to the Viser viewer']
```

Usage

```
{'init_viser_server': 'initialize a Viser server for MuJoCo scene visualization with a custom app name', 'build_scene_from_xml': 'build and log a MuJoCo scene from an XML file into the Viser viewer', 'build_scene_from_spec': 'build and log a Viser scene directly from a MuJoCo MjSpec and compiled model', 'log_simulation_frame': 'log a MuJoCo simulation frame to Viser with body positions and optional reference data', 'log_traces_from_info': 'log optimization traces with optional reference traces and cost data to the Viser viewer'}
```

