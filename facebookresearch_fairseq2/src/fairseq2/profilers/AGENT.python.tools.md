# Agent Python Tools

- repo: facebookresearch/fairseq2
- repo_uri: https://github.com/facebookresearch/fairseq2.git

## File: facebookresearch_fairseq2/src/fairseq2/profilers/composite.py

Prompts

```
['create a CompositeProfiler that aggregates multiple Profiler instances into a single profiler', 'start all profilers in a CompositeProfiler by calling its start method', 'stop all profilers in a CompositeProfiler by calling its stop method', 'advance all profilers in a CompositeProfiler by calling its step method', 'review the CompositeProfiler class that delegates start, stop, and step to a sequence of profilers', 'create a subclass of Profiler that implements start, stop, and step methods for custom profiling', 'use a Profiler instance as a context manager to auto start and stop profiling', 'call the step method on a Profiler to mark a profiling boundary between operations', 'use the NOOP_PROFILER singleton as a no-op placeholder when profiling is disabled', 'review the Profiler abstract base class and its start, stop, and step contract', 'create a TorchProfiler instance with CPU and CUDA profiling activities and a custom schedule', 'start the TorchProfiler to begin recording CPU and CUDA profiling data', 'stop the TorchProfiler to end recording and finalize trace output', 'advance the TorchProfiler to the next step in its profiling schedule', 'review the TorchProfiler constructor to understand schedule parameters and tensorboard trace handler setup']
```

Usage

```
{'create_composite_profiler': 'create a CompositeProfiler that aggregates multiple Profiler instances into a single profiler', 'start_composite_profiler': 'start all profilers in a CompositeProfiler by calling its start method', 'stop_composite_profiler': 'stop all profilers in a CompositeProfiler by calling its stop method', 'step_composite_profiler': 'advance all profilers in a CompositeProfiler by calling its step method', 'review_composite_profiler_class': 'review the CompositeProfiler class that delegates start, stop, and step to a sequence of profilers'}
```

## File: facebookresearch_fairseq2/src/fairseq2/profilers/profiler.py

Prompts

```
['create a CompositeProfiler that aggregates multiple Profiler instances into a single profiler', 'start all profilers in a CompositeProfiler by calling its start method', 'stop all profilers in a CompositeProfiler by calling its stop method', 'advance all profilers in a CompositeProfiler by calling its step method', 'review the CompositeProfiler class that delegates start, stop, and step to a sequence of profilers', 'create a subclass of Profiler that implements start, stop, and step methods for custom profiling', 'use a Profiler instance as a context manager to auto start and stop profiling', 'call the step method on a Profiler to mark a profiling boundary between operations', 'use the NOOP_PROFILER singleton as a no-op placeholder when profiling is disabled', 'review the Profiler abstract base class and its start, stop, and step contract', 'create a TorchProfiler instance with CPU and CUDA profiling activities and a custom schedule', 'start the TorchProfiler to begin recording CPU and CUDA profiling data', 'stop the TorchProfiler to end recording and finalize trace output', 'advance the TorchProfiler to the next step in its profiling schedule', 'review the TorchProfiler constructor to understand schedule parameters and tensorboard trace handler setup']
```

Usage

```
{'create_Profiler_subclass': 'create a subclass of Profiler that implements start, stop, and step methods for custom profiling', 'use_Profiler_context_manager': 'use a Profiler instance as a context manager to auto start and stop profiling', 'call_Profiler_step': 'call the step method on a Profiler to mark a profiling boundary between operations', 'use_NOOP_PROFILER': 'use the NOOP_PROFILER singleton as a no-op placeholder when profiling is disabled', 'review_Profiler_ABC': 'review the Profiler abstract base class and its start, stop, and step contract'}
```

## File: facebookresearch_fairseq2/src/fairseq2/profilers/torch.py

Prompts

```
['create a CompositeProfiler that aggregates multiple Profiler instances into a single profiler', 'start all profilers in a CompositeProfiler by calling its start method', 'stop all profilers in a CompositeProfiler by calling its stop method', 'advance all profilers in a CompositeProfiler by calling its step method', 'review the CompositeProfiler class that delegates start, stop, and step to a sequence of profilers', 'create a subclass of Profiler that implements start, stop, and step methods for custom profiling', 'use a Profiler instance as a context manager to auto start and stop profiling', 'call the step method on a Profiler to mark a profiling boundary between operations', 'use the NOOP_PROFILER singleton as a no-op placeholder when profiling is disabled', 'review the Profiler abstract base class and its start, stop, and step contract', 'create a TorchProfiler instance with CPU and CUDA profiling activities and a custom schedule', 'start the TorchProfiler to begin recording CPU and CUDA profiling data', 'stop the TorchProfiler to end recording and finalize trace output', 'advance the TorchProfiler to the next step in its profiling schedule', 'review the TorchProfiler constructor to understand schedule parameters and tensorboard trace handler setup']
```

Usage

```
{'create_TorchProfiler': 'create a TorchProfiler instance with CPU and CUDA profiling activities and a custom schedule', 'start_TorchProfiler': 'start the TorchProfiler to begin recording CPU and CUDA profiling data', 'stop_TorchProfiler': 'stop the TorchProfiler to end recording and finalize trace output', 'step_TorchProfiler': 'advance the TorchProfiler to the next step in its profiling schedule', 'review_TorchProfiler_init': 'review the TorchProfiler constructor to understand schedule parameters and tensorboard trace handler setup'}
```

