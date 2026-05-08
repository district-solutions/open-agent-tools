# Agent Python Tools

- repo: facebookresearch/hydra
- repo_uri: https://github.com/facebookresearch/hydra.git

## File: facebookresearch_hydra/plugins/hydra_rq_launcher/hydra_plugins/hydra_rq_launcher/_core.py

Prompts

```
['execute a Hydra sweep job by running the task function with the given sweep config and singleton state', 'launch Hydra sweep jobs by enqueuing them into an RQ queue and polling until all finish', 'configure a Redis or FakeRedis connection for the RQ queue based on the launcher config mock setting', 'review the execute_job function to understand how it sets up globals and singleton state before running', 'refactor the launch function to handle the StopAfterEnqueue exception when stop_after_enqueue is enabled', 'review the RQLauncher class that extends Hydra Launcher to enqueue jobs via Redis Queue', 'review the RQLauncher constructor that initializes config, task function, and RQ structured settings', 'review the RQLauncher setup method that stores hydra context, task function, and config', 'review the RQLauncher launch method that delegates job launching to the _core module', 'refactor the RQLauncher launch method to customize job enqueueing or polling behavior']
```

Usage

```
{'execute_job_run_hydra_sweep': 'execute a Hydra sweep job by running the task function with the given sweep config and singleton state', 'launch_enqueue_and_poll_rq_jobs': 'launch Hydra sweep jobs by enqueuing them into an RQ queue and polling until all finish', 'launch_configure_redis_connection': 'configure a Redis or FakeRedis connection for the RQ queue based on the launcher config mock setting', 'review_execute_job_singleton_setup': 'review the execute_job function to understand how it sets up globals and singleton state before running', 'refactor_launch_stop_after_enqueue': 'refactor the launch function to handle the StopAfterEnqueue exception when stop_after_enqueue is enabled'}
```

## File: facebookresearch_hydra/plugins/hydra_rq_launcher/hydra_plugins/hydra_rq_launcher/rq_launcher.py

Prompts

```
['execute a Hydra sweep job by running the task function with the given sweep config and singleton state', 'launch Hydra sweep jobs by enqueuing them into an RQ queue and polling until all finish', 'configure a Redis or FakeRedis connection for the RQ queue based on the launcher config mock setting', 'review the execute_job function to understand how it sets up globals and singleton state before running', 'refactor the launch function to handle the StopAfterEnqueue exception when stop_after_enqueue is enabled', 'review the RQLauncher class that extends Hydra Launcher to enqueue jobs via Redis Queue', 'review the RQLauncher constructor that initializes config, task function, and RQ structured settings', 'review the RQLauncher setup method that stores hydra context, task function, and config', 'review the RQLauncher launch method that delegates job launching to the _core module', 'refactor the RQLauncher launch method to customize job enqueueing or polling behavior']
```

Usage

```
{'review_RQLauncher_class': 'review the RQLauncher class that extends Hydra Launcher to enqueue jobs via Redis Queue', 'review_RQLauncher_init': 'review the RQLauncher constructor that initializes config, task function, and RQ structured settings', 'review_RQLauncher_setup': 'review the RQLauncher setup method that stores hydra context, task function, and config', 'review_RQLauncher_launch': 'review the RQLauncher launch method that delegates job launching to the _core module', 'refactor_RQLauncher_launch': 'refactor the RQLauncher launch method to customize job enqueueing or polling behavior'}
```

