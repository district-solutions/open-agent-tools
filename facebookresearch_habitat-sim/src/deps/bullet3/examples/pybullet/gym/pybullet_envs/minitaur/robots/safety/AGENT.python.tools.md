# Agent Python Tools

- repo: facebookresearch/habitat-sim
- repo_uri: https://github.com/facebookresearch/habitat-sim

## File: facebookresearch_habitat-sim/src/deps/bullet3/examples/pybullet/gym/pybullet_envs/minitaur/robots/safety/motor_action_validator.py

Prompts

```
['create a MotorActionValidator instance with motor ID and safety bounds for position, velocity, torque, and PD gains', 'review the on_action method that validates motor actions against position, velocity, torque, and timestamp bounds', 'test the on_state method to ensure it correctly stores the latest motor state for validation', 'refactor the MotorActionValidator to support additional safety bounds for custom motor control parameters', 'summarize the MotorActionValidator class that monitors motor commands and detects unsafe behaviors like bang-bang control', 'create a MotorStateValidator instance with motor ID and bound parameters for safety validation', 'validate a new motor state by calling on_state with a MotorState object', 'review the MotorStateValidator class and its position velocity torque and power bound checks', 'test the on_state method to verify it raises OutOfBoundError when motor readings exceed bounds', 'refactor the MotorStateValidator to use a different moving window filter for average velocity and power', 'create a SafetyChecker instance with a robot to validate motor states and actions', 'check the robot state by calling SafetyChecker.check_state to validate all motor states', 'check motor actions by calling SafetyChecker.check_motor_action with action and control mode', 'review the SafetyChecker constructor to understand motor state and action validator initialization', 'summarize the SafetyChecker class which validates robot motor states and motor actions for safety', "assert a float value is within a Bound object's lower and upper inclusive limits", 'convert a position control action sequence into MotorAction instances for each robot motor', 'convert a torque or PWM control action sequence into MotorAction instances for each robot motor', 'convert a hybrid control action sequence with position, velocity, and torque into MotorAction instances', "compute a numerically stable O(1) moving window average using Neumaier's summation algorithm"]
```

Usage

```
{'create_MotorActionValidator': 'create a MotorActionValidator instance with motor ID and safety bounds for position, velocity, torque, and PD gains', 'review_MotorActionValidator_on_action': 'review the on_action method that validates motor actions against position, velocity, torque, and timestamp bounds', 'test_MotorActionValidator_on_state': 'test the on_state method to ensure it correctly stores the latest motor state for validation', 'refactor_MotorActionValidator_bounds': 'refactor the MotorActionValidator to support additional safety bounds for custom motor control parameters', 'summarize_MotorActionValidator': 'summarize the MotorActionValidator class that monitors motor commands and detects unsafe behaviors like bang-bang control'}
```

## File: facebookresearch_habitat-sim/src/deps/bullet3/examples/pybullet/gym/pybullet_envs/minitaur/robots/safety/motor_state_validator.py

Prompts

```
['create a MotorActionValidator instance with motor ID and safety bounds for position, velocity, torque, and PD gains', 'review the on_action method that validates motor actions against position, velocity, torque, and timestamp bounds', 'test the on_state method to ensure it correctly stores the latest motor state for validation', 'refactor the MotorActionValidator to support additional safety bounds for custom motor control parameters', 'summarize the MotorActionValidator class that monitors motor commands and detects unsafe behaviors like bang-bang control', 'create a MotorStateValidator instance with motor ID and bound parameters for safety validation', 'validate a new motor state by calling on_state with a MotorState object', 'review the MotorStateValidator class and its position velocity torque and power bound checks', 'test the on_state method to verify it raises OutOfBoundError when motor readings exceed bounds', 'refactor the MotorStateValidator to use a different moving window filter for average velocity and power', 'create a SafetyChecker instance with a robot to validate motor states and actions', 'check the robot state by calling SafetyChecker.check_state to validate all motor states', 'check motor actions by calling SafetyChecker.check_motor_action with action and control mode', 'review the SafetyChecker constructor to understand motor state and action validator initialization', 'summarize the SafetyChecker class which validates robot motor states and motor actions for safety', "assert a float value is within a Bound object's lower and upper inclusive limits", 'convert a position control action sequence into MotorAction instances for each robot motor', 'convert a torque or PWM control action sequence into MotorAction instances for each robot motor', 'convert a hybrid control action sequence with position, velocity, and torque into MotorAction instances', "compute a numerically stable O(1) moving window average using Neumaier's summation algorithm"]
```

Usage

```
{'create_MotorStateValidator': 'create a MotorStateValidator instance with motor ID and bound parameters for safety validation', 'validate_on_state': 'validate a new motor state by calling on_state with a MotorState object', 'review_MotorStateValidator_bounds': 'review the MotorStateValidator class and its position velocity torque and power bound checks', 'test_on_state_validation': 'test the on_state method to verify it raises OutOfBoundError when motor readings exceed bounds', 'refactor_MotorStateValidator_filter': 'refactor the MotorStateValidator to use a different moving window filter for average velocity and power'}
```

