# Agent Python Tools

- repo: facebookresearch/compilergym
- repo_uri: https://github.com/facebookresearch/compilergym

## File: facebookresearch_compilergym/examples/sensitivity_analysis/action_sensitivity_analysis.py

Prompts

```
['run action sensitivity analysis to estimate immediate reward of compiler optimization passes using random trials', 'run a single trial with random warmup steps then compute the immediate reward of a given compiler action', 'get rewards and runtimes for a specific compiler action by running multiple random trials with warmup steps', 'run the main entry point to evaluate immediate reward of all or selected LLVM compiler actions via CLI flags', 'review the run_action_sensitivity_analysis function to understand how ThreadPoolExecutor parallelizes sensitivity analysis across multiple actions', 'test the action sensitivity analysis by running trials on llvm-v0 with specified actions and benchmarks', 'run evaluation on sensitivity analysis results using rewards and runtimes output files', 'review the test function that validates action sensitivity analysis output files are created correctly', 'summarize the end-to-end test that runs action sensitivity analysis and evaluates results', 'run benchmark sensitivity analysis on a list of benchmarks with random walk trials and save results to CSV', 'run the benchmark sensitivity analysis CLI tool with flags for environment, reward, and benchmark selection', 'review the run_benchmark_sensitivity_analysis function that uses ThreadPoolExecutor to parallelize sensitivity analysis across benchmarks', 'test the end-to-end benchmark sensitivity analysis pipeline with a temporary directory and assertions', 'review the test function that validates benchmark sensitivity analysis output files are created correctly', 'summarize the test function that runs sensitivity analysis on llvm-v0 with IrInstructionCountO3 reward', 'run concurrent sensitivity analysis futures and write reward and runtime results to CSV files', 'create a SensitivityAnalysisResult named tuple with a name, runtimes array, and rewards array', 'review the run_sensitivity_analysis_eval function that parses CSV logs and prints a tabulated summary with mean, median, max, and std', 'review the main entry point that reads output_dir and analysis flags and evaluates sensitivity analysis CSV logs']
```

Usage

```
{'run_action_sensitivity_analysis': 'run action sensitivity analysis to estimate immediate reward of compiler optimization passes using random trials', 'run_one_trial': 'run a single trial with random warmup steps then compute the immediate reward of a given compiler action', 'get_rewards': 'get rewards and runtimes for a specific compiler action by running multiple random trials with warmup steps', 'run_main_entry': 'run the main entry point to evaluate immediate reward of all or selected LLVM compiler actions via CLI flags', 'review_run_action_sensitivity_analysis': 'review the run_action_sensitivity_analysis function to understand how ThreadPoolExecutor parallelizes sensitivity analysis across multiple actions'}
```

## File: facebookresearch_compilergym/examples/sensitivity_analysis/action_sensitivity_analysis_test.py

Prompts

```
['run action sensitivity analysis to estimate immediate reward of compiler optimization passes using random trials', 'run a single trial with random warmup steps then compute the immediate reward of a given compiler action', 'get rewards and runtimes for a specific compiler action by running multiple random trials with warmup steps', 'run the main entry point to evaluate immediate reward of all or selected LLVM compiler actions via CLI flags', 'review the run_action_sensitivity_analysis function to understand how ThreadPoolExecutor parallelizes sensitivity analysis across multiple actions', 'test the action sensitivity analysis by running trials on llvm-v0 with specified actions and benchmarks', 'run evaluation on sensitivity analysis results using rewards and runtimes output files', 'review the test function that validates action sensitivity analysis output files are created correctly', 'summarize the end-to-end test that runs action sensitivity analysis and evaluates results', 'run benchmark sensitivity analysis on a list of benchmarks with random walk trials and save results to CSV', 'run the benchmark sensitivity analysis CLI tool with flags for environment, reward, and benchmark selection', 'review the run_benchmark_sensitivity_analysis function that uses ThreadPoolExecutor to parallelize sensitivity analysis across benchmarks', 'test the end-to-end benchmark sensitivity analysis pipeline with a temporary directory and assertions', 'review the test function that validates benchmark sensitivity analysis output files are created correctly', 'summarize the test function that runs sensitivity analysis on llvm-v0 with IrInstructionCountO3 reward', 'run concurrent sensitivity analysis futures and write reward and runtime results to CSV files', 'create a SensitivityAnalysisResult named tuple with a name, runtimes array, and rewards array', 'review the run_sensitivity_analysis_eval function that parses CSV logs and prints a tabulated summary with mean, median, max, and std', 'review the main entry point that reads output_dir and analysis flags and evaluates sensitivity analysis CSV logs']
```

