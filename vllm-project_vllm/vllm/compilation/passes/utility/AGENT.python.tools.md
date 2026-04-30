# Agent Python Tools

- repo: vllm-project/vllm
- repo_uri: https://github.com/vllm-project/vllm

## File: vllm-project_vllm/vllm/compilation/passes/utility/fix_functionalization.py

Prompts

```
['run the FixFunctionalizationPass on a torch fx graph to defunctionalize nodes and avoid redundant tensor copies', 'defunctionalize auto-functionalized graph nodes by replacing them with inplace calls to avoid redundant tensor copies', 'replace getitem users of an auto-functionalized node with the mutated in-place arguments', 'insert a new defunctionalized call node into an fx graph before the original auto-functionalized node', 'get all operator.getitem users of an auto-functionalized node indexed by the index they retrieve', 'run the NoOpEliminationPass on a torch.fx.Graph to remove redundant reshape and slice operations', 'test the dims_equivalent method to check if two tensor dimensions are equivalent', 'test the all_dims_equivalent method to compare two full tensor shapes for equivalence', 'refactor chains of consecutive reshape operations into a single reshape on the base tensor', 'review the NoOpEliminationPass class that removes no-op reshapes, slices, and slice_scatter operations for RMSNorm-quant fusion']
```

Usage

```
{'run_FixFunctionalizationPass': 'run the FixFunctionalizationPass on a torch fx graph to defunctionalize nodes and avoid redundant tensor copies', 'defunctionalize_nodes': 'defunctionalize auto-functionalized graph nodes by replacing them with inplace calls to avoid redundant tensor copies', 'replace_users_with_mutated_args': 'replace getitem users of an auto-functionalized node with the mutated in-place arguments', 'insert_defunctionalized_node': 'insert a new defunctionalized call node into an fx graph before the original auto-functionalized node', 'getitem_users': 'get all operator.getitem users of an auto-functionalized node indexed by the index they retrieve'}
```

## File: vllm-project_vllm/vllm/compilation/passes/utility/noop_elimination.py

Prompts

```
['run the FixFunctionalizationPass on a torch fx graph to defunctionalize nodes and avoid redundant tensor copies', 'defunctionalize auto-functionalized graph nodes by replacing them with inplace calls to avoid redundant tensor copies', 'replace getitem users of an auto-functionalized node with the mutated in-place arguments', 'insert a new defunctionalized call node into an fx graph before the original auto-functionalized node', 'get all operator.getitem users of an auto-functionalized node indexed by the index they retrieve', 'run the NoOpEliminationPass on a torch.fx.Graph to remove redundant reshape and slice operations', 'test the dims_equivalent method to check if two tensor dimensions are equivalent', 'test the all_dims_equivalent method to compare two full tensor shapes for equivalence', 'refactor chains of consecutive reshape operations into a single reshape on the base tensor', 'review the NoOpEliminationPass class that removes no-op reshapes, slices, and slice_scatter operations for RMSNorm-quant fusion']
```

Usage

```
{'run_noop_elimination_pass': 'run the NoOpEliminationPass on a torch.fx.Graph to remove redundant reshape and slice operations', 'test_dims_equivalent': 'test the dims_equivalent method to check if two tensor dimensions are equivalent', 'test_all_dims_equivalent': 'test the all_dims_equivalent method to compare two full tensor shapes for equivalence', 'refactor_reshape_chains': 'refactor chains of consecutive reshape operations into a single reshape on the base tensor', 'review_noop_elimination_pass': 'review the NoOpEliminationPass class that removes no-op reshapes, slices, and slice_scatter operations for RMSNorm-quant fusion'}
```

