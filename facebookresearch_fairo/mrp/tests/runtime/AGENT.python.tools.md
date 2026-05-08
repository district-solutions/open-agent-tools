# Agent Python Tools

- repo: facebookresearch/fairo
- repo_uri: https://github.com/facebookresearch/fairo

## File: facebookresearch_fairo/mrp/tests/runtime/test_base.py

Prompts

```
['test that BaseLauncher.run raises NotImplementedError when called without a subclass implementation', 'test that BaseLauncher.get_pid raises NotImplementedError when called without a subclass implementation', 'test that down_watcher calls the ondown callback when a DOWN ProcInfo event is received', 'test that down_watcher does not call the ondown callback when only UP ProcInfo events are received', 'test that down_watcher calls ondown when a DOWN event appears after an UP event in the stream', 'test that mrp.Conda runtime skips rebuilding when build=False is passed to mrp.cmd.up', 'test that mrp.Conda build cache skips setup_commands on unchanged definitions and rebuilds on changes', 'reset MRP process definitions and remove conda config directories for given process names', 'read all log messages for a given topic using a0.ReaderSync and return them as a list', 'configure an mrp process with a Conda runtime specifying dependencies, setup_commands, and run_command', 'test that an MRP process defined with a Conda runtime receives the correct environment variables', 'define an MRP process using mrp.Conda as the runtime with a custom run command and environment variables', 'start an MRP process by name using mrp.cmd.up with optional log reset', 'wait for an MRP process to complete using mrp.cmd.wait', 'clear all previously defined MRP processes using mrp.process_def.defined_processes.clear', 'test that environment variables are correctly passed to an MRP Host process and captured in its output', 'define an MRP process with a Host runtime, custom command, and environment variables using mrp.process', 'create an MRP Host runtime that executes a shell command like env using mrp.Host']
```

Usage

```
{'test_BaseLauncher_run': 'test that BaseLauncher.run raises NotImplementedError when called without a subclass implementation', 'test_BaseLauncher_get_pid': 'test that BaseLauncher.get_pid raises NotImplementedError when called without a subclass implementation', 'test_down_watcher_calls_ondown': 'test that down_watcher calls the ondown callback when a DOWN ProcInfo event is received', 'test_down_watcher_skips_up': 'test that down_watcher does not call the ondown callback when only UP ProcInfo events are received', 'test_down_watcher_mixed_events': 'test that down_watcher calls ondown when a DOWN event appears after an UP event in the stream'}
```

## File: facebookresearch_fairo/mrp/tests/runtime/test_conda_build.py

Prompts

```
['test that BaseLauncher.run raises NotImplementedError when called without a subclass implementation', 'test that BaseLauncher.get_pid raises NotImplementedError when called without a subclass implementation', 'test that down_watcher calls the ondown callback when a DOWN ProcInfo event is received', 'test that down_watcher does not call the ondown callback when only UP ProcInfo events are received', 'test that down_watcher calls ondown when a DOWN event appears after an UP event in the stream', 'test that mrp.Conda runtime skips rebuilding when build=False is passed to mrp.cmd.up', 'test that mrp.Conda build cache skips setup_commands on unchanged definitions and rebuilds on changes', 'reset MRP process definitions and remove conda config directories for given process names', 'read all log messages for a given topic using a0.ReaderSync and return them as a list', 'configure an mrp process with a Conda runtime specifying dependencies, setup_commands, and run_command', 'test that an MRP process defined with a Conda runtime receives the correct environment variables', 'define an MRP process using mrp.Conda as the runtime with a custom run command and environment variables', 'start an MRP process by name using mrp.cmd.up with optional log reset', 'wait for an MRP process to complete using mrp.cmd.wait', 'clear all previously defined MRP processes using mrp.process_def.defined_processes.clear', 'test that environment variables are correctly passed to an MRP Host process and captured in its output', 'define an MRP process with a Host runtime, custom command, and environment variables using mrp.process', 'create an MRP Host runtime that executes a shell command like env using mrp.Host']
```

Usage

```
{'test_conda_nobuild': 'test that mrp.Conda runtime skips rebuilding when build=False is passed to mrp.cmd.up', 'test_conda_build_cache': 'test that mrp.Conda build cache skips setup_commands on unchanged definitions and rebuilds on changes', 'reset_state': 'reset MRP process definitions and remove conda config directories for given process names', 'read_logs': 'read all log messages for a given topic using a0.ReaderSync and return them as a list', 'mrp_Conda_runtime': 'configure an mrp process with a Conda runtime specifying dependencies, setup_commands, and run_command'}
```

