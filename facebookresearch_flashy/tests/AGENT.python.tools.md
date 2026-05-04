# Agent Python Tools

- repo: facebookresearch/flashy
- repo_uri: https://github.com/facebookresearch/flashy

## File: facebookresearch_flashy/tests/test_distrib.py

Prompts

```
['test the flashy distrib module by spawning 8 processes and running distributed tensor operations', 'run distrib.broadcast_tensors to broadcast tensors from rank 0 to all processes in the group', 'test distrib.average_tensors to compute the average of tensors across all distributed processes', 'review distrib.sync_model and eager_sync_model for synchronizing model gradients across distributed processes', 'test distrib.broadcast_object to broadcast a Python object from rank 0 to all worker processes', 'test the dora CLI run command with stop_at parameter to verify experiment history length', 'test that running dora again appends to existing experiment history without clearing old data', 'test the dora CLI run command with distributed data parallel workers using --ddp_workers flag', 'test getting an experiment object via train.main.get_xp and loading its link history', 'test the dora CLI run command with the --clear flag to reset experiment state']
```

Usage

```
{'test_distrib_module': 'test the flashy distrib module by spawning 8 processes and running distributed tensor operations', 'run_broadcast_tensors': 'run distrib.broadcast_tensors to broadcast tensors from rank 0 to all processes in the group', 'test_average_tensors': 'test distrib.average_tensors to compute the average of tensors across all distributed processes', 'review_sync_model': 'review distrib.sync_model and eager_sync_model for synchronizing model gradients across distributed processes', 'test_broadcast_object': 'test distrib.broadcast_object to broadcast a Python object from rank 0 to all worker processes'}
```

## File: facebookresearch_flashy/tests/test_integ.py

Prompts

```
['test the flashy distrib module by spawning 8 processes and running distributed tensor operations', 'run distrib.broadcast_tensors to broadcast tensors from rank 0 to all processes in the group', 'test distrib.average_tensors to compute the average of tensors across all distributed processes', 'review distrib.sync_model and eager_sync_model for synchronizing model gradients across distributed processes', 'test distrib.broadcast_object to broadcast a Python object from rank 0 to all worker processes', 'test the dora CLI run command with stop_at parameter to verify experiment history length', 'test that running dora again appends to existing experiment history without clearing old data', 'test the dora CLI run command with distributed data parallel workers using --ddp_workers flag', 'test getting an experiment object via train.main.get_xp and loading its link history', 'test the dora CLI run command with the --clear flag to reset experiment state']
```

Usage

```
{'test_integ_dora_run': 'test the dora CLI run command with stop_at parameter to verify experiment history length', 'test_integ_experiment_resume': 'test that running dora again appends to existing experiment history without clearing old data', 'test_integ_ddp_workers': 'test the dora CLI run command with distributed data parallel workers using --ddp_workers flag', 'test_integ_get_xp': 'test getting an experiment object via train.main.get_xp and loading its link history', 'test_integ_clear_flag': 'test the dora CLI run command with the --clear flag to reset experiment state'}
```

