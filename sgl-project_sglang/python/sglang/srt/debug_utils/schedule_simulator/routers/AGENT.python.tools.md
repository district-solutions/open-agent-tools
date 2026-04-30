# Agent Python Tools

- repo: sgl-project/sglang
- repo_uri: https://github.com/sgl-project/sglang

## File: sgl-project_sglang/python/sglang/srt/debug_utils/schedule_simulator/routers/base.py

Prompts

```
['review the RouterPolicy abstract class and its route method', 'test the RouterPolicy abstract base class and its route method signature', 'refactor the RouterPolicy class to add additional routing logic', 'create a concrete subclass of RouterPolicy that implements the route method', 'summarize the RouterPolicy abstract class and its purpose', 'create a RandomRouter instance with a specified number of GPUs for random request routing', 'route an incoming SimRequest to a random GPU using RandomRouter', 'build a RouterPolicy subclass that implements the abstract route method for GPU selection', 'create a SimRequest dataclass instance with request_id, input_len, and output_len fields', 'test the SimRequest seq_len and is_finished methods for request lifecycle tracking', 'create a RoundRobinRouter with a specified number of GPUs for distributing requests across GPU instances', 'route a SimRequest to the next available GPU using round-robin scheduling', 'build a RoundRobinRouter instance that cycles through GPUs in order for each incoming request', 'test that RoundRobinRouter distributes requests evenly across all GPUs in round-robin fashion', 'review the RoundRobinRouter class and its route method for GPU assignment logic', 'create a StickyRouter instance with a specified number of GPUs for routing requests', 'route a SimRequest to a GPU based on its group_id with sticky assignment', 'assign a random GPU index from 0 to num_gpus-1 for a new request group', 'test the StickyRouter routes requests to the same GPU for repeated group_ids', 'review the StickyRouter class and its group-to-GPU sticky routing policy']
```

Usage

```
{'review_ROUTER_POLICY': 'review the RouterPolicy abstract class and its route method', 'test_ROUTER_POLICY_ROUTE': 'test the RouterPolicy abstract base class and its route method signature', 'refactor_ROUTER_POLICY': 'refactor the RouterPolicy class to add additional routing logic', 'create_ROUTER_POLICY_SUBCLASS': 'create a concrete subclass of RouterPolicy that implements the route method', 'summarize_ROUTER_POLICY': 'summarize the RouterPolicy abstract class and its purpose'}
```

## File: sgl-project_sglang/python/sglang/srt/debug_utils/schedule_simulator/routers/random_router.py

Prompts

```
['review the RouterPolicy abstract class and its route method', 'test the RouterPolicy abstract base class and its route method signature', 'refactor the RouterPolicy class to add additional routing logic', 'create a concrete subclass of RouterPolicy that implements the route method', 'summarize the RouterPolicy abstract class and its purpose', 'create a RandomRouter instance with a specified number of GPUs for random request routing', 'route an incoming SimRequest to a random GPU using RandomRouter', 'build a RouterPolicy subclass that implements the abstract route method for GPU selection', 'create a SimRequest dataclass instance with request_id, input_len, and output_len fields', 'test the SimRequest seq_len and is_finished methods for request lifecycle tracking', 'create a RoundRobinRouter with a specified number of GPUs for distributing requests across GPU instances', 'route a SimRequest to the next available GPU using round-robin scheduling', 'build a RoundRobinRouter instance that cycles through GPUs in order for each incoming request', 'test that RoundRobinRouter distributes requests evenly across all GPUs in round-robin fashion', 'review the RoundRobinRouter class and its route method for GPU assignment logic', 'create a StickyRouter instance with a specified number of GPUs for routing requests', 'route a SimRequest to a GPU based on its group_id with sticky assignment', 'assign a random GPU index from 0 to num_gpus-1 for a new request group', 'test the StickyRouter routes requests to the same GPU for repeated group_ids', 'review the StickyRouter class and its group-to-GPU sticky routing policy']
```

Usage

```
{'create_RandomRouter': 'create a RandomRouter instance with a specified number of GPUs for random request routing', 'route_request_random_router': 'route an incoming SimRequest to a random GPU using RandomRouter', 'build_RouterPolicy_subclass': 'build a RouterPolicy subclass that implements the abstract route method for GPU selection', 'create_SimRequest': 'create a SimRequest dataclass instance with request_id, input_len, and output_len fields', 'test_SimRequest_methods': 'test the SimRequest seq_len and is_finished methods for request lifecycle tracking'}
```

