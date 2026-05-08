# Agent Python Tools

- repo: facebookresearch/hydra
- repo_uri: https://github.com/facebookresearch/hydra.git

## File: facebookresearch_hydra/plugins/hydra_optuna_sweeper/example/custom-search-space-objective.py

Prompts

```
['run the hydra main function to compute a multi-dimensional sphere objective from config parameters', 'configure an optuna trial to suggest float values for z and w parameters dynamically', 'review the multi_dimensional_sphere function that returns the sum of squared w, x, y, z config values', 'review the configure function that uses trial params to set conditional search space bounds for z', 'summarize the custom search space objective example that demonstrates dynamic parameter suggestion with optuna', 'run the binh_and_korn function to compute two objective values from config parameters x and y', 'create a Hydra-configured multi-objective optimization function that returns two objective values from x and y', 'test the binh_and_korn function by running it with Hydra CLI and config values for x and y', 'refactor the binh_and_korn function to support additional objective values beyond the current two', 'summarize the binh_and_korn function which computes v0 and v1 objective values using the Binh and Korn test problem', 'run the sphere function to compute x squared plus y squared using Hydra and Optuna sweeper', 'run the sphere function with error flag set to true to simulate a RuntimeError exception', 'review the sphere function that takes x and y from Hydra config and returns x squared plus y squared', 'refactor the sphere function to use different config parameters or add additional optimization variables', 'test the sphere function with Optuna TPE sampler across 20 trials minimizing x squared plus y squared']
```

Usage

```
{'run_multi_dimensional_sphere': 'run the hydra main function to compute a multi-dimensional sphere objective from config parameters', 'configure_optuna_trial': 'configure an optuna trial to suggest float values for z and w parameters dynamically', 'review_multi_dimensional_sphere': 'review the multi_dimensional_sphere function that returns the sum of squared w, x, y, z config values', 'review_configure': 'review the configure function that uses trial params to set conditional search space bounds for z', 'summarize_custom_search_space': 'summarize the custom search space objective example that demonstrates dynamic parameter suggestion with optuna'}
```

## File: facebookresearch_hydra/plugins/hydra_optuna_sweeper/example/multi-objective.py

Prompts

```
['run the hydra main function to compute a multi-dimensional sphere objective from config parameters', 'configure an optuna trial to suggest float values for z and w parameters dynamically', 'review the multi_dimensional_sphere function that returns the sum of squared w, x, y, z config values', 'review the configure function that uses trial params to set conditional search space bounds for z', 'summarize the custom search space objective example that demonstrates dynamic parameter suggestion with optuna', 'run the binh_and_korn function to compute two objective values from config parameters x and y', 'create a Hydra-configured multi-objective optimization function that returns two objective values from x and y', 'test the binh_and_korn function by running it with Hydra CLI and config values for x and y', 'refactor the binh_and_korn function to support additional objective values beyond the current two', 'summarize the binh_and_korn function which computes v0 and v1 objective values using the Binh and Korn test problem', 'run the sphere function to compute x squared plus y squared using Hydra and Optuna sweeper', 'run the sphere function with error flag set to true to simulate a RuntimeError exception', 'review the sphere function that takes x and y from Hydra config and returns x squared plus y squared', 'refactor the sphere function to use different config parameters or add additional optimization variables', 'test the sphere function with Optuna TPE sampler across 20 trials minimizing x squared plus y squared']
```

Usage

```
{'run_binh_and_korn': 'run the binh_and_korn function to compute two objective values from config parameters x and y', 'create_multi_objective_objective': 'create a Hydra-configured multi-objective optimization function that returns two objective values from x and y', 'test_binh_and_korn': 'test the binh_and_korn function by running it with Hydra CLI and config values for x and y', 'refactor_binh_and_korn': 'refactor the binh_and_korn function to support additional objective values beyond the current two', 'summarize_binh_and_korn': 'summarize the binh_and_korn function which computes v0 and v1 objective values using the Binh and Korn test problem'}
```

## File: facebookresearch_hydra/plugins/hydra_optuna_sweeper/example/sphere.py

Prompts

```
['run the hydra main function to compute a multi-dimensional sphere objective from config parameters', 'configure an optuna trial to suggest float values for z and w parameters dynamically', 'review the multi_dimensional_sphere function that returns the sum of squared w, x, y, z config values', 'review the configure function that uses trial params to set conditional search space bounds for z', 'summarize the custom search space objective example that demonstrates dynamic parameter suggestion with optuna', 'run the binh_and_korn function to compute two objective values from config parameters x and y', 'create a Hydra-configured multi-objective optimization function that returns two objective values from x and y', 'test the binh_and_korn function by running it with Hydra CLI and config values for x and y', 'refactor the binh_and_korn function to support additional objective values beyond the current two', 'summarize the binh_and_korn function which computes v0 and v1 objective values using the Binh and Korn test problem', 'run the sphere function to compute x squared plus y squared using Hydra and Optuna sweeper', 'run the sphere function with error flag set to true to simulate a RuntimeError exception', 'review the sphere function that takes x and y from Hydra config and returns x squared plus y squared', 'refactor the sphere function to use different config parameters or add additional optimization variables', 'test the sphere function with Optuna TPE sampler across 20 trials minimizing x squared plus y squared']
```

Usage

```
{'run_sphere_optimization': 'run the sphere function to compute x squared plus y squared using Hydra and Optuna sweeper', 'run_sphere_with_error': 'run the sphere function with error flag set to true to simulate a RuntimeError exception', 'review_sphere_function': 'review the sphere function that takes x and y from Hydra config and returns x squared plus y squared', 'refactor_sphere_config': 'refactor the sphere function to use different config parameters or add additional optimization variables', 'test_sphere_optuna_sweeper': 'test the sphere function with Optuna TPE sampler across 20 trials minimizing x squared plus y squared'}
```

