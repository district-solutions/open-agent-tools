# Agent Python Tools

- repo: vllm-project/vllm
- repo_uri: https://github.com/vllm-project/vllm

## File: vllm-project_vllm/vllm/v1/core/sched/interface.py

Prompts

```
['schedule requests for processing in a single forward pass of the vLLM model', 'update scheduler state based on model runner output including generated token ids and draft token ids', "add a new request to the scheduler's internal queue for processing", 'finish requests in the scheduler queue by request id with a specified finished status', 'reset the KV cache prefix cache for the scheduler optionally preempting running requests', 'create NewRequestData from a Request object with block IDs and optional prefill token IDs', 'build an empty CachedRequestData instance with zeroed lists and sets for scheduling', 'build an empty SchedulerOutput with no scheduled requests or finished IDs', 'test whether a request is in context phase by checking its num_output_tokens via is_context_phase', 'summarize SchedulerOutput fields including scheduled new/cached requests, token counts, and connector metadata', 'create a request queue factory function that instantiates FCFS or priority queue based on SchedulingPolicy', 'build a first-come-first-served request queue supporting add, pop, peek, prepend, and remove operations', 'build a priority request queue backed by a min-heap ordered by priority then arrival time', 'test the abstract RequestQueue interface with add, pop, peek, prepend, and remove methods', 'review the SchedulingPolicy enum with FCFS and PRIORITY scheduling options', 'preempt a running request by freeing its KV cache blocks and moving it back to the waiting queue', 'test check_sequence_repetition to detect repeating patterns in a sequence of token IDs', 'test check_stop to determine if a vLLM request should stop generating output', 'test remove_all to remove specified items from a Python list', 'review check_sequence_repetition for detecting repetition patterns in token sequences', 'review check_stop for evaluating vLLM request termination conditions']
```

Usage

```
{'schedule_requests': 'schedule requests for processing in a single forward pass of the vLLM model', 'update_from_output': 'update scheduler state based on model runner output including generated token ids and draft token ids', 'add_request': "add a new request to the scheduler's internal queue for processing", 'finish_requests': 'finish requests in the scheduler queue by request id with a specified finished status', 'reset_prefix_cache': 'reset the KV cache prefix cache for the scheduler optionally preempting running requests'}
```

## File: vllm-project_vllm/vllm/v1/core/sched/output.py

Prompts

```
['schedule requests for processing in a single forward pass of the vLLM model', 'update scheduler state based on model runner output including generated token ids and draft token ids', "add a new request to the scheduler's internal queue for processing", 'finish requests in the scheduler queue by request id with a specified finished status', 'reset the KV cache prefix cache for the scheduler optionally preempting running requests', 'create NewRequestData from a Request object with block IDs and optional prefill token IDs', 'build an empty CachedRequestData instance with zeroed lists and sets for scheduling', 'build an empty SchedulerOutput with no scheduled requests or finished IDs', 'test whether a request is in context phase by checking its num_output_tokens via is_context_phase', 'summarize SchedulerOutput fields including scheduled new/cached requests, token counts, and connector metadata', 'create a request queue factory function that instantiates FCFS or priority queue based on SchedulingPolicy', 'build a first-come-first-served request queue supporting add, pop, peek, prepend, and remove operations', 'build a priority request queue backed by a min-heap ordered by priority then arrival time', 'test the abstract RequestQueue interface with add, pop, peek, prepend, and remove methods', 'review the SchedulingPolicy enum with FCFS and PRIORITY scheduling options', 'preempt a running request by freeing its KV cache blocks and moving it back to the waiting queue', 'test check_sequence_repetition to detect repeating patterns in a sequence of token IDs', 'test check_stop to determine if a vLLM request should stop generating output', 'test remove_all to remove specified items from a Python list', 'review check_sequence_repetition for detecting repetition patterns in token sequences', 'review check_stop for evaluating vLLM request termination conditions']
```

Usage

```
{'create_NewRequestData_from_request': 'create NewRequestData from a Request object with block IDs and optional prefill token IDs', 'build_CachedRequestData_make_empty': 'build an empty CachedRequestData instance with zeroed lists and sets for scheduling', 'build_SchedulerOutput_make_empty': 'build an empty SchedulerOutput with no scheduled requests or finished IDs', 'test_CachedRequestData_is_context_phase': 'test whether a request is in context phase by checking its num_output_tokens via is_context_phase', 'summarize_SchedulerOutput_fields': 'summarize SchedulerOutput fields including scheduled new/cached requests, token counts, and connector metadata'}
```

## File: vllm-project_vllm/vllm/v1/core/sched/request_queue.py

Prompts

```
['schedule requests for processing in a single forward pass of the vLLM model', 'update scheduler state based on model runner output including generated token ids and draft token ids', "add a new request to the scheduler's internal queue for processing", 'finish requests in the scheduler queue by request id with a specified finished status', 'reset the KV cache prefix cache for the scheduler optionally preempting running requests', 'create NewRequestData from a Request object with block IDs and optional prefill token IDs', 'build an empty CachedRequestData instance with zeroed lists and sets for scheduling', 'build an empty SchedulerOutput with no scheduled requests or finished IDs', 'test whether a request is in context phase by checking its num_output_tokens via is_context_phase', 'summarize SchedulerOutput fields including scheduled new/cached requests, token counts, and connector metadata', 'create a request queue factory function that instantiates FCFS or priority queue based on SchedulingPolicy', 'build a first-come-first-served request queue supporting add, pop, peek, prepend, and remove operations', 'build a priority request queue backed by a min-heap ordered by priority then arrival time', 'test the abstract RequestQueue interface with add, pop, peek, prepend, and remove methods', 'review the SchedulingPolicy enum with FCFS and PRIORITY scheduling options', 'preempt a running request by freeing its KV cache blocks and moving it back to the waiting queue', 'test check_sequence_repetition to detect repeating patterns in a sequence of token IDs', 'test check_stop to determine if a vLLM request should stop generating output', 'test remove_all to remove specified items from a Python list', 'review check_sequence_repetition for detecting repetition patterns in token sequences', 'review check_stop for evaluating vLLM request termination conditions']
```

