# Agent Python Tools

- repo: facebookresearch/labgraph
- repo_uri: https://github.com/facebookresearch/labgraph

## File: facebookresearch_labgraph/devices/webcam/pose_vis/runners/benchmark_runner.py

Prompts

```
['run the BenchmarkRunner to gather performance details from video sources with specified resolutions', 'create a BenchmarkRunnerConfig dataclass with sources, resolutions, output path, output name, and run time', 'register benchmark nodes by calling register_nodes on BenchmarkRunner to set up the BENCHMARK node and connections', 'run a SourceStreamRunner with configured sources and resolutions as part of the benchmark pipeline', 'add a connection from BENCHMARK OUTPUT_EXIT to DISPLAY or TERM_HANDLER based on display framerate config', 'create a ReplayStreamRunnerConfig dataclass instance with a path string for the log file to replay', 'run a ReplayStreamRunner with PoseVisConfig and ReplayStreamRunnerConfig to replay pose visualization log files', 'call register_nodes on ReplayStreamRunner to resolve the path and add a ReplayStream node to the graph', 'review the ReplayStreamRunner class that extends PoseVisRunner to replay log files via ReplayStream', 'summarize the ReplayStreamRunnerConfig dataclass that holds the path attribute for replay log file configuration', 'create a SourceStreamRunnerConfig dataclass with sources and resolutions for video capture', 'create a SourceStreamRunner instance with PoseVisConfig and SourceStreamRunnerConfig to capture video sources', 'run register_nodes on SourceStreamRunner to add a STREAM node sorted by lowest framerate', 'review the SourceStreamRunner class that extends PoseVisRunner to capture video from multiple sources', 'summarize the SourceStreamRunnerConfig dataclass attributes including sources list and resolutions tuples']
```

Usage

```
{'run_benchmark': 'run the BenchmarkRunner to gather performance details from video sources with specified resolutions', 'create_benchmark_config': 'create a BenchmarkRunnerConfig dataclass with sources, resolutions, output path, output name, and run time', 'register_benchmark_nodes': 'register benchmark nodes by calling register_nodes on BenchmarkRunner to set up the BENCHMARK node and connections', 'run_source_stream': 'run a SourceStreamRunner with configured sources and resolutions as part of the benchmark pipeline', 'add_benchmark_connection': 'add a connection from BENCHMARK OUTPUT_EXIT to DISPLAY or TERM_HANDLER based on display framerate config'}
```

## File: facebookresearch_labgraph/devices/webcam/pose_vis/runners/replay_runner.py

Prompts

```
['run the BenchmarkRunner to gather performance details from video sources with specified resolutions', 'create a BenchmarkRunnerConfig dataclass with sources, resolutions, output path, output name, and run time', 'register benchmark nodes by calling register_nodes on BenchmarkRunner to set up the BENCHMARK node and connections', 'run a SourceStreamRunner with configured sources and resolutions as part of the benchmark pipeline', 'add a connection from BENCHMARK OUTPUT_EXIT to DISPLAY or TERM_HANDLER based on display framerate config', 'create a ReplayStreamRunnerConfig dataclass instance with a path string for the log file to replay', 'run a ReplayStreamRunner with PoseVisConfig and ReplayStreamRunnerConfig to replay pose visualization log files', 'call register_nodes on ReplayStreamRunner to resolve the path and add a ReplayStream node to the graph', 'review the ReplayStreamRunner class that extends PoseVisRunner to replay log files via ReplayStream', 'summarize the ReplayStreamRunnerConfig dataclass that holds the path attribute for replay log file configuration', 'create a SourceStreamRunnerConfig dataclass with sources and resolutions for video capture', 'create a SourceStreamRunner instance with PoseVisConfig and SourceStreamRunnerConfig to capture video sources', 'run register_nodes on SourceStreamRunner to add a STREAM node sorted by lowest framerate', 'review the SourceStreamRunner class that extends PoseVisRunner to capture video from multiple sources', 'summarize the SourceStreamRunnerConfig dataclass attributes including sources list and resolutions tuples']
```

Usage

```
{'create_ReplayStreamRunnerConfig': 'create a ReplayStreamRunnerConfig dataclass instance with a path string for the log file to replay', 'run_ReplayStreamRunner': 'run a ReplayStreamRunner with PoseVisConfig and ReplayStreamRunnerConfig to replay pose visualization log files', 'register_nodes_ReplayStreamRunner': 'call register_nodes on ReplayStreamRunner to resolve the path and add a ReplayStream node to the graph', 'review_ReplayStreamRunner': 'review the ReplayStreamRunner class that extends PoseVisRunner to replay log files via ReplayStream', 'summarize_ReplayStreamRunnerConfig': 'summarize the ReplayStreamRunnerConfig dataclass that holds the path attribute for replay log file configuration'}
```

## File: facebookresearch_labgraph/devices/webcam/pose_vis/runners/source_runner.py

Prompts

```
['run the BenchmarkRunner to gather performance details from video sources with specified resolutions', 'create a BenchmarkRunnerConfig dataclass with sources, resolutions, output path, output name, and run time', 'register benchmark nodes by calling register_nodes on BenchmarkRunner to set up the BENCHMARK node and connections', 'run a SourceStreamRunner with configured sources and resolutions as part of the benchmark pipeline', 'add a connection from BENCHMARK OUTPUT_EXIT to DISPLAY or TERM_HANDLER based on display framerate config', 'create a ReplayStreamRunnerConfig dataclass instance with a path string for the log file to replay', 'run a ReplayStreamRunner with PoseVisConfig and ReplayStreamRunnerConfig to replay pose visualization log files', 'call register_nodes on ReplayStreamRunner to resolve the path and add a ReplayStream node to the graph', 'review the ReplayStreamRunner class that extends PoseVisRunner to replay log files via ReplayStream', 'summarize the ReplayStreamRunnerConfig dataclass that holds the path attribute for replay log file configuration', 'create a SourceStreamRunnerConfig dataclass with sources and resolutions for video capture', 'create a SourceStreamRunner instance with PoseVisConfig and SourceStreamRunnerConfig to capture video sources', 'run register_nodes on SourceStreamRunner to add a STREAM node sorted by lowest framerate', 'review the SourceStreamRunner class that extends PoseVisRunner to capture video from multiple sources', 'summarize the SourceStreamRunnerConfig dataclass attributes including sources list and resolutions tuples']
```

Usage

```
{'create_SourceStreamRunnerConfig': 'create a SourceStreamRunnerConfig dataclass with sources and resolutions for video capture', 'create_SourceStreamRunner': 'create a SourceStreamRunner instance with PoseVisConfig and SourceStreamRunnerConfig to capture video sources', 'run_register_nodes': 'run register_nodes on SourceStreamRunner to add a STREAM node sorted by lowest framerate', 'review_SourceStreamRunner': 'review the SourceStreamRunner class that extends PoseVisRunner to capture video from multiple sources', 'summarize_SourceStreamRunnerConfig': 'summarize the SourceStreamRunnerConfig dataclass attributes including sources list and resolutions tuples'}
```

