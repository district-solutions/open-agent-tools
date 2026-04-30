# Agent Python Tools

- repo: kludex/uvicorn
- repo_uri: https://github.com/kludex/uvicorn

## File: kludex_uvicorn/uvicorn/supervisors/basereload.py

Prompts

```
['create a uvicorn reloader instance with BaseReload using a Config, target callable, and list of sockets', 'run the uvicorn BaseReload reloader loop that detects file changes and restarts the subprocess', 'review the BaseReload startup method that registers signal handlers and spawns the child subprocess', 'refactor the BaseReload restart method to terminate and restart the child process on file changes', 'summarize the BaseReload shutdown method that terminates the subprocess and closes sockets', 'run uvicorn with multiple worker processes using the Multiprocess class and config', 'create a Process instance to manage a single uvicorn worker subprocess with sockets', 'test if a uvicorn worker process is alive by sending ping and checking pong response', 'review Multiprocess signal handlers for SIGINT, SIGTERM, SIGHUP, SIGTTIN, and SIGTTOU', 'summarize the process lifecycle including start, terminate, kill, and join operations', 'build a StatReload instance that watches Python files and restarts uvicorn on changes', 'create a StatReload instance and check if any Python file has been modified since last check', 'test the StatReload iter_py_files method to yield all Python files in reload directories', 'review the StatReload restart method that clears mtimes cache and triggers a parent restart', 'summarize the StatReload should_restart method that detects file modifications via mtime comparison', 'create a FileFilter instance that filters file paths based on uvicorn config include and exclude patterns', 'run a WatchFilesReload reloader that monitors directories for file changes and triggers restarts', 'review the FileFilter.__call__ method that returns True if a path matches include patterns and not exclude patterns', 'review the WatchFilesReload.should_restart method that checks for file changes and returns filtered paths', 'build a WatchFilesReload instance with a uvicorn Config, target callable, and list of sockets for file watching']
```

Usage

```
{'create_BaseReload': 'create a uvicorn reloader instance with BaseReload using a Config, target callable, and list of sockets', 'run_BaseReload': 'run the uvicorn BaseReload reloader loop that detects file changes and restarts the subprocess', 'review_BaseReload_startup': 'review the BaseReload startup method that registers signal handlers and spawns the child subprocess', 'refactor_BaseReload_restart': 'refactor the BaseReload restart method to terminate and restart the child process on file changes', 'summarize_BaseReload_shutdown': 'summarize the BaseReload shutdown method that terminates the subprocess and closes sockets'}
```

## File: kludex_uvicorn/uvicorn/supervisors/multiprocess.py

Prompts

```
['create a uvicorn reloader instance with BaseReload using a Config, target callable, and list of sockets', 'run the uvicorn BaseReload reloader loop that detects file changes and restarts the subprocess', 'review the BaseReload startup method that registers signal handlers and spawns the child subprocess', 'refactor the BaseReload restart method to terminate and restart the child process on file changes', 'summarize the BaseReload shutdown method that terminates the subprocess and closes sockets', 'run uvicorn with multiple worker processes using the Multiprocess class and config', 'create a Process instance to manage a single uvicorn worker subprocess with sockets', 'test if a uvicorn worker process is alive by sending ping and checking pong response', 'review Multiprocess signal handlers for SIGINT, SIGTERM, SIGHUP, SIGTTIN, and SIGTTOU', 'summarize the process lifecycle including start, terminate, kill, and join operations', 'build a StatReload instance that watches Python files and restarts uvicorn on changes', 'create a StatReload instance and check if any Python file has been modified since last check', 'test the StatReload iter_py_files method to yield all Python files in reload directories', 'review the StatReload restart method that clears mtimes cache and triggers a parent restart', 'summarize the StatReload should_restart method that detects file modifications via mtime comparison', 'create a FileFilter instance that filters file paths based on uvicorn config include and exclude patterns', 'run a WatchFilesReload reloader that monitors directories for file changes and triggers restarts', 'review the FileFilter.__call__ method that returns True if a path matches include patterns and not exclude patterns', 'review the WatchFilesReload.should_restart method that checks for file changes and returns filtered paths', 'build a WatchFilesReload instance with a uvicorn Config, target callable, and list of sockets for file watching']
```

Usage

```
{'run_multiprocess_server': 'run uvicorn with multiple worker processes using the Multiprocess class and config', 'create_process_instance': 'create a Process instance to manage a single uvicorn worker subprocess with sockets', 'test_process_health': 'test if a uvicorn worker process is alive by sending ping and checking pong response', 'review_signal_handlers': 'review Multiprocess signal handlers for SIGINT, SIGTERM, SIGHUP, SIGTTIN, and SIGTTOU', 'summarize_process_lifecycle': 'summarize the process lifecycle including start, terminate, kill, and join operations'}
```