## File: sgl-project_sglang/python/sglang/srt/debug_utils/schedule_simulator/routers/round_robin_router.py

Prompts

```
['review the RouterPolicy abstract class and its route method', 'test the RouterPolicy abstract base class and its route method signature', 'refactor the RouterPolicy class to add additional routing logic', 'create a concrete subclass of RouterPolicy that implements the route method', 'summarize the RouterPolicy abstract class and its purpose', 'create a RandomRouter instance with a specified number of GPUs for random request routing', 'route an incoming SimRequest to a random GPU using RandomRouter', 'build a RouterPolicy subclass that implements the abstract route method for GPU selection', 'create a SimRequest dataclass instance with request_id, input_len, and output_len fields', 'test the SimRequest seq_len and is_finished methods for request lifecycle tracking', 'create a RoundRobinRouter with a specified number of GPUs for distributing requests across GPU instances', 'route a SimRequest to the next available GPU using round-robin scheduling', 'build a RoundRobinRouter instance that cycles through GPUs in order for each incoming request', 'test that RoundRobinRouter distributes requests evenly across all GPUs in round-robin fashion', 'review the RoundRobinRouter class and its route method for GPU assignment logic', 'create a StickyRouter instance with a specified number of GPUs for routing requests', 'route a SimRequest to a GPU based on its group_id with sticky assignment', 'assign a random GPU index from 0 to num_gpus-1 for a new request group', 'test the StickyRouter routes requests to the same GPU for repeated group_ids', 'review the StickyRouter class and its group-to-GPU sticky routing policy']
```

Usage

```
{'create_round_robin_router': 'create a RoundRobinRouter with a specified number of GPUs for distributing requests across GPU instances', 'route_request_round_robin': 'route a SimRequest to the next available GPU using round-robin scheduling', 'build_round_robin_router': 'build a RoundRobinRouter instance that cycles through GPUs in order for each incoming request', 'test_round_robin_distribution': 'test that RoundRobinRouter distributes requests evenly across all GPUs in round-robin fashion', 'review_round_robin_router': 'review the RoundRobinRouter class and its route method for GPU assignment logic'}
```

## File: sgl-project_sglang/python/sglang/srt/debug_utils/schedule_simulator/routers/sticky_router.py

Prompts

```
['review the RouterPolicy abstract class and its route method', 'test the RouterPolicy abstract base class and its route method signature', 'refactor the RouterPolicy class to add additional routing logic', 'create a concrete subclass of RouterPolicy that implements the route method', 'summarize the RouterPolicy abstract class and its purpose', 'create a RandomRouter instance with a specified number of GPUs for random request routing', 'route an incoming SimRequest to a random GPU using RandomRouter', 'build a RouterPolicy subclass that implements the abstract route method for GPU selection', 'create a SimRequest dataclass instance with request_id, input_len, and output_len fields', 'test the SimRequest seq_len and is_finished methods for request lifecycle tracking', 'create a RoundRobinRouter with a specified number of GPUs for distributing requests across GPU instances', 'route a SimRequest to the next available GPU using round-robin scheduling', 'build a RoundRobinRouter instance that cycles through GPUs in order for each incoming request', 'test that RoundRobinRouter distributes requests evenly across all GPUs in round-robin fashion', 'review the RoundRobinRouter class and its route method for GPU assignment logic', 'create a StickyRouter instance with a specified number of GPUs for routing requests', 'route a SimRequest to a GPU based on its group_id with sticky assignment', 'assign a random GPU index from 0 to num_gpus-1 for a new request group', 'test the StickyRouter routes requests to the same GPU for repeated group_ids', 'review the StickyRouter class and its group-to-GPU sticky routing policy']
```

Usage

```
{'create_sticky_router': 'create a StickyRouter instance with a specified number of GPUs for routing requests', 'route_request': 'route a SimRequest to a GPU based on its group_id with sticky assignment', 'assign_gpu': 'assign a random GPU index from 0 to num_gpus-1 for a new request group', 'test_sticky_router': 'test the StickyRouter routes requests to the same GPU for repeated group_ids', 'review_sticky_router': 'review the StickyRouter class and its group-to-GPU sticky routing policy'}
```

