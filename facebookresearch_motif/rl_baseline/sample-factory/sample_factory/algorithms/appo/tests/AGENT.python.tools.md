# Agent Python Tools

- repo: facebookresearch/motif
- repo_uri: https://github.com/facebookresearch/motif

## File: facebookresearch_motif/rl_baseline/sample-factory/sample_factory/algorithms/appo/tests/test_model.py

Prompts

```
['run a forward pass through the APPO actor-critic model on CPU or GPU with timing', 'test the APPO actor-critic model forward pass on CPU device', 'test the APPO actor-critic model forward pass on GPU device if CUDA available', 'create an APPO actor-critic model from config and environment observation and action spaces', 'review the TestModel class and its forward pass test methods for APPO model testing', 'test the build_rnn_inputs function with random dones and GRU packed sequences', 'test the build_core_out_from_seq function to reconstruct RNN output from packed sequences', 'test that packed RNN output matches the loop-based RNN implementation across 100 iterations', 'test the full RNN packed sequence test with T=37 N=64 D=42 dimensions', 'test the trivial RNN packed sequence test with T=5 N=1 D=1 dimensions']
```

Usage

```
{'run_forward_pass': 'run a forward pass through the APPO actor-critic model on CPU or GPU with timing', 'test_forward_pass_cpu': 'test the APPO actor-critic model forward pass on CPU device', 'test_forward_pass_gpu': 'test the APPO actor-critic model forward pass on GPU device if CUDA available', 'create_actor_critic': 'create an APPO actor-critic model from config and environment observation and action spaces', 'review_TestModel': 'review the TestModel class and its forward pass test methods for APPO model testing'}
```

## File: facebookresearch_motif/rl_baseline/sample-factory/sample_factory/algorithms/appo/tests/test_rnn.py

Prompts

```
['run a forward pass through the APPO actor-critic model on CPU or GPU with timing', 'test the APPO actor-critic model forward pass on CPU device', 'test the APPO actor-critic model forward pass on GPU device if CUDA available', 'create an APPO actor-critic model from config and environment observation and action spaces', 'review the TestModel class and its forward pass test methods for APPO model testing', 'test the build_rnn_inputs function with random dones and GRU packed sequences', 'test the build_core_out_from_seq function to reconstruct RNN output from packed sequences', 'test that packed RNN output matches the loop-based RNN implementation across 100 iterations', 'test the full RNN packed sequence test with T=37 N=64 D=42 dimensions', 'test the trivial RNN packed sequence test with T=5 N=1 D=1 dimensions']
```

Usage

```
{'test_build_rnn_inputs': 'test the build_rnn_inputs function with random dones and GRU packed sequences', 'test_build_core_out_from_seq': 'test the build_core_out_from_seq function to reconstruct RNN output from packed sequences', 'test_check_packed_version_matching_loopy_version': 'test that packed RNN output matches the loop-based RNN implementation across 100 iterations', 'test_test_full': 'test the full RNN packed sequence test with T=37 N=64 D=42 dimensions', 'test_test_trivial': 'test the trivial RNN packed sequence test with T=5 N=1 D=1 dimensions'}
```

