# Agent Python Tools

- repo: facebookresearch/flsim
- repo_uri: https://github.com/facebookresearch/flsim

## File: facebookresearch_flsim/flsim/privacy/tests/test_dp_integration.py

Prompts

```
['run the pytest test suite for differential privacy integration in FLSim federated learning', 'test that DP and non-DP models produce identical results when noise is zero and clipping is infinite', 'test that user-level DP is equivalent to sample-level DP under degenerate conditions with one example per user', 'test DP-SGD training with adaptive clipping and verify noise produces different model weights', 'test that DP-FTRL with zero noise produces the same model as standard FedAvg', 'test the GaussianPrivacyEngine class to verify privacy budget calculations and noise addition to model updates', 'test the CummuNoiseTorch class to verify tree-based noise accumulation matches expected variance', 'test the CummuNoiseEffTorch class to verify efficient tree-based noise accumulation with correct variance', 'test that GaussianPrivacyEngine throws PrivacyEngineNotAttachedException when add_noise is called before attaching a model', 'test GaussianPrivacyEngine with adaptive clipping to verify noise multiplier follows the formula from Theorem 1', 'test the calc_clip_factor function to verify clipping value divided by norm is correct', 'test the calc_norm function to verify L2 norm calculation of model parameters', 'test the UserUpdateClipper class to clip model updates so their norm does not exceed max_norm', 'test the AdaptiveClipper class to verify it tracks the median norm quantile over multiple rounds', 'test the AdaptiveClipper class to verify max_norm never exceeds the configured max_clipbound']
```

Usage

```
{'run_dp_integration_tests': 'run the pytest test suite for differential privacy integration in FLSim federated learning', 'test_dp_turned_off_by_params': 'test that DP and non-DP models produce identical results when noise is zero and clipping is infinite', 'test_user_dp_equivalent_sample_dp': 'test that user-level DP is equivalent to sample-level DP under degenerate conditions with one example per user', 'test_dp_sgd_with_adaptive_clipping': 'test DP-SGD training with adaptive clipping and verify noise produces different model weights', 'test_dp_ftrl_with_no_noise_same_as_fedavg': 'test that DP-FTRL with zero noise produces the same model as standard FedAvg'}
```

## File: facebookresearch_flsim/flsim/privacy/tests/test_privacy_engine.py

Prompts

```
['run the pytest test suite for differential privacy integration in FLSim federated learning', 'test that DP and non-DP models produce identical results when noise is zero and clipping is infinite', 'test that user-level DP is equivalent to sample-level DP under degenerate conditions with one example per user', 'test DP-SGD training with adaptive clipping and verify noise produces different model weights', 'test that DP-FTRL with zero noise produces the same model as standard FedAvg', 'test the GaussianPrivacyEngine class to verify privacy budget calculations and noise addition to model updates', 'test the CummuNoiseTorch class to verify tree-based noise accumulation matches expected variance', 'test the CummuNoiseEffTorch class to verify efficient tree-based noise accumulation with correct variance', 'test that GaussianPrivacyEngine throws PrivacyEngineNotAttachedException when add_noise is called before attaching a model', 'test GaussianPrivacyEngine with adaptive clipping to verify noise multiplier follows the formula from Theorem 1', 'test the calc_clip_factor function to verify clipping value divided by norm is correct', 'test the calc_norm function to verify L2 norm calculation of model parameters', 'test the UserUpdateClipper class to clip model updates so their norm does not exceed max_norm', 'test the AdaptiveClipper class to verify it tracks the median norm quantile over multiple rounds', 'test the AdaptiveClipper class to verify max_norm never exceeds the configured max_clipbound']
```

Usage

```
{'test_gaussian_privacy_engine': 'test the GaussianPrivacyEngine class to verify privacy budget calculations and noise addition to model updates', 'test_cummu_noise_torch': 'test the CummuNoiseTorch class to verify tree-based noise accumulation matches expected variance', 'test_cummu_noise_eff_torch': 'test the CummuNoiseEffTorch class to verify efficient tree-based noise accumulation with correct variance', 'test_privacy_engine_attach': 'test that GaussianPrivacyEngine throws PrivacyEngineNotAttachedException when add_noise is called before attaching a model', 'test_adaptive_clipping_noise': 'test GaussianPrivacyEngine with adaptive clipping to verify noise multiplier follows the formula from Theorem 1'}
```

## File: facebookresearch_flsim/flsim/privacy/tests/test_user_update_clipper.py

Prompts

```
['run the pytest test suite for differential privacy integration in FLSim federated learning', 'test that DP and non-DP models produce identical results when noise is zero and clipping is infinite', 'test that user-level DP is equivalent to sample-level DP under degenerate conditions with one example per user', 'test DP-SGD training with adaptive clipping and verify noise produces different model weights', 'test that DP-FTRL with zero noise produces the same model as standard FedAvg', 'test the GaussianPrivacyEngine class to verify privacy budget calculations and noise addition to model updates', 'test the CummuNoiseTorch class to verify tree-based noise accumulation matches expected variance', 'test the CummuNoiseEffTorch class to verify efficient tree-based noise accumulation with correct variance', 'test that GaussianPrivacyEngine throws PrivacyEngineNotAttachedException when add_noise is called before attaching a model', 'test GaussianPrivacyEngine with adaptive clipping to verify noise multiplier follows the formula from Theorem 1', 'test the calc_clip_factor function to verify clipping value divided by norm is correct', 'test the calc_norm function to verify L2 norm calculation of model parameters', 'test the UserUpdateClipper class to clip model updates so their norm does not exceed max_norm', 'test the AdaptiveClipper class to verify it tracks the median norm quantile over multiple rounds', 'test the AdaptiveClipper class to verify max_norm never exceeds the configured max_clipbound']
```

Usage

```
{'test_calc_clip_factor': 'test the calc_clip_factor function to verify clipping value divided by norm is correct', 'test_calc_user_update_norm': 'test the calc_norm function to verify L2 norm calculation of model parameters', 'test_user_update_clipper_clip': 'test the UserUpdateClipper class to clip model updates so their norm does not exceed max_norm', 'test_adaptive_clipper_median_norm': 'test the AdaptiveClipper class to verify it tracks the median norm quantile over multiple rounds', 'test_adaptive_clipper_norm_bounds': 'test the AdaptiveClipper class to verify max_norm never exceeds the configured max_clipbound'}
```

