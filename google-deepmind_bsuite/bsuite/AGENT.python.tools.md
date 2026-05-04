# Agent Python Tools

- repo: google-deepmind/bsuite
- repo_uri: https://github.com/google-deepmind/bsuite

## File: google-deepmind_bsuite/bsuite/bsuite.py

Prompts

```
['load a bsuite environment by its bsuite_id like catch/0 using load_from_id', 'load a bsuite environment by experiment name and kwargs using the load function', 'load a bsuite environment and record results to CSV files in a directory', 'load a bsuite environment and log results directly to the terminal', 'unpack a bsuite_id string into its experiment name and setting index tuple', 'test that sweep BANDIT SWEEP and TESTING collections contain expected bsuite experiment IDs', 'test that sweep BANDIT SWEEP TESTING and TAGS are immutable and reject assignment', 'review the SweepTest class and its test_sweep_contents and test_sweep_immutable methods', 'run the SweepTest test class using absltest to verify sweep module correctness', 'summarize the SweepTest class which validates bsuite sweep collection contents and immutability']
```

Usage

```
{'load_bsuite_environment_from_id': 'load a bsuite environment by its bsuite_id like catch/0 using load_from_id', 'load_bsuite_environment_by_name': 'load a bsuite environment by experiment name and kwargs using the load function', 'load_and_record_to_csv': 'load a bsuite environment and record results to CSV files in a directory', 'load_and_record_to_terminal': 'load a bsuite environment and log results directly to the terminal', 'unpack_bsuite_id': 'unpack a bsuite_id string into its experiment name and setting index tuple'}
```

## File: google-deepmind_bsuite/bsuite/sweep_test.py

Prompts

```
['load a bsuite environment by its bsuite_id like catch/0 using load_from_id', 'load a bsuite environment by experiment name and kwargs using the load function', 'load a bsuite environment and record results to CSV files in a directory', 'load a bsuite environment and log results directly to the terminal', 'unpack a bsuite_id string into its experiment name and setting index tuple', 'test that sweep BANDIT SWEEP and TESTING collections contain expected bsuite experiment IDs', 'test that sweep BANDIT SWEEP TESTING and TAGS are immutable and reject assignment', 'review the SweepTest class and its test_sweep_contents and test_sweep_immutable methods', 'run the SweepTest test class using absltest to verify sweep module correctness', 'summarize the SweepTest class which validates bsuite sweep collection contents and immutability']
```

Usage

```
{'test_sweep_contents': 'test that sweep BANDIT SWEEP and TESTING collections contain expected bsuite experiment IDs', 'test_sweep_immutable': 'test that sweep BANDIT SWEEP TESTING and TAGS are immutable and reject assignment', 'review_sweep_test_class': 'review the SweepTest class and its test_sweep_contents and test_sweep_immutable methods', 'run_sweep_tests': 'run the SweepTest test class using absltest to verify sweep module correctness', 'summarize_sweep_test': 'summarize the SweepTest class which validates bsuite sweep collection contents and immutability'}
```

