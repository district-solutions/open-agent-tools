# Agent Python Tools

- repo: facebookresearch/flowmatching
- repo_uri: https://github.com/facebookresearch/flow_matching

## File: facebookresearch_flowmatching/flow_matching/path/scheduler/schedule_transform.py

Prompts

```
['build a ScheduleTransformedModel wrapping a velocity model with original and new schedulers', 'create a ScheduleTransformedModel using CondOTScheduler as original and CosineScheduler as new scheduler', 'run the forward pass of a ScheduleTransformedModel with input tensor x and time tensor t', 'test the ScheduleTransformedModel by sampling with ODESolver using the transformed velocity model', 'review the ScheduleTransformedModel forward method that computes transformed marginal velocity using scale-time transformation', 'build a python module to create a CondOTScheduler and compute alpha_t and sigma_t for a given time tensor', 'build a python module to create a PolynomialConvexScheduler with exponent n and compute path coefficients for a time tensor', 'build a python module to create a VPScheduler with beta_min and beta_max and compute variance preserving path coefficients', 'build a python module to create a CosineScheduler and compute cosine-based alpha_t and sigma_t for a time tensor', 'test the snr_inverse method of a scheduler class to compute time t from a given signal-to-noise ratio tensor']
```

Usage

```
{'build_schedule_transformed_model': 'build a ScheduleTransformedModel wrapping a velocity model with original and new schedulers', 'create_schedule_transformed_model_with_cosine': 'create a ScheduleTransformedModel using CondOTScheduler as original and CosineScheduler as new scheduler', 'run_transformed_model_forward': 'run the forward pass of a ScheduleTransformedModel with input tensor x and time tensor t', 'test_schedule_transformed_model': 'test the ScheduleTransformedModel by sampling with ODESolver using the transformed velocity model', 'review_schedule_transformed_model_forward': 'review the ScheduleTransformedModel forward method that computes transformed marginal velocity using scale-time transformation'}
```

## File: facebookresearch_flowmatching/flow_matching/path/scheduler/scheduler.py

Prompts

```
['build a ScheduleTransformedModel wrapping a velocity model with original and new schedulers', 'create a ScheduleTransformedModel using CondOTScheduler as original and CosineScheduler as new scheduler', 'run the forward pass of a ScheduleTransformedModel with input tensor x and time tensor t', 'test the ScheduleTransformedModel by sampling with ODESolver using the transformed velocity model', 'review the ScheduleTransformedModel forward method that computes transformed marginal velocity using scale-time transformation', 'build a python module to create a CondOTScheduler and compute alpha_t and sigma_t for a given time tensor', 'build a python module to create a PolynomialConvexScheduler with exponent n and compute path coefficients for a time tensor', 'build a python module to create a VPScheduler with beta_min and beta_max and compute variance preserving path coefficients', 'build a python module to create a CosineScheduler and compute cosine-based alpha_t and sigma_t for a time tensor', 'test the snr_inverse method of a scheduler class to compute time t from a given signal-to-noise ratio tensor']
```

Usage

```
{'build_condot_scheduler': 'build a python module to create a CondOTScheduler and compute alpha_t and sigma_t for a given time tensor', 'build_polynomial_convex_scheduler': 'build a python module to create a PolynomialConvexScheduler with exponent n and compute path coefficients for a time tensor', 'build_vp_scheduler': 'build a python module to create a VPScheduler with beta_min and beta_max and compute variance preserving path coefficients', 'build_cosine_scheduler': 'build a python module to create a CosineScheduler and compute cosine-based alpha_t and sigma_t for a time tensor', 'test_snr_inverse': 'test the snr_inverse method of a scheduler class to compute time t from a given signal-to-noise ratio tensor'}
```

