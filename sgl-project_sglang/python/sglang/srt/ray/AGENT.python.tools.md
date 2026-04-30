# Agent Python Tools

- repo: sgl-project/sglang
- repo_uri: https://github.com/sgl-project/sglang

## File: sgl-project_sglang/python/sglang/srt/ray/data_parallel_controller.py

Prompts

```
['create a RayDataParallelController instance with server_args, port_args, placement_group, bundle_for_node, and rank0_node_ip', 'launch DP scheduler Ray actors per data-parallel rank using ZMQ PUSH sockets and pre-bound NCCL ports', 'launch DP attention scheduler Ray actors with pre-allocated worker ports bound to the rank-0 node IP', 'run event loops for all SchedulerActor Ray actors and wait for initialization info via ray.get', 'review the RayDataParallelController class that overrides DataParallelController to use Ray actors instead of mp.Process', 'create a RayEngine instance that launches scheduler processes as Ray actors with placement group scheduling', 'build a RaySchedulerInitResult dataclass holding scheduler infos, wait callbacks, and Ray actor handles for cleanup', 'run Ray scheduler processes launched as Ray actors with tensor parallel or data parallel configuration', 'run data parallel scheduler processes via RayDataParallelController with per-DP-rank scheduler actors', 'test the _find_engine_bundle function to find which placement group bundle is on the same node as the Engine', 'run an HTTP server with Ray-based scheduler actors for SGLang using launch_server', 'build a Ray remote actor that wraps SGLang Scheduler to manage one GPU and run the Scheduler + TpModelWorker stack', 'create a SchedulerActor instance with server args, port args, gpu id, tp rank, attn cp rank, moe dp rank, moe ep rank, pp rank, and dp rank', 'get scheduler initialization info dictionary for the Ray actor handshake', 'run the SchedulerActor event loop that sets the CUDA device and blocks until shutdown', 'review the SchedulerActor Ray remote class and its GPU assignment, NUMA binding, and scheduler lifecycle logic']
```

Usage

```
{'create_RayDataParallelController': 'create a RayDataParallelController instance with server_args, port_args, placement_group, bundle_for_node, and rank0_node_ip', 'launch_dp_schedulers': 'launch DP scheduler Ray actors per data-parallel rank using ZMQ PUSH sockets and pre-bound NCCL ports', 'launch_dp_attention_schedulers': 'launch DP attention scheduler Ray actors with pre-allocated worker ports bound to the rank-0 node IP', 'run_RayDataParallelController_event_loops': 'run event loops for all SchedulerActor Ray actors and wait for initialization info via ray.get', 'review_RayDataParallelController': 'review the RayDataParallelController class that overrides DataParallelController to use Ray actors instead of mp.Process'}
```

## File: sgl-project_sglang/python/sglang/srt/ray/engine.py

Prompts

```
['create a RayDataParallelController instance with server_args, port_args, placement_group, bundle_for_node, and rank0_node_ip', 'launch DP scheduler Ray actors per data-parallel rank using ZMQ PUSH sockets and pre-bound NCCL ports', 'launch DP attention scheduler Ray actors with pre-allocated worker ports bound to the rank-0 node IP', 'run event loops for all SchedulerActor Ray actors and wait for initialization info via ray.get', 'review the RayDataParallelController class that overrides DataParallelController to use Ray actors instead of mp.Process', 'create a RayEngine instance that launches scheduler processes as Ray actors with placement group scheduling', 'build a RaySchedulerInitResult dataclass holding scheduler infos, wait callbacks, and Ray actor handles for cleanup', 'run Ray scheduler processes launched as Ray actors with tensor parallel or data parallel configuration', 'run data parallel scheduler processes via RayDataParallelController with per-DP-rank scheduler actors', 'test the _find_engine_bundle function to find which placement group bundle is on the same node as the Engine', 'run an HTTP server with Ray-based scheduler actors for SGLang using launch_server', 'build a Ray remote actor that wraps SGLang Scheduler to manage one GPU and run the Scheduler + TpModelWorker stack', 'create a SchedulerActor instance with server args, port args, gpu id, tp rank, attn cp rank, moe dp rank, moe ep rank, pp rank, and dp rank', 'get scheduler initialization info dictionary for the Ray actor handshake', 'run the SchedulerActor event loop that sets the CUDA device and blocks until shutdown', 'review the SchedulerActor Ray remote class and its GPU assignment, NUMA binding, and scheduler lifecycle logic']
```

Usage

