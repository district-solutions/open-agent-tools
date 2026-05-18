# Agent Python Tools

- repo: facebookresearch/nevergrad
- repo_uri: https://github.com/facebookresearch/nevergrad

## File: facebookresearch_nevergrad/nevergrad/functions/olympussurfaces/core.py

Prompts

```
['create an OlympusSurface instance with a specified surface kind, dimension, and noise configuration', 'simulate an Olympus surface evaluation on input data with Gaussian, Uniform, or Gamma noise', 'run an OlympusEmulator with a specified dataset and NeuralNet or BayesNeuralNet model', 'get the noise-free evaluation of an OlympusSurface using the evaluation_function method', 'configure an OlympusEmulator parametrization with dataset-derived bounds and dimension', 'test OlympusSurface with GaussianNoise, UniformNoise, or GammaNoise across all surface kinds', 'create an OlympusSurface instance with a specified kind and noise_kind for optimization experiments', 'run an OlympusSurface function on a random input vector and assert the result is finite', 'review OlympusSurface randomization by comparing two instances with the same kind and noise_kind', 'test OlympusSurface and raise UnsupportedExperiment when running on Windows']
```

Usage

```
{'create_olympus_surface': 'create an OlympusSurface instance with a specified surface kind, dimension, and noise configuration', 'simulate_surface_with_noise': 'simulate an Olympus surface evaluation on input data with Gaussian, Uniform, or Gamma noise', 'run_olympus_emulator': 'run an OlympusEmulator with a specified dataset and NeuralNet or BayesNeuralNet model', 'get_surface_evaluation': 'get the noise-free evaluation of an OlympusSurface using the evaluation_function method', 'configure_emulator_parametrization': 'configure an OlympusEmulator parametrization with dataset-derived bounds and dimension'}
```

## File: facebookresearch_nevergrad/nevergrad/functions/olympussurfaces/test_core.py

Prompts

```
['create an OlympusSurface instance with a specified surface kind, dimension, and noise configuration', 'simulate an Olympus surface evaluation on input data with Gaussian, Uniform, or Gamma noise', 'run an OlympusEmulator with a specified dataset and NeuralNet or BayesNeuralNet model', 'get the noise-free evaluation of an OlympusSurface using the evaluation_function method', 'configure an OlympusEmulator parametrization with dataset-derived bounds and dimension', 'test OlympusSurface with GaussianNoise, UniformNoise, or GammaNoise across all surface kinds', 'create an OlympusSurface instance with a specified kind and noise_kind for optimization experiments', 'run an OlympusSurface function on a random input vector and assert the result is finite', 'review OlympusSurface randomization by comparing two instances with the same kind and noise_kind', 'test OlympusSurface and raise UnsupportedExperiment when running on Windows']
```

Usage

```
{'test_olympus_surface_with_noise': 'test OlympusSurface with GaussianNoise, UniformNoise, or GammaNoise across all surface kinds', 'create_olympus_surface_instance': 'create an OlympusSurface instance with a specified kind and noise_kind for optimization experiments', 'run_olympus_surface_evaluation': 'run an OlympusSurface function on a random input vector and assert the result is finite', 'review_olympus_surface_randomization': 'review OlympusSurface randomization by comparing two instances with the same kind and noise_kind', 'test_olympus_surface_windows_support': 'test OlympusSurface and raise UnsupportedExperiment when running on Windows'}
```

