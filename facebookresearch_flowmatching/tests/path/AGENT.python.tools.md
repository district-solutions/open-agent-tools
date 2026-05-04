# Agent Python Tools

- repo: facebookresearch/flowmatching
- repo_uri: https://github.com/facebookresearch/flow_matching

## File: facebookresearch_flowmatching/tests/path/test_path.py

Prompts

```
['test AffineProbPath sample method to verify interpolated x_t and dx_t shapes match inputs', 'test CondOTProbPath target_to_velocity and velocity_to_target round-trip conversion', 'test CondOTProbPath target_to_epsilon and epsilon_to_target round-trip conversion', 'test GeodesicProbPath on a Sphere manifold to verify samples stay on the sphere surface', 'test MixtureDiscreteProbPath sample method at t=0 and t=1 boundary conditions', 'test the ScheduleTransformedModel to verify transformed scheduler samples match original scheduler samples', 'run the DummyModel forward pass that multiplies input tensor by time squared', 'create a ScheduleTransformedModel wrapping a velocity model with original and new schedulers', 'build an ODESolver with a velocity model and sample using euler method', 'review the TestScheduleTransformedModel unittest class that validates schedule transformation correctness', 'test the CondOTScheduler class by calling it with a tensor and verifying output shapes', 'test the CosineScheduler class by computing alpha_t and sigma_t from time tensors', 'test the VPScheduler class by calling it with time tensors and checking SNR inverse recovery', 'test the LinearVPScheduler class by verifying output shapes and SNR inverse recovery', 'test the PolynomialConvexScheduler class with n=2 and verify kappa and SNR inverse recovery']
```

Usage

```
{'test_AffineProbPath_sample': 'test AffineProbPath sample method to verify interpolated x_t and dx_t shapes match inputs', 'test_CondOTProbPath_velocity_conversion': 'test CondOTProbPath target_to_velocity and velocity_to_target round-trip conversion', 'test_CondOTProbPath_epsilon_conversion': 'test CondOTProbPath target_to_epsilon and epsilon_to_target round-trip conversion', 'test_GeodesicProbPath_sphere': 'test GeodesicProbPath on a Sphere manifold to verify samples stay on the sphere surface', 'test_MixtureDiscreteProbPath_sample': 'test MixtureDiscreteProbPath sample method at t=0 and t=1 boundary conditions'}
```

## File: facebookresearch_flowmatching/tests/path/test_schedule_transform.py

Prompts

```
['test AffineProbPath sample method to verify interpolated x_t and dx_t shapes match inputs', 'test CondOTProbPath target_to_velocity and velocity_to_target round-trip conversion', 'test CondOTProbPath target_to_epsilon and epsilon_to_target round-trip conversion', 'test GeodesicProbPath on a Sphere manifold to verify samples stay on the sphere surface', 'test MixtureDiscreteProbPath sample method at t=0 and t=1 boundary conditions', 'test the ScheduleTransformedModel to verify transformed scheduler samples match original scheduler samples', 'run the DummyModel forward pass that multiplies input tensor by time squared', 'create a ScheduleTransformedModel wrapping a velocity model with original and new schedulers', 'build an ODESolver with a velocity model and sample using euler method', 'review the TestScheduleTransformedModel unittest class that validates schedule transformation correctness', 'test the CondOTScheduler class by calling it with a tensor and verifying output shapes', 'test the CosineScheduler class by computing alpha_t and sigma_t from time tensors', 'test the VPScheduler class by calling it with time tensors and checking SNR inverse recovery', 'test the LinearVPScheduler class by verifying output shapes and SNR inverse recovery', 'test the PolynomialConvexScheduler class with n=2 and verify kappa and SNR inverse recovery']
```

Usage

```
{'test_schedule_transformation': 'test the ScheduleTransformedModel to verify transformed scheduler samples match original scheduler samples', 'run_DummyModel_forward': 'run the DummyModel forward pass that multiplies input tensor by time squared', 'create_ScheduleTransformedModel': 'create a ScheduleTransformedModel wrapping a velocity model with original and new schedulers', 'build_ODESolver_sample': 'build an ODESolver with a velocity model and sample using euler method', 'review_TestScheduleTransformedModel': 'review the TestScheduleTransformedModel unittest class that validates schedule transformation correctness'}
```

## File: facebookresearch_flowmatching/tests/path/test_scheduler.py

Prompts

```
['test AffineProbPath sample method to verify interpolated x_t and dx_t shapes match inputs', 'test CondOTProbPath target_to_velocity and velocity_to_target round-trip conversion', 'test CondOTProbPath target_to_epsilon and epsilon_to_target round-trip conversion', 'test GeodesicProbPath on a Sphere manifold to verify samples stay on the sphere surface', 'test MixtureDiscreteProbPath sample method at t=0 and t=1 boundary conditions', 'test the ScheduleTransformedModel to verify transformed scheduler samples match original scheduler samples', 'run the DummyModel forward pass that multiplies input tensor by time squared', 'create a ScheduleTransformedModel wrapping a velocity model with original and new schedulers', 'build an ODESolver with a velocity model and sample using euler method', 'review the TestScheduleTransformedModel unittest class that validates schedule transformation correctness', 'test the CondOTScheduler class by calling it with a tensor and verifying output shapes', 'test the CosineScheduler class by computing alpha_t and sigma_t from time tensors', 'test the VPScheduler class by calling it with time tensors and checking SNR inverse recovery', 'test the LinearVPScheduler class by verifying output shapes and SNR inverse recovery', 'test the PolynomialConvexScheduler class with n=2 and verify kappa and SNR inverse recovery']
```

Usage

```
{'test_cond_ot_scheduler': 'test the CondOTScheduler class by calling it with a tensor and verifying output shapes', 'test_cosine_scheduler': 'test the CosineScheduler class by computing alpha_t and sigma_t from time tensors', 'test_vp_scheduler': 'test the VPScheduler class by calling it with time tensors and checking SNR inverse recovery', 'test_linear_vp_scheduler': 'test the LinearVPScheduler class by verifying output shapes and SNR inverse recovery', 'test_polynomial_convex_scheduler': 'test the PolynomialConvexScheduler class with n=2 and verify kappa and SNR inverse recovery'}
```

