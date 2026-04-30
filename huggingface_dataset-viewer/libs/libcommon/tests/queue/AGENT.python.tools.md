# Agent Python Tools

- repo: huggingface/dataset-viewer
- repo_uri: https://github.com/huggingface/dataset-viewer

## File: huggingface_dataset-viewer/libs/libcommon/tests/queue/test_dataset_blockages.py

Prompts

```
['test the block_dataset function to block a dataset in the queue', 'test the get_blocked_datasets function to retrieve all blocked datasets from the queue', 'test the is_blocked function to check if a specific dataset is blocked', 'test the parametrized test_dataset_blockage function with multiple dataset input scenarios', 'run the pytest test suite for dataset blockage queue operations', 'test the Queue.add_job method to add jobs with type, dataset, revision, and difficulty', 'test the Queue.start_job method to start the highest priority waiting job from the queue', 'test the Queue.finish_job method to mark a started job as finished and record past job metrics', 'test the Queue.delete_waiting_jobs_by_job_id method to remove specific waiting jobs by their job IDs', 'test the lock context manager with multiprocessing pool to ensure concurrent jobs serialize correctly', 'test the lock.git_branch context manager to ensure concurrent git branch writes are serialized', 'test the Lock mongoengine document to verify lock key and owner fields are stored correctly', 'run a locked increment operation using the lock context manager with a custom key and owner', 'run a git branch locked increment using lock.git_branch to serialize writes to a dataset branch', 'create a past job record in MongoDB with a dataset name, start time, and finish time', 'test the create_past_job function with various durations to verify correct duration storage', 'test that create_past_job skips recording jobs with duration below the minimum threshold', 'test that create_past_job raises TypeError when given a timezone-naive started_at datetime', 'test that datasets exceeding the blockage threshold are correctly identified as blocked by get_blocked_datasets']
```

Usage

```
{'test_block_dataset': 'test the block_dataset function to block a dataset in the queue', 'test_get_blocked_datasets': 'test the get_blocked_datasets function to retrieve all blocked datasets from the queue', 'test_is_blocked': 'test the is_blocked function to check if a specific dataset is blocked', 'test_dataset_blockage_parametrized': 'test the parametrized test_dataset_blockage function with multiple dataset input scenarios', 'run_test_dataset_blockages': 'run the pytest test suite for dataset blockage queue operations'}
```

## File: huggingface_dataset-viewer/libs/libcommon/tests/queue/test_jobs.py

Prompts

```
['test the block_dataset function to block a dataset in the queue', 'test the get_blocked_datasets function to retrieve all blocked datasets from the queue', 'test the is_blocked function to check if a specific dataset is blocked', 'test the parametrized test_dataset_blockage function with multiple dataset input scenarios', 'run the pytest test suite for dataset blockage queue operations', 'test the Queue.add_job method to add jobs with type, dataset, revision, and difficulty', 'test the Queue.start_job method to start the highest priority waiting job from the queue', 'test the Queue.finish_job method to mark a started job as finished and record past job metrics', 'test the Queue.delete_waiting_jobs_by_job_id method to remove specific waiting jobs by their job IDs', 'test the lock context manager with multiprocessing pool to ensure concurrent jobs serialize correctly', 'test the lock.git_branch context manager to ensure concurrent git branch writes are serialized', 'test the Lock mongoengine document to verify lock key and owner fields are stored correctly', 'run a locked increment operation using the lock context manager with a custom key and owner', 'run a git branch locked increment using lock.git_branch to serialize writes to a dataset branch', 'create a past job record in MongoDB with a dataset name, start time, and finish time', 'test the create_past_job function with various durations to verify correct duration storage', 'test that create_past_job skips recording jobs with duration below the minimum threshold', 'test that create_past_job raises TypeError when given a timezone-naive started_at datetime', 'test that datasets exceeding the blockage threshold are correctly identified as blocked by get_blocked_datasets']
```

Usage

```
{'test_add_job': 'test the Queue.add_job method to add jobs with type, dataset, revision, and difficulty', 'test_start_job': 'test the Queue.start_job method to start the highest priority waiting job from the queue', 'test_finish_job': 'test the Queue.finish_job method to mark a started job as finished and record past job metrics', 'test_delete_waiting_jobs': 'test the Queue.delete_waiting_jobs_by_job_id method to remove specific waiting jobs by their job IDs', 'test_block_dataset': 'test the block_dataset function to rate-limit a dataset and prevent its jobs from being started'}
```

