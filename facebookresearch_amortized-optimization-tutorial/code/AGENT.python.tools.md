# Agent Python Tools

- repo: facebookresearch/amortized-optimization-tutorial
- repo_uri: https://github.com/facebookresearch/amortized-optimization-tutorial

## File: facebookresearch_amortized-optimization-tutorial/code/evaluate_amortization_speed_control.py

Prompts

```
['run the amortization speed evaluation script for model-free and model-based control on a trained humanoid agent', "run the collect_eval_episode function to gather observations from a trained agent's evaluation episode in the environment", 'run evaluate_amortization_speed with a custom amortization model and objective to measure optimization convergence over iterations', 'review the main function that loads a trained SAC agent and evaluates amortization speed for model-free and model-based control', 'review the collect_eval_episode function that runs an agent in the environment and returns stacked observation tensors', 'build a benchmark that compares amortization model inference speed to Adam optimization over 2000 iterations', 'create a convergence plot showing objective value versus Adam iterations with standard deviation shading', 'create a runtime plot showing objective value versus wall-clock time with amortized baseline overlay', 'review evaluate_amortization_speed to understand how it benchmarks amortization models and generates comparison plots', 'run the VAE amortization speed evaluation on MNIST samples and save reconstructions', 'sample from a Gaussian distribution given mean and logvar tensors using reparameterization', 'unflatten a concatenated latent distribution tensor into separate mean and logvar tensors', 'estimate the ELBO for VAE samples using a decoder, binary cross-entropy, and KL divergence', 'evaluate amortization speed by optimizing latent variables with Adam over 2000 iterations', 'convert right ascension and declination coordinates to 3D Euclidean x, y, z coordinates', 'convert 3D Euclidean x, y, z coordinates back to right ascension and declination', 'convert PyTorch tensor Euclidean coordinates to celestial right ascension and declination', 'compute the great circle distance between two points on a unit sphere using PyTorch', 'create a c-convex function on the sphere with random components and evaluate it at given points']
```

Usage

```
{'run_amortization_speed_evaluation': 'run the amortization speed evaluation script for model-free and model-based control on a trained humanoid agent', 'run_collect_eval_episode': "run the collect_eval_episode function to gather observations from a trained agent's evaluation episode in the environment", 'run_evaluate_amortization_speed': 'run evaluate_amortization_speed with a custom amortization model and objective to measure optimization convergence over iterations', 'review_main': 'review the main function that loads a trained SAC agent and evaluates amortization speed for model-free and model-based control', 'review_collect_eval_episode': 'review the collect_eval_episode function that runs an agent in the environment and returns stacked observation tensors'}
```

## File: facebookresearch_amortized-optimization-tutorial/code/evaluate_amortization_speed_function.py

Prompts

```
['run the amortization speed evaluation script for model-free and model-based control on a trained humanoid agent', "run the collect_eval_episode function to gather observations from a trained agent's evaluation episode in the environment", 'run evaluate_amortization_speed with a custom amortization model and objective to measure optimization convergence over iterations', 'review the main function that loads a trained SAC agent and evaluates amortization speed for model-free and model-based control', 'review the collect_eval_episode function that runs an agent in the environment and returns stacked observation tensors', 'build a benchmark that compares amortization model inference speed to Adam optimization over 2000 iterations', 'create a convergence plot showing objective value versus Adam iterations with standard deviation shading', 'create a runtime plot showing objective value versus wall-clock time with amortized baseline overlay', 'review evaluate_amortization_speed to understand how it benchmarks amortization models and generates comparison plots', 'run the VAE amortization speed evaluation on MNIST samples and save reconstructions', 'sample from a Gaussian distribution given mean and logvar tensors using reparameterization', 'unflatten a concatenated latent distribution tensor into separate mean and logvar tensors', 'estimate the ELBO for VAE samples using a decoder, binary cross-entropy, and KL divergence', 'evaluate amortization speed by optimizing latent variables with Adam over 2000 iterations', 'convert right ascension and declination coordinates to 3D Euclidean x, y, z coordinates', 'convert 3D Euclidean x, y, z coordinates back to right ascension and declination', 'convert PyTorch tensor Euclidean coordinates to celestial right ascension and declination', 'compute the great circle distance between two points on a unit sphere using PyTorch', 'create a c-convex function on the sphere with random components and evaluate it at given points']
```

Usage

```
{'run_evaluate_amortization_speed': 'run evaluate_amortization_speed to benchmark an amortization model against Adam optimization and save PDF plots', 'build_amortization_benchmark': 'build a benchmark that compares amortization model inference speed to Adam optimization over 2000 iterations', 'create_objective_convergence_plot': 'create a convergence plot showing objective value versus Adam iterations with standard deviation shading', 'create_runtime_convergence_plot': 'create a runtime plot showing objective value versus wall-clock time with amortized baseline overlay', 'review_evaluate_amortization_speed': 'review evaluate_amortization_speed to understand how it benchmarks amortization models and generates comparison plots'}
```

