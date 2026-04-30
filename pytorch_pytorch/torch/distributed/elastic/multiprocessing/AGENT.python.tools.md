# Agent Python Tools

- repo: pytorch/pytorch
- repo_uri: https://github.com/pytorch/pytorch.git

## File: pytorch_pytorch/torch/distributed/elastic/multiprocessing/api.py

Prompts

```
['create a MultiprocessContext to launch worker processes as a callable entrypoint with stdout/stderr redirection', 'create a SubprocessContext to launch worker processes as a binary entrypoint with stdout/stderr redirection', 'run PContext.wait to poll and wait for all launched processes to complete or fail with optional timeout', 'build PContext.close to gracefully terminate all worker processes and clean up redirect and error file resources', 'test Std.from_str to parse a string into a Std flag value or a per-rank mapping dictionary', 'redirect stdout to a log file using redirect_stdout context manager', 'redirect stderr to a log file using redirect_stderr context manager', 'redirect stdout or stderr to a file using the redirect context manager with custom stream', 'get the libc shared library on unix systems for low-level fd redirection', 'validate that a stream name is stdout or stderr before redirection', 'create a TailLog instance to tail multiple log files with custom headers and output destination', 'run TailLog.start() to begin tailing log files in background threads', 'test the tail_logfile function that reads and writes log lines with headers until finished', 'stop TailLog by signaling finished events and shutting down the thread pool', 'review the TailLog.stopped() method that returns whether the tailer has been stopped']
```

Usage

```
{'create_MultiprocessContext': 'create a MultiprocessContext to launch worker processes as a callable entrypoint with stdout/stderr redirection', 'create_SubprocessContext': 'create a SubprocessContext to launch worker processes as a binary entrypoint with stdout/stderr redirection', 'run_PContext_wait': 'run PContext.wait to poll and wait for all launched processes to complete or fail with optional timeout', 'build_PContext_close': 'build PContext.close to gracefully terminate all worker processes and clean up redirect and error file resources', 'test_Std_from_str': 'test Std.from_str to parse a string into a Std flag value or a per-rank mapping dictionary'}
```

## File: pytorch_pytorch/torch/distributed/elastic/multiprocessing/redirects.py

Prompts

```
['create a MultiprocessContext to launch worker processes as a callable entrypoint with stdout/stderr redirection', 'create a SubprocessContext to launch worker processes as a binary entrypoint with stdout/stderr redirection', 'run PContext.wait to poll and wait for all launched processes to complete or fail with optional timeout', 'build PContext.close to gracefully terminate all worker processes and clean up redirect and error file resources', 'test Std.from_str to parse a string into a Std flag value or a per-rank mapping dictionary', 'redirect stdout to a log file using redirect_stdout context manager', 'redirect stderr to a log file using redirect_stderr context manager', 'redirect stdout or stderr to a file using the redirect context manager with custom stream', 'get the libc shared library on unix systems for low-level fd redirection', 'validate that a stream name is stdout or stderr before redirection', 'create a TailLog instance to tail multiple log files with custom headers and output destination', 'run TailLog.start() to begin tailing log files in background threads', 'test the tail_logfile function that reads and writes log lines with headers until finished', 'stop TailLog by signaling finished events and shutting down the thread pool', 'review the TailLog.stopped() method that returns whether the tailer has been stopped']
```

Usage

```
{'redirect_stdout_file': 'redirect stdout to a log file using redirect_stdout context manager', 'redirect_stderr_file': 'redirect stderr to a log file using redirect_stderr context manager', 'redirect_custom_stream_file': 'redirect stdout or stderr to a file using the redirect context manager with custom stream', 'get_libc_unix': 'get the libc shared library on unix systems for low-level fd redirection', 'validate_std_stream': 'validate that a stream name is stdout or stderr before redirection'}
```

## File: pytorch_pytorch/torch/distributed/elastic/multiprocessing/tail_log.py

Prompts

```
['create a MultiprocessContext to launch worker processes as a callable entrypoint with stdout/stderr redirection', 'create a SubprocessContext to launch worker processes as a binary entrypoint with stdout/stderr redirection', 'run PContext.wait to poll and wait for all launched processes to complete or fail with optional timeout', 'build PContext.close to gracefully terminate all worker processes and clean up redirect and error file resources', 'test Std.from_str to parse a string into a Std flag value or a per-rank mapping dictionary', 'redirect stdout to a log file using redirect_stdout context manager', 'redirect stderr to a log file using redirect_stderr context manager', 'redirect stdout or stderr to a file using the redirect context manager with custom stream', 'get the libc shared library on unix systems for low-level fd redirection', 'validate that a stream name is stdout or stderr before redirection', 'create a TailLog instance to tail multiple log files with custom headers and output destination', 'run TailLog.start() to begin tailing log files in background threads', 'test the tail_logfile function that reads and writes log lines with headers until finished', 'stop TailLog by signaling finished events and shutting down the thread pool', 'review the TailLog.stopped() method that returns whether the tailer has been stopped']
```

Usage

```
{'create_TailLog': 'create a TailLog instance to tail multiple log files with custom headers and output destination', 'run_TailLog_start': 'run TailLog.start() to begin tailing log files in background threads', 'test_tail_logfile': 'test the tail_logfile function that reads and writes log lines with headers until finished', 'stop_TailLog': 'stop TailLog by signaling finished events and shutting down the thread pool', 'review_TailLog_stopped': 'review the TailLog.stopped() method that returns whether the tailer has been stopped'}
```

