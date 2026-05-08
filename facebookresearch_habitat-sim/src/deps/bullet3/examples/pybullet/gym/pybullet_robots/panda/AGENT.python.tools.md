# Agent Python Tools

- repo: facebookresearch/habitat-sim
- repo_uri: https://github.com/facebookresearch/habitat-sim

## File: facebookresearch_habitat-sim/src/deps/bullet3/examples/pybullet/gym/pybullet_robots/panda/batchsim3.py

Prompts

```
['run a multi-process PyBullet simulation with Panda robots using ExploreWorker and Pipe-based IPC', 'create an ExploreWorker process that receives RESET, EXPLORE, and CLOSE messages via a multiprocessing Pipe', 'reset the PyBullet physics environment with gravity, solver parameters, and PandaSim instances per worker', 'step the simulation for a fixed number of timesteps across all PandaSim instances in a worker', 'merge per-process batchsim JSON trace files into a single Chrome trace format output file', 'run multiple parallel Panda robot grasp simulations using PyBullet multiprocessing workers', 'create an ExploreWorker process that receives RESET, EXPLORE, and CLOSE messages via a Pipe', 'build a grid of PandaSimAuto instances with configurable spatial offsets per worker process', 'test the parent-child Pipe communication pattern for sending RESET and EXPLORE commands to workers', 'merge per-process batchsim JSON trace files into a single Chrome trace format output file', 'create a PandaSim instance with a bullet client and offset to load the panda robot and scene objects', 'step the PandaSim simulation to compute inverse kinematics and apply position control to panda joints', 'reset the PandaSim simulation state by calling the reset method on the PandaSim instance', 'review the PandaSim __init__ method that loads URDF models and configures joint states for the panda robot', 'refactor the PandaSim step method to support custom end effector trajectories instead of hardcoded sinusoidal motion', 'create a PandaSim instance that loads a Franka Panda robot and scene objects into the pybullet client', 'run the PandaSim step method to compute inverse kinematics and control joint motors for the current state', 'test the PandaSim update_state method to verify keyboard-driven state transitions between grasp modes', 'create a PandaSimAuto instance that auto-plays a predefined sequence of approach, grasp, lift, and release states', 'review the PandaSimAuto update_state method to understand time-based state progression through the grasp sequence']
```

Usage

```
{'run_batch_panda_simulation': 'run a multi-process PyBullet simulation with Panda robots using ExploreWorker and Pipe-based IPC', 'create_explore_worker_process': 'create an ExploreWorker process that receives RESET, EXPLORE, and CLOSE messages via a multiprocessing Pipe', 'reset_simulation_environment': 'reset the PyBullet physics environment with gravity, solver parameters, and PandaSim instances per worker', 'step_simulation_exploration': 'step the simulation for a fixed number of timesteps across all PandaSim instances in a worker', 'merge_trace_json_files': 'merge per-process batchsim JSON trace files into a single Chrome trace format output file'}
```

## File: facebookresearch_habitat-sim/src/deps/bullet3/examples/pybullet/gym/pybullet_robots/panda/batchsim3_grasp.py

Prompts

```
['run a multi-process PyBullet simulation with Panda robots using ExploreWorker and Pipe-based IPC', 'create an ExploreWorker process that receives RESET, EXPLORE, and CLOSE messages via a multiprocessing Pipe', 'reset the PyBullet physics environment with gravity, solver parameters, and PandaSim instances per worker', 'step the simulation for a fixed number of timesteps across all PandaSim instances in a worker', 'merge per-process batchsim JSON trace files into a single Chrome trace format output file', 'run multiple parallel Panda robot grasp simulations using PyBullet multiprocessing workers', 'create an ExploreWorker process that receives RESET, EXPLORE, and CLOSE messages via a Pipe', 'build a grid of PandaSimAuto instances with configurable spatial offsets per worker process', 'test the parent-child Pipe communication pattern for sending RESET and EXPLORE commands to workers', 'merge per-process batchsim JSON trace files into a single Chrome trace format output file', 'create a PandaSim instance with a bullet client and offset to load the panda robot and scene objects', 'step the PandaSim simulation to compute inverse kinematics and apply position control to panda joints', 'reset the PandaSim simulation state by calling the reset method on the PandaSim instance', 'review the PandaSim __init__ method that loads URDF models and configures joint states for the panda robot', 'refactor the PandaSim step method to support custom end effector trajectories instead of hardcoded sinusoidal motion', 'create a PandaSim instance that loads a Franka Panda robot and scene objects into the pybullet client', 'run the PandaSim step method to compute inverse kinematics and control joint motors for the current state', 'test the PandaSim update_state method to verify keyboard-driven state transitions between grasp modes', 'create a PandaSimAuto instance that auto-plays a predefined sequence of approach, grasp, lift, and release states', 'review the PandaSimAuto update_state method to understand time-based state progression through the grasp sequence']
```

Usage

```
{'run_batch_panda_simulations': 'run multiple parallel Panda robot grasp simulations using PyBullet multiprocessing workers', 'create_exploreworker_process': 'create an ExploreWorker process that receives RESET, EXPLORE, and CLOSE messages via a Pipe', 'build_pandasimauto_grid': 'build a grid of PandaSimAuto instances with configurable spatial offsets per worker process', 'test_multiprocessing_pipes': 'test the parent-child Pipe communication pattern for sending RESET and EXPLORE commands to workers', 'merge_chrome_trace_json': 'merge per-process batchsim JSON trace files into a single Chrome trace format output file'}
```

