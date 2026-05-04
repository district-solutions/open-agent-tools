# Agent Python Tools

- repo: google-deepmind/ai-safety-gridworlds
- repo_uri: https://github.com/google-deepmind/ai-safety-gridworlds

## File: google-deepmind_ai-safety-gridworlds/ai_safety_gridworlds/environments/shared/rl/array_spec.py

Prompts

```
['create an ArraySpec to describe a numpy array shape and dtype before the array exists', 'validate a numpy array conforms to an ArraySpec shape and dtype requirements', 'generate a test numpy array value that conforms to an ArraySpec specification', 'create a BoundedArraySpec with minimum and maximum bounds for numpy array element values', 'validate a numpy array conforms to a BoundedArraySpec including shape, dtype, and value bounds', 'create a Python class that subclasses Base and implements reset, step, observation_spec, and action_spec methods', 'build a TimeStep with StepType.FIRST using the restart helper function with an observation', 'create a TimeStep with StepType.MID using the transition helper function with reward, observation, and discount', 'implement an RL environment that uses the Base class context manager protocol for resource cleanup', 'check if a TimeStep is first, mid, or last using the first, mid, and last methods', 'create a pycolab Environment adapter wrapping a game factory with discrete actions and an observation distiller', 'reset the pycolab Environment to start a new episode and return the initial timestep', 'step the pycolab Environment forward with an action and return observations reward and discount', 'build a Distiller that repaints observation characters then converts them to numpy arrays for TensorFlow', 'review the pycolab Environment action spec to inspect discrete and continuous action bounds']
```

Usage

```
{'create_ArraySpec': 'create an ArraySpec to describe a numpy array shape and dtype before the array exists', 'validate_ArraySpec': 'validate a numpy array conforms to an ArraySpec shape and dtype requirements', 'generate_ArraySpec_value': 'generate a test numpy array value that conforms to an ArraySpec specification', 'create_BoundedArraySpec': 'create a BoundedArraySpec with minimum and maximum bounds for numpy array element values', 'validate_BoundedArraySpec': 'validate a numpy array conforms to a BoundedArraySpec including shape, dtype, and value bounds'}
```

## File: google-deepmind_ai-safety-gridworlds/ai_safety_gridworlds/environments/shared/rl/array_spec_test.py

Prompts

```
['create an ArraySpec to describe a numpy array shape and dtype before the array exists', 'validate a numpy array conforms to an ArraySpec shape and dtype requirements', 'generate a test numpy array value that conforms to an ArraySpec specification', 'create a BoundedArraySpec with minimum and maximum bounds for numpy array element values', 'validate a numpy array conforms to a BoundedArraySpec including shape, dtype, and value bounds', 'create a Python class that subclasses Base and implements reset, step, observation_spec, and action_spec methods', 'build a TimeStep with StepType.FIRST using the restart helper function with an observation', 'create a TimeStep with StepType.MID using the transition helper function with reward, observation, and discount', 'implement an RL environment that uses the Base class context manager protocol for resource cleanup', 'check if a TimeStep is first, mid, or last using the first, mid, and last methods', 'create a pycolab Environment adapter wrapping a game factory with discrete actions and an observation distiller', 'reset the pycolab Environment to start a new episode and return the initial timestep', 'step the pycolab Environment forward with an action and return observations reward and discount', 'build a Distiller that repaints observation characters then converts them to numpy arrays for TensorFlow', 'review the pycolab Environment action spec to inspect discrete and continuous action bounds']
```

Usage

```
{'create_ArraySpec': 'create an ArraySpec with a given shape and numpy dtype for describing array contracts', 'validate_ArraySpec': 'validate a numpy array against an ArraySpec to check shape and dtype conformance', 'generate_ArraySpec_value': 'generate a zero-filled test numpy array that conforms to an ArraySpec shape and dtype', 'create_BoundedArraySpec': 'create a BoundedArraySpec with shape, dtype, and minimum and maximum value bounds', 'validate_BoundedArraySpec': 'validate a numpy array against a BoundedArraySpec to check shape, dtype, and value bounds'}
```

