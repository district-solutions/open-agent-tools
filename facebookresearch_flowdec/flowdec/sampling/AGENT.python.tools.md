# Agent Python Tools

- repo: facebookresearch/flowdec
- repo_uri: https://github.com/facebookresearch/flowdec

## File: facebookresearch_flowdec/flowdec/sampling/correctors.py

Prompts

```
['create a new corrector subclass that implements the abstract update_fn method for custom SDE sampling', 'run the AnnealedLangevinDynamics corrector update_fn to perform multiple Langevin dynamics steps on a tensor', 'use the CorrectorRegistry to look up and instantiate a registered corrector by name such as ald or none', 'review the Corrector abstract base class and its update_fn signature for implementing new corrector algorithms', 'test the NoneCorrector update_fn to verify it returns the input tensor unchanged without modification', 'create an EulerMaruyamaPredictor instance with an SDE and score function for stochastic sampling', 'create a ReverseDiffusionPredictor instance with an SDE and score function for reverse diffusion sampling', 'run the update_fn method on a Predictor to advance state x at time step t', 'register a custom Predictor subclass into the PredictorRegistry with a unique string key', 'create a NonePredictor that returns the input state unchanged for identity sampling steps', 'create a Heun2 ODE solver instance with explicit order-2 stepping for torchdyn', 'create a Heun2_EulerLast solver that uses Euler on the last step to avoid t=1 evaluation', 'run a single Heun2 step by calling step with function f, state x, time t, and dt', 'run a single Heun2_EulerLast step that conditionally applies Euler or Heun correction based on t+dt', 'get a solver instance by name using get_solver which returns custom solvers or passes strings to torchdyn']
```

Usage

```
{'create_corrector_subclass': 'create a new corrector subclass that implements the abstract update_fn method for custom SDE sampling', 'run_annealed_langevin_dynamics': 'run the AnnealedLangevinDynamics corrector update_fn to perform multiple Langevin dynamics steps on a tensor', 'use_corrector_registry': 'use the CorrectorRegistry to look up and instantiate a registered corrector by name such as ald or none', 'review_corrector_base_class': 'review the Corrector abstract base class and its update_fn signature for implementing new corrector algorithms', 'test_none_corrector': 'test the NoneCorrector update_fn to verify it returns the input tensor unchanged without modification'}
```

## File: facebookresearch_flowdec/flowdec/sampling/predictors.py

Prompts

```
['create a new corrector subclass that implements the abstract update_fn method for custom SDE sampling', 'run the AnnealedLangevinDynamics corrector update_fn to perform multiple Langevin dynamics steps on a tensor', 'use the CorrectorRegistry to look up and instantiate a registered corrector by name such as ald or none', 'review the Corrector abstract base class and its update_fn signature for implementing new corrector algorithms', 'test the NoneCorrector update_fn to verify it returns the input tensor unchanged without modification', 'create an EulerMaruyamaPredictor instance with an SDE and score function for stochastic sampling', 'create a ReverseDiffusionPredictor instance with an SDE and score function for reverse diffusion sampling', 'run the update_fn method on a Predictor to advance state x at time step t', 'register a custom Predictor subclass into the PredictorRegistry with a unique string key', 'create a NonePredictor that returns the input state unchanged for identity sampling steps', 'create a Heun2 ODE solver instance with explicit order-2 stepping for torchdyn', 'create a Heun2_EulerLast solver that uses Euler on the last step to avoid t=1 evaluation', 'run a single Heun2 step by calling step with function f, state x, time t, and dt', 'run a single Heun2_EulerLast step that conditionally applies Euler or Heun correction based on t+dt', 'get a solver instance by name using get_solver which returns custom solvers or passes strings to torchdyn']
```

Usage

```
{'create_euler_maruyama_predictor': 'create an EulerMaruyamaPredictor instance with an SDE and score function for stochastic sampling', 'create_reverse_diffusion_predictor': 'create a ReverseDiffusionPredictor instance with an SDE and score function for reverse diffusion sampling', 'run_predictor_update': 'run the update_fn method on a Predictor to advance state x at time step t', 'register_custom_predictor': 'register a custom Predictor subclass into the PredictorRegistry with a unique string key', 'create_none_predictor': 'create a NonePredictor that returns the input state unchanged for identity sampling steps'}
```

## File: facebookresearch_flowdec/flowdec/sampling/solvers.py

Prompts

```
['create a new corrector subclass that implements the abstract update_fn method for custom SDE sampling', 'run the AnnealedLangevinDynamics corrector update_fn to perform multiple Langevin dynamics steps on a tensor', 'use the CorrectorRegistry to look up and instantiate a registered corrector by name such as ald or none', 'review the Corrector abstract base class and its update_fn signature for implementing new corrector algorithms', 'test the NoneCorrector update_fn to verify it returns the input tensor unchanged without modification', 'create an EulerMaruyamaPredictor instance with an SDE and score function for stochastic sampling', 'create a ReverseDiffusionPredictor instance with an SDE and score function for reverse diffusion sampling', 'run the update_fn method on a Predictor to advance state x at time step t', 'register a custom Predictor subclass into the PredictorRegistry with a unique string key', 'create a NonePredictor that returns the input state unchanged for identity sampling steps', 'create a Heun2 ODE solver instance with explicit order-2 stepping for torchdyn', 'create a Heun2_EulerLast solver that uses Euler on the last step to avoid t=1 evaluation', 'run a single Heun2 step by calling step with function f, state x, time t, and dt', 'run a single Heun2_EulerLast step that conditionally applies Euler or Heun correction based on t+dt', 'get a solver instance by name using get_solver which returns custom solvers or passes strings to torchdyn']
```

Usage

```
{'create_heun2_solver': 'create a Heun2 ODE solver instance with explicit order-2 stepping for torchdyn', 'create_heun2_eulerlast_solver': 'create a Heun2_EulerLast solver that uses Euler on the last step to avoid t=1 evaluation', 'run_heun2_step': 'run a single Heun2 step by calling step with function f, state x, time t, and dt', 'run_heun2_eulerlast_step': 'run a single Heun2_EulerLast step that conditionally applies Euler or Heun correction based on t+dt', 'get_solver_by_name': 'get a solver instance by name using get_solver which returns custom solvers or passes strings to torchdyn'}
```

