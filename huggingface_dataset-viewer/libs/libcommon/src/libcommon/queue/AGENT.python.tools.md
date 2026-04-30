# Agent Python Tools

- repo: huggingface/dataset-viewer
- repo_uri: https://github.com/huggingface/dataset-viewer

## File: huggingface_dataset-viewer/libs/libcommon/src/libcommon/queue/dataset_blockages.py

Prompts

```
['create a dataset blockage in the mongoDB database for a given dataset name', 'return the list of all currently blocked datasets from the database', 'check if a specific dataset is currently blocked and return a boolean', 'create a mongoengine document to represent a dataset blockage with dataset and blocked_at fields', 'review the constant that sets the 6 hour TTL expiration for dataset blockages', 'add a job to the queue with a type, dataset, revision, and difficulty level', 'start the next waiting job from the queue by priority and creation date', 'finish a started job, delete it from the queue, and release its lock', 'get zombie jobs that have not sent heartbeats within a maximum time threshold', 'delete all waiting jobs for a given dataset and release their locks', 'create a MongoDB lock context manager with a key and owner to prevent concurrent access', 'acquire a MongoDB lock with exponential backoff retry and raise TimeoutError on failure', 'release a MongoDB lock by setting the owner to None for a given key', 'lock a git branch of a dataset on the hub for read/write operations using lock.git_branch', 'review the Lock mongoengine Document schema with key, owner, ttl, and TTL indexes', 'increase the job total metric count for a given dataset job type and status in MongoDB', 'decrease the job total metric count for a given job type and status in MongoDB', 'update metrics by decreasing the previous status count and increasing the new status count for a job type', 'decrease the worker size jobs count metric by difficulty level in MongoDB', 'get the worker size category from a job difficulty value using the WorkerSizeJobsCountDocument class', 'create a past job entry in MongoDB with dataset name, start time, and finish time', 'query PastJobDocument objects by dataset to sum durations and check rate limiting thresholds', 'configure the RATE_LIMIT_WINDOW_SECONDS constant to control how long past job records are retained', 'set an ALLOWED_COMPUTE_MULTIPLIER for a dataset to allocate more compute time than the default threshold', 'define a mongoengine PastJobDocument schema with dataset, duration, and finished_at fields for job tracking']
```

Usage

```
{'block_dataset': 'create a dataset blockage in the mongoDB database for a given dataset name', 'get_blocked_datasets': 'return the list of all currently blocked datasets from the database', 'is_blocked': 'check if a specific dataset is currently blocked and return a boolean', 'DatasetBlockageDocument': 'create a mongoengine document to represent a dataset blockage with dataset and blocked_at fields', 'DATASET_BLOCKAGE_EXPIRE_AFTER_SECONDS': 'review the constant that sets the 6 hour TTL expiration for dataset blockages'}
```

## File: huggingface_dataset-viewer/libs/libcommon/src/libcommon/queue/jobs.py

Prompts

```
['create a dataset blockage in the mongoDB database for a given dataset name', 'return the list of all currently blocked datasets from the database', 'check if a specific dataset is currently blocked and return a boolean', 'create a mongoengine document to represent a dataset blockage with dataset and blocked_at fields', 'review the constant that sets the 6 hour TTL expiration for dataset blockages', 'add a job to the queue with a type, dataset, revision, and difficulty level', 'start the next waiting job from the queue by priority and creation date', 'finish a started job, delete it from the queue, and release its lock', 'get zombie jobs that have not sent heartbeats within a maximum time threshold', 'delete all waiting jobs for a given dataset and release their locks', 'create a MongoDB lock context manager with a key and owner to prevent concurrent access', 'acquire a MongoDB lock with exponential backoff retry and raise TimeoutError on failure', 'release a MongoDB lock by setting the owner to None for a given key', 'lock a git branch of a dataset on the hub for read/write operations using lock.git_branch', 'review the Lock mongoengine Document schema with key, owner, ttl, and TTL indexes', 'increase the job total metric count for a given dataset job type and status in MongoDB', 'decrease the job total metric count for a given job type and status in MongoDB', 'update metrics by decreasing the previous status count and increasing the new status count for a job type', 'decrease the worker size jobs count metric by difficulty level in MongoDB', 'get the worker size category from a job difficulty value using the WorkerSizeJobsCountDocument class', 'create a past job entry in MongoDB with dataset name, start time, and finish time', 'query PastJobDocument objects by dataset to sum durations and check rate limiting thresholds', 'configure the RATE_LIMIT_WINDOW_SECONDS constant to control how long past job records are retained', 'set an ALLOWED_COMPUTE_MULTIPLIER for a dataset to allocate more compute time than the default threshold', 'define a mongoengine PastJobDocument schema with dataset, duration, and finished_at fields for job tracking']
```

