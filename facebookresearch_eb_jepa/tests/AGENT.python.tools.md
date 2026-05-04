# Agent Python Tools

- repo: facebookresearch/eb/jepa
- repo_uri: https://github.com/facebookresearch/eb_jepa

## File: facebookresearch_eb_jepa/tests/test_jepa_output_formats.py

Prompts

```
['run all JEPA unroll output format tests for parallel and autoregressive modes', 'create a Video JEPA model with ResNet5 encoder and ResUNet predictor for Moving MNIST', 'create an Action-Conditioned Video JEPA model with ImpalaEncoder and RNNPredictor for two_rooms', 'test the JEPA unroll function parallel mode output format with return_all_steps', 'test the JEPA unroll function autoregressive mode tensor shapes for planning and MPC', 'run pytest to verify VICRegLoss std computation equals HingeStdLoss with centering', 'run pytest to verify VICRegLoss covariance computation equals CovarianceLoss class output', 'run pytest to verify VICRegLoss decomposes into HingeStdLoss plus CovarianceLoss plus MSE', 'run pytest to verify VCLoss output structure and coefficient weighting on 5D tensors', 'run pytest to verify refactored VICRegLoss matches original inline implementation']
```

Usage

```
{'run_all_tests': 'run all JEPA unroll output format tests for parallel and autoregressive modes', 'create_video_jepa_model': 'create a Video JEPA model with ResNet5 encoder and ResUNet predictor for Moving MNIST', 'create_ac_video_jepa_model': 'create an Action-Conditioned Video JEPA model with ImpalaEncoder and RNNPredictor for two_rooms', 'test_unroll_parallel_mode_output_format': 'test the JEPA unroll function parallel mode output format with return_all_steps', 'test_unroll_autoregressive_mode_shapes': 'test the JEPA unroll function autoregressive mode tensor shapes for planning and MPC'}
```

## File: facebookresearch_eb_jepa/tests/test_loss_equivalences.py

Prompts

```
['run all JEPA unroll output format tests for parallel and autoregressive modes', 'create a Video JEPA model with ResNet5 encoder and ResUNet predictor for Moving MNIST', 'create an Action-Conditioned Video JEPA model with ImpalaEncoder and RNNPredictor for two_rooms', 'test the JEPA unroll function parallel mode output format with return_all_steps', 'test the JEPA unroll function autoregressive mode tensor shapes for planning and MPC', 'run pytest to verify VICRegLoss std computation equals HingeStdLoss with centering', 'run pytest to verify VICRegLoss covariance computation equals CovarianceLoss class output', 'run pytest to verify VICRegLoss decomposes into HingeStdLoss plus CovarianceLoss plus MSE', 'run pytest to verify VCLoss output structure and coefficient weighting on 5D tensors', 'run pytest to verify refactored VICRegLoss matches original inline implementation']
```

Usage

```
{'run_test_std_loss_equivalence': 'run pytest to verify VICRegLoss std computation equals HingeStdLoss with centering', 'run_test_cov_loss_equivalence': 'run pytest to verify VICRegLoss covariance computation equals CovarianceLoss class output', 'run_test_vicreg_decomposition': 'run pytest to verify VICRegLoss decomposes into HingeStdLoss plus CovarianceLoss plus MSE', 'run_test_vc_loss': 'run pytest to verify VCLoss output structure and coefficient weighting on 5D tensors', 'run_test_vicreg_regression': 'run pytest to verify refactored VICRegLoss matches original inline implementation'}
```

