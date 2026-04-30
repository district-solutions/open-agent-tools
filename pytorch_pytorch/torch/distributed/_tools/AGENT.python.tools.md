# Agent Python Tools

- repo: pytorch/pytorch
- repo_uri: https://github.com/pytorch/pytorch.git

## File: pytorch_pytorch/torch/distributed/_tools/memory_tracker.py

Prompts

```
['create a MemoryTracker instance to collect and plot operator-level memory stats', 'run start_monitor on a PyTorch module to track memory allocated, active, and reserved per operator', 'summarize the top 20 operators that generate the most memory using MemoryTracker.summary', 'review memory usage traces by plotting allocated, active, and reserved memory with MemoryTracker.show_traces', 'test saving and loading MemoryTracker stats via pickle for offline trace plotting']
```

Usage

```
{'create_memory_tracker': 'create a MemoryTracker instance to collect and plot operator-level memory stats', 'run_memory_tracker_monitor': 'run start_monitor on a PyTorch module to track memory allocated, active, and reserved per operator', 'summarize_memory_tracker': 'summarize the top 20 operators that generate the most memory using MemoryTracker.summary', 'review_memory_tracker_traces': 'review memory usage traces by plotting allocated, active, and reserved memory with MemoryTracker.show_traces', 'test_memory_tracker_save_load': 'test saving and loading MemoryTracker stats via pickle for offline trace plotting'}
```