## File: facebookresearch_fairo/mrp/tests/runtime/test_conda_env.py

Prompts

```
['test that BaseLauncher.run raises NotImplementedError when called without a subclass implementation', 'test that BaseLauncher.get_pid raises NotImplementedError when called without a subclass implementation', 'test that down_watcher calls the ondown callback when a DOWN ProcInfo event is received', 'test that down_watcher does not call the ondown callback when only UP ProcInfo events are received', 'test that down_watcher calls ondown when a DOWN event appears after an UP event in the stream', 'test that mrp.Conda runtime skips rebuilding when build=False is passed to mrp.cmd.up', 'test that mrp.Conda build cache skips setup_commands on unchanged definitions and rebuilds on changes', 'reset MRP process definitions and remove conda config directories for given process names', 'read all log messages for a given topic using a0.ReaderSync and return them as a list', 'configure an mrp process with a Conda runtime specifying dependencies, setup_commands, and run_command', 'test that an MRP process defined with a Conda runtime receives the correct environment variables', 'define an MRP process using mrp.Conda as the runtime with a custom run command and environment variables', 'start an MRP process by name using mrp.cmd.up with optional log reset', 'wait for an MRP process to complete using mrp.cmd.wait', 'clear all previously defined MRP processes using mrp.process_def.defined_processes.clear', 'test that environment variables are correctly passed to an MRP Host process and captured in its output', 'define an MRP process with a Host runtime, custom command, and environment variables using mrp.process', 'create an MRP Host runtime that executes a shell command like env using mrp.Host']
```

Usage

```
{'test_conda_env_process': 'test that an MRP process defined with a Conda runtime receives the correct environment variables', 'define_mrp_process_with_conda_runtime': 'define an MRP process using mrp.Conda as the runtime with a custom run command and environment variables', 'start_mrp_process': 'start an MRP process by name using mrp.cmd.up with optional log reset', 'wait_for_mrp_process': 'wait for an MRP process to complete using mrp.cmd.wait', 'clear_defined_mrp_processes': 'clear all previously defined MRP processes using mrp.process_def.defined_processes.clear'}
```

## File: facebookresearch_fairo/mrp/tests/runtime/test_host_env.py

Prompts

```
['test that BaseLauncher.run raises NotImplementedError when called without a subclass implementation', 'test that BaseLauncher.get_pid raises NotImplementedError when called without a subclass implementation', 'test that down_watcher calls the ondown callback when a DOWN ProcInfo event is received', 'test that down_watcher does not call the ondown callback when only UP ProcInfo events are received', 'test that down_watcher calls ondown when a DOWN event appears after an UP event in the stream', 'test that mrp.Conda runtime skips rebuilding when build=False is passed to mrp.cmd.up', 'test that mrp.Conda build cache skips setup_commands on unchanged definitions and rebuilds on changes', 'reset MRP process definitions and remove conda config directories for given process names', 'read all log messages for a given topic using a0.ReaderSync and return them as a list', 'configure an mrp process with a Conda runtime specifying dependencies, setup_commands, and run_command', 'test that an MRP process defined with a Conda runtime receives the correct environment variables', 'define an MRP process using mrp.Conda as the runtime with a custom run command and environment variables', 'start an MRP process by name using mrp.cmd.up with optional log reset', 'wait for an MRP process to complete using mrp.cmd.wait', 'clear all previously defined MRP processes using mrp.process_def.defined_processes.clear', 'test that environment variables are correctly passed to an MRP Host process and captured in its output', 'define an MRP process with a Host runtime, custom command, and environment variables using mrp.process', 'create an MRP Host runtime that executes a shell command like env using mrp.Host']
```

Usage

```
{'test_host_env': 'test that environment variables are correctly passed to an MRP Host process and captured in its output', 'define_mrp_process': 'define an MRP process with a Host runtime, custom command, and environment variables using mrp.process', 'create_mrp_host_runtime': 'create an MRP Host runtime that executes a shell command like env using mrp.Host', 'start_mrp_process': 'start an MRP process by name and reset its logs using mrp.cmd.up', 'wait_for_mrp_process': 'wait for an MRP process to complete execution using mrp.cmd.wait'}
```