```
{'create_ray_engine': 'create a RayEngine instance that launches scheduler processes as Ray actors with placement group scheduling', 'build_ray_scheduler_init_result': 'build a RaySchedulerInitResult dataclass holding scheduler infos, wait callbacks, and Ray actor handles for cleanup', 'run_ray_scheduler_processes': 'run Ray scheduler processes launched as Ray actors with tensor parallel or data parallel configuration', 'run_dp_scheduler_processes': 'run data parallel scheduler processes via RayDataParallelController with per-DP-rank scheduler actors', 'test_find_engine_bundle': 'test the _find_engine_bundle function to find which placement group bundle is on the same node as the Engine'}
```

## File: sgl-project_sglang/python/sglang/srt/ray/http_server.py

Prompts

```
['create a RayDataParallelController instance with server_args, port_args, placement_group, bundle_for_node, and rank0_node_ip', 'launch DP scheduler Ray actors per data-parallel rank using ZMQ PUSH sockets and pre-bound NCCL ports', 'launch DP attention scheduler Ray actors with pre-allocated worker ports bound to the rank-0 node IP', 'run event loops for all SchedulerActor Ray actors and wait for initialization info via ray.get', 'review the RayDataParallelController class that overrides DataParallelController to use Ray actors instead of mp.Process', 'create a RayEngine instance that launches scheduler processes as Ray actors with placement group scheduling', 'build a RaySchedulerInitResult dataclass holding scheduler infos, wait callbacks, and Ray actor handles for cleanup', 'run Ray scheduler processes launched as Ray actors with tensor parallel or data parallel configuration', 'run data parallel scheduler processes via RayDataParallelController with per-DP-rank scheduler actors', 'test the _find_engine_bundle function to find which placement group bundle is on the same node as the Engine', 'run an HTTP server with Ray-based scheduler actors for SGLang using launch_server', 'build a Ray remote actor that wraps SGLang Scheduler to manage one GPU and run the Scheduler + TpModelWorker stack', 'create a SchedulerActor instance with server args, port args, gpu id, tp rank, attn cp rank, moe dp rank, moe ep rank, pp rank, and dp rank', 'get scheduler initialization info dictionary for the Ray actor handshake', 'run the SchedulerActor event loop that sets the CUDA device and blocks until shutdown', 'review the SchedulerActor Ray remote class and its GPU assignment, NUMA binding, and scheduler lifecycle logic']
```

Usage

```
{'run_http_server_with_ray': 'run an HTTP server with Ray-based scheduler actors for SGLang using launch_server'}
```

## File: sgl-project_sglang/python/sglang/srt/ray/scheduler_actor.py

Prompts

```
['create a RayDataParallelController instance with server_args, port_args, placement_group, bundle_for_node, and rank0_node_ip', 'launch DP scheduler Ray actors per data-parallel rank using ZMQ PUSH sockets and pre-bound NCCL ports', 'launch DP attention scheduler Ray actors with pre-allocated worker ports bound to the rank-0 node IP', 'run event loops for all SchedulerActor Ray actors and wait for initialization info via ray.get', 'review the RayDataParallelController class that overrides DataParallelController to use Ray actors instead of mp.Process', 'create a RayEngine instance that launches scheduler processes as Ray actors with placement group scheduling', 'build a RaySchedulerInitResult dataclass holding scheduler infos, wait callbacks, and Ray actor handles for cleanup', 'run Ray scheduler processes launched as Ray actors with tensor parallel or data parallel configuration', 'run data parallel scheduler processes via RayDataParallelController with per-DP-rank scheduler actors', 'test the _find_engine_bundle function to find which placement group bundle is on the same node as the Engine', 'run an HTTP server with Ray-based scheduler actors for SGLang using launch_server', 'build a Ray remote actor that wraps SGLang Scheduler to manage one GPU and run the Scheduler + TpModelWorker stack', 'create a SchedulerActor instance with server args, port args, gpu id, tp rank, attn cp rank, moe dp rank, moe ep rank, pp rank, and dp rank', 'get scheduler initialization info dictionary for the Ray actor handshake', 'run the SchedulerActor event loop that sets the CUDA device and blocks until shutdown', 'review the SchedulerActor Ray remote class and its GPU assignment, NUMA binding, and scheduler lifecycle logic']
```

Usage

```
{'build_scheduler_actor': 'build a Ray remote actor that wraps SGLang Scheduler to manage one GPU and run the Scheduler + TpModelWorker stack', 'create_scheduler_init': 'create a SchedulerActor instance with server args, port args, gpu id, tp rank, attn cp rank, moe dp rank, moe ep rank, pp rank, and dp rank', 'get_scheduler_info': 'get scheduler initialization info dictionary for the Ray actor handshake', 'run_scheduler_event_loop': 'run the SchedulerActor event loop that sets the CUDA device and blocks until shutdown', 'review_scheduler_actor': 'review the SchedulerActor Ray remote class and its GPU assignment, NUMA binding, and scheduler lifecycle logic'}
```

