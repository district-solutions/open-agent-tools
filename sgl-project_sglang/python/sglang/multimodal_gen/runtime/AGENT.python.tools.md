# Agent Python Tools

- repo: sgl-project/sglang
- repo_uri: https://github.com/sgl-project/sglang

## File: sgl-project_sglang/python/sglang/multimodal_gen/runtime/launch_server.py

Prompts

```
['launch a monolithic diffusion server with GPU worker processes and an optional HTTP server', 'launch a pool-based disaggregated diffusion server with separate encoder, denoiser, and decoder GPU instances', 'launch a DiffusionServer head node that connects to remote encoder, denoiser, and decoder role endpoints', 'launch a standalone disaggregated role instance such as encoder, denoiser, or decoder with GPU workers', 'route to the correct launch function based on the disagg_role argument such as monolithic, server, encoder, denoiser, or decoder', 'run a ZMQ broker that listens for offline jobs and forwards them to the scheduler', 'initialize the synchronous SchedulerClient with ServerArgs for scheduler communication', 'forward a request batch to the scheduler using the synchronous SchedulerClient', 'initialize the asynchronous AsyncSchedulerClient with ServerArgs for scheduler communication', 'forward a request batch to the scheduler using the asynchronous AsyncSchedulerClient', 'build ServerArgs from command-line arguments using prepare_server_args with argv list of strings', 'create ServerArgs from a dictionary of configuration kwargs including model_path and pipeline_config', 'run ServerArgs parameter validation including offload, parallelism, and pipeline consistency checks', 'test ServerArgs port allocation with settle_port retry logic and strict-ports mode', 'review PortArgs creation from ServerArgs generating scheduler, nccl, rpc, and metrics IPC endpoints']
```

Usage

```
{'launch_server': 'launch a monolithic diffusion server with GPU worker processes and an optional HTTP server', 'launch_pool_disagg_server': 'launch a pool-based disaggregated diffusion server with separate encoder, denoiser, and decoder GPU instances', 'launch_disagg_server': 'launch a DiffusionServer head node that connects to remote encoder, denoiser, and decoder role endpoints', 'launch_disagg_role': 'launch a standalone disaggregated role instance such as encoder, denoiser, or decoder with GPU workers', 'dispatch_launch': 'route to the correct launch function based on the disagg_role argument such as monolithic, server, encoder, denoiser, or decoder'}
```

## File: sgl-project_sglang/python/sglang/multimodal_gen/runtime/scheduler_client.py

Prompts

```
['launch a monolithic diffusion server with GPU worker processes and an optional HTTP server', 'launch a pool-based disaggregated diffusion server with separate encoder, denoiser, and decoder GPU instances', 'launch a DiffusionServer head node that connects to remote encoder, denoiser, and decoder role endpoints', 'launch a standalone disaggregated role instance such as encoder, denoiser, or decoder with GPU workers', 'route to the correct launch function based on the disagg_role argument such as monolithic, server, encoder, denoiser, or decoder', 'run a ZMQ broker that listens for offline jobs and forwards them to the scheduler', 'initialize the synchronous SchedulerClient with ServerArgs for scheduler communication', 'forward a request batch to the scheduler using the synchronous SchedulerClient', 'initialize the asynchronous AsyncSchedulerClient with ServerArgs for scheduler communication', 'forward a request batch to the scheduler using the asynchronous AsyncSchedulerClient', 'build ServerArgs from command-line arguments using prepare_server_args with argv list of strings', 'create ServerArgs from a dictionary of configuration kwargs including model_path and pipeline_config', 'run ServerArgs parameter validation including offload, parallelism, and pipeline consistency checks', 'test ServerArgs port allocation with settle_port retry logic and strict-ports mode', 'review PortArgs creation from ServerArgs generating scheduler, nccl, rpc, and metrics IPC endpoints']
```

Usage

```
{'run_zeromq_broker': 'run a ZMQ broker that listens for offline jobs and forwards them to the scheduler', 'initialize_sync_scheduler_client': 'initialize the synchronous SchedulerClient with ServerArgs for scheduler communication', 'forward_batch_sync_scheduler_client': 'forward a request batch to the scheduler using the synchronous SchedulerClient', 'initialize_async_scheduler_client': 'initialize the asynchronous AsyncSchedulerClient with ServerArgs for scheduler communication', 'forward_batch_async_scheduler_client': 'forward a request batch to the scheduler using the asynchronous AsyncSchedulerClient'}
```

## File: sgl-project_sglang/python/sglang/multimodal_gen/runtime/server_args.py

Prompts

```
['launch a monolithic diffusion server with GPU worker processes and an optional HTTP server', 'launch a pool-based disaggregated diffusion server with separate encoder, denoiser, and decoder GPU instances', 'launch a DiffusionServer head node that connects to remote encoder, denoiser, and decoder role endpoints', 'launch a standalone disaggregated role instance such as encoder, denoiser, or decoder with GPU workers', 'route to the correct launch function based on the disagg_role argument such as monolithic, server, encoder, denoiser, or decoder', 'run a ZMQ broker that listens for offline jobs and forwards them to the scheduler', 'initialize the synchronous SchedulerClient with ServerArgs for scheduler communication', 'forward a request batch to the scheduler using the synchronous SchedulerClient', 'initialize the asynchronous AsyncSchedulerClient with ServerArgs for scheduler communication', 'forward a request batch to the scheduler using the asynchronous AsyncSchedulerClient', 'build ServerArgs from command-line arguments using prepare_server_args with argv list of strings', 'create ServerArgs from a dictionary of configuration kwargs including model_path and pipeline_config', 'run ServerArgs parameter validation including offload, parallelism, and pipeline consistency checks', 'test ServerArgs port allocation with settle_port retry logic and strict-ports mode', 'review PortArgs creation from ServerArgs generating scheduler, nccl, rpc, and metrics IPC endpoints']
```

Usage

```
{'build_server_args_from_cli': 'build ServerArgs from command-line arguments using prepare_server_args with argv list of strings', 'create_server_args_from_dict': 'create ServerArgs from a dictionary of configuration kwargs including model_path and pipeline_config', 'run_server_args_validation': 'run ServerArgs parameter validation including offload, parallelism, and pipeline consistency checks', 'test_server_args_port_allocation': 'test ServerArgs port allocation with settle_port retry logic and strict-ports mode', 'review_port_args_creation': 'review PortArgs creation from ServerArgs generating scheduler, nccl, rpc, and metrics IPC endpoints'}
```