## File: facebookresearch_amortized-optimization-tutorial/code/evaluate_amortization_speed_vae.py

Prompts

```
['run the amortization speed evaluation script for model-free and model-based control on a trained humanoid agent', "run the collect_eval_episode function to gather observations from a trained agent's evaluation episode in the environment", 'run evaluate_amortization_speed with a custom amortization model and objective to measure optimization convergence over iterations', 'review the main function that loads a trained SAC agent and evaluates amortization speed for model-free and model-based control', 'review the collect_eval_episode function that runs an agent in the environment and returns stacked observation tensors', 'build a benchmark that compares amortization model inference speed to Adam optimization over 2000 iterations', 'create a convergence plot showing objective value versus Adam iterations with standard deviation shading', 'create a runtime plot showing objective value versus wall-clock time with amortized baseline overlay', 'review evaluate_amortization_speed to understand how it benchmarks amortization models and generates comparison plots', 'run the VAE amortization speed evaluation on MNIST samples and save reconstructions', 'sample from a Gaussian distribution given mean and logvar tensors using reparameterization', 'unflatten a concatenated latent distribution tensor into separate mean and logvar tensors', 'estimate the ELBO for VAE samples using a decoder, binary cross-entropy, and KL divergence', 'evaluate amortization speed by optimizing latent variables with Adam over 2000 iterations', 'convert right ascension and declination coordinates to 3D Euclidean x, y, z coordinates', 'convert 3D Euclidean x, y, z coordinates back to right ascension and declination', 'convert PyTorch tensor Euclidean coordinates to celestial right ascension and declination', 'compute the great circle distance between two points on a unit sphere using PyTorch', 'create a c-convex function on the sphere with random components and evaluate it at given points']
```

Usage

```
{'run_vae_amortization_evaluation': 'run the VAE amortization speed evaluation on MNIST samples and save reconstructions', 'sample_gaussian': 'sample from a Gaussian distribution given mean and logvar tensors using reparameterization', 'unflatten_latent': 'unflatten a concatenated latent distribution tensor into separate mean and logvar tensors', 'estimate_elbo': 'estimate the ELBO for VAE samples using a decoder, binary cross-entropy, and KL divergence', 'evaluate_amortization_speed': 'evaluate amortization speed by optimizing latent variables with Adam over 2000 iterations'}
```

## File: facebookresearch_amortized-optimization-tutorial/code/train-sphere.py

Prompts

```
['run the amortization speed evaluation script for model-free and model-based control on a trained humanoid agent', "run the collect_eval_episode function to gather observations from a trained agent's evaluation episode in the environment", 'run evaluate_amortization_speed with a custom amortization model and objective to measure optimization convergence over iterations', 'review the main function that loads a trained SAC agent and evaluates amortization speed for model-free and model-based control', 'review the collect_eval_episode function that runs an agent in the environment and returns stacked observation tensors', 'build a benchmark that compares amortization model inference speed to Adam optimization over 2000 iterations', 'create a convergence plot showing objective value versus Adam iterations with standard deviation shading', 'create a runtime plot showing objective value versus wall-clock time with amortized baseline overlay', 'review evaluate_amortization_speed to understand how it benchmarks amortization models and generates comparison plots', 'run the VAE amortization speed evaluation on MNIST samples and save reconstructions', 'sample from a Gaussian distribution given mean and logvar tensors using reparameterization', 'unflatten a concatenated latent distribution tensor into separate mean and logvar tensors', 'estimate the ELBO for VAE samples using a decoder, binary cross-entropy, and KL divergence', 'evaluate amortization speed by optimizing latent variables with Adam over 2000 iterations', 'convert right ascension and declination coordinates to 3D Euclidean x, y, z coordinates', 'convert 3D Euclidean x, y, z coordinates back to right ascension and declination', 'convert PyTorch tensor Euclidean coordinates to celestial right ascension and declination', 'compute the great circle distance between two points on a unit sphere using PyTorch', 'create a c-convex function on the sphere with random components and evaluate it at given points']
```

Usage

```
{'run_celestial_to_euclidean': 'convert right ascension and declination coordinates to 3D Euclidean x, y, z coordinates', 'run_euclidean_to_celestial': 'convert 3D Euclidean x, y, z coordinates back to right ascension and declination', 'run_euclidean_to_celestial_th': 'convert PyTorch tensor Euclidean coordinates to celestial right ascension and declination', 'run_sphere_dist_th': 'compute the great circle distance between two points on a unit sphere using PyTorch', 'run_c_convex': 'create a c-convex function on the sphere with random components and evaluate it at given points'}
```