## File: google-deepmind_ai-safety-gridworlds/ai_safety_gridworlds/environments/shared/rl/environment.py

Prompts

```
['create an ArraySpec to describe a numpy array shape and dtype before the array exists', 'validate a numpy array conforms to an ArraySpec shape and dtype requirements', 'generate a test numpy array value that conforms to an ArraySpec specification', 'create a BoundedArraySpec with minimum and maximum bounds for numpy array element values', 'validate a numpy array conforms to a BoundedArraySpec including shape, dtype, and value bounds', 'create a Python class that subclasses Base and implements reset, step, observation_spec, and action_spec methods', 'build a TimeStep with StepType.FIRST using the restart helper function with an observation', 'create a TimeStep with StepType.MID using the transition helper function with reward, observation, and discount', 'implement an RL environment that uses the Base class context manager protocol for resource cleanup', 'check if a TimeStep is first, mid, or last using the first, mid, and last methods', 'create a pycolab Environment adapter wrapping a game factory with discrete actions and an observation distiller', 'reset the pycolab Environment to start a new episode and return the initial timestep', 'step the pycolab Environment forward with an action and return observations reward and discount', 'build a Distiller that repaints observation characters then converts them to numpy arrays for TensorFlow', 'review the pycolab Environment action spec to inspect discrete and continuous action bounds']
```

Usage

```
{'create_rl_environment_subclass': 'create a Python class that subclasses Base and implements reset, step, observation_spec, and action_spec methods', 'build_timestep_with_restart': 'build a TimeStep with StepType.FIRST using the restart helper function with an observation', 'create_transition_timestep': 'create a TimeStep with StepType.MID using the transition helper function with reward, observation, and discount', 'implement_environment_context_manager': 'implement an RL environment that uses the Base class context manager protocol for resource cleanup', 'check_timestep_step_type': 'check if a TimeStep is first, mid, or last using the first, mid, and last methods'}
```

## File: google-deepmind_ai-safety-gridworlds/ai_safety_gridworlds/environments/shared/rl/pycolab_interface.py

Prompts

```
['create an ArraySpec to describe a numpy array shape and dtype before the array exists', 'validate a numpy array conforms to an ArraySpec shape and dtype requirements', 'generate a test numpy array value that conforms to an ArraySpec specification', 'create a BoundedArraySpec with minimum and maximum bounds for numpy array element values', 'validate a numpy array conforms to a BoundedArraySpec including shape, dtype, and value bounds', 'create a Python class that subclasses Base and implements reset, step, observation_spec, and action_spec methods', 'build a TimeStep with StepType.FIRST using the restart helper function with an observation', 'create a TimeStep with StepType.MID using the transition helper function with reward, observation, and discount', 'implement an RL environment that uses the Base class context manager protocol for resource cleanup', 'check if a TimeStep is first, mid, or last using the first, mid, and last methods', 'create a pycolab Environment adapter wrapping a game factory with discrete actions and an observation distiller', 'reset the pycolab Environment to start a new episode and return the initial timestep', 'step the pycolab Environment forward with an action and return observations reward and discount', 'build a Distiller that repaints observation characters then converts them to numpy arrays for TensorFlow', 'review the pycolab Environment action spec to inspect discrete and continuous action bounds']
```

Usage

```
{'create_environment_adapter': 'create a pycolab Environment adapter wrapping a game factory with discrete actions and an observation distiller', 'reset_environment_episode': 'reset the pycolab Environment to start a new episode and return the initial timestep', 'step_environment_action': 'step the pycolab Environment forward with an action and return observations reward and discount', 'build_distiller_pipeline': 'build a Distiller that repaints observation characters then converts them to numpy arrays for TensorFlow', 'review_environment_action_spec': 'review the pycolab Environment action spec to inspect discrete and continuous action bounds'}
```

