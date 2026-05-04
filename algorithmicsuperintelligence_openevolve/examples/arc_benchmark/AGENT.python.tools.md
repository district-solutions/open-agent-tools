# Agent Python Tools

- repo: algorithmicsuperintelligence/openevolve
- repo_uri: https://github.com/algorithmicsuperintelligence/openevolve

## File: algorithmicsuperintelligence_openevolve/examples/arc_benchmark/evaluator.py

Prompts

```
['run the evaluate function to score an ARC program against training challenges using pass at 2 accuracy', 'compute pass at 2 accuracy for a single ARC test case by comparing two attempts against ground truth', 'compute pass at 2 accuracy across multiple ARC test cases and collect diagnostics for each', 'extract failure artifacts from diagnostics to identify size mismatches or incorrect cells in model attempts', 'review the pass at 2 diagnostics to find incorrect cell indices and perfect match status per attempt', 'generate a config.yaml file from an ARC benchmark task by loading base_config.yaml and injecting the task prompt', 'load an ARC challenge task from a JSON file and format it as a puzzle-solving prompt string', 'run the script to generate a config.yaml for a given ARC task using ARC_TASK_FILE and TASK_NUM env vars', 'review the load_task_as_prompt function to understand how it extracts train and test grids from an ARC task JSON', 'refactor generate_config to accept a custom output path instead of hardcoding config.yaml', 'run transform_grid_attempt_1 to rotate a 2D grid 90 degrees clockwise and increment each cell by 1 modulo 10', 'run transform_grid_attempt_2 to upsample a 2D grid into 2x2 blocks and invert colors by mapping v to 9 minus v', 'test _validate_grid to verify a 2D array contains only integer values in the range 0 to 9', 'refactor transform_grid_attempt_1 to apply a different rotation angle or arithmetic operation on grid cells', 'refactor transform_grid_attempt_2 to use a different upsample factor or color transformation formula', 'run the post evolution evaluation on the best program against ARC benchmark test tasks', 'load the best_program.py module dynamically from the outputs directory', 'review the evaluate function that validates transform_grid_attempt_1 and transform_grid_attempt_2', 'test the pass at 2 accuracy of two transform attempts against ARC ground truth solutions', 'summarize the evaluation metrics and failure artifacts from the ARC benchmark run']
```

Usage

```
{'evaluate_arc_program': 'run the evaluate function to score an ARC program against training challenges using pass at 2 accuracy', 'compute_pass_at_2_single': 'compute pass at 2 accuracy for a single ARC test case by comparing two attempts against ground truth', 'compute_pass_at_2_multi': 'compute pass at 2 accuracy across multiple ARC test cases and collect diagnostics for each', 'extract_failure_artifacts': 'extract failure artifacts from diagnostics to identify size mismatches or incorrect cells in model attempts', 'review_pass_at_2_diagnostics': 'review the pass at 2 diagnostics to find incorrect cell indices and perfect match status per attempt'}
```

## File: algorithmicsuperintelligence_openevolve/examples/arc_benchmark/generate_config.py

Prompts

```
['run the evaluate function to score an ARC program against training challenges using pass at 2 accuracy', 'compute pass at 2 accuracy for a single ARC test case by comparing two attempts against ground truth', 'compute pass at 2 accuracy across multiple ARC test cases and collect diagnostics for each', 'extract failure artifacts from diagnostics to identify size mismatches or incorrect cells in model attempts', 'review the pass at 2 diagnostics to find incorrect cell indices and perfect match status per attempt', 'generate a config.yaml file from an ARC benchmark task by loading base_config.yaml and injecting the task prompt', 'load an ARC challenge task from a JSON file and format it as a puzzle-solving prompt string', 'run the script to generate a config.yaml for a given ARC task using ARC_TASK_FILE and TASK_NUM env vars', 'review the load_task_as_prompt function to understand how it extracts train and test grids from an ARC task JSON', 'refactor generate_config to accept a custom output path instead of hardcoding config.yaml', 'run transform_grid_attempt_1 to rotate a 2D grid 90 degrees clockwise and increment each cell by 1 modulo 10', 'run transform_grid_attempt_2 to upsample a 2D grid into 2x2 blocks and invert colors by mapping v to 9 minus v', 'test _validate_grid to verify a 2D array contains only integer values in the range 0 to 9', 'refactor transform_grid_attempt_1 to apply a different rotation angle or arithmetic operation on grid cells', 'refactor transform_grid_attempt_2 to use a different upsample factor or color transformation formula', 'run the post evolution evaluation on the best program against ARC benchmark test tasks', 'load the best_program.py module dynamically from the outputs directory', 'review the evaluate function that validates transform_grid_attempt_1 and transform_grid_attempt_2', 'test the pass at 2 accuracy of two transform attempts against ARC ground truth solutions', 'summarize the evaluation metrics and failure artifacts from the ARC benchmark run']
```

Usage

```
{'generate_config_yaml': 'generate a config.yaml file from an ARC benchmark task by loading base_config.yaml and injecting the task prompt', 'load_task_as_prompt': 'load an ARC challenge task from a JSON file and format it as a puzzle-solving prompt string', 'run_arc_config_gen': 'run the script to generate a config.yaml for a given ARC task using ARC_TASK_FILE and TASK_NUM env vars', 'review_load_task_as_prompt': 'review the load_task_as_prompt function to understand how it extracts train and test grids from an ARC task JSON', 'refactor_generate_config': 'refactor generate_config to accept a custom output path instead of hardcoding config.yaml'}
```