Usage

```
{'test_run_action_sensitivity_analysis': 'test the action sensitivity analysis by running trials on llvm-v0 with specified actions and benchmarks', 'run_action_sensitivity_analysis': 'run an action sensitivity analysis with specified actions, reward space, number of trials, and warmup steps', 'run_sensitivity_analysis_eval': 'run evaluation on sensitivity analysis results using rewards and runtimes output files', 'review_test_run_action_sensitivity_analysis': 'review the test function that validates action sensitivity analysis output files are created correctly', 'summarize_test_run_action_sensitivity_analysis': 'summarize the end-to-end test that runs action sensitivity analysis and evaluates results'}
```

## File: facebookresearch_compilergym/examples/sensitivity_analysis/benchmark_sensitivity_analysis.py

Prompts

```
['run action sensitivity analysis to estimate immediate reward of compiler optimization passes using random trials', 'run a single trial with random warmup steps then compute the immediate reward of a given compiler action', 'get rewards and runtimes for a specific compiler action by running multiple random trials with warmup steps', 'run the main entry point to evaluate immediate reward of all or selected LLVM compiler actions via CLI flags', 'review the run_action_sensitivity_analysis function to understand how ThreadPoolExecutor parallelizes sensitivity analysis across multiple actions', 'test the action sensitivity analysis by running trials on llvm-v0 with specified actions and benchmarks', 'run evaluation on sensitivity analysis results using rewards and runtimes output files', 'review the test function that validates action sensitivity analysis output files are created correctly', 'summarize the end-to-end test that runs action sensitivity analysis and evaluates results', 'run benchmark sensitivity analysis on a list of benchmarks with random walk trials and save results to CSV', 'run the benchmark sensitivity analysis CLI tool with flags for environment, reward, and benchmark selection', 'review the run_benchmark_sensitivity_analysis function that uses ThreadPoolExecutor to parallelize sensitivity analysis across benchmarks', 'test the end-to-end benchmark sensitivity analysis pipeline with a temporary directory and assertions', 'review the test function that validates benchmark sensitivity analysis output files are created correctly', 'summarize the test function that runs sensitivity analysis on llvm-v0 with IrInstructionCountO3 reward', 'run concurrent sensitivity analysis futures and write reward and runtime results to CSV files', 'create a SensitivityAnalysisResult named tuple with a name, runtimes array, and rewards array', 'review the run_sensitivity_analysis_eval function that parses CSV logs and prints a tabulated summary with mean, median, max, and std', 'review the main entry point that reads output_dir and analysis flags and evaluates sensitivity analysis CSV logs']
```

Usage

```
{'run_benchmark_sensitivity_analysis': 'run benchmark sensitivity analysis on a list of benchmarks with random walk trials and save results to CSV', 'run_one_trial': 'run a single random trial on a CompilerEnv and return the cumulative episode reward', 'get_rewards': 'get episode rewards for a benchmark by running multiple random trials with configurable step bounds', 'main_entry': 'run the benchmark sensitivity analysis CLI tool with flags for environment, reward, and benchmark selection', 'review_run_benchmark_sensitivity_analysis': 'review the run_benchmark_sensitivity_analysis function that uses ThreadPoolExecutor to parallelize sensitivity analysis across benchmarks'}
```

## File: facebookresearch_compilergym/examples/sensitivity_analysis/benchmark_sensitivity_analysis_test.py

Prompts

