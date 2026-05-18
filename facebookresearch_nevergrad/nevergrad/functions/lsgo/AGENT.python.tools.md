# Agent Python Tools

- repo: facebookresearch/nevergrad
- repo_uri: https://github.com/facebookresearch/nevergrad

## File: facebookresearch_nevergrad/nevergrad/functions/lsgo/_core.py

Prompts

```
['run the sphere benchmark function on a numpy array to compute sum of squared values', 'run the rosenbrock benchmark function on a numpy array to evaluate the classic optimization test', 'run the ackley benchmark function on a numpy array to evaluate a multimodal optimization test', 'create a random Rotation transformation matrix for a given dimension using QR decomposition', 'apply a list of callable transformations sequentially to a numpy array input', 'create an LSGO benchmark function by number from 1 to 15 using make_function', 'read LSGO coefficient data files from cdatafiles directory by function name using read_data', 'create an instrumented ExperimentFunction from an LsgoFunction with a bounding transform method', 'build a FunctionChunk that chains transforms then applies a weighted loss on input arrays', 'evaluate an LsgoFunction on an input array and get its optimization space dimension', 'test sphere, elliptic, ackley, schwefel, and rosenbrock benchmark functions with expected output values', 'test Asymmetry, Illconditionning, Translation, and Rotation transformation classes on numpy arrays', 'test the split function that partitions a permutation array into subarrays by dimensions and overlap', 'test the irregularity transformation function on a list of float values', 'review the parametrized test cases covering benchmark functions and transformation utilities', 'test ShiftedElliptic, ShiftedRastrigin, ShiftedAckley, ShiftedRosenbrock, and ShiftedSchwefel functions against expected values', 'test reading LSGO benchmark data files and verify matrix shapes and values', 'test all 15 LSGO functions evaluated on a zero vector with expected outputs', 'test all 15 LSGO functions evaluated on a ones vector with expected outputs', 'test make_function to create LSGO benchmark functions by number and verify dimension and optimum']
```

Usage

```
{'run_benchmark_function_sphere': 'run the sphere benchmark function on a numpy array to compute sum of squared values', 'run_benchmark_function_rosenbrock': 'run the rosenbrock benchmark function on a numpy array to evaluate the classic optimization test', 'run_benchmark_function_ackley': 'run the ackley benchmark function on a numpy array to evaluate a multimodal optimization test', 'create_rotation_from_random': 'create a random Rotation transformation matrix for a given dimension using QR decomposition', 'apply_transforms_pipeline': 'apply a list of callable transformations sequentially to a numpy array input'}
```

## File: facebookresearch_nevergrad/nevergrad/functions/lsgo/_funcs.py

Prompts

```
['run the sphere benchmark function on a numpy array to compute sum of squared values', 'run the rosenbrock benchmark function on a numpy array to evaluate the classic optimization test', 'run the ackley benchmark function on a numpy array to evaluate a multimodal optimization test', 'create a random Rotation transformation matrix for a given dimension using QR decomposition', 'apply a list of callable transformations sequentially to a numpy array input', 'create an LSGO benchmark function by number from 1 to 15 using make_function', 'read LSGO coefficient data files from cdatafiles directory by function name using read_data', 'create an instrumented ExperimentFunction from an LsgoFunction with a bounding transform method', 'build a FunctionChunk that chains transforms then applies a weighted loss on input arrays', 'evaluate an LsgoFunction on an input array and get its optimization space dimension', 'test sphere, elliptic, ackley, schwefel, and rosenbrock benchmark functions with expected output values', 'test Asymmetry, Illconditionning, Translation, and Rotation transformation classes on numpy arrays', 'test the split function that partitions a permutation array into subarrays by dimensions and overlap', 'test the irregularity transformation function on a list of float values', 'review the parametrized test cases covering benchmark functions and transformation utilities', 'test ShiftedElliptic, ShiftedRastrigin, ShiftedAckley, ShiftedRosenbrock, and ShiftedSchwefel functions against expected values', 'test reading LSGO benchmark data files and verify matrix shapes and values', 'test all 15 LSGO functions evaluated on a zero vector with expected outputs', 'test all 15 LSGO functions evaluated on a ones vector with expected outputs', 'test make_function to create LSGO benchmark functions by number and verify dimension and optimum']
```

Usage

```
{'make_function_LSGO': 'create an LSGO benchmark function by number from 1 to 15 using make_function', 'read_data_cdatafiles': 'read LSGO coefficient data files from cdatafiles directory by function name using read_data', 'instrumented_LsgoFunction': 'create an instrumented ExperimentFunction from an LsgoFunction with a bounding transform method', 'FunctionChunk_transforms_loss': 'build a FunctionChunk that chains transforms then applies a weighted loss on input arrays', 'LsgoFunction_call_dimension': 'evaluate an LsgoFunction on an input array and get its optimization space dimension'}
```