## File: facebookresearch_habitat-sim/src/deps/bullet3/examples/pybullet/gym/pybullet_envs/minitaur/robots/safety/safety_checker.py

Prompts

```
['create a MotorActionValidator instance with motor ID and safety bounds for position, velocity, torque, and PD gains', 'review the on_action method that validates motor actions against position, velocity, torque, and timestamp bounds', 'test the on_state method to ensure it correctly stores the latest motor state for validation', 'refactor the MotorActionValidator to support additional safety bounds for custom motor control parameters', 'summarize the MotorActionValidator class that monitors motor commands and detects unsafe behaviors like bang-bang control', 'create a MotorStateValidator instance with motor ID and bound parameters for safety validation', 'validate a new motor state by calling on_state with a MotorState object', 'review the MotorStateValidator class and its position velocity torque and power bound checks', 'test the on_state method to verify it raises OutOfBoundError when motor readings exceed bounds', 'refactor the MotorStateValidator to use a different moving window filter for average velocity and power', 'create a SafetyChecker instance with a robot to validate motor states and actions', 'check the robot state by calling SafetyChecker.check_state to validate all motor states', 'check motor actions by calling SafetyChecker.check_motor_action with action and control mode', 'review the SafetyChecker constructor to understand motor state and action validator initialization', 'summarize the SafetyChecker class which validates robot motor states and motor actions for safety', "assert a float value is within a Bound object's lower and upper inclusive limits", 'convert a position control action sequence into MotorAction instances for each robot motor', 'convert a torque or PWM control action sequence into MotorAction instances for each robot motor', 'convert a hybrid control action sequence with position, velocity, and torque into MotorAction instances', "compute a numerically stable O(1) moving window average using Neumaier's summation algorithm"]
```

Usage

```
{'create_SafetyChecker': 'create a SafetyChecker instance with a robot to validate motor states and actions', 'check_state_SafetyChecker': 'check the robot state by calling SafetyChecker.check_state to validate all motor states', 'check_motor_action_SafetyChecker': 'check motor actions by calling SafetyChecker.check_motor_action with action and control mode', 'review_SafetyChecker_init': 'review the SafetyChecker constructor to understand motor state and action validator initialization', 'summarize_SafetyChecker': 'summarize the SafetyChecker class which validates robot motor states and motor actions for safety'}
```

## File: facebookresearch_habitat-sim/src/deps/bullet3/examples/pybullet/gym/pybullet_envs/minitaur/robots/safety/utilities.py

Prompts

```
['create a MotorActionValidator instance with motor ID and safety bounds for position, velocity, torque, and PD gains', 'review the on_action method that validates motor actions against position, velocity, torque, and timestamp bounds', 'test the on_state method to ensure it correctly stores the latest motor state for validation', 'refactor the MotorActionValidator to support additional safety bounds for custom motor control parameters', 'summarize the MotorActionValidator class that monitors motor commands and detects unsafe behaviors like bang-bang control', 'create a MotorStateValidator instance with motor ID and bound parameters for safety validation', 'validate a new motor state by calling on_state with a MotorState object', 'review the MotorStateValidator class and its position velocity torque and power bound checks', 'test the on_state method to verify it raises OutOfBoundError when motor readings exceed bounds', 'refactor the MotorStateValidator to use a different moving window filter for average velocity and power', 'create a SafetyChecker instance with a robot to validate motor states and actions', 'check the robot state by calling SafetyChecker.check_state to validate all motor states', 'check motor actions by calling SafetyChecker.check_motor_action with action and control mode', 'review the SafetyChecker constructor to understand motor state and action validator initialization', 'summarize the SafetyChecker class which validates robot motor states and motor actions for safety', "assert a float value is within a Bound object's lower and upper inclusive limits", 'convert a position control action sequence into MotorAction instances for each robot motor', 'convert a torque or PWM control action sequence into MotorAction instances for each robot motor', 'convert a hybrid control action sequence with position, velocity, and torque into MotorAction instances', "compute a numerically stable O(1) moving window average using Neumaier's summation algorithm"]
```

Usage

```
{'assert_in_bound': "assert a float value is within a Bound object's lower and upper inclusive limits", 'convert_to_motor_action_position': 'convert a position control action sequence into MotorAction instances for each robot motor', 'convert_to_motor_action_torque': 'convert a torque or PWM control action sequence into MotorAction instances for each robot motor', 'convert_to_motor_action_hybrid': 'convert a hybrid control action sequence with position, velocity, and torque into MotorAction instances', 'MovingWindowFilter_calculate_average': "compute a numerically stable O(1) moving window average using Neumaier's summation algorithm"}
```

