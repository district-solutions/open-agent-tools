# Agent Python Tools

- repo: algorithmicsuperintelligence/openevolve
- repo_uri: https://github.com/algorithmicsuperintelligence/openevolve

## File: algorithmicsuperintelligence_openevolve/tests/integration/test_examples_validation.py

Prompts

```
['test that example config YAML files load into valid Config objects without errors', 'test that an evaluator module exposes a callable evaluate function via dynamic import', 'test that the evaluator can score an initial program and return a combined_score metric', 'test that the ProgramDatabase can store and retrieve Program objects by their unique id', 'test that all evaluator modules in the examples directory can be imported and have an evaluate function', 'run evolve_function to optimize a Python function using an LLM with test cases', 'run evolve_code to optimize a code string with evolve block markers and a custom evaluator', 'run run_evolution to evolve a program file using an evaluator file and LLM', 'run run_evolution with string inputs and a lambda evaluator for quick program evolution', 'test the OpenEvolve library API integration with a real LLM server using pytest', 'run an evolution loop on a Python program file with a custom evaluator function', 'test that the Config class has llm, database, evaluator, and prompt attributes', 'create an LLMModelConfig with name, api_key, api_base, weight, timeout, and retries', 'create an EvolutionResult with best_score, best_code, metrics, and output_dir', 'test that run_evolution raises ValueError when no LLM models are configured']
```

Usage

```
{'test_config_loads': 'test that example config YAML files load into valid Config objects without errors', 'test_evaluator_has_evaluate_function': 'test that an evaluator module exposes a callable evaluate function via dynamic import', 'test_evaluator_runs_on_initial_program': 'test that the evaluator can score an initial program and return a combined_score metric', 'test_database_stores_and_retrieves_programs': 'test that the ProgramDatabase can store and retrieve Program objects by their unique id', 'test_evaluators_are_importable': 'test that all evaluator modules in the examples directory can be imported and have an evaluate function'}
```

## File: algorithmicsuperintelligence_openevolve/tests/integration/test_library_api.py

Prompts

```
['test that example config YAML files load into valid Config objects without errors', 'test that an evaluator module exposes a callable evaluate function via dynamic import', 'test that the evaluator can score an initial program and return a combined_score metric', 'test that the ProgramDatabase can store and retrieve Program objects by their unique id', 'test that all evaluator modules in the examples directory can be imported and have an evaluate function', 'run evolve_function to optimize a Python function using an LLM with test cases', 'run evolve_code to optimize a code string with evolve block markers and a custom evaluator', 'run run_evolution to evolve a program file using an evaluator file and LLM', 'run run_evolution with string inputs and a lambda evaluator for quick program evolution', 'test the OpenEvolve library API integration with a real LLM server using pytest', 'run an evolution loop on a Python program file with a custom evaluator function', 'test that the Config class has llm, database, evaluator, and prompt attributes', 'create an LLMModelConfig with name, api_key, api_base, weight, timeout, and retries', 'create an EvolutionResult with best_score, best_code, metrics, and output_dir', 'test that run_evolution raises ValueError when no LLM models are configured']
```

Usage

```
{'run_evolve_function': 'run evolve_function to optimize a Python function using an LLM with test cases', 'run_evolve_code': 'run evolve_code to optimize a code string with evolve block markers and a custom evaluator', 'run_run_evolution': 'run run_evolution to evolve a program file using an evaluator file and LLM', 'run_run_evolution_string': 'run run_evolution with string inputs and a lambda evaluator for quick program evolution', 'test_library_api_integration': 'test the OpenEvolve library API integration with a real LLM server using pytest'}
```

## File: algorithmicsuperintelligence_openevolve/tests/integration/test_smoke.py

Prompts

```
['test that example config YAML files load into valid Config objects without errors', 'test that an evaluator module exposes a callable evaluate function via dynamic import', 'test that the evaluator can score an initial program and return a combined_score metric', 'test that the ProgramDatabase can store and retrieve Program objects by their unique id', 'test that all evaluator modules in the examples directory can be imported and have an evaluate function', 'run evolve_function to optimize a Python function using an LLM with test cases', 'run evolve_code to optimize a code string with evolve block markers and a custom evaluator', 'run run_evolution to evolve a program file using an evaluator file and LLM', 'run run_evolution with string inputs and a lambda evaluator for quick program evolution', 'test the OpenEvolve library API integration with a real LLM server using pytest', 'run an evolution loop on a Python program file with a custom evaluator function', 'test that the Config class has llm, database, evaluator, and prompt attributes', 'create an LLMModelConfig with name, api_key, api_base, weight, timeout, and retries', 'create an EvolutionResult with best_score, best_code, metrics, and output_dir', 'test that run_evolution raises ValueError when no LLM models are configured']
```

Usage

```
{'run_evolution': 'run an evolution loop on a Python program file with a custom evaluator function', 'test_config_validation': 'test that the Config class has llm, database, evaluator, and prompt attributes', 'create_llm_model_config': 'create an LLMModelConfig with name, api_key, api_base, weight, timeout, and retries', 'create_evolution_result': 'create an EvolutionResult with best_score, best_code, metrics, and output_dir', 'test_library_api_validation': 'test that run_evolution raises ValueError when no LLM models are configured'}
```