## File: facebookresearch_nevergrad/nevergrad/functions/lsgo/test_core.py

Prompts

```
['run the sphere benchmark function on a numpy array to compute sum of squared values', 'run the rosenbrock benchmark function on a numpy array to evaluate the classic optimization test', 'run the ackley benchmark function on a numpy array to evaluate a multimodal optimization test', 'create a random Rotation transformation matrix for a given dimension using QR decomposition', 'apply a list of callable transformations sequentially to a numpy array input', 'create an LSGO benchmark function by number from 1 to 15 using make_function', 'read LSGO coefficient data files from cdatafiles directory by function name using read_data', 'create an instrumented ExperimentFunction from an LsgoFunction with a bounding transform method', 'build a FunctionChunk that chains transforms then applies a weighted loss on input arrays', 'evaluate an LsgoFunction on an input array and get its optimization space dimension', 'test sphere, elliptic, ackley, schwefel, and rosenbrock benchmark functions with expected output values', 'test Asymmetry, Illconditionning, Translation, and Rotation transformation classes on numpy arrays', 'test the split function that partitions a permutation array into subarrays by dimensions and overlap', 'test the irregularity transformation function on a list of float values', 'review the parametrized test cases covering benchmark functions and transformation utilities', 'test ShiftedElliptic, ShiftedRastrigin, ShiftedAckley, ShiftedRosenbrock, and ShiftedSchwefel functions against expected values', 'test reading LSGO benchmark data files and verify matrix shapes and values', 'test all 15 LSGO functions evaluated on a zero vector with expected outputs', 'test all 15 LSGO functions evaluated on a ones vector with expected outputs', 'test make_function to create LSGO benchmark functions by number and verify dimension and optimum']
```

Usage

```
{'test_benchmark_functions': 'test sphere, elliptic, ackley, schwefel, and rosenbrock benchmark functions with expected output values', 'test_transform_classes': 'test Asymmetry, Illconditionning, Translation, and Rotation transformation classes on numpy arrays', 'test_split_function': 'test the split function that partitions a permutation array into subarrays by dimensions and overlap', 'test_irregularity_transform': 'test the irregularity transformation function on a list of float values', 'review_core_test_coverage': 'review the parametrized test cases covering benchmark functions and transformation utilities'}
```

## File: facebookresearch_nevergrad/nevergrad/functions/lsgo/test_funcs.py

Prompts

```
['run the sphere benchmark function on a numpy array to compute sum of squared values', 'run the rosenbrock benchmark function on a numpy array to evaluate the classic optimization test', 'run the ackley benchmark function on a numpy array to evaluate a multimodal optimization test', 'create a random Rotation transformation matrix for a given dimension using QR decomposition', 'apply a list of callable transformations sequentially to a numpy array input', 'create an LSGO benchmark function by number from 1 to 15 using make_function', 'read LSGO coefficient data files from cdatafiles directory by function name using read_data', 'create an instrumented ExperimentFunction from an LsgoFunction with a bounding transform method', 'build a FunctionChunk that chains transforms then applies a weighted loss on input arrays', 'evaluate an LsgoFunction on an input array and get its optimization space dimension', 'test sphere, elliptic, ackley, schwefel, and rosenbrock benchmark functions with expected output values', 'test Asymmetry, Illconditionning, Translation, and Rotation transformation classes on numpy arrays', 'test the split function that partitions a permutation array into subarrays by dimensions and overlap', 'test the irregularity transformation function on a list of float values', 'review the parametrized test cases covering benchmark functions and transformation utilities', 'test ShiftedElliptic, ShiftedRastrigin, ShiftedAckley, ShiftedRosenbrock, and ShiftedSchwefel functions against expected values', 'test reading LSGO benchmark data files and verify matrix shapes and values', 'test all 15 LSGO functions evaluated on a zero vector with expected outputs', 'test all 15 LSGO functions evaluated on a ones vector with expected outputs', 'test make_function to create LSGO benchmark functions by number and verify dimension and optimum']
```

Usage

```
{'test_shifted_benchmark_functions': 'test ShiftedElliptic, ShiftedRastrigin, ShiftedAckley, ShiftedRosenbrock, and ShiftedSchwefel functions against expected values', 'test_read_data': 'test reading LSGO benchmark data files and verify matrix shapes and values', 'test_functions_zeros': 'test all 15 LSGO functions evaluated on a zero vector with expected outputs', 'test_functions_ones': 'test all 15 LSGO functions evaluated on a ones vector with expected outputs', 'test_make_function': 'test make_function to create LSGO benchmark functions by number and verify dimension and optimum'}
```

