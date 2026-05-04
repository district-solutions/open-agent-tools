# Agent Python Tools

- repo: facebookresearch/eai-vc
- repo_uri: https://github.com/facebookresearch/eai-vc

## File: facebookresearch_eai-vc/third_party/mujoco-py/examples/mjvive.py

Prompts

```
['init a MuJoCo simulation with GLFW window and side-by-side stereo rendering for VR display', 'init OpenVR tracking space and get recommended render target size before MuJoCo setup', 'init OpenVR camera frustums and OpenGL textures after MuJoCo rendering context is ready', 'update VR HMD poses and controller states to sync camera position with head tracking', 'render the MuJoCo scene to both the GLFW window and OpenVR HMD texture buffers', 'load a MuJoCo XML model from a file path using load_model_from_path', 'create an MjSim simulator with a custom render_callback function for per-frame rendering', 'create an MjViewer instance from an MjSim to render the simulation loop', 'use TextureModder to randomize geometry textures in a MuJoCo simulation each render frame', 'run a render loop with viewer.render() and break after a frame count when TESTING is set', 'run a MuJoCo simulation that modifies joint qpos values during execution', 'load a MuJoCo model from an XML string using load_model_from_xml', 'create an MjSim simulation instance from a loaded MuJoCo model', 'get and set the simulation state including qpos via sim.get_state and sim.set_state', 'get the qpos array index for a named joint using sim.model.get_joint_qpos_addr']
```

Usage

```
{'init_mujoco_vr_simulation': 'init a MuJoCo simulation with GLFW window and side-by-side stereo rendering for VR display', 'init_openvr_pre_mujoco': 'init OpenVR tracking space and get recommended render target size before MuJoCo setup', 'init_openvr_post_mujoco': 'init OpenVR camera frustums and OpenGL textures after MuJoCo rendering context is ready', 'update_vr_poses': 'update VR HMD poses and controller states to sync camera position with head tracking', 'render_vr_frame': 'render the MuJoCo scene to both the GLFW window and OpenVR HMD texture buffers'}
```

## File: facebookresearch_eai-vc/third_party/mujoco-py/examples/render_callback.py

Prompts

```
['init a MuJoCo simulation with GLFW window and side-by-side stereo rendering for VR display', 'init OpenVR tracking space and get recommended render target size before MuJoCo setup', 'init OpenVR camera frustums and OpenGL textures after MuJoCo rendering context is ready', 'update VR HMD poses and controller states to sync camera position with head tracking', 'render the MuJoCo scene to both the GLFW window and OpenVR HMD texture buffers', 'load a MuJoCo XML model from a file path using load_model_from_path', 'create an MjSim simulator with a custom render_callback function for per-frame rendering', 'create an MjViewer instance from an MjSim to render the simulation loop', 'use TextureModder to randomize geometry textures in a MuJoCo simulation each render frame', 'run a render loop with viewer.render() and break after a frame count when TESTING is set', 'run a MuJoCo simulation that modifies joint qpos values during execution', 'load a MuJoCo model from an XML string using load_model_from_xml', 'create an MjSim simulation instance from a loaded MuJoCo model', 'get and set the simulation state including qpos via sim.get_state and sim.set_state', 'get the qpos array index for a named joint using sim.model.get_joint_qpos_addr']
```

Usage

```
{'load_model_from_path': 'load a MuJoCo XML model from a file path using load_model_from_path', 'create_MjSim_with_render_callback': 'create an MjSim simulator with a custom render_callback function for per-frame rendering', 'create_MjViewer': 'create an MjViewer instance from an MjSim to render the simulation loop', 'use_TextureModder': 'use TextureModder to randomize geometry textures in a MuJoCo simulation each render frame', 'run_render_loop': 'run a render loop with viewer.render() and break after a frame count when TESTING is set'}
```

## File: facebookresearch_eai-vc/third_party/mujoco-py/examples/setting_state.py

Prompts

```
['init a MuJoCo simulation with GLFW window and side-by-side stereo rendering for VR display', 'init OpenVR tracking space and get recommended render target size before MuJoCo setup', 'init OpenVR camera frustums and OpenGL textures after MuJoCo rendering context is ready', 'update VR HMD poses and controller states to sync camera position with head tracking', 'render the MuJoCo scene to both the GLFW window and OpenVR HMD texture buffers', 'load a MuJoCo XML model from a file path using load_model_from_path', 'create an MjSim simulator with a custom render_callback function for per-frame rendering', 'create an MjViewer instance from an MjSim to render the simulation loop', 'use TextureModder to randomize geometry textures in a MuJoCo simulation each render frame', 'run a render loop with viewer.render() and break after a frame count when TESTING is set', 'run a MuJoCo simulation that modifies joint qpos values during execution', 'load a MuJoCo model from an XML string using load_model_from_xml', 'create an MjSim simulation instance from a loaded MuJoCo model', 'get and set the simulation state including qpos via sim.get_state and sim.set_state', 'get the qpos array index for a named joint using sim.model.get_joint_qpos_addr']
```

Usage

```
{'run_simulation_modify_qpos': 'run a MuJoCo simulation that modifies joint qpos values during execution', 'load_model_from_xml': 'load a MuJoCo model from an XML string using load_model_from_xml', 'create_mjsim': 'create an MjSim simulation instance from a loaded MuJoCo model', 'get_set_sim_state': 'get and set the simulation state including qpos via sim.get_state and sim.set_state', 'get_joint_qpos_addr': 'get the qpos array index for a named joint using sim.model.get_joint_qpos_addr'}
```

