# Agent Python Tools

- repo: facebookresearch/compilergym
- repo_uri: https://github.com/facebookresearch/compilergym

## File: facebookresearch_compilergym/leaderboard/llvm_instcount/e_greedy/e_greedy.py

Prompts

```
['run an epsilon-greedy search on an LLVM environment to optimize instruction count', 'select the best action by evaluating all options in parallel using a thread pool executor', 'create a RewardAction named tuple pairing a reward float with an action integer', 'evaluate an LLVM instruction count policy by running the e_greedy_search function as the main entry point', 'fork a CompilerEnv to safely evaluate each action in parallel without affecting the main environment', 'test the eval_llvm_instcount_policy function using e_greedy_search as the policy with minimal benchmarks and no validation', 'test that select_best_action recovers correctly when the LlvmEnv service has been closed', 'run the e_greedy_search policy against LLVM benchmarks using eval_llvm_instcount_policy with configurable nproc and epsilon flags', 'test the IrInstructionCount reward space by resetting an LlvmEnv on a specific benchmark like cbench-v1/crc32', 'test select_best_action using a ThreadPoolExecutor to evaluate all actions in parallel and return the best reward-action pair']
```

Usage

```
{'run_e_greedy_search': 'run an epsilon-greedy search on an LLVM environment to optimize instruction count', 'select_best_action': 'select the best action by evaluating all options in parallel using a thread pool executor', 'create_reward_action': 'create a RewardAction named tuple pairing a reward float with an action integer', 'eval_llvm_instcount_policy': 'evaluate an LLVM instruction count policy by running the e_greedy_search function as the main entry point', 'fork_env_for_action_eval': 'fork a CompilerEnv to safely evaluate each action in parallel without affecting the main environment'}
```

## File: facebookresearch_compilergym/leaderboard/llvm_instcount/e_greedy/e_greedy_test.py

Prompts

```
['run an epsilon-greedy search on an LLVM environment to optimize instruction count', 'select the best action by evaluating all options in parallel using a thread pool executor', 'create a RewardAction named tuple pairing a reward float with an action integer', 'evaluate an LLVM instruction count policy by running the e_greedy_search function as the main entry point', 'fork a CompilerEnv to safely evaluate each action in parallel without affecting the main environment', 'test the eval_llvm_instcount_policy function using e_greedy_search as the policy with minimal benchmarks and no validation', 'test that select_best_action recovers correctly when the LlvmEnv service has been closed', 'run the e_greedy_search policy against LLVM benchmarks using eval_llvm_instcount_policy with configurable nproc and epsilon flags', 'test the IrInstructionCount reward space by resetting an LlvmEnv on a specific benchmark like cbench-v1/crc32', 'test select_best_action using a ThreadPoolExecutor to evaluate all actions in parallel and return the best reward-action pair']
```

Usage

```
{'test_eval_llvm_instcount_policy_with_e_greedy_search': 'test the eval_llvm_instcount_policy function using e_greedy_search as the policy with minimal benchmarks and no validation', 'test_select_best_action_after_env_close': 'test that select_best_action recovers correctly when the LlvmEnv service has been closed', 'run_e_greedy_search_evaluation': 'run the e_greedy_search policy against LLVM benchmarks using eval_llvm_instcount_policy with configurable nproc and epsilon flags', 'test_reward_space_ir_instruction_count': 'test the IrInstructionCount reward space by resetting an LlvmEnv on a specific benchmark like cbench-v1/crc32', 'test_select_best_action_with_thread_pool': 'test select_best_action using a ThreadPoolExecutor to evaluate all actions in parallel and return the best reward-action pair'}
```