## File: algorithmicsuperintelligence_openevolve/examples/arc_benchmark/initial_program.py

Prompts

```
['run the evaluate function to score an ARC program against training challenges using pass at 2 accuracy', 'compute pass at 2 accuracy for a single ARC test case by comparing two attempts against ground truth', 'compute pass at 2 accuracy across multiple ARC test cases and collect diagnostics for each', 'extract failure artifacts from diagnostics to identify size mismatches or incorrect cells in model attempts', 'review the pass at 2 diagnostics to find incorrect cell indices and perfect match status per attempt', 'generate a config.yaml file from an ARC benchmark task by loading base_config.yaml and injecting the task prompt', 'load an ARC challenge task from a JSON file and format it as a puzzle-solving prompt string', 'run the script to generate a config.yaml for a given ARC task using ARC_TASK_FILE and TASK_NUM env vars', 'review the load_task_as_prompt function to understand how it extracts train and test grids from an ARC task JSON', 'refactor generate_config to accept a custom output path instead of hardcoding config.yaml', 'run transform_grid_attempt_1 to rotate a 2D grid 90 degrees clockwise and increment each cell by 1 modulo 10', 'run transform_grid_attempt_2 to upsample a 2D grid into 2x2 blocks and invert colors by mapping v to 9 minus v', 'test _validate_grid to verify a 2D array contains only integer values in the range 0 to 9', 'refactor transform_grid_attempt_1 to apply a different rotation angle or arithmetic operation on grid cells', 'refactor transform_grid_attempt_2 to use a different upsample factor or color transformation formula', 'run the post evolution evaluation on the best program against ARC benchmark test tasks', 'load the best_program.py module dynamically from the outputs directory', 'review the evaluate function that validates transform_grid_attempt_1 and transform_grid_attempt_2', 'test the pass at 2 accuracy of two transform attempts against ARC ground truth solutions', 'summarize the evaluation metrics and failure artifacts from the ARC benchmark run']
```

Usage

```
{'run_transform_grid_attempt_1': 'run transform_grid_attempt_1 to rotate a 2D grid 90 degrees clockwise and increment each cell by 1 modulo 10', 'run_transform_grid_attempt_2': 'run transform_grid_attempt_2 to upsample a 2D grid into 2x2 blocks and invert colors by mapping v to 9 minus v', 'test_validate_grid': 'test _validate_grid to verify a 2D array contains only integer values in the range 0 to 9', 'refactor_transform_grid_attempt_1': 'refactor transform_grid_attempt_1 to apply a different rotation angle or arithmetic operation on grid cells', 'refactor_transform_grid_attempt_2': 'refactor transform_grid_attempt_2 to use a different upsample factor or color transformation formula'}
```

## File: algorithmicsuperintelligence_openevolve/examples/arc_benchmark/post_evolution_eval.py

Prompts

```
['run the evaluate function to score an ARC program against training challenges using pass at 2 accuracy', 'compute pass at 2 accuracy for a single ARC test case by comparing two attempts against ground truth', 'compute pass at 2 accuracy across multiple ARC test cases and collect diagnostics for each', 'extract failure artifacts from diagnostics to identify size mismatches or incorrect cells in model attempts', 'review the pass at 2 diagnostics to find incorrect cell indices and perfect match status per attempt', 'generate a config.yaml file from an ARC benchmark task by loading base_config.yaml and injecting the task prompt', 'load an ARC challenge task from a JSON file and format it as a puzzle-solving prompt string', 'run the script to generate a config.yaml for a given ARC task using ARC_TASK_FILE and TASK_NUM env vars', 'review the load_task_as_prompt function to understand how it extracts train and test grids from an ARC task JSON', 'refactor generate_config to accept a custom output path instead of hardcoding config.yaml', 'run transform_grid_attempt_1 to rotate a 2D grid 90 degrees clockwise and increment each cell by 1 modulo 10', 'run transform_grid_attempt_2 to upsample a 2D grid into 2x2 blocks and invert colors by mapping v to 9 minus v', 'test _validate_grid to verify a 2D array contains only integer values in the range 0 to 9', 'refactor transform_grid_attempt_1 to apply a different rotation angle or arithmetic operation on grid cells', 'refactor transform_grid_attempt_2 to use a different upsample factor or color transformation formula', 'run the post evolution evaluation on the best program against ARC benchmark test tasks', 'load the best_program.py module dynamically from the outputs directory', 'review the evaluate function that validates transform_grid_attempt_1 and transform_grid_attempt_2', 'test the pass at 2 accuracy of two transform attempts against ARC ground truth solutions', 'summarize the evaluation metrics and failure artifacts from the ARC benchmark run']
```

Usage

```
{'run_evaluate_arc_program': 'run the post evolution evaluation on the best program against ARC benchmark test tasks', 'run_load_program_module': 'load the best_program.py module dynamically from the outputs directory', 'review_evaluate_function': 'review the evaluate function that validates transform_grid_attempt_1 and transform_grid_attempt_2', 'test_pass_at_2_accuracy': 'test the pass at 2 accuracy of two transform attempts against ARC ground truth solutions', 'summarize_evaluation_result': 'summarize the evaluation metrics and failure artifacts from the ARC benchmark run'}
```

