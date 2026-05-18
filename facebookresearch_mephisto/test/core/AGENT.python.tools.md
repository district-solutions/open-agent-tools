# Agent Python Tools

- repo: facebookresearch/mephisto
- repo_uri: https://github.com/facebookresearch/mephisto

## File: facebookresearch_mephisto/test/core/test_live_runs.py

Prompts

```
['test the Mephisto live run system using LocalMephistoDB with mock workers and agents', 'test the Mephisto live run system using MephistoSingletonDB with mock workers and agents', 'test websocket channel initialization, registration, and shutdown in the Mephisto client IO handler', 'test registering and running a concurrent task run with multiple mock workers and agents', 'test registering and running a task run with screening tasks and qualification validation', 'test that the Mephisto Operator can be initialized with a database instance', 'test running a concurrent task with multiple connected mock workers submitting units', 'test running a non-concurrent task where workers complete assignments sequentially', 'test that a task run shuts down when no_submission_patience timeout is exceeded', 'test allowed_concurrent and maximum_units_per_worker restrictions on mock worker agent creation', 'test the TaskLauncher initialization on a task run with mock assignment data', 'test the TaskLauncher create, launch, and expire assignment lifecycle using mock data', 'test the TaskLauncher concurrent unit capacity limits with a LimitedDict tracker', 'test the TaskLauncher assignment creation from a generator yielding mock data', 'review the LimitedDict class that tracks whether its size exceeds a configured limit']
```

Usage

```
{'test_live_runs_local_db': 'test the Mephisto live run system using LocalMephistoDB with mock workers and agents', 'test_live_runs_singleton_db': 'test the Mephisto live run system using MephistoSingletonDB with mock workers and agents', 'test_channel_operations': 'test websocket channel initialization, registration, and shutdown in the Mephisto client IO handler', 'test_register_concurrent_run': 'test registering and running a concurrent task run with multiple mock workers and agents', 'test_register_run_with_screening': 'test registering and running a task run with screening tasks and qualification validation'}
```

## File: facebookresearch_mephisto/test/core/test_operator.py

Prompts

```
['test the Mephisto live run system using LocalMephistoDB with mock workers and agents', 'test the Mephisto live run system using MephistoSingletonDB with mock workers and agents', 'test websocket channel initialization, registration, and shutdown in the Mephisto client IO handler', 'test registering and running a concurrent task run with multiple mock workers and agents', 'test registering and running a task run with screening tasks and qualification validation', 'test that the Mephisto Operator can be initialized with a database instance', 'test running a concurrent task with multiple connected mock workers submitting units', 'test running a non-concurrent task where workers complete assignments sequentially', 'test that a task run shuts down when no_submission_patience timeout is exceeded', 'test allowed_concurrent and maximum_units_per_worker restrictions on mock worker agent creation', 'test the TaskLauncher initialization on a task run with mock assignment data', 'test the TaskLauncher create, launch, and expire assignment lifecycle using mock data', 'test the TaskLauncher concurrent unit capacity limits with a LimitedDict tracker', 'test the TaskLauncher assignment creation from a generator yielding mock data', 'review the LimitedDict class that tracks whether its size exceeds a configured limit']
```

Usage

```
{'test_operator_initialization': 'test that the Mephisto Operator can be initialized with a database instance', 'test_concurrent_task_run': 'test running a concurrent task with multiple connected mock workers submitting units', 'test_non_concurrent_task_run': 'test running a non-concurrent task where workers complete assignments sequentially', 'test_patience_shutdown': 'test that a task run shuts down when no_submission_patience timeout is exceeded', 'test_worker_restrictions': 'test allowed_concurrent and maximum_units_per_worker restrictions on mock worker agent creation'}
```

## File: facebookresearch_mephisto/test/core/test_task_launcher.py

Prompts

```
['test the Mephisto live run system using LocalMephistoDB with mock workers and agents', 'test the Mephisto live run system using MephistoSingletonDB with mock workers and agents', 'test websocket channel initialization, registration, and shutdown in the Mephisto client IO handler', 'test registering and running a concurrent task run with multiple mock workers and agents', 'test registering and running a task run with screening tasks and qualification validation', 'test that the Mephisto Operator can be initialized with a database instance', 'test running a concurrent task with multiple connected mock workers submitting units', 'test running a non-concurrent task where workers complete assignments sequentially', 'test that a task run shuts down when no_submission_patience timeout is exceeded', 'test allowed_concurrent and maximum_units_per_worker restrictions on mock worker agent creation', 'test the TaskLauncher initialization on a task run with mock assignment data', 'test the TaskLauncher create, launch, and expire assignment lifecycle using mock data', 'test the TaskLauncher concurrent unit capacity limits with a LimitedDict tracker', 'test the TaskLauncher assignment creation from a generator yielding mock data', 'review the LimitedDict class that tracks whether its size exceeds a configured limit']
```

Usage

```
{'test_tasklauncher_init': 'test the TaskLauncher initialization on a task run with mock assignment data', 'test_tasklauncher_create_launch_expire': 'test the TaskLauncher create, launch, and expire assignment lifecycle using mock data', 'test_tasklauncher_concurrent_unit_cap': 'test the TaskLauncher concurrent unit capacity limits with a LimitedDict tracker', 'test_tasklauncher_assignments_generator': 'test the TaskLauncher assignment creation from a generator yielding mock data', 'review_limiteddict_class': 'review the LimitedDict class that tracks whether its size exceeds a configured limit'}
```

