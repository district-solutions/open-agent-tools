# Agent Python Tools

- repo: pytorch/pytorch
- repo_uri: https://github.com/pytorch/pytorch.git

## File: pytorch_pytorch/torch/mps/event.py

Prompts

```
['create an MPS event to synchronize and measure timing on the Metal Performance Shaders device', 'record an MPS event in the default stream to mark device progress', 'make future work in the default stream wait for an MPS event to complete', 'query whether all work captured by an MPS event has completed', 'measure elapsed time in milliseconds between two recorded MPS events', 'start OS Signpost tracing on the MPS backend with interval mode to trace GPU operation durations', 'start OS Signpost tracing on the MPS backend with event mode to mark GPU operation completion', 'stop OS Signpost tracing on the MPS backend', 'profile MPS GPU operations using the profile context manager with interval tracing', 'profile MPS GPU operations using the profile context manager with wait_until_completed for single dispatch timeline']
```

Usage

```
{'create_mps_event': 'create an MPS event to synchronize and measure timing on the Metal Performance Shaders device', 'record_mps_event': 'record an MPS event in the default stream to mark device progress', 'wait_for_mps_event': 'make future work in the default stream wait for an MPS event to complete', 'query_mps_event_status': 'query whether all work captured by an MPS event has completed', 'measure_elapsed_time': 'measure elapsed time in milliseconds between two recorded MPS events'}
```

## File: pytorch_pytorch/torch/mps/profiler.py

Prompts

```
['create an MPS event to synchronize and measure timing on the Metal Performance Shaders device', 'record an MPS event in the default stream to mark device progress', 'make future work in the default stream wait for an MPS event to complete', 'query whether all work captured by an MPS event has completed', 'measure elapsed time in milliseconds between two recorded MPS events', 'start OS Signpost tracing on the MPS backend with interval mode to trace GPU operation durations', 'start OS Signpost tracing on the MPS backend with event mode to mark GPU operation completion', 'stop OS Signpost tracing on the MPS backend', 'profile MPS GPU operations using the profile context manager with interval tracing', 'profile MPS GPU operations using the profile context manager with wait_until_completed for single dispatch timeline']
```

Usage

```
{'start_mps_profiler': 'start OS Signpost tracing on the MPS backend with interval mode to trace GPU operation durations', 'start_mps_profiler_event': 'start OS Signpost tracing on the MPS backend with event mode to mark GPU operation completion', 'stop_mps_profiler': 'stop OS Signpost tracing on the MPS backend', 'profile_mps_with_context_manager': 'profile MPS GPU operations using the profile context manager with interval tracing', 'profile_mps_wait_completed': 'profile MPS GPU operations using the profile context manager with wait_until_completed for single dispatch timeline'}
```