```
['run action sensitivity analysis to estimate immediate reward of compiler optimization passes using random trials', 'run a single trial with random warmup steps then compute the immediate reward of a given compiler action', 'get rewards and runtimes for a specific compiler action by running multiple random trials with warmup steps', 'run the main entry point to evaluate immediate reward of all or selected LLVM compiler actions via CLI flags', 'review the run_action_sensitivity_analysis function to understand how ThreadPoolExecutor parallelizes sensitivity analysis across multiple actions', 'test the action sensitivity analysis by running trials on llvm-v0 with specified actions and benchmarks', 'run evaluation on sensitivity analysis results using rewards and runtimes output files', 'review the test function that validates action sensitivity analysis output files are created correctly', 'summarize the end-to-end test that runs action sensitivity analysis and evaluates results', 'run benchmark sensitivity analysis on a list of benchmarks with random walk trials and save results to CSV', 'run the benchmark sensitivity analysis CLI tool with flags for environment, reward, and benchmark selection', 'review the run_benchmark_sensitivity_analysis function that uses ThreadPoolExecutor to parallelize sensitivity analysis across benchmarks', 'test the end-to-end benchmark sensitivity analysis pipeline with a temporary directory and assertions', 'review the test function that validates benchmark sensitivity analysis output files are created correctly', 'summarize the test function that runs sensitivity analysis on llvm-v0 with IrInstructionCountO3 reward', 'run concurrent sensitivity analysis futures and write reward and runtime results to CSV files', 'create a SensitivityAnalysisResult named tuple with a name, runtimes array, and rewards array', 'review the run_sensitivity_analysis_eval function that parses CSV logs and prints a tabulated summary with mean, median, max, and std', 'review the main entry point that reads output_dir and analysis flags and evaluates sensitivity analysis CSV logs']
```

Usage

```
{'run_benchmark_sensitivity_analysis': 'run benchmark sensitivity analysis on CompilerGym benchmarks with configurable trials, steps, and rewards', 'run_sensitivity_analysis_eval': 'run sensitivity analysis evaluation on collected rewards and runtimes data files', 'test_run_benchmark_sensitivity_analysis': 'test the end-to-end benchmark sensitivity analysis pipeline with a temporary directory and assertions', 'review_test_run_benchmark_sensitivity_analysis': 'review the test function that validates benchmark sensitivity analysis output files are created correctly', 'summarize_test_run_benchmark_sensitivity_analysis': 'summarize the test function that runs sensitivity analysis on llvm-v0 with IrInstructionCountO3 reward'}
```

## File: facebookresearch_compilergym/examples/sensitivity_analysis/sensitivity_analysis_eval.py

Prompts

```
['run action sensitivity analysis to estimate immediate reward of compiler optimization passes using random trials', 'run a single trial with random warmup steps then compute the immediate reward of a given compiler action', 'get rewards and runtimes for a specific compiler action by running multiple random trials with warmup steps', 'run the main entry point to evaluate immediate reward of all or selected LLVM compiler actions via CLI flags', 'review the run_action_sensitivity_analysis function to understand how ThreadPoolExecutor parallelizes sensitivity analysis across multiple actions', 'test the action sensitivity analysis by running trials on llvm-v0 with specified actions and benchmarks', 'run evaluation on sensitivity analysis results using rewards and runtimes output files', 'review the test function that validates action sensitivity analysis output files are created correctly', 'summarize the end-to-end test that runs action sensitivity analysis and evaluates results', 'run benchmark sensitivity analysis on a list of benchmarks with random walk trials and save results to CSV', 'run the benchmark sensitivity analysis CLI tool with flags for environment, reward, and benchmark selection', 'review the run_benchmark_sensitivity_analysis function that uses ThreadPoolExecutor to parallelize sensitivity analysis across benchmarks', 'test the end-to-end benchmark sensitivity analysis pipeline with a temporary directory and assertions', 'review the test function that validates benchmark sensitivity analysis output files are created correctly', 'summarize the test function that runs sensitivity analysis on llvm-v0 with IrInstructionCountO3 reward', 'run concurrent sensitivity analysis futures and write reward and runtime results to CSV files', 'create a SensitivityAnalysisResult named tuple with a name, runtimes array, and rewards array', 'review the run_sensitivity_analysis_eval function that parses CSV logs and prints a tabulated summary with mean, median, max, and std', 'review the main entry point that reads output_dir and analysis flags and evaluates sensitivity analysis CSV logs']
```

Usage

```
{'run_sensitivity_analysis_eval': 'run the sensitivity analysis evaluation tool to print a summary table of rewards and runtimes from CSV logs', 'run_sensitivity_analysis': 'run concurrent sensitivity analysis futures and write reward and runtime results to CSV files', 'create_SensitivityAnalysisResult': 'create a SensitivityAnalysisResult named tuple with a name, runtimes array, and rewards array', 'review_run_sensitivity_analysis_eval': 'review the run_sensitivity_analysis_eval function that parses CSV logs and prints a tabulated summary with mean, median, max, and std', 'review_main_entry': 'review the main entry point that reads output_dir and analysis flags and evaluates sensitivity analysis CSV logs'}
```