## File: huggingface_dataset-viewer/libs/libcommon/tests/queue/test_lock.py

Prompts

```
['test the block_dataset function to block a dataset in the queue', 'test the get_blocked_datasets function to retrieve all blocked datasets from the queue', 'test the is_blocked function to check if a specific dataset is blocked', 'test the parametrized test_dataset_blockage function with multiple dataset input scenarios', 'run the pytest test suite for dataset blockage queue operations', 'test the Queue.add_job method to add jobs with type, dataset, revision, and difficulty', 'test the Queue.start_job method to start the highest priority waiting job from the queue', 'test the Queue.finish_job method to mark a started job as finished and record past job metrics', 'test the Queue.delete_waiting_jobs_by_job_id method to remove specific waiting jobs by their job IDs', 'test the lock context manager with multiprocessing pool to ensure concurrent jobs serialize correctly', 'test the lock.git_branch context manager to ensure concurrent git branch writes are serialized', 'test the Lock mongoengine document to verify lock key and owner fields are stored correctly', 'run a locked increment operation using the lock context manager with a custom key and owner', 'run a git branch locked increment using lock.git_branch to serialize writes to a dataset branch', 'create a past job record in MongoDB with a dataset name, start time, and finish time', 'test the create_past_job function with various durations to verify correct duration storage', 'test that create_past_job skips recording jobs with duration below the minimum threshold', 'test that create_past_job raises TypeError when given a timezone-naive started_at datetime', 'test that datasets exceeding the blockage threshold are correctly identified as blocked by get_blocked_datasets']
```

Usage

```
{'test_lock_context_manager': 'test the lock context manager with multiprocessing pool to ensure concurrent jobs serialize correctly', 'test_lock_git_branch': 'test the lock.git_branch context manager to ensure concurrent git branch writes are serialized', 'test_Lock_document': 'test the Lock mongoengine document to verify lock key and owner fields are stored correctly', 'run_locked_increment': 'run a locked increment operation using the lock context manager with a custom key and owner', 'run_git_branch_locked_increment': 'run a git branch locked increment using lock.git_branch to serialize writes to a dataset branch'}
```

## File: huggingface_dataset-viewer/libs/libcommon/tests/queue/test_past_jobs.py

Prompts

```
['test the block_dataset function to block a dataset in the queue', 'test the get_blocked_datasets function to retrieve all blocked datasets from the queue', 'test the is_blocked function to check if a specific dataset is blocked', 'test the parametrized test_dataset_blockage function with multiple dataset input scenarios', 'run the pytest test suite for dataset blockage queue operations', 'test the Queue.add_job method to add jobs with type, dataset, revision, and difficulty', 'test the Queue.start_job method to start the highest priority waiting job from the queue', 'test the Queue.finish_job method to mark a started job as finished and record past job metrics', 'test the Queue.delete_waiting_jobs_by_job_id method to remove specific waiting jobs by their job IDs', 'test the lock context manager with multiprocessing pool to ensure concurrent jobs serialize correctly', 'test the lock.git_branch context manager to ensure concurrent git branch writes are serialized', 'test the Lock mongoengine document to verify lock key and owner fields are stored correctly', 'run a locked increment operation using the lock context manager with a custom key and owner', 'run a git branch locked increment using lock.git_branch to serialize writes to a dataset branch', 'create a past job record in MongoDB with a dataset name, start time, and finish time', 'test the create_past_job function with various durations to verify correct duration storage', 'test that create_past_job skips recording jobs with duration below the minimum threshold', 'test that create_past_job raises TypeError when given a timezone-naive started_at datetime', 'test that datasets exceeding the blockage threshold are correctly identified as blocked by get_blocked_datasets']
```

Usage

```
{'create_past_job': 'create a past job record in MongoDB with a dataset name, start time, and finish time', 'test_create_past_job': 'test the create_past_job function with various durations to verify correct duration storage', 'test_create_past_job_with_short_duration': 'test that create_past_job skips recording jobs with duration below the minimum threshold', 'test_create_past_job_raises_if_timezone_unaware': 'test that create_past_job raises TypeError when given a timezone-naive started_at datetime', 'test_block_datasets': 'test that datasets exceeding the blockage threshold are correctly identified as blocked by get_blocked_datasets'}
```

