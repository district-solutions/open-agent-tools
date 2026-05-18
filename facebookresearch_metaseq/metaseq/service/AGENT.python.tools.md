# Agent Python Tools

- repo: facebookresearch/metaseq
- repo_uri: https://github.com/facebookresearch/metaseq

## File: facebookresearch_metaseq/metaseq/service/queue.py

Prompts

```
['create a KeyedPriorityQueueCollection to group priority queues by key for worker types', 'put an item into a keyed priority queue collection using a specific key', 'get the key of the queue with the most jobs from a KeyedPriorityQueueCollection', 'create a PriorityQueueRingShard with configurable shards and deskew factor for even distribution', 'get the shard index for a given key using SHA1 hashing with optional deskewing', 'normalize newlines in a string by converting carriage returns to line feeds', 'get the IP address or hostname of the current machine', 'build a configured logger for the metaseq interactive CLI module', 'review the normalize_newlines function to understand how it handles different line ending formats', 'test the get_my_ip function to verify it returns the correct host IP address', 'create a WorkItem dataclass instance with cost, uid, return_queue, data, prompt_len, and gen_len fields', 'compare two WorkItem instances using less-than or equality operators based on cost and uid', 'call WorkItem.generate_worker to submit an encoded prompt to a batch queue and get generation results', 'call queue_key on a WorkItem to derive a PriorityQueueRingShard key from generation arguments like temperature and top_p', 'compute a WorkItem cost using the formula enc_len plus the ceiling of (enc_len divided by 10) squared']
```

Usage

```
{'create_keyed_priority_queue_collection': 'create a KeyedPriorityQueueCollection to group priority queues by key for worker types', 'put_item_into_keyed_queue': 'put an item into a keyed priority queue collection using a specific key', 'get_largest_queue_key': 'get the key of the queue with the most jobs from a KeyedPriorityQueueCollection', 'create_priority_queue_ring_shard': 'create a PriorityQueueRingShard with configurable shards and deskew factor for even distribution', 'get_shard_index_for_key': 'get the shard index for a given key using SHA1 hashing with optional deskewing'}
```

## File: facebookresearch_metaseq/metaseq/service/utils.py

Prompts

```
['create a KeyedPriorityQueueCollection to group priority queues by key for worker types', 'put an item into a keyed priority queue collection using a specific key', 'get the key of the queue with the most jobs from a KeyedPriorityQueueCollection', 'create a PriorityQueueRingShard with configurable shards and deskew factor for even distribution', 'get the shard index for a given key using SHA1 hashing with optional deskewing', 'normalize newlines in a string by converting carriage returns to line feeds', 'get the IP address or hostname of the current machine', 'build a configured logger for the metaseq interactive CLI module', 'review the normalize_newlines function to understand how it handles different line ending formats', 'test the get_my_ip function to verify it returns the correct host IP address', 'create a WorkItem dataclass instance with cost, uid, return_queue, data, prompt_len, and gen_len fields', 'compare two WorkItem instances using less-than or equality operators based on cost and uid', 'call WorkItem.generate_worker to submit an encoded prompt to a batch queue and get generation results', 'call queue_key on a WorkItem to derive a PriorityQueueRingShard key from generation arguments like temperature and top_p', 'compute a WorkItem cost using the formula enc_len plus the ceiling of (enc_len divided by 10) squared']
```

Usage

```
{'normalize_newlines': 'normalize newlines in a string by converting carriage returns to line feeds', 'get_my_ip': 'get the IP address or hostname of the current machine', 'build_logger': 'build a configured logger for the metaseq interactive CLI module', 'review_normalize_newlines': 'review the normalize_newlines function to understand how it handles different line ending formats', 'test_get_my_ip': 'test the get_my_ip function to verify it returns the correct host IP address'}
```

## File: facebookresearch_metaseq/metaseq/service/workers.py

Prompts

```
['create a KeyedPriorityQueueCollection to group priority queues by key for worker types', 'put an item into a keyed priority queue collection using a specific key', 'get the key of the queue with the most jobs from a KeyedPriorityQueueCollection', 'create a PriorityQueueRingShard with configurable shards and deskew factor for even distribution', 'get the shard index for a given key using SHA1 hashing with optional deskewing', 'normalize newlines in a string by converting carriage returns to line feeds', 'get the IP address or hostname of the current machine', 'build a configured logger for the metaseq interactive CLI module', 'review the normalize_newlines function to understand how it handles different line ending formats', 'test the get_my_ip function to verify it returns the correct host IP address', 'create a WorkItem dataclass instance with cost, uid, return_queue, data, prompt_len, and gen_len fields', 'compare two WorkItem instances using less-than or equality operators based on cost and uid', 'call WorkItem.generate_worker to submit an encoded prompt to a batch queue and get generation results', 'call queue_key on a WorkItem to derive a PriorityQueueRingShard key from generation arguments like temperature and top_p', 'compute a WorkItem cost using the formula enc_len plus the ceiling of (enc_len divided by 10) squared']
```

Usage

```
{'create_workitem_for_priority_queue': 'create a WorkItem dataclass instance with cost, uid, return_queue, data, prompt_len, and gen_len fields', 'compare_workitems_by_cost_and_uid': 'compare two WorkItem instances using less-than or equality operators based on cost and uid', 'generate_worker_for_batch_inference': 'call WorkItem.generate_worker to submit an encoded prompt to a batch queue and get generation results', 'compute_queue_key_from_generation_args': 'call queue_key on a WorkItem to derive a PriorityQueueRingShard key from generation arguments like temperature and top_p', 'calculate_workitem_cost_for_attention': 'compute a WorkItem cost using the formula enc_len plus the ceiling of (enc_len divided by 10) squared'}
```