Usage

```
{'add_job_to_queue': 'add a job to the queue with a type, dataset, revision, and difficulty level', 'start_next_waiting_job': 'start the next waiting job from the queue by priority and creation date', 'finish_job_and_release_lock': 'finish a started job, delete it from the queue, and release its lock', 'get_zombie_jobs': 'get zombie jobs that have not sent heartbeats within a maximum time threshold', 'delete_dataset_waiting_jobs': 'delete all waiting jobs for a given dataset and release their locks'}
```

## File: huggingface_dataset-viewer/libs/libcommon/src/libcommon/queue/lock.py

Prompts

```
['create a dataset blockage in the mongoDB database for a given dataset name', 'return the list of all currently blocked datasets from the database', 'check if a specific dataset is currently blocked and return a boolean', 'create a mongoengine document to represent a dataset blockage with dataset and blocked_at fields', 'review the constant that sets the 6 hour TTL expiration for dataset blockages', 'add a job to the queue with a type, dataset, revision, and difficulty level', 'start the next waiting job from the queue by priority and creation date', 'finish a started job, delete it from the queue, and release its lock', 'get zombie jobs that have not sent heartbeats within a maximum time threshold', 'delete all waiting jobs for a given dataset and release their locks', 'create a MongoDB lock context manager with a key and owner to prevent concurrent access', 'acquire a MongoDB lock with exponential backoff retry and raise TimeoutError on failure', 'release a MongoDB lock by setting the owner to None for a given key', 'lock a git branch of a dataset on the hub for read/write operations using lock.git_branch', 'review the Lock mongoengine Document schema with key, owner, ttl, and TTL indexes', 'increase the job total metric count for a given dataset job type and status in MongoDB', 'decrease the job total metric count for a given job type and status in MongoDB', 'update metrics by decreasing the previous status count and increasing the new status count for a job type', 'decrease the worker size jobs count metric by difficulty level in MongoDB', 'get the worker size category from a job difficulty value using the WorkerSizeJobsCountDocument class', 'create a past job entry in MongoDB with dataset name, start time, and finish time', 'query PastJobDocument objects by dataset to sum durations and check rate limiting thresholds', 'configure the RATE_LIMIT_WINDOW_SECONDS constant to control how long past job records are retained', 'set an ALLOWED_COMPUTE_MULTIPLIER for a dataset to allocate more compute time than the default threshold', 'define a mongoengine PastJobDocument schema with dataset, duration, and finished_at fields for job tracking']
```

Usage

```
{'create_lock_context_manager': 'create a MongoDB lock context manager with a key and owner to prevent concurrent access', 'acquire_lock_with_retry': 'acquire a MongoDB lock with exponential backoff retry and raise TimeoutError on failure', 'release_lock_by_key': 'release a MongoDB lock by setting the owner to None for a given key', 'lock_git_branch': 'lock a git branch of a dataset on the hub for read/write operations using lock.git_branch', 'review_lock_document_schema': 'review the Lock mongoengine Document schema with key, owner, ttl, and TTL indexes'}
```

## File: huggingface_dataset-viewer/libs/libcommon/src/libcommon/queue/metrics.py

Prompts

