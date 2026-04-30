# Agent Python Tools

- repo: sgl-project/sglang
- repo_uri: https://github.com/sgl-project/sglang

## File: sgl-project_sglang/python/sglang/multimodal_gen/runtime/pipelines_core/executors/parallel_executor.py

Prompts

```
['execute a list of pipeline stages on a batch respecting their declared parallelism type', 'collect and broadcast batches from main rank across tensor parallel and CFG parallel groups', 'execute pipeline stages only on the main rank with barrier synchronization for non-main ranks', 'execute pipeline stages with classifier-free guidance parallel broadcast from rank 0', 'execute pipeline stages on all ranks with replicated batch data', 'create a PipelineExecutor subclass that implements execute to run pipeline stages on a batch', 'run execute_with_profiling to execute pipeline stages with automatic profiling and timing', 'build a Timer instance to wrap StageProfiler with simple start/end logging for pipeline stages', 'test profile_execution context manager to conditionally profile batch execution based on profile flags', 'review the PipelineExecutor abstract base class and its execute method for pipeline orchestration', 'run the SyncExecutor pipeline stages sequentially with a batch and server args', 'execute the SyncExecutor pipeline stages sequentially and return an OutputBatch', 'profile all pipeline stages sequentially using SGLDiffusionProfiler in SyncExecutor', 'create a SyncExecutor instance that runs pipeline stages sequentially', 'test the SyncExecutor class and its sequential pipeline execution methods']
```

Usage

```
{'execute_pipeline_stages': 'execute a list of pipeline stages on a batch respecting their declared parallelism type', 'collect_from_main': 'collect and broadcast batches from main rank across tensor parallel and CFG parallel groups', 'execute_main_rank_only': 'execute pipeline stages only on the main rank with barrier synchronization for non-main ranks', 'execute_cfg_parallel': 'execute pipeline stages with classifier-free guidance parallel broadcast from rank 0', 'execute_replicated': 'execute pipeline stages on all ranks with replicated batch data'}
```

## File: sgl-project_sglang/python/sglang/multimodal_gen/runtime/pipelines_core/executors/pipeline_executor.py

Prompts

```
['execute a list of pipeline stages on a batch respecting their declared parallelism type', 'collect and broadcast batches from main rank across tensor parallel and CFG parallel groups', 'execute pipeline stages only on the main rank with barrier synchronization for non-main ranks', 'execute pipeline stages with classifier-free guidance parallel broadcast from rank 0', 'execute pipeline stages on all ranks with replicated batch data', 'create a PipelineExecutor subclass that implements execute to run pipeline stages on a batch', 'run execute_with_profiling to execute pipeline stages with automatic profiling and timing', 'build a Timer instance to wrap StageProfiler with simple start/end logging for pipeline stages', 'test profile_execution context manager to conditionally profile batch execution based on profile flags', 'review the PipelineExecutor abstract base class and its execute method for pipeline orchestration', 'run the SyncExecutor pipeline stages sequentially with a batch and server args', 'execute the SyncExecutor pipeline stages sequentially and return an OutputBatch', 'profile all pipeline stages sequentially using SGLDiffusionProfiler in SyncExecutor', 'create a SyncExecutor instance that runs pipeline stages sequentially', 'test the SyncExecutor class and its sequential pipeline execution methods']
```

Usage

```
{'create_pipeline_executor': 'create a PipelineExecutor subclass that implements execute to run pipeline stages on a batch', 'run_execute_with_profiling': 'run execute_with_profiling to execute pipeline stages with automatic profiling and timing', 'build_timer_stage': 'build a Timer instance to wrap StageProfiler with simple start/end logging for pipeline stages', 'test_profile_execution': 'test profile_execution context manager to conditionally profile batch execution based on profile flags', 'review_pipeline_executor': 'review the PipelineExecutor abstract base class and its execute method for pipeline orchestration'}
```

## File: sgl-project_sglang/python/sglang/multimodal_gen/runtime/pipelines_core/executors/sync_executor.py

Prompts

```
['execute a list of pipeline stages on a batch respecting their declared parallelism type', 'collect and broadcast batches from main rank across tensor parallel and CFG parallel groups', 'execute pipeline stages only on the main rank with barrier synchronization for non-main ranks', 'execute pipeline stages with classifier-free guidance parallel broadcast from rank 0', 'execute pipeline stages on all ranks with replicated batch data', 'create a PipelineExecutor subclass that implements execute to run pipeline stages on a batch', 'run execute_with_profiling to execute pipeline stages with automatic profiling and timing', 'build a Timer instance to wrap StageProfiler with simple start/end logging for pipeline stages', 'test profile_execution context manager to conditionally profile batch execution based on profile flags', 'review the PipelineExecutor abstract base class and its execute method for pipeline orchestration', 'run the SyncExecutor pipeline stages sequentially with a batch and server args', 'execute the SyncExecutor pipeline stages sequentially and return an OutputBatch', 'profile all pipeline stages sequentially using SGLDiffusionProfiler in SyncExecutor', 'create a SyncExecutor instance that runs pipeline stages sequentially', 'test the SyncExecutor class and its sequential pipeline execution methods']
```

Usage

```
{'run_pipeline_sync_executor': 'run the SyncExecutor pipeline stages sequentially with a batch and server args', 'execute_sync_pipeline': 'execute the SyncExecutor pipeline stages sequentially and return an OutputBatch', 'profile_sync_pipeline_stages': 'profile all pipeline stages sequentially using SGLDiffusionProfiler in SyncExecutor', 'create_sync_executor': 'create a SyncExecutor instance that runs pipeline stages sequentially', 'test_sync_executor': 'test the SyncExecutor class and its sequential pipeline execution methods'}
```