## File: kludex_uvicorn/uvicorn/supervisors/statreload.py

Prompts

```
['create a uvicorn reloader instance with BaseReload using a Config, target callable, and list of sockets', 'run the uvicorn BaseReload reloader loop that detects file changes and restarts the subprocess', 'review the BaseReload startup method that registers signal handlers and spawns the child subprocess', 'refactor the BaseReload restart method to terminate and restart the child process on file changes', 'summarize the BaseReload shutdown method that terminates the subprocess and closes sockets', 'run uvicorn with multiple worker processes using the Multiprocess class and config', 'create a Process instance to manage a single uvicorn worker subprocess with sockets', 'test if a uvicorn worker process is alive by sending ping and checking pong response', 'review Multiprocess signal handlers for SIGINT, SIGTERM, SIGHUP, SIGTTIN, and SIGTTOU', 'summarize the process lifecycle including start, terminate, kill, and join operations', 'build a StatReload instance that watches Python files and restarts uvicorn on changes', 'create a StatReload instance and check if any Python file has been modified since last check', 'test the StatReload iter_py_files method to yield all Python files in reload directories', 'review the StatReload restart method that clears mtimes cache and triggers a parent restart', 'summarize the StatReload should_restart method that detects file modifications via mtime comparison', 'create a FileFilter instance that filters file paths based on uvicorn config include and exclude patterns', 'run a WatchFilesReload reloader that monitors directories for file changes and triggers restarts', 'review the FileFilter.__call__ method that returns True if a path matches include patterns and not exclude patterns', 'review the WatchFilesReload.should_restart method that checks for file changes and returns filtered paths', 'build a WatchFilesReload instance with a uvicorn Config, target callable, and list of sockets for file watching']
```

Usage

```
{'build_statreload_reloader': 'build a StatReload instance that watches Python files and restarts uvicorn on changes', 'create_statreload_check_restart': 'create a StatReload instance and check if any Python file has been modified since last check', 'test_statreload_iter_py_files': 'test the StatReload iter_py_files method to yield all Python files in reload directories', 'review_statrestart_restart': 'review the StatReload restart method that clears mtimes cache and triggers a parent restart', 'summarize_statreload_should_restart': 'summarize the StatReload should_restart method that detects file modifications via mtime comparison'}
```

## File: kludex_uvicorn/uvicorn/supervisors/watchfilesreload.py

Prompts

```
['create a uvicorn reloader instance with BaseReload using a Config, target callable, and list of sockets', 'run the uvicorn BaseReload reloader loop that detects file changes and restarts the subprocess', 'review the BaseReload startup method that registers signal handlers and spawns the child subprocess', 'refactor the BaseReload restart method to terminate and restart the child process on file changes', 'summarize the BaseReload shutdown method that terminates the subprocess and closes sockets', 'run uvicorn with multiple worker processes using the Multiprocess class and config', 'create a Process instance to manage a single uvicorn worker subprocess with sockets', 'test if a uvicorn worker process is alive by sending ping and checking pong response', 'review Multiprocess signal handlers for SIGINT, SIGTERM, SIGHUP, SIGTTIN, and SIGTTOU', 'summarize the process lifecycle including start, terminate, kill, and join operations', 'build a StatReload instance that watches Python files and restarts uvicorn on changes', 'create a StatReload instance and check if any Python file has been modified since last check', 'test the StatReload iter_py_files method to yield all Python files in reload directories', 'review the StatReload restart method that clears mtimes cache and triggers a parent restart', 'summarize the StatReload should_restart method that detects file modifications via mtime comparison', 'create a FileFilter instance that filters file paths based on uvicorn config include and exclude patterns', 'run a WatchFilesReload reloader that monitors directories for file changes and triggers restarts', 'review the FileFilter.__call__ method that returns True if a path matches include patterns and not exclude patterns', 'review the WatchFilesReload.should_restart method that checks for file changes and returns filtered paths', 'build a WatchFilesReload instance with a uvicorn Config, target callable, and list of sockets for file watching']
```

Usage

```
{'create_FileFilter': 'create a FileFilter instance that filters file paths based on uvicorn config include and exclude patterns', 'run_WatchFilesReload': 'run a WatchFilesReload reloader that monitors directories for file changes and triggers restarts', 'review_FileFilter_call': 'review the FileFilter.__call__ method that returns True if a path matches include patterns and not exclude patterns', 'review_WatchFilesReload_should_restart': 'review the WatchFilesReload.should_restart method that checks for file changes and returns filtered paths', 'build_WatchFilesReload_config': 'build a WatchFilesReload instance with a uvicorn Config, target callable, and list of sockets for file watching'}
```

