# Agent Python Tools

- repo: facebookresearch/deepbisim4control
- repo_uri: https://github.com/facebookresearch/deep_bisim4control

## File: facebookresearch_deepbisim4control/local_dm_control_suite/wrappers/action_noise.py

Prompts

```
["create a Wrapper instance to add Gaussian noise to a dm_control environment's actions", 'run a step on the wrapped environment that applies clipped Gaussian noise to the action', 'reset the underlying dm_control environment through the action noise wrapper', 'review the Wrapper init to understand how it validates finite action bounds', 'summarize how the Wrapper computes noise standard deviation as a fraction of the action range', 'run the absltest suite to test the action noise wrapper step and clipping behavior', 'test the action noise wrapper step method with parameterized lower upper bounds and noise scale', 'test that noisy actions are clipped to stay within the bounded action spec limits', 'test that the action noise wrapper raises a ValueError when action bounds contain inf or nan', 'test that the action noise wrapper correctly passes through reset observation_spec and action_spec calls', 'create a Wrapper instance that adds rendered pixel observations to a dm_control environment', 'build a pixel-only environment by wrapping a control env with pixels_only set to True', 'test the Wrapper reset and step methods to verify pixel observations are added to time steps', 'review the Wrapper observation_spec method to understand how pixel specs are constructed from env physics', 'refactor the Wrapper to pass custom render_kwargs to the mujoco Physics render method', 'test the pixels.Wrapper with a cartpole swingup environment using dict observations', 'test the pixels.Wrapper with a FakeArrayObservationEnvironment using single array observations', 'test the pixels.Wrapper in pixels_only mode to verify only pixel keys remain', 'test the pixels.Wrapper with custom render_kwargs for width and height', 'test the FakeArrayObservationEnvironment mock class for dm_env observation specs']
```

Usage

```
{'create_action_noise_wrapper': "create a Wrapper instance to add Gaussian noise to a dm_control environment's actions", 'run_noisy_step': 'run a step on the wrapped environment that applies clipped Gaussian noise to the action', 'reset_wrapped_env': 'reset the underlying dm_control environment through the action noise wrapper', 'review_wrapper_bounds_check': 'review the Wrapper init to understand how it validates finite action bounds', 'summarize_noise_scale': 'summarize how the Wrapper computes noise standard deviation as a fraction of the action range'}
```

## File: facebookresearch_deepbisim4control/local_dm_control_suite/wrappers/action_noise_test.py

Prompts

```
["create a Wrapper instance to add Gaussian noise to a dm_control environment's actions", 'run a step on the wrapped environment that applies clipped Gaussian noise to the action', 'reset the underlying dm_control environment through the action noise wrapper', 'review the Wrapper init to understand how it validates finite action bounds', 'summarize how the Wrapper computes noise standard deviation as a fraction of the action range', 'run the absltest suite to test the action noise wrapper step and clipping behavior', 'test the action noise wrapper step method with parameterized lower upper bounds and noise scale', 'test that noisy actions are clipped to stay within the bounded action spec limits', 'test that the action noise wrapper raises a ValueError when action bounds contain inf or nan', 'test that the action noise wrapper correctly passes through reset observation_spec and action_spec calls', 'create a Wrapper instance that adds rendered pixel observations to a dm_control environment', 'build a pixel-only environment by wrapping a control env with pixels_only set to True', 'test the Wrapper reset and step methods to verify pixel observations are added to time steps', 'review the Wrapper observation_spec method to understand how pixel specs are constructed from env physics', 'refactor the Wrapper to pass custom render_kwargs to the mujoco Physics render method', 'test the pixels.Wrapper with a cartpole swingup environment using dict observations', 'test the pixels.Wrapper with a FakeArrayObservationEnvironment using single array observations', 'test the pixels.Wrapper in pixels_only mode to verify only pixel keys remain', 'test the pixels.Wrapper with custom render_kwargs for width and height', 'test the FakeArrayObservationEnvironment mock class for dm_env observation specs']
```

Usage

```
{'run_action_noise_tests': 'run the absltest suite to test the action noise wrapper step and clipping behavior', 'test_action_noise_step': 'test the action noise wrapper step method with parameterized lower upper bounds and noise scale', 'test_action_clipping': 'test that noisy actions are clipped to stay within the bounded action spec limits', 'test_non_finite_bounds_error': 'test that the action noise wrapper raises a ValueError when action bounds contain inf or nan', 'test_wrapper_passthrough': 'test that the action noise wrapper correctly passes through reset observation_spec and action_spec calls'}
```

