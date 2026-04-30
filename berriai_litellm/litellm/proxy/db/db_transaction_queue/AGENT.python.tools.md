# Agent Python Tools

- repo: berriai/litellm
- repo_uri: https://github.com/berriai/litellm

## File: berriai_litellm/litellm/proxy/db/db_transaction_queue/daily_spend_update_queue.py

Prompts

```
['create a DailySpendUpdateQueue instance to buffer in-memory daily spend updates for database commits', 'add_update daily spend transactions to the queue with spend, token, and request count metrics', 'aggregate_queue_updates combines all queued updates into a single aggregated entry to reduce queue size', 'flush_and_get_aggregated_daily_spend_update_transactions retrieves and aggregates all queued updates by transaction key', 'get_aggregated_daily_spend_update_transactions statically merges multiple update dicts by summing spend and token metrics', 'create a PodLockManager instance to manage distributed Redis locks for cron jobs across pods', 'get_redis_lock_key builds a Redis lock key string from a cronjob_id for pod lock management', 'acquire_lock attempts to acquire a Redis lock for a cronjob_id with optional TTL across distributed pods', 'release_lock releases a Redis lock for a cronjob_id using atomic compare-and-delete to prevent races', 'compare_and_delete_lock atomically deletes a Redis lock key only if the current pod owns it', 'create a SpendUpdateQueue instance to buffer in-memory spend updates before committing to the database', 'add a spend update item to the in-memory queue with entity type, entity id, and response cost', 'aggregate all spend update items in the queue by entity type and entity id to reduce queue size', 'flush all queued updates and return aggregated DB spend update transactions grouped by entity type', 'aggregate a list of spend update items into DBSpendUpdateTransactions grouped by entity type and id', 'create a ToolDiscoveryQueue instance for in-memory tool registry upsert buffering', 'build a tool discovery item and add it to the queue via add_update with set-deduplication by tool_name', 'test the flush method returns pending items and clears the seen-set for the next cycle', 'refactor the add_update method to skip enqueueing items with empty tool_name', 'review the ToolDiscoveryQueue class and its deduplication logic across flush cycles']
```

Usage

```
{'create_DailySpendUpdateQueue': 'create a DailySpendUpdateQueue instance to buffer in-memory daily spend updates for database commits', 'add_update_DailySpendUpdateQueue': 'add_update daily spend transactions to the queue with spend, token, and request count metrics', 'aggregate_queue_updates_DailySpendUpdateQueue': 'aggregate_queue_updates combines all queued updates into a single aggregated entry to reduce queue size', 'flush_and_get_aggregated_daily_spend_update_transactions_DailySpendUpdateQueue': 'flush_and_get_aggregated_daily_spend_update_transactions retrieves and aggregates all queued updates by transaction key', 'get_aggregated_daily_spend_update_transactions_DailySpendUpdateQueue': 'get_aggregated_daily_spend_update_transactions statically merges multiple update dicts by summing spend and token metrics'}
```

## File: berriai_litellm/litellm/proxy/db/db_transaction_queue/pod_lock_manager.py

Prompts

```
['create a DailySpendUpdateQueue instance to buffer in-memory daily spend updates for database commits', 'add_update daily spend transactions to the queue with spend, token, and request count metrics', 'aggregate_queue_updates combines all queued updates into a single aggregated entry to reduce queue size', 'flush_and_get_aggregated_daily_spend_update_transactions retrieves and aggregates all queued updates by transaction key', 'get_aggregated_daily_spend_update_transactions statically merges multiple update dicts by summing spend and token metrics', 'create a PodLockManager instance to manage distributed Redis locks for cron jobs across pods', 'get_redis_lock_key builds a Redis lock key string from a cronjob_id for pod lock management', 'acquire_lock attempts to acquire a Redis lock for a cronjob_id with optional TTL across distributed pods', 'release_lock releases a Redis lock for a cronjob_id using atomic compare-and-delete to prevent races', 'compare_and_delete_lock atomically deletes a Redis lock key only if the current pod owns it', 'create a SpendUpdateQueue instance to buffer in-memory spend updates before committing to the database', 'add a spend update item to the in-memory queue with entity type, entity id, and response cost', 'aggregate all spend update items in the queue by entity type and entity id to reduce queue size', 'flush all queued updates and return aggregated DB spend update transactions grouped by entity type', 'aggregate a list of spend update items into DBSpendUpdateTransactions grouped by entity type and id', 'create a ToolDiscoveryQueue instance for in-memory tool registry upsert buffering', 'build a tool discovery item and add it to the queue via add_update with set-deduplication by tool_name', 'test the flush method returns pending items and clears the seen-set for the next cycle', 'refactor the add_update method to skip enqueueing items with empty tool_name', 'review the ToolDiscoveryQueue class and its deduplication logic across flush cycles']
```

Usage

```
{'create_PodLockManager': 'create a PodLockManager instance to manage distributed Redis locks for cron jobs across pods', 'get_redis_lock_key_PodLockManager': 'get_redis_lock_key builds a Redis lock key string from a cronjob_id for pod lock management', 'acquire_lock_PodLockManager': 'acquire_lock attempts to acquire a Redis lock for a cronjob_id with optional TTL across distributed pods', 'release_lock_PodLockManager': 'release_lock releases a Redis lock for a cronjob_id using atomic compare-and-delete to prevent races', 'compare_and_delete_lock_PodLockManager': 'compare_and_delete_lock atomically deletes a Redis lock key only if the current pod owns it'}
```

