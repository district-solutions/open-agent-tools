# Agent Python Tools

- repo: facebookresearch/denoisedmdp
- repo_uri: https://github.com/facebookresearch/denoised_mdp

## File: facebookresearch_denoisedmdp/denoised_mdp/envs/dmc/dmc2gym/local_dm_control_suite/wrappers/action_noise.py

Prompts

```
["create a Wrapper that adds Gaussian noise to a dm_control environment's actions with a configurable scale", 'wrap a dm_control suite environment with the action noise Wrapper to inject Gaussian noise during step calls', 'call step on the Wrapper to execute an action with clipped Gaussian noise added before forwarding to the underlying environment', 'review the Wrapper __init__ to understand how it validates that all action spec bounds are finite before computing noise std', 'refactor the Wrapper to customize the noise scale parameter which controls the standard deviation as a fraction of the action range', 'test the action noise wrapper step method with parameterized lower upper bounds and noise scale', 'test the action noise wrapper clips noisy actions to stay within the action spec bounds', 'test the action noise wrapper raises ValueError when action spec bounds contain inf or nan', 'test the action noise wrapper reset method delegates to the underlying environment reset', 'test the action noise wrapper observation_spec and action_spec delegate to the underlying environment', 'create a Wrapper instance that adds rendered pixel observations to a dm_control environment', 'create a pixel-only Wrapper that discards state observations and returns only rendered pixels', 'create a Wrapper with pixels_only=False to include both state and pixel observations', 'reset the wrapped environment and get a time step with pixel observations added', 'step the wrapped environment with an action and get a time step with pixel observations', 'test the pixels.Wrapper with a cartpole swingup environment using dict observations and custom render dimensions', 'test the pixels.Wrapper with a FakeArrayObservationEnvironment using single array observations and pixels_only mode', 'run the absltest PixelsTest suite to verify pixel wrapper behavior for dict and array observation environments', 'review the FakePhysics class render method that returns a 4x5x3 uint8 zero-filled numpy array', 'review the FakeArrayObservationEnvironment class that implements dm_env.Environment with a 2-element float observation spec']
```

Usage

```
{'create_action_noise_wrapper': "create a Wrapper that adds Gaussian noise to a dm_control environment's actions with a configurable scale", 'wrap_env_with_noise': 'wrap a dm_control suite environment with the action noise Wrapper to inject Gaussian noise during step calls', 'step_with_noisy_action': 'call step on the Wrapper to execute an action with clipped Gaussian noise added before forwarding to the underlying environment', 'review_wrapper_bounds_validation': 'review the Wrapper __init__ to understand how it validates that all action spec bounds are finite before computing noise std', 'refactor_noise_scale': 'refactor the Wrapper to customize the noise scale parameter which controls the standard deviation as a fraction of the action range'}
```

## File: facebookresearch_denoisedmdp/denoised_mdp/envs/dmc/dmc2gym/local_dm_control_suite/wrappers/action_noise_test.py

Prompts

```
["create a Wrapper that adds Gaussian noise to a dm_control environment's actions with a configurable scale", 'wrap a dm_control suite environment with the action noise Wrapper to inject Gaussian noise during step calls', 'call step on the Wrapper to execute an action with clipped Gaussian noise added before forwarding to the underlying environment', 'review the Wrapper __init__ to understand how it validates that all action spec bounds are finite before computing noise std', 'refactor the Wrapper to customize the noise scale parameter which controls the standard deviation as a fraction of the action range', 'test the action noise wrapper step method with parameterized lower upper bounds and noise scale', 'test the action noise wrapper clips noisy actions to stay within the action spec bounds', 'test the action noise wrapper raises ValueError when action spec bounds contain inf or nan', 'test the action noise wrapper reset method delegates to the underlying environment reset', 'test the action noise wrapper observation_spec and action_spec delegate to the underlying environment', 'create a Wrapper instance that adds rendered pixel observations to a dm_control environment', 'create a pixel-only Wrapper that discards state observations and returns only rendered pixels', 'create a Wrapper with pixels_only=False to include both state and pixel observations', 'reset the wrapped environment and get a time step with pixel observations added', 'step the wrapped environment with an action and get a time step with pixel observations', 'test the pixels.Wrapper with a cartpole swingup environment using dict observations and custom render dimensions', 'test the pixels.Wrapper with a FakeArrayObservationEnvironment using single array observations and pixels_only mode', 'run the absltest PixelsTest suite to verify pixel wrapper behavior for dict and array observation environments', 'review the FakePhysics class render method that returns a 4x5x3 uint8 zero-filled numpy array', 'review the FakeArrayObservationEnvironment class that implements dm_env.Environment with a 2-element float observation spec']
```

Usage

```
{'test_action_noise_wrapper_step': 'test the action noise wrapper step method with parameterized lower upper bounds and noise scale', 'test_action_noise_clipping': 'test the action noise wrapper clips noisy actions to stay within the action spec bounds', 'test_action_noise_non_finite_bounds': 'test the action noise wrapper raises ValueError when action spec bounds contain inf or nan', 'test_action_noise_wrapper_reset': 'test the action noise wrapper reset method delegates to the underlying environment reset', 'test_action_noise_wrapper_specs': 'test the action noise wrapper observation_spec and action_spec delegate to the underlying environment'}
```

