# Agent Python Tools

- repo: algorithmicsuperintelligence/openevolve
- repo_uri: https://github.com/algorithmicsuperintelligence/openevolve

## File: algorithmicsuperintelligence_openevolve/examples/algotune/fft_cmplx_scipy_fftpack/best_program.py

Prompts

```
['run the FFT solver on a complex-valued matrix using run_solver', 'compute the N-dimensional FFT of a complex matrix with FFTComplexScipyFFTpack.solve', 'validate an FFT solution against numpy reference using FFTComplexScipyFFTpack.is_solution', 'review the FFTComplexScipyFFTpack class and its solve and is_solution methods', 'summarize the JIT-compiled JAX FFT function _jit_fftn and its usage', 'run the evaluator to compare an evolved FFT solution against the AlgoTune baseline and measure speedup', 'run the first stage evaluation to check if an evolved program has basic functionality and runs without errors', 'run the second stage evaluation to perform thorough baseline comparison testing on an evolved program', 'calculate the speedup ratio between a baseline implementation time and an evolved solution time in milliseconds', 'run any function with a configurable timeout using a thread pool executor and raise TimeoutError on expiry', 'solve an N-dimensional FFT problem on a complex matrix using FFTComplexScipyFFTpack.solve', 'refactor FFTComplexScipyFFTpack.solve to use a faster FFT backend like pyfftw or JAX']
```

Usage

```
{'run_fft_solver': 'run the FFT solver on a complex-valued matrix using run_solver', 'solve_fft_complex': 'compute the N-dimensional FFT of a complex matrix with FFTComplexScipyFFTpack.solve', 'validate_fft_solution': 'validate an FFT solution against numpy reference using FFTComplexScipyFFTpack.is_solution', 'review_fft_class': 'review the FFTComplexScipyFFTpack class and its solve and is_solution methods', 'summarize_jit_fftn': 'summarize the JIT-compiled JAX FFT function _jit_fftn and its usage'}
```

## File: algorithmicsuperintelligence_openevolve/examples/algotune/fft_cmplx_scipy_fftpack/evaluator.py

Prompts

```
['run the FFT solver on a complex-valued matrix using run_solver', 'compute the N-dimensional FFT of a complex matrix with FFTComplexScipyFFTpack.solve', 'validate an FFT solution against numpy reference using FFTComplexScipyFFTpack.is_solution', 'review the FFTComplexScipyFFTpack class and its solve and is_solution methods', 'summarize the JIT-compiled JAX FFT function _jit_fftn and its usage', 'run the evaluator to compare an evolved FFT solution against the AlgoTune baseline and measure speedup', 'run the first stage evaluation to check if an evolved program has basic functionality and runs without errors', 'run the second stage evaluation to perform thorough baseline comparison testing on an evolved program', 'calculate the speedup ratio between a baseline implementation time and an evolved solution time in milliseconds', 'run any function with a configurable timeout using a thread pool executor and raise TimeoutError on expiry', 'solve an N-dimensional FFT problem on a complex matrix using FFTComplexScipyFFTpack.solve', 'refactor FFTComplexScipyFFTpack.solve to use a faster FFT backend like pyfftw or JAX']
```

Usage

```
{'evaluate_evolved_program': 'run the evaluator to compare an evolved FFT solution against the AlgoTune baseline and measure speedup', 'evaluate_stage1_basic_check': 'run the first stage evaluation to check if an evolved program has basic functionality and runs without errors', 'evaluate_stage2_full_test': 'run the second stage evaluation to perform thorough baseline comparison testing on an evolved program', 'calculate_speedup_ratio': 'calculate the speedup ratio between a baseline implementation time and an evolved solution time in milliseconds', 'run_function_with_timeout': 'run any function with a configurable timeout using a thread pool executor and raise TimeoutError on expiry'}
```

## File: algorithmicsuperintelligence_openevolve/examples/algotune/fft_cmplx_scipy_fftpack/initial_program.py

Prompts

```
['run the FFT solver on a complex-valued matrix using run_solver', 'compute the N-dimensional FFT of a complex matrix with FFTComplexScipyFFTpack.solve', 'validate an FFT solution against numpy reference using FFTComplexScipyFFTpack.is_solution', 'review the FFTComplexScipyFFTpack class and its solve and is_solution methods', 'summarize the JIT-compiled JAX FFT function _jit_fftn and its usage', 'run the evaluator to compare an evolved FFT solution against the AlgoTune baseline and measure speedup', 'run the first stage evaluation to check if an evolved program has basic functionality and runs without errors', 'run the second stage evaluation to perform thorough baseline comparison testing on an evolved program', 'calculate the speedup ratio between a baseline implementation time and an evolved solution time in milliseconds', 'run any function with a configurable timeout using a thread pool executor and raise TimeoutError on expiry', 'solve an N-dimensional FFT problem on a complex matrix using FFTComplexScipyFFTpack.solve', 'refactor FFTComplexScipyFFTpack.solve to use a faster FFT backend like pyfftw or JAX']
```

Usage

```
{'run_fft_solver': 'run the FFT solver on a complex-valued matrix using run_solver', 'solve_fft_problem': 'solve an N-dimensional FFT problem on a complex matrix using FFTComplexScipyFFTpack.solve', 'validate_fft_solution': 'validate an FFT solution against numpy reference using FFTComplexScipyFFTpack.is_solution', 'review_fft_class': 'review the FFTComplexScipyFFTpack class and its solve and is_solution methods', 'refactor_fft_solve': 'refactor FFTComplexScipyFFTpack.solve to use a faster FFT backend like pyfftw or JAX'}
```

