# Agent Python Tools

- repo: pytorch/pytorch
- repo_uri: https://github.com/pytorch/pytorch.git

## File: pytorch_pytorch/torch/distributed/elastic/timer/api.py

Prompts

```
['configure the global PyTorch elastic timer client for countdown timer operations', 'create a TimerRequest data object with worker_id, scope_id, and expiration_time for timer acquisition', 'build a TimerServer implementation that monitors active timers and reaps expired workers', 'build a TimerClient implementation that acquires and releases countdown timers via a TimerServer', 'run a code block wrapped in the expires context manager to trigger worker reaping on timeout', 'create a FileTimerClient that sends timer acquisition and release requests via a named pipe to a FileTimerServer', 'create a FileTimerServer that monitors worker timers on a named pipe and reaps expired worker processes', 'create a FileTimerRequest data object with worker pid, scope id, expiration time, and kill signal for inter-process timer communication', 'test the FileTimerServer.get_expired_timers method to return a dict mapping expired worker pids to their timer requests', 'test the FileTimerServer._reap_worker method to send a signal to a worker process and handle process lookup errors', 'create a LocalTimerClient that sends timer acquire and release requests via a multiprocessing queue to a LocalTimerServer', 'create a LocalTimerServer that monitors worker timers via a multiprocessing queue and reaps expired worker processes', 'create a MultiprocessingRequestQueue backed by a multiprocessing Queue for inter-process timer request communication']
```

Usage

```
{'configure_timer_client': 'configure the global PyTorch elastic timer client for countdown timer operations', 'create_timer_request': 'create a TimerRequest data object with worker_id, scope_id, and expiration_time for timer acquisition', 'build_timer_server': 'build a TimerServer implementation that monitors active timers and reaps expired workers', 'build_timer_client': 'build a TimerClient implementation that acquires and releases countdown timers via a TimerServer', 'run_expires_context': 'run a code block wrapped in the expires context manager to trigger worker reaping on timeout'}
```

## File: pytorch_pytorch/torch/distributed/elastic/timer/file_based_local_timer.py

Prompts

```
['configure the global PyTorch elastic timer client for countdown timer operations', 'create a TimerRequest data object with worker_id, scope_id, and expiration_time for timer acquisition', 'build a TimerServer implementation that monitors active timers and reaps expired workers', 'build a TimerClient implementation that acquires and releases countdown timers via a TimerServer', 'run a code block wrapped in the expires context manager to trigger worker reaping on timeout', 'create a FileTimerClient that sends timer acquisition and release requests via a named pipe to a FileTimerServer', 'create a FileTimerServer that monitors worker timers on a named pipe and reaps expired worker processes', 'create a FileTimerRequest data object with worker pid, scope id, expiration time, and kill signal for inter-process timer communication', 'test the FileTimerServer.get_expired_timers method to return a dict mapping expired worker pids to their timer requests', 'test the FileTimerServer._reap_worker method to send a signal to a worker process and handle process lookup errors', 'create a LocalTimerClient that sends timer acquire and release requests via a multiprocessing queue to a LocalTimerServer', 'create a LocalTimerServer that monitors worker timers via a multiprocessing queue and reaps expired worker processes', 'create a MultiprocessingRequestQueue backed by a multiprocessing Queue for inter-process timer request communication']
```

Usage

```
{'create_file_timer_client': 'create a FileTimerClient that sends timer acquisition and release requests via a named pipe to a FileTimerServer', 'create_file_timer_server': 'create a FileTimerServer that monitors worker timers on a named pipe and reaps expired worker processes', 'create_file_timer_request': 'create a FileTimerRequest data object with worker pid, scope id, expiration time, and kill signal for inter-process timer communication', 'test_get_expired_timers': 'test the FileTimerServer.get_expired_timers method to return a dict mapping expired worker pids to their timer requests', 'test_reap_worker': 'test the FileTimerServer._reap_worker method to send a signal to a worker process and handle process lookup errors'}
```

## File: pytorch_pytorch/torch/distributed/elastic/timer/local_timer.py

Prompts

```
['configure the global PyTorch elastic timer client for countdown timer operations', 'create a TimerRequest data object with worker_id, scope_id, and expiration_time for timer acquisition', 'build a TimerServer implementation that monitors active timers and reaps expired workers', 'build a TimerClient implementation that acquires and releases countdown timers via a TimerServer', 'run a code block wrapped in the expires context manager to trigger worker reaping on timeout', 'create a FileTimerClient that sends timer acquisition and release requests via a named pipe to a FileTimerServer', 'create a FileTimerServer that monitors worker timers on a named pipe and reaps expired worker processes', 'create a FileTimerRequest data object with worker pid, scope id, expiration time, and kill signal for inter-process timer communication', 'test the FileTimerServer.get_expired_timers method to return a dict mapping expired worker pids to their timer requests', 'test the FileTimerServer._reap_worker method to send a signal to a worker process and handle process lookup errors', 'create a LocalTimerClient that sends timer acquire and release requests via a multiprocessing queue to a LocalTimerServer', 'create a LocalTimerServer that monitors worker timers via a multiprocessing queue and reaps expired worker processes', 'create a MultiprocessingRequestQueue backed by a multiprocessing Queue for inter-process timer request communication']
```

Usage

```
{'create_local_timer_client': 'create a LocalTimerClient that sends timer acquire and release requests via a multiprocessing queue to a LocalTimerServer', 'create_local_timer_server': 'create a LocalTimerServer that monitors worker timers via a multiprocessing queue and reaps expired worker processes', 'create_multiprocessing_request_queue': 'create a MultiprocessingRequestQueue backed by a multiprocessing Queue for inter-process timer request communication', 'test_get_expired_timers': 'test the LocalTimerServer.get_expired_timers method to return a dict mapping expired worker pids to their timer requests', 'test_reap_worker': 'test the LocalTimerServer._reap_worker method to send SIGKILL to a worker process and handle process lookup errors'}
```