## File: facebookresearch_deepbisim4control/local_dm_control_suite/wrappers/pixels.py

Prompts

```
["create a Wrapper instance to add Gaussian noise to a dm_control environment's actions", 'run a step on the wrapped environment that applies clipped Gaussian noise to the action', 'reset the underlying dm_control environment through the action noise wrapper', 'review the Wrapper init to understand how it validates finite action bounds', 'summarize how the Wrapper computes noise standard deviation as a fraction of the action range', 'run the absltest suite to test the action noise wrapper step and clipping behavior', 'test the action noise wrapper step method with parameterized lower upper bounds and noise scale', 'test that noisy actions are clipped to stay within the bounded action spec limits', 'test that the action noise wrapper raises a ValueError when action bounds contain inf or nan', 'test that the action noise wrapper correctly passes through reset observation_spec and action_spec calls', 'create a Wrapper instance that adds rendered pixel observations to a dm_control environment', 'build a pixel-only environment by wrapping a control env with pixels_only set to True', 'test the Wrapper reset and step methods to verify pixel observations are added to time steps', 'review the Wrapper observation_spec method to understand how pixel specs are constructed from env physics', 'refactor the Wrapper to pass custom render_kwargs to the mujoco Physics render method', 'test the pixels.Wrapper with a cartpole swingup environment using dict observations', 'test the pixels.Wrapper with a FakeArrayObservationEnvironment using single array observations', 'test the pixels.Wrapper in pixels_only mode to verify only pixel keys remain', 'test the pixels.Wrapper with custom render_kwargs for width and height', 'test the FakeArrayObservationEnvironment mock class for dm_env observation specs']
```

Usage

```
{'create_pixel_wrapper': 'create a Wrapper instance that adds rendered pixel observations to a dm_control environment', 'build_pixels_only_env': 'build a pixel-only environment by wrapping a control env with pixels_only set to True', 'test_wrapper_reset_step': 'test the Wrapper reset and step methods to verify pixel observations are added to time steps', 'review_wrapper_observation_spec': 'review the Wrapper observation_spec method to understand how pixel specs are constructed from env physics', 'refactor_wrapper_render_kwargs': 'refactor the Wrapper to pass custom render_kwargs to the mujoco Physics render method'}
```

## File: facebookresearch_deepbisim4control/local_dm_control_suite/wrappers/pixels_test.py

Prompts

```
["create a Wrapper instance to add Gaussian noise to a dm_control environment's actions", 'run a step on the wrapped environment that applies clipped Gaussian noise to the action', 'reset the underlying dm_control environment through the action noise wrapper', 'review the Wrapper init to understand how it validates finite action bounds', 'summarize how the Wrapper computes noise standard deviation as a fraction of the action range', 'run the absltest suite to test the action noise wrapper step and clipping behavior', 'test the action noise wrapper step method with parameterized lower upper bounds and noise scale', 'test that noisy actions are clipped to stay within the bounded action spec limits', 'test that the action noise wrapper raises a ValueError when action bounds contain inf or nan', 'test that the action noise wrapper correctly passes through reset observation_spec and action_spec calls', 'create a Wrapper instance that adds rendered pixel observations to a dm_control environment', 'build a pixel-only environment by wrapping a control env with pixels_only set to True', 'test the Wrapper reset and step methods to verify pixel observations are added to time steps', 'review the Wrapper observation_spec method to understand how pixel specs are constructed from env physics', 'refactor the Wrapper to pass custom render_kwargs to the mujoco Physics render method', 'test the pixels.Wrapper with a cartpole swingup environment using dict observations', 'test the pixels.Wrapper with a FakeArrayObservationEnvironment using single array observations', 'test the pixels.Wrapper in pixels_only mode to verify only pixel keys remain', 'test the pixels.Wrapper with custom render_kwargs for width and height', 'test the FakeArrayObservationEnvironment mock class for dm_env observation specs']
```

Usage

```
{'test_pixels_wrapper_dict_observation': 'test the pixels.Wrapper with a cartpole swingup environment using dict observations', 'test_pixels_wrapper_array_observation': 'test the pixels.Wrapper with a FakeArrayObservationEnvironment using single array observations', 'test_pixels_only_mode': 'test the pixels.Wrapper in pixels_only mode to verify only pixel keys remain', 'test_pixels_wrapper_render_kwargs': 'test the pixels.Wrapper with custom render_kwargs for width and height', 'test_fake_array_observation_environment': 'test the FakeArrayObservationEnvironment mock class for dm_env observation specs'}
```