Usage

```
{'create_request_queue': 'create a request queue factory function that instantiates FCFS or priority queue based on SchedulingPolicy', 'build_fcfs_request_queue': 'build a first-come-first-served request queue supporting add, pop, peek, prepend, and remove operations', 'build_priority_request_queue': 'build a priority request queue backed by a min-heap ordered by priority then arrival time', 'test_request_queue_interface': 'test the abstract RequestQueue interface with add, pop, peek, prepend, and remove methods', 'review_scheduling_policy_enum': 'review the SchedulingPolicy enum with FCFS and PRIORITY scheduling options'}
```

## File: vllm-project_vllm/vllm/v1/core/sched/scheduler.py

Prompts

```
['schedule requests for processing in a single forward pass of the vLLM model', 'update scheduler state based on model runner output including generated token ids and draft token ids', "add a new request to the scheduler's internal queue for processing", 'finish requests in the scheduler queue by request id with a specified finished status', 'reset the KV cache prefix cache for the scheduler optionally preempting running requests', 'create NewRequestData from a Request object with block IDs and optional prefill token IDs', 'build an empty CachedRequestData instance with zeroed lists and sets for scheduling', 'build an empty SchedulerOutput with no scheduled requests or finished IDs', 'test whether a request is in context phase by checking its num_output_tokens via is_context_phase', 'summarize SchedulerOutput fields including scheduled new/cached requests, token counts, and connector metadata', 'create a request queue factory function that instantiates FCFS or priority queue based on SchedulingPolicy', 'build a first-come-first-served request queue supporting add, pop, peek, prepend, and remove operations', 'build a priority request queue backed by a min-heap ordered by priority then arrival time', 'test the abstract RequestQueue interface with add, pop, peek, prepend, and remove methods', 'review the SchedulingPolicy enum with FCFS and PRIORITY scheduling options', 'preempt a running request by freeing its KV cache blocks and moving it back to the waiting queue', 'test check_sequence_repetition to detect repeating patterns in a sequence of token IDs', 'test check_stop to determine if a vLLM request should stop generating output', 'test remove_all to remove specified items from a Python list', 'review check_sequence_repetition for detecting repetition patterns in token sequences', 'review check_stop for evaluating vLLM request termination conditions']
```

Usage

```
{'schedule_requests': 'schedule requests from waiting and running queues respecting token and block budget constraints', 'update_from_output': 'update scheduler state after receiving model runner output including sampled tokens and KV connector results', 'add_request': 'add a new request to the scheduler or update an existing streaming request with a new input chunk', 'preempt_request': 'preempt a running request by freeing its KV cache blocks and moving it back to the waiting queue', 'finish_requests': 'finish requests by setting their status and freeing their resources optionally aborting client connections'}
```

## File: vllm-project_vllm/vllm/v1/core/sched/utils.py

Prompts

```
['schedule requests for processing in a single forward pass of the vLLM model', 'update scheduler state based on model runner output including generated token ids and draft token ids', "add a new request to the scheduler's internal queue for processing", 'finish requests in the scheduler queue by request id with a specified finished status', 'reset the KV cache prefix cache for the scheduler optionally preempting running requests', 'create NewRequestData from a Request object with block IDs and optional prefill token IDs', 'build an empty CachedRequestData instance with zeroed lists and sets for scheduling', 'build an empty SchedulerOutput with no scheduled requests or finished IDs', 'test whether a request is in context phase by checking its num_output_tokens via is_context_phase', 'summarize SchedulerOutput fields including scheduled new/cached requests, token counts, and connector metadata', 'create a request queue factory function that instantiates FCFS or priority queue based on SchedulingPolicy', 'build a first-come-first-served request queue supporting add, pop, peek, prepend, and remove operations', 'build a priority request queue backed by a min-heap ordered by priority then arrival time', 'test the abstract RequestQueue interface with add, pop, peek, prepend, and remove methods', 'review the SchedulingPolicy enum with FCFS and PRIORITY scheduling options', 'preempt a running request by freeing its KV cache blocks and moving it back to the waiting queue', 'test check_sequence_repetition to detect repeating patterns in a sequence of token IDs', 'test check_stop to determine if a vLLM request should stop generating output', 'test remove_all to remove specified items from a Python list', 'review check_sequence_repetition for detecting repetition patterns in token sequences', 'review check_stop for evaluating vLLM request termination conditions']
```

Usage

```
{'test_check_sequence_repetition': 'test check_sequence_repetition to detect repeating patterns in a sequence of token IDs', 'test_check_stop': 'test check_stop to determine if a vLLM request should stop generating output', 'test_remove_all': 'test remove_all to remove specified items from a Python list', 'review_check_sequence_repetition': 'review check_sequence_repetition for detecting repetition patterns in token sequences', 'review_check_stop': 'review check_stop for evaluating vLLM request termination conditions'}
```

