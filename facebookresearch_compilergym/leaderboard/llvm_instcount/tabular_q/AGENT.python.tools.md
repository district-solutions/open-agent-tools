# Agent Python Tools

- repo: facebookresearch/compilergym
- repo_uri: https://github.com/facebookresearch/compilergym

## File: facebookresearch_compilergym/leaderboard/llvm_instcount/tabular_q/tabular_q_eval.py

Prompts

```
['run tabular Q-learning evaluation on the LLVM instcount leaderboard using the CompilerGym environment', 'train a Q-table policy on a forked LlvmEnv using the Autophase observation space', 'execute a rollout of the trained Q-table policy on the LLVM environment without printing output', 'evaluate a tabular Q-learning policy against the LLVM instcount leaderboard benchmark', 'fork an LlvmEnv instance to create an isolated training environment for Q-learning', 'test the tabular Q-learning policy evaluation on the LLVM instcount leaderboard with minimal benchmarks', 'run the tabular Q-learning test module directly using the test_main entry point', 'test the LLVM instcount policy evaluator using the train_and_run function from tabular_q_eval', 'test the tabular Q evaluation by configuring absl flags for n, max_benchmarks, nproc, and novalidate', 'test that the tabular Q policy evaluation raises SystemExit when run with pytest']
```

Usage

```
{'run_tabular_q_evaluation': 'run tabular Q-learning evaluation on the LLVM instcount leaderboard using the CompilerGym environment', 'train_q_table': 'train a Q-table policy on a forked LlvmEnv using the Autophase observation space', 'rollout_trained_policy': 'execute a rollout of the trained Q-table policy on the LLVM environment without printing output', 'eval_llvm_instcount_policy': 'evaluate a tabular Q-learning policy against the LLVM instcount leaderboard benchmark', 'fork_llvm_env': 'fork an LlvmEnv instance to create an isolated training environment for Q-learning'}
```

## File: facebookresearch_compilergym/leaderboard/llvm_instcount/tabular_q/tabular_q_test.py

Prompts

```
['run tabular Q-learning evaluation on the LLVM instcount leaderboard using the CompilerGym environment', 'train a Q-table policy on a forked LlvmEnv using the Autophase observation space', 'execute a rollout of the trained Q-table policy on the LLVM environment without printing output', 'evaluate a tabular Q-learning policy against the LLVM instcount leaderboard benchmark', 'fork an LlvmEnv instance to create an isolated training environment for Q-learning', 'test the tabular Q-learning policy evaluation on the LLVM instcount leaderboard with minimal benchmarks', 'run the tabular Q-learning test module directly using the test_main entry point', 'test the LLVM instcount policy evaluator using the train_and_run function from tabular_q_eval', 'test the tabular Q evaluation by configuring absl flags for n, max_benchmarks, nproc, and novalidate', 'test that the tabular Q policy evaluation raises SystemExit when run with pytest']
```

Usage

```
{'test_tabular_q': 'test the tabular Q-learning policy evaluation on the LLVM instcount leaderboard with minimal benchmarks', 'run_tabular_q_test_main': 'run the tabular Q-learning test module directly using the test_main entry point', 'test_eval_llvm_instcount_policy': 'test the LLVM instcount policy evaluator using the train_and_run function from tabular_q_eval', 'test_tabular_q_with_flags': 'test the tabular Q evaluation by configuring absl flags for n, max_benchmarks, nproc, and novalidate', 'test_tabular_q_system_exit': 'test that the tabular Q policy evaluation raises SystemExit when run with pytest'}
```