## File: facebookresearch_denoisedmdp/denoised_mdp/envs/dmc/dmc2gym/local_dm_control_suite/wrappers/pixels.py

Prompts

```
["create a Wrapper that adds Gaussian noise to a dm_control environment's actions with a configurable scale", 'wrap a dm_control suite environment with the action noise Wrapper to inject Gaussian noise during step calls', 'call step on the Wrapper to execute an action with clipped Gaussian noise added before forwarding to the underlying environment', 'review the Wrapper __init__ to understand how it validates that all action spec bounds are finite before computing noise std', 'refactor the Wrapper to customize the noise scale parameter which controls the standard deviation as a fraction of the action range', 'test the action noise wrapper step method with parameterized lower upper bounds and noise scale', 'test the action noise wrapper clips noisy actions to stay within the action spec bounds', 'test the action noise wrapper raises ValueError when action spec bounds contain inf or nan', 'test the action noise wrapper reset method delegates to the underlying environment reset', 'test the action noise wrapper observation_spec and action_spec delegate to the underlying environment', 'create a Wrapper instance that adds rendered pixel observations to a dm_control environment', 'create a pixel-only Wrapper that discards state observations and returns only rendered pixels', 'create a Wrapper with pixels_only=False to include both state and pixel observations', 'reset the wrapped environment and get a time step with pixel observations added', 'step the wrapped environment with an action and get a time step with pixel observations', 'test the pixels.Wrapper with a cartpole swingup environment using dict observations and custom render dimensions', 'test the pixels.Wrapper with a FakeArrayObservationEnvironment using single array observations and pixels_only mode', 'run the absltest PixelsTest suite to verify pixel wrapper behavior for dict and array observation environments', 'review the FakePhysics class render method that returns a 4x5x3 uint8 zero-filled numpy array', 'review the FakeArrayObservationEnvironment class that implements dm_env.Environment with a 2-element float observation spec']
```

Usage

```
{'create_pixel_wrapper': 'create a Wrapper instance that adds rendered pixel observations to a dm_control environment', 'create_pixels_only_wrapper': 'create a pixel-only Wrapper that discards state observations and returns only rendered pixels', 'create_mixed_observation_wrapper': 'create a Wrapper with pixels_only=False to include both state and pixel observations', 'reset_wrapped_env': 'reset the wrapped environment and get a time step with pixel observations added', 'step_wrapped_env': 'step the wrapped environment with an action and get a time step with pixel observations'}
```

## File: facebookresearch_denoisedmdp/denoised_mdp/envs/dmc/dmc2gym/local_dm_control_suite/wrappers/pixels_test.py

Prompts

```
["create a Wrapper that adds Gaussian noise to a dm_control environment's actions with a configurable scale", 'wrap a dm_control suite environment with the action noise Wrapper to inject Gaussian noise during step calls', 'call step on the Wrapper to execute an action with clipped Gaussian noise added before forwarding to the underlying environment', 'review the Wrapper __init__ to understand how it validates that all action spec bounds are finite before computing noise std', 'refactor the Wrapper to customize the noise scale parameter which controls the standard deviation as a fraction of the action range', 'test the action noise wrapper step method with parameterized lower upper bounds and noise scale', 'test the action noise wrapper clips noisy actions to stay within the action spec bounds', 'test the action noise wrapper raises ValueError when action spec bounds contain inf or nan', 'test the action noise wrapper reset method delegates to the underlying environment reset', 'test the action noise wrapper observation_spec and action_spec delegate to the underlying environment', 'create a Wrapper instance that adds rendered pixel observations to a dm_control environment', 'create a pixel-only Wrapper that discards state observations and returns only rendered pixels', 'create a Wrapper with pixels_only=False to include both state and pixel observations', 'reset the wrapped environment and get a time step with pixel observations added', 'step the wrapped environment with an action and get a time step with pixel observations', 'test the pixels.Wrapper with a cartpole swingup environment using dict observations and custom render dimensions', 'test the pixels.Wrapper with a FakeArrayObservationEnvironment using single array observations and pixels_only mode', 'run the absltest PixelsTest suite to verify pixel wrapper behavior for dict and array observation environments', 'review the FakePhysics class render method that returns a 4x5x3 uint8 zero-filled numpy array', 'review the FakeArrayObservationEnvironment class that implements dm_env.Environment with a 2-element float observation spec']
```

Usage

```
{'test_pixels_wrapper_dict_observation': 'test the pixels.Wrapper with a cartpole swingup environment using dict observations and custom render dimensions', 'test_pixels_wrapper_array_observation': 'test the pixels.Wrapper with a FakeArrayObservationEnvironment using single array observations and pixels_only mode', 'run_pixels_test_suite': 'run the absltest PixelsTest suite to verify pixel wrapper behavior for dict and array observation environments', 'review_fakephysics_render': 'review the FakePhysics class render method that returns a 4x5x3 uint8 zero-filled numpy array', 'review_fakearrayobservationenvironment': 'review the FakeArrayObservationEnvironment class that implements dm_env.Environment with a 2-element float observation spec'}
```

