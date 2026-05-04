# Agent Python Tools

- repo: algorithmicsuperintelligence/openevolve
- repo_uri: https://github.com/algorithmicsuperintelligence/openevolve

## File: algorithmicsuperintelligence_openevolve/examples/algotune/fft_convolution/best_program.py

Prompts

```
['run the FFT convolution solver on two signals with a specified mode like full, same, or valid', 'solve a convolution problem by passing signal_x, signal_y, and mode to the FFTConvolution solve method', 'validate a convolution solution against a scipy reference using the is_solution method with tolerance checks', 'compute the full FFT-based convolution of two signals returning output length len_x plus len_y minus one', 'compute the valid mode FFT convolution returning only the parts where both signals fully overlap', 'evaluate an evolved fft convolution program against the AlgoTune baseline and calculate speedup scores', 'run a function with a configurable timeout using concurrent futures ThreadPoolExecutor', 'calculate the speedup ratio between baseline and evolved solution execution times', 'run a stage 1 basic functionality check on an evolved program to verify it runs successfully', 'measure the baseline AlgoTune implementation performance with warmup runs and timing statistics']
```

Usage

```
{'run_fft_convolution_solver': 'run the FFT convolution solver on two signals with a specified mode like full, same, or valid', 'solve_convolution_problem': 'solve a convolution problem by passing signal_x, signal_y, and mode to the FFTConvolution solve method', 'validate_convolution_solution': 'validate a convolution solution against a scipy reference using the is_solution method with tolerance checks', 'compute_full_convolution': 'compute the full FFT-based convolution of two signals returning output length len_x plus len_y minus one', 'compute_valid_convolution': 'compute the valid mode FFT convolution returning only the parts where both signals fully overlap'}
```

## File: algorithmicsuperintelligence_openevolve/examples/algotune/fft_convolution/evaluator.py

Prompts

```
['run the FFT convolution solver on two signals with a specified mode like full, same, or valid', 'solve a convolution problem by passing signal_x, signal_y, and mode to the FFTConvolution solve method', 'validate a convolution solution against a scipy reference using the is_solution method with tolerance checks', 'compute the full FFT-based convolution of two signals returning output length len_x plus len_y minus one', 'compute the valid mode FFT convolution returning only the parts where both signals fully overlap', 'evaluate an evolved fft convolution program against the AlgoTune baseline and calculate speedup scores', 'run a function with a configurable timeout using concurrent futures ThreadPoolExecutor', 'calculate the speedup ratio between baseline and evolved solution execution times', 'run a stage 1 basic functionality check on an evolved program to verify it runs successfully', 'measure the baseline AlgoTune implementation performance with warmup runs and timing statistics']
```

Usage

```
{'evaluate_fft_convolution_program': 'evaluate an evolved fft convolution program against the AlgoTune baseline and calculate speedup scores', 'run_with_timeout': 'run a function with a configurable timeout using concurrent futures ThreadPoolExecutor', 'calculate_speedup': 'calculate the speedup ratio between baseline and evolved solution execution times', 'evaluate_stage1_basic_check': 'run a stage 1 basic functionality check on an evolved program to verify it runs successfully', 'measure_baseline_performance': 'measure the baseline AlgoTune implementation performance with warmup runs and timing statistics'}
```

## File: algorithmicsuperintelligence_openevolve/examples/algotune/fft_convolution/initial_program.py

Prompts

```
['run the FFT convolution solver on two signals with a specified mode like full, same, or valid', 'solve a convolution problem by passing signal_x, signal_y, and mode to the FFTConvolution solve method', 'validate a convolution solution against a scipy reference using the is_solution method with tolerance checks', 'compute the full FFT-based convolution of two signals returning output length len_x plus len_y minus one', 'compute the valid mode FFT convolution returning only the parts where both signals fully overlap', 'evaluate an evolved fft convolution program against the AlgoTune baseline and calculate speedup scores', 'run a function with a configurable timeout using concurrent futures ThreadPoolExecutor', 'calculate the speedup ratio between baseline and evolved solution execution times', 'run a stage 1 basic functionality check on an evolved program to verify it runs successfully', 'measure the baseline AlgoTune implementation performance with warmup runs and timing statistics']
```

Usage

```
{'run_fft_convolution_solver': 'run the FFT convolution solver on two signals with a specified mode', 'solve_convolution_problem': 'solve a convolution problem using FFT by passing signal_x, signal_y, and mode to FFTConvolution.solve', 'validate_convolution_solution': 'validate a convolution solution against a reference using FFTConvolution.is_solution with tolerance checks', 'compute_full_convolution': 'compute the full convolution of two signals using FFTConvolution.solve with mode set to full', 'compute_valid_convolution': 'compute the valid convolution of two signals using FFTConvolution.solve with mode set to valid'}
```

