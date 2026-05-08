# Agent Python Tools

- repo: facebookresearch/home-robot
- repo_uri: https://github.com/facebookresearch/home-robot

## File: facebookresearch_home-robot/tests/home_robot/control/test_velocity_controllers.py

Prompts

```
['test the GotoVelocityController by verifying controller outputs match cached reference data', 'run the pytest test that validates GotoVelocityController input-output pairs against a cached dataset', 'create a pytest fixture that instantiates a GotoVelocityController for test use', 'generate and cache a JSON dataset of controller input-output pairs for regression testing', 'review the pytest test file that validates GotoVelocityController behavior using cached datasets', 'generate random controller input with yaw, location, goal flag, and goal coordinates', 'get controller output by setting yaw tracking, pose feedback, and goal then computing control', 'test the generate_controller_input function returns a tuple of yaw, location, goal flag, and goal', 'test the get_controller_output function with a mock controller and random input', 'refactor the get_controller_output function to accept keyword arguments instead of a tuple input']
```

Usage

```
{'test_GotoVelocityController_input_output': 'test the GotoVelocityController by verifying controller outputs match cached reference data', 'run_test_controller_input_output': 'run the pytest test that validates GotoVelocityController input-output pairs against a cached dataset', 'create_controller_fixture': 'create a pytest fixture that instantiates a GotoVelocityController for test use', 'generate_controller_dataset': 'generate and cache a JSON dataset of controller input-output pairs for regression testing', 'review_test_velocity_controllers': 'review the pytest test file that validates GotoVelocityController behavior using cached datasets'}
```

## File: facebookresearch_home-robot/tests/home_robot/control/utils.py

Prompts

```
['test the GotoVelocityController by verifying controller outputs match cached reference data', 'run the pytest test that validates GotoVelocityController input-output pairs against a cached dataset', 'create a pytest fixture that instantiates a GotoVelocityController for test use', 'generate and cache a JSON dataset of controller input-output pairs for regression testing', 'review the pytest test file that validates GotoVelocityController behavior using cached datasets', 'generate random controller input with yaw, location, goal flag, and goal coordinates', 'get controller output by setting yaw tracking, pose feedback, and goal then computing control', 'test the generate_controller_input function returns a tuple of yaw, location, goal flag, and goal', 'test the get_controller_output function with a mock controller and random input', 'refactor the get_controller_output function to accept keyword arguments instead of a tuple input']
```

Usage

```
{'generate_controller_input': 'generate random controller input with yaw, location, goal flag, and goal coordinates', 'get_controller_output': 'get controller output by setting yaw tracking, pose feedback, and goal then computing control', 'test_generate_controller_input': 'test the generate_controller_input function returns a tuple of yaw, location, goal flag, and goal', 'test_get_controller_output': 'test the get_controller_output function with a mock controller and random input', 'refactor_get_controller_output': 'refactor the get_controller_output function to accept keyword arguments instead of a tuple input'}
```

