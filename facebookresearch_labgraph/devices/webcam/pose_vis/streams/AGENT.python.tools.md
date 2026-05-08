# Agent Python Tools

- repo: facebookresearch/labgraph
- repo_uri: https://github.com/facebookresearch/labgraph

## File: facebookresearch_labgraph/devices/webcam/pose_vis/streams/replay_stream.py

Prompts

```
['run the ReplayStream node to replay capture results from an HDF5 log file', 'create a ReplayStreamConfig with a log path and list of PoseVisExtension objects', 'setup the ReplayStream node to initialize an HDF5Reader for the configured log file', 'use the read_log async publisher to iterate through captures and yield CaptureResult messages', 'create a ReplayStreamState with a PerfUtility and optional HDF5Reader for tracking replay performance', 'create a SourceStreamConfig with sources, resolutions, extensions, and target framerate for the SourceStream node', 'create a SourceStreamState with an optional CaptureHandler and PerfUtility for tracking capture state', 'run the SourceStream async publisher to capture frames from all sources and publish CaptureResult messages', 'review the SourceStream setup method that initializes a CaptureHandler with configured sources and extensions', 'refactor the SourceStream cleanup method to properly shut down the CaptureHandler and release resources']
```

Usage

```
{'run_replay_stream': 'run the ReplayStream node to replay capture results from an HDF5 log file', 'create_replay_stream_config': 'create a ReplayStreamConfig with a log path and list of PoseVisExtension objects', 'setup_replay_stream': 'setup the ReplayStream node to initialize an HDF5Reader for the configured log file', 'read_log_publisher': 'use the read_log async publisher to iterate through captures and yield CaptureResult messages', 'create_replay_stream_state': 'create a ReplayStreamState with a PerfUtility and optional HDF5Reader for tracking replay performance'}
```

## File: facebookresearch_labgraph/devices/webcam/pose_vis/streams/source_stream.py

Prompts

```
['run the ReplayStream node to replay capture results from an HDF5 log file', 'create a ReplayStreamConfig with a log path and list of PoseVisExtension objects', 'setup the ReplayStream node to initialize an HDF5Reader for the configured log file', 'use the read_log async publisher to iterate through captures and yield CaptureResult messages', 'create a ReplayStreamState with a PerfUtility and optional HDF5Reader for tracking replay performance', 'create a SourceStreamConfig with sources, resolutions, extensions, and target framerate for the SourceStream node', 'create a SourceStreamState with an optional CaptureHandler and PerfUtility for tracking capture state', 'run the SourceStream async publisher to capture frames from all sources and publish CaptureResult messages', 'review the SourceStream setup method that initializes a CaptureHandler with configured sources and extensions', 'refactor the SourceStream cleanup method to properly shut down the CaptureHandler and release resources']
```

Usage

```
{'create_SourceStreamConfig': 'create a SourceStreamConfig with sources, resolutions, extensions, and target framerate for the SourceStream node', 'create_SourceStreamState': 'create a SourceStreamState with an optional CaptureHandler and PerfUtility for tracking capture state', 'run_SourceStream_read_sources': 'run the SourceStream async publisher to capture frames from all sources and publish CaptureResult messages', 'review_SourceStream_setup': 'review the SourceStream setup method that initializes a CaptureHandler with configured sources and extensions', 'refactor_SourceStream_cleanup': 'refactor the SourceStream cleanup method to properly shut down the CaptureHandler and release resources'}
```