## File: facebookresearch_habitat-sim/src/deps/bullet3/examples/pybullet/gym/pybullet_robots/panda/panda_sim.py

Prompts

```
['run a multi-process PyBullet simulation with Panda robots using ExploreWorker and Pipe-based IPC', 'create an ExploreWorker process that receives RESET, EXPLORE, and CLOSE messages via a multiprocessing Pipe', 'reset the PyBullet physics environment with gravity, solver parameters, and PandaSim instances per worker', 'step the simulation for a fixed number of timesteps across all PandaSim instances in a worker', 'merge per-process batchsim JSON trace files into a single Chrome trace format output file', 'run multiple parallel Panda robot grasp simulations using PyBullet multiprocessing workers', 'create an ExploreWorker process that receives RESET, EXPLORE, and CLOSE messages via a Pipe', 'build a grid of PandaSimAuto instances with configurable spatial offsets per worker process', 'test the parent-child Pipe communication pattern for sending RESET and EXPLORE commands to workers', 'merge per-process batchsim JSON trace files into a single Chrome trace format output file', 'create a PandaSim instance with a bullet client and offset to load the panda robot and scene objects', 'step the PandaSim simulation to compute inverse kinematics and apply position control to panda joints', 'reset the PandaSim simulation state by calling the reset method on the PandaSim instance', 'review the PandaSim __init__ method that loads URDF models and configures joint states for the panda robot', 'refactor the PandaSim step method to support custom end effector trajectories instead of hardcoded sinusoidal motion', 'create a PandaSim instance that loads a Franka Panda robot and scene objects into the pybullet client', 'run the PandaSim step method to compute inverse kinematics and control joint motors for the current state', 'test the PandaSim update_state method to verify keyboard-driven state transitions between grasp modes', 'create a PandaSimAuto instance that auto-plays a predefined sequence of approach, grasp, lift, and release states', 'review the PandaSimAuto update_state method to understand time-based state progression through the grasp sequence']
```

Usage

```
{'create_panda_sim_instance': 'create a PandaSim instance with a bullet client and offset to load the panda robot and scene objects', 'step_panda_sim': 'step the PandaSim simulation to compute inverse kinematics and apply position control to panda joints', 'reset_panda_sim': 'reset the PandaSim simulation state by calling the reset method on the PandaSim instance', 'review_panda_sim_init': 'review the PandaSim __init__ method that loads URDF models and configures joint states for the panda robot', 'refactor_panda_sim_step': 'refactor the PandaSim step method to support custom end effector trajectories instead of hardcoded sinusoidal motion'}
```

## File: facebookresearch_habitat-sim/src/deps/bullet3/examples/pybullet/gym/pybullet_robots/panda/panda_sim_grasp.py

Prompts

```
['run a multi-process PyBullet simulation with Panda robots using ExploreWorker and Pipe-based IPC', 'create an ExploreWorker process that receives RESET, EXPLORE, and CLOSE messages via a multiprocessing Pipe', 'reset the PyBullet physics environment with gravity, solver parameters, and PandaSim instances per worker', 'step the simulation for a fixed number of timesteps across all PandaSim instances in a worker', 'merge per-process batchsim JSON trace files into a single Chrome trace format output file', 'run multiple parallel Panda robot grasp simulations using PyBullet multiprocessing workers', 'create an ExploreWorker process that receives RESET, EXPLORE, and CLOSE messages via a Pipe', 'build a grid of PandaSimAuto instances with configurable spatial offsets per worker process', 'test the parent-child Pipe communication pattern for sending RESET and EXPLORE commands to workers', 'merge per-process batchsim JSON trace files into a single Chrome trace format output file', 'create a PandaSim instance with a bullet client and offset to load the panda robot and scene objects', 'step the PandaSim simulation to compute inverse kinematics and apply position control to panda joints', 'reset the PandaSim simulation state by calling the reset method on the PandaSim instance', 'review the PandaSim __init__ method that loads URDF models and configures joint states for the panda robot', 'refactor the PandaSim step method to support custom end effector trajectories instead of hardcoded sinusoidal motion', 'create a PandaSim instance that loads a Franka Panda robot and scene objects into the pybullet client', 'run the PandaSim step method to compute inverse kinematics and control joint motors for the current state', 'test the PandaSim update_state method to verify keyboard-driven state transitions between grasp modes', 'create a PandaSimAuto instance that auto-plays a predefined sequence of approach, grasp, lift, and release states', 'review the PandaSimAuto update_state method to understand time-based state progression through the grasp sequence']
```

Usage

```
{'create_PandaSim': 'create a PandaSim instance that loads a Franka Panda robot and scene objects into the pybullet client', 'run_PandaSim_step': 'run the PandaSim step method to compute inverse kinematics and control joint motors for the current state', 'test_PandaSim_update_state': 'test the PandaSim update_state method to verify keyboard-driven state transitions between grasp modes', 'create_PandaSimAuto': 'create a PandaSimAuto instance that auto-plays a predefined sequence of approach, grasp, lift, and release states', 'review_PandaSimAuto_update_state': 'review the PandaSimAuto update_state method to understand time-based state progression through the grasp sequence'}
```