```
['create a dataset blockage in the mongoDB database for a given dataset name', 'return the list of all currently blocked datasets from the database', 'check if a specific dataset is currently blocked and return a boolean', 'create a mongoengine document to represent a dataset blockage with dataset and blocked_at fields', 'review the constant that sets the 6 hour TTL expiration for dataset blockages', 'add a job to the queue with a type, dataset, revision, and difficulty level', 'start the next waiting job from the queue by priority and creation date', 'finish a started job, delete it from the queue, and release its lock', 'get zombie jobs that have not sent heartbeats within a maximum time threshold', 'delete all waiting jobs for a given dataset and release their locks', 'create a MongoDB lock context manager with a key and owner to prevent concurrent access', 'acquire a MongoDB lock with exponential backoff retry and raise TimeoutError on failure', 'release a MongoDB lock by setting the owner to None for a given key', 'lock a git branch of a dataset on the hub for read/write operations using lock.git_branch', 'review the Lock mongoengine Document schema with key, owner, ttl, and TTL indexes', 'increase the job total metric count for a given dataset job type and status in MongoDB', 'decrease the job total metric count for a given job type and status in MongoDB', 'update metrics by decreasing the previous status count and increasing the new status count for a job type', 'decrease the worker size jobs count metric by difficulty level in MongoDB', 'get the worker size category from a job difficulty value using the WorkerSizeJobsCountDocument class', 'create a past job entry in MongoDB with dataset name, start time, and finish time', 'query PastJobDocument objects by dataset to sum durations and check rate limiting thresholds', 'configure the RATE_LIMIT_WINDOW_SECONDS constant to control how long past job records are retained', 'set an ALLOWED_COMPUTE_MULTIPLIER for a dataset to allocate more compute time than the default threshold', 'define a mongoengine PastJobDocument schema with dataset, duration, and finished_at fields for job tracking']
```

Usage

```
{'increase_metric': 'increase the job total metric count for a given dataset job type and status in MongoDB', 'decrease_metric': 'decrease the job total metric count for a given job type and status in MongoDB', 'update_metrics_for_type': 'update metrics by decreasing the previous status count and increasing the new status count for a job type', 'decrease_worker_size_metrics': 'decrease the worker size jobs count metric by difficulty level in MongoDB', 'get_worker_size': 'get the worker size category from a job difficulty value using the WorkerSizeJobsCountDocument class'}
```

## File: huggingface_dataset-viewer/libs/libcommon/src/libcommon/queue/past_jobs.py

Prompts

```
['create a dataset blockage in the mongoDB database for a given dataset name', 'return the list of all currently blocked datasets from the database', 'check if a specific dataset is currently blocked and return a boolean', 'create a mongoengine document to represent a dataset blockage with dataset and blocked_at fields', 'review the constant that sets the 6 hour TTL expiration for dataset blockages', 'add a job to the queue with a type, dataset, revision, and difficulty level', 'start the next waiting job from the queue by priority and creation date', 'finish a started job, delete it from the queue, and release its lock', 'get zombie jobs that have not sent heartbeats within a maximum time threshold', 'delete all waiting jobs for a given dataset and release their locks', 'create a MongoDB lock context manager with a key and owner to prevent concurrent access', 'acquire a MongoDB lock with exponential backoff retry and raise TimeoutError on failure', 'release a MongoDB lock by setting the owner to None for a given key', 'lock a git branch of a dataset on the hub for read/write operations using lock.git_branch', 'review the Lock mongoengine Document schema with key, owner, ttl, and TTL indexes', 'increase the job total metric count for a given dataset job type and status in MongoDB', 'decrease the job total metric count for a given job type and status in MongoDB', 'update metrics by decreasing the previous status count and increasing the new status count for a job type', 'decrease the worker size jobs count metric by difficulty level in MongoDB', 'get the worker size category from a job difficulty value using the WorkerSizeJobsCountDocument class', 'create a past job entry in MongoDB with dataset name, start time, and finish time', 'query PastJobDocument objects by dataset to sum durations and check rate limiting thresholds', 'configure the RATE_LIMIT_WINDOW_SECONDS constant to control how long past job records are retained', 'set an ALLOWED_COMPUTE_MULTIPLIER for a dataset to allocate more compute time than the default threshold', 'define a mongoengine PastJobDocument schema with dataset, duration, and finished_at fields for job tracking']
```

Usage

```
{'create_past_job': 'create a past job entry in MongoDB with dataset name, start time, and finish time', 'query_past_job_documents': 'query PastJobDocument objects by dataset to sum durations and check rate limiting thresholds', 'configure_rate_limit_window': 'configure the RATE_LIMIT_WINDOW_SECONDS constant to control how long past job records are retained', 'set_compute_multiplier': 'set an ALLOWED_COMPUTE_MULTIPLIER for a dataset to allocate more compute time than the default threshold', 'define_past_job_document_schema': 'define a mongoengine PastJobDocument schema with dataset, duration, and finished_at fields for job tracking'}
```

