# Agent Python Tools

- repo: facebookresearch/compilergym
- repo_uri: https://github.com/facebookresearch/compilergym

## File: facebookresearch_compilergym/leaderboard/llvm_instcount/random_search/random_search.py

Prompts

```
['run a random search on an LLVM environment using parallel RandomAgentWorker threads', 'run the eval_llvm_instcount_policy function with the random_search policy on the LLVM benchmark', 'create a RandomAgentWorker with a make_env lambda and patience parameter for parallel search', 'define the patience_ratio flag to control patience as a ratio of the action space size', 'define the search_time flag to set the minimum seconds to run the random search', 'test the random search policy evaluation using eval_llvm_instcount_policy with configured command line flags', 'run the test_random_search function to verify eval_llvm_instcount_policy raises SystemExit with random_search policy', 'test eval_llvm_instcount_policy by passing random_search as the policy argument with pytest', 'test setting command line flags like n, max_benchmarks, search_time, nproc, patience_ratio, and novalidate', 'run the test main entry point to execute all tests in the random_search test module']
```

Usage

```
{'run_random_search': 'run a random search on an LLVM environment using parallel RandomAgentWorker threads', 'run_eval_llvm_instcount_policy': 'run the eval_llvm_instcount_policy function with the random_search policy on the LLVM benchmark', 'create_random_agent_worker': 'create a RandomAgentWorker with a make_env lambda and patience parameter for parallel search', 'define_patience_ratio_flag': 'define the patience_ratio flag to control patience as a ratio of the action space size', 'define_search_time_flag': 'define the search_time flag to set the minimum seconds to run the random search'}
```

## File: facebookresearch_compilergym/leaderboard/llvm_instcount/random_search/random_search_test.py

Prompts

```
['run a random search on an LLVM environment using parallel RandomAgentWorker threads', 'run the eval_llvm_instcount_policy function with the random_search policy on the LLVM benchmark', 'create a RandomAgentWorker with a make_env lambda and patience parameter for parallel search', 'define the patience_ratio flag to control patience as a ratio of the action space size', 'define the search_time flag to set the minimum seconds to run the random search', 'test the random search policy evaluation using eval_llvm_instcount_policy with configured command line flags', 'run the test_random_search function to verify eval_llvm_instcount_policy raises SystemExit with random_search policy', 'test eval_llvm_instcount_policy by passing random_search as the policy argument with pytest', 'test setting command line flags like n, max_benchmarks, search_time, nproc, patience_ratio, and novalidate', 'run the test main entry point to execute all tests in the random_search test module']
```

Usage

```
{'test_random_search': 'test the random search policy evaluation using eval_llvm_instcount_policy with configured command line flags', 'run_test_random_search': 'run the test_random_search function to verify eval_llvm_instcount_policy raises SystemExit with random_search policy', 'test_eval_llvm_instcount_policy': 'test eval_llvm_instcount_policy by passing random_search as the policy argument with pytest', 'test_set_command_line_flags': 'test setting command line flags like n, max_benchmarks, search_time, nproc, patience_ratio, and novalidate', 'run_test_main': 'run the test main entry point to execute all tests in the random_search test module'}
```

