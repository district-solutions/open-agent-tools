# Agent Python Tools

- repo: facebookresearch/fairo
- repo_uri: https://github.com/facebookresearch/fairo

## File: facebookresearch_fairo/polymetis/examples/custom_simulation/double_integrator_sim.py

Prompts

```
['create a DoubleIntegratorSim instance with specified dof, hz, and mass parameters', 'run a double integrator simulation using SimInterface with arm control and step callbacks', 'get the current RobotState protobuf with joint positions, velocities, and torque data', 'apply a TorqueCommand to update the force buffer for the next simulation step', 'step the simulation forward by updating position and velocity using Euler integration']
```

Usage

```
{'create_double_integrator_sim': 'create a DoubleIntegratorSim instance with specified dof, hz, and mass parameters', 'run_double_integrator_simulation': 'run a double integrator simulation using SimInterface with arm control and step callbacks', 'get_robot_state': 'get the current RobotState protobuf with joint positions, velocities, and torque data', 'apply_torque_control': 'apply a TorqueCommand to update the force buffer for the next simulation step', 'step_simulation': 'step the simulation forward by updating position and velocity using Euler integration'}
```

