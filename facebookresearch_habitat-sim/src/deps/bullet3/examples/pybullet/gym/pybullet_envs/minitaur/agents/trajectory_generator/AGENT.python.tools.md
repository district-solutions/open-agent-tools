# Agent Python Tools

- repo: facebookresearch/habitat-sim
- repo_uri: https://github.com/facebookresearch/habitat-sim

## File: facebookresearch_habitat-sim/src/deps/bullet3/examples/pybullet/gym/pybullet_envs/minitaur/agents/trajectory_generator/controller_simple.py

Prompts

```
['create a SimpleLegController instance with an initial phase for quadruped leg motion control', 'get the swing and extend parameters for a leg based on the current phase and intensity', 'reset the SimpleLegController phase back to its initial value for a fresh gait cycle', 'adjust the center extension of the leg controller toward a target walking height value', 'adjust the intensity of the leg controller toward a target motion scaling coefficient', 'step the in-place trajectory generator forward by advancing leg phases and computing extensions', 'reset the quadruped leg phases to their initial staggered starting positions', 'compute leg extension values using an asymmetric sine wave based on phase and parameters', 'review the step function to understand how it advances phases and computes leg extensions for all four legs', 'summarize the trajectory generator parameters including stance_lift_cutoff, amplitude_stance, amplitude_lift, and center_extension', 'create a TgSimple trajectory generator instance with custom leg phase offsets and coupling mode', 'get 8 motor actions for quadruped walking by calling get_actions with delta time and tg_params', 'get the lower and upper bounds for trajectory generator parameters like intensity and walk height', 'calculate a progressed phase for the circular asymmetrical integrator given a delta period and swing stance ratio', 'get the internal phase state of all integrators as sine and cosine values for the trajectory generator']
```

Usage

```
{'create_SimpleLegController': 'create a SimpleLegController instance with an initial phase for quadruped leg motion control', 'get_swing_extend': 'get the swing and extend parameters for a leg based on the current phase and intensity', 'reset_SimpleLegController': 'reset the SimpleLegController phase back to its initial value for a fresh gait cycle', 'adjust_center_extension': 'adjust the center extension of the leg controller toward a target walking height value', 'adjust_intensity': 'adjust the intensity of the leg controller toward a target motion scaling coefficient'}
```

## File: facebookresearch_habitat-sim/src/deps/bullet3/examples/pybullet/gym/pybullet_envs/minitaur/agents/trajectory_generator/tg_inplace.py

Prompts

```
['create a SimpleLegController instance with an initial phase for quadruped leg motion control', 'get the swing and extend parameters for a leg based on the current phase and intensity', 'reset the SimpleLegController phase back to its initial value for a fresh gait cycle', 'adjust the center extension of the leg controller toward a target walking height value', 'adjust the intensity of the leg controller toward a target motion scaling coefficient', 'step the in-place trajectory generator forward by advancing leg phases and computing extensions', 'reset the quadruped leg phases to their initial staggered starting positions', 'compute leg extension values using an asymmetric sine wave based on phase and parameters', 'review the step function to understand how it advances phases and computes leg extensions for all four legs', 'summarize the trajectory generator parameters including stance_lift_cutoff, amplitude_stance, amplitude_lift, and center_extension', 'create a TgSimple trajectory generator instance with custom leg phase offsets and coupling mode', 'get 8 motor actions for quadruped walking by calling get_actions with delta time and tg_params', 'get the lower and upper bounds for trajectory generator parameters like intensity and walk height', 'calculate a progressed phase for the circular asymmetrical integrator given a delta period and swing stance ratio', 'get the internal phase state of all integrators as sine and cosine values for the trajectory generator']
```

Usage

```
{'step_trajectory_generator': 'step the in-place trajectory generator forward by advancing leg phases and computing extensions', 'reset_leg_phases': 'reset the quadruped leg phases to their initial staggered starting positions', 'compute_asymmetric_sine_actions': 'compute leg extension values using an asymmetric sine wave based on phase and parameters', 'review_step_function': 'review the step function to understand how it advances phases and computes leg extensions for all four legs', 'summarize_tg_params': 'summarize the trajectory generator parameters including stance_lift_cutoff, amplitude_stance, amplitude_lift, and center_extension'}
```

## File: facebookresearch_habitat-sim/src/deps/bullet3/examples/pybullet/gym/pybullet_envs/minitaur/agents/trajectory_generator/tg_simple.py

Prompts

```
['create a SimpleLegController instance with an initial phase for quadruped leg motion control', 'get the swing and extend parameters for a leg based on the current phase and intensity', 'reset the SimpleLegController phase back to its initial value for a fresh gait cycle', 'adjust the center extension of the leg controller toward a target walking height value', 'adjust the intensity of the leg controller toward a target motion scaling coefficient', 'step the in-place trajectory generator forward by advancing leg phases and computing extensions', 'reset the quadruped leg phases to their initial staggered starting positions', 'compute leg extension values using an asymmetric sine wave based on phase and parameters', 'review the step function to understand how it advances phases and computes leg extensions for all four legs', 'summarize the trajectory generator parameters including stance_lift_cutoff, amplitude_stance, amplitude_lift, and center_extension', 'create a TgSimple trajectory generator instance with custom leg phase offsets and coupling mode', 'get 8 motor actions for quadruped walking by calling get_actions with delta time and tg_params', 'get the lower and upper bounds for trajectory generator parameters like intensity and walk height', 'calculate a progressed phase for the circular asymmetrical integrator given a delta period and swing stance ratio', 'get the internal phase state of all integrators as sine and cosine values for the trajectory generator']
```

Usage

```
{'create_TgSimple': 'create a TgSimple trajectory generator instance with custom leg phase offsets and coupling mode', 'get_actions_TgSimple': 'get 8 motor actions for quadruped walking by calling get_actions with delta time and tg_params', 'get_parameter_bounds_TgSimple': 'get the lower and upper bounds for trajectory generator parameters like intensity and walk height', 'calculate_progressed_phase_CircularAsymmetricalIntegratorUnit': 'calculate a progressed phase for the circular asymmetrical integrator given a delta period and swing stance ratio', 'get_state_TgSimple': 'get the internal phase state of all integrators as sine and cosine values for the trajectory generator'}
```