## File: berriai_litellm/litellm/proxy/db/db_transaction_queue/spend_update_queue.py

Prompts

```
['create a DailySpendUpdateQueue instance to buffer in-memory daily spend updates for database commits', 'add_update daily spend transactions to the queue with spend, token, and request count metrics', 'aggregate_queue_updates combines all queued updates into a single aggregated entry to reduce queue size', 'flush_and_get_aggregated_daily_spend_update_transactions retrieves and aggregates all queued updates by transaction key', 'get_aggregated_daily_spend_update_transactions statically merges multiple update dicts by summing spend and token metrics', 'create a PodLockManager instance to manage distributed Redis locks for cron jobs across pods', 'get_redis_lock_key builds a Redis lock key string from a cronjob_id for pod lock management', 'acquire_lock attempts to acquire a Redis lock for a cronjob_id with optional TTL across distributed pods', 'release_lock releases a Redis lock for a cronjob_id using atomic compare-and-delete to prevent races', 'compare_and_delete_lock atomically deletes a Redis lock key only if the current pod owns it', 'create a SpendUpdateQueue instance to buffer in-memory spend updates before committing to the database', 'add a spend update item to the in-memory queue with entity type, entity id, and response cost', 'aggregate all spend update items in the queue by entity type and entity id to reduce queue size', 'flush all queued updates and return aggregated DB spend update transactions grouped by entity type', 'aggregate a list of spend update items into DBSpendUpdateTransactions grouped by entity type and id', 'create a ToolDiscoveryQueue instance for in-memory tool registry upsert buffering', 'build a tool discovery item and add it to the queue via add_update with set-deduplication by tool_name', 'test the flush method returns pending items and clears the seen-set for the next cycle', 'refactor the add_update method to skip enqueueing items with empty tool_name', 'review the ToolDiscoveryQueue class and its deduplication logic across flush cycles']
```

Usage

```
{'create_SpendUpdateQueue': 'create a SpendUpdateQueue instance to buffer in-memory spend updates before committing to the database', 'add_update_to_queue': 'add a spend update item to the in-memory queue with entity type, entity id, and response cost', 'aggregate_queue_updates': 'aggregate all spend update items in the queue by entity type and entity id to reduce queue size', 'flush_and_get_aggregated_db_spend_update_transactions': 'flush all queued updates and return aggregated DB spend update transactions grouped by entity type', 'get_aggregated_db_spend_update_transactions': 'aggregate a list of spend update items into DBSpendUpdateTransactions grouped by entity type and id'}
```

## File: berriai_litellm/litellm/proxy/db/db_transaction_queue/tool_discovery_queue.py

Prompts

```
['create a DailySpendUpdateQueue instance to buffer in-memory daily spend updates for database commits', 'add_update daily spend transactions to the queue with spend, token, and request count metrics', 'aggregate_queue_updates combines all queued updates into a single aggregated entry to reduce queue size', 'flush_and_get_aggregated_daily_spend_update_transactions retrieves and aggregates all queued updates by transaction key', 'get_aggregated_daily_spend_update_transactions statically merges multiple update dicts by summing spend and token metrics', 'create a PodLockManager instance to manage distributed Redis locks for cron jobs across pods', 'get_redis_lock_key builds a Redis lock key string from a cronjob_id for pod lock management', 'acquire_lock attempts to acquire a Redis lock for a cronjob_id with optional TTL across distributed pods', 'release_lock releases a Redis lock for a cronjob_id using atomic compare-and-delete to prevent races', 'compare_and_delete_lock atomically deletes a Redis lock key only if the current pod owns it', 'create a SpendUpdateQueue instance to buffer in-memory spend updates before committing to the database', 'add a spend update item to the in-memory queue with entity type, entity id, and response cost', 'aggregate all spend update items in the queue by entity type and entity id to reduce queue size', 'flush all queued updates and return aggregated DB spend update transactions grouped by entity type', 'aggregate a list of spend update items into DBSpendUpdateTransactions grouped by entity type and id', 'create a ToolDiscoveryQueue instance for in-memory tool registry upsert buffering', 'build a tool discovery item and add it to the queue via add_update with set-deduplication by tool_name', 'test the flush method returns pending items and clears the seen-set for the next cycle', 'refactor the add_update method to skip enqueueing items with empty tool_name', 'review the ToolDiscoveryQueue class and its deduplication logic across flush cycles']
```

Usage

```
{'create_tool_discovery_queue': 'create a ToolDiscoveryQueue instance for in-memory tool registry upsert buffering', 'build_add_update': 'build a tool discovery item and add it to the queue via add_update with set-deduplication by tool_name', 'test_flush': 'test the flush method returns pending items and clears the seen-set for the next cycle', 'refactor_add_update': 'refactor the add_update method to skip enqueueing items with empty tool_name', 'review_tool_discovery_queue': 'review the ToolDiscoveryQueue class and its deduplication logic across flush cycles'}
```

