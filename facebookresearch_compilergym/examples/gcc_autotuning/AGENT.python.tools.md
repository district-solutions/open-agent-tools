# Agent Python Tools

- repo: facebookresearch/compilergym
- repo_uri: https://github.com/facebookresearch/compilergym

## File: facebookresearch_compilergym/examples/gcc_autotuning/info.py

Prompts

```
['run the typer CLI info command to print geometric mean of scaled_size from results.csv files in log directories', 'run experiments_from_paths to load a list of Experiment objects from given log directory paths', 'review the info command that walks log directories, reads results CSVs, and aggregates scaled_size by geometric mean', 'review the experiments_from_paths function that loads Experiment objects from log directories with pydantic validation error handling', 'refactor the info command to support additional aggregation metrics beyond geometric mean of scaled_size', 'run the GCC autotuning script with random, hillclimb, or genetic search strategies', 'run a random search over GCC compiler options to find the best configuration', 'run a hill climbing search that mutates GCC options within a small neighborhood', 'run a genetic algorithm to optimize GCC compiler options across a population', 'run a search for a specific benchmark and return the best size compared to baseline', 'run a smoke test for GCC autotuning with random, hillclimb, or genetic search strategies', 'check whether Docker is available on the system by calling docker.from_env', 'check whether a system GCC compiler is available and return a cached boolean result', 'get the absolute path of the system GCC compiler using the which command', 'list all available GCC binaries including Docker containers and system GCC paths']
```

Usage

```
{'run_info_cli': 'run the typer CLI info command to print geometric mean of scaled_size from results.csv files in log directories', 'run_experiments_from_paths': 'run experiments_from_paths to load a list of Experiment objects from given log directory paths', 'review_info_command': 'review the info command that walks log directories, reads results CSVs, and aggregates scaled_size by geometric mean', 'review_experiments_from_paths': 'review the experiments_from_paths function that loads Experiment objects from log directories with pydantic validation error handling', 'refactor_info_command': 'refactor the info command to support additional aggregation metrics beyond geometric mean of scaled_size'}
```

## File: facebookresearch_compilergym/examples/gcc_autotuning/tune.py

Prompts

```
['run the typer CLI info command to print geometric mean of scaled_size from results.csv files in log directories', 'run experiments_from_paths to load a list of Experiment objects from given log directory paths', 'review the info command that walks log directories, reads results CSVs, and aggregates scaled_size by geometric mean', 'review the experiments_from_paths function that loads Experiment objects from log directories with pydantic validation error handling', 'refactor the info command to support additional aggregation metrics beyond geometric mean of scaled_size', 'run the GCC autotuning script with random, hillclimb, or genetic search strategies', 'run a random search over GCC compiler options to find the best configuration', 'run a hill climbing search that mutates GCC options within a small neighborhood', 'run a genetic algorithm to optimize GCC compiler options across a population', 'run a search for a specific benchmark and return the best size compared to baseline', 'run a smoke test for GCC autotuning with random, hillclimb, or genetic search strategies', 'check whether Docker is available on the system by calling docker.from_env', 'check whether a system GCC compiler is available and return a cached boolean result', 'get the absolute path of the system GCC compiler using the which command', 'list all available GCC binaries including Docker containers and system GCC paths']
```

Usage

```
{'run_gcc_autotuning_search': 'run the GCC autotuning script with random, hillclimb, or genetic search strategies', 'run_random_search': 'run a random search over GCC compiler options to find the best configuration', 'run_hill_climb_search': 'run a hill climbing search that mutates GCC options within a small neighborhood', 'run_genetic_algorithm_search': 'run a genetic algorithm to optimize GCC compiler options across a population', 'run_search_with_benchmark': 'run a search for a specific benchmark and return the best size compared to baseline'}
```

## File: facebookresearch_compilergym/examples/gcc_autotuning/tune_test.py

Prompts

```
['run the typer CLI info command to print geometric mean of scaled_size from results.csv files in log directories', 'run experiments_from_paths to load a list of Experiment objects from given log directory paths', 'review the info command that walks log directories, reads results CSVs, and aggregates scaled_size by geometric mean', 'review the experiments_from_paths function that loads Experiment objects from log directories with pydantic validation error handling', 'refactor the info command to support additional aggregation metrics beyond geometric mean of scaled_size', 'run the GCC autotuning script with random, hillclimb, or genetic search strategies', 'run a random search over GCC compiler options to find the best configuration', 'run a hill climbing search that mutates GCC options within a small neighborhood', 'run a genetic algorithm to optimize GCC compiler options across a population', 'run a search for a specific benchmark and return the best size compared to baseline', 'run a smoke test for GCC autotuning with random, hillclimb, or genetic search strategies', 'check whether Docker is available on the system by calling docker.from_env', 'check whether a system GCC compiler is available and return a cached boolean result', 'get the absolute path of the system GCC compiler using the which command', 'list all available GCC binaries including Docker containers and system GCC paths']
```

Usage

```
{'test_gcc_autotuning_smoke': 'run a smoke test for GCC autotuning with random, hillclimb, or genetic search strategies', 'check_docker_availability': 'check whether Docker is available on the system by calling docker.from_env', 'check_system_gcc_availability': 'check whether a system GCC compiler is available and return a cached boolean result', 'get_system_gcc_path': 'get the absolute path of the system GCC compiler using the which command', 'list_available_gcc_bins': 'list all available GCC binaries including Docker containers and system GCC paths'}
```

