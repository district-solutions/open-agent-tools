# Agent Python Tools

- repo: facebookresearch/aira-dojo
- repo_uri: https://github.com/facebookresearch/aira-dojo

## File: facebookresearch_aira-dojo/src/dojo/solvers/mcts/mcts.py

Prompts

```
['run the MCTS solver to search for the best code solution using UCT selection and LLM operators', 'create an MCTSNode with plan, code, and parent references for use in the MCTS search tree', 'compute the UCT selection score for a node using normalized Q-value and exploration term', 'normalize a Q-value to the 0-1 range using global max and min Q-value bounds', 'run a debug cycle on a buggy MCTSNode to iteratively fix and evaluate the solution']
```

Usage

```
{'run_MCTS_solver': 'run the MCTS solver to search for the best code solution using UCT selection and LLM operators', 'create_MCTSNode': 'create an MCTSNode with plan, code, and parent references for use in the MCTS search tree', 'compute_uct_value': 'compute the UCT selection score for a node using normalized Q-value and exploration term', 'normalize_q_value': 'normalize a Q-value to the 0-1 range using global max and min Q-value bounds', 'debug_cycle_MCTS': 'run a debug cycle on a buggy MCTSNode to iteratively fix and evaluate the solution'}
```

