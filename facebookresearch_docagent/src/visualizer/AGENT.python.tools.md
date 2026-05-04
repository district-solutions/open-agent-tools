# Agent Python Tools

- repo: facebookresearch/docagent
- repo_uri: https://github.com/facebookresearch/docagent

## File: facebookresearch_docagent/src/visualizer/progress.py

Prompts

```
['create a ProgressVisualizer instance with components dictionary and topologically sorted order list', 'initialize the ProgressVisualizer to display the terminal header and create a tqdm progress bar', 'update the ProgressVisualizer with a component ID and status to track docstring generation progress', 'finalize the ProgressVisualizer to close the progress bar and print summary statistics', 'show dependency graph statistics including component counts and average dependencies per component', 'create a StatusVisualizer instance to visualize DocAssist agent workflow status in the terminal', 'update the StatusVisualizer to highlight the currently active agent and display a status message', 'set the current code component and file path being processed by the StatusVisualizer', 'reset the StatusVisualizer state and clear the terminal screen', 'get the color for an agent based on whether it is the currently active agent', 'create a singleton WebSocketManager to manage socket.io connections for sending visualization updates', 'emit a status_update event to the web interface with the current active agent and component info', 'patch StatusVisualizer and ProgressVisualizer classes to add web interface support via monkey-patching', 'create a WebStatusAdapter to wrap a StatusVisualizer and send agent status updates to the web', 'create a WebProgressAdapter to wrap a ProgressVisualizer and send component progress updates to the web']
```

Usage

```
{'create_ProgressVisualizer': 'create a ProgressVisualizer instance with components dictionary and topologically sorted order list', 'initialize_ProgressVisualizer': 'initialize the ProgressVisualizer to display the terminal header and create a tqdm progress bar', 'update_ProgressVisualizer': 'update the ProgressVisualizer with a component ID and status to track docstring generation progress', 'finalize_ProgressVisualizer': 'finalize the ProgressVisualizer to close the progress bar and print summary statistics', 'show_dependency_stats_ProgressVisualizer': 'show dependency graph statistics including component counts and average dependencies per component'}
```

## File: facebookresearch_docagent/src/visualizer/status.py

Prompts

```
['create a ProgressVisualizer instance with components dictionary and topologically sorted order list', 'initialize the ProgressVisualizer to display the terminal header and create a tqdm progress bar', 'update the ProgressVisualizer with a component ID and status to track docstring generation progress', 'finalize the ProgressVisualizer to close the progress bar and print summary statistics', 'show dependency graph statistics including component counts and average dependencies per component', 'create a StatusVisualizer instance to visualize DocAssist agent workflow status in the terminal', 'update the StatusVisualizer to highlight the currently active agent and display a status message', 'set the current code component and file path being processed by the StatusVisualizer', 'reset the StatusVisualizer state and clear the terminal screen', 'get the color for an agent based on whether it is the currently active agent', 'create a singleton WebSocketManager to manage socket.io connections for sending visualization updates', 'emit a status_update event to the web interface with the current active agent and component info', 'patch StatusVisualizer and ProgressVisualizer classes to add web interface support via monkey-patching', 'create a WebStatusAdapter to wrap a StatusVisualizer and send agent status updates to the web', 'create a WebProgressAdapter to wrap a ProgressVisualizer and send component progress updates to the web']
```

Usage

```
{'create_status_visualizer': 'create a StatusVisualizer instance to visualize DocAssist agent workflow status in the terminal', 'update_active_agent': 'update the StatusVisualizer to highlight the currently active agent and display a status message', 'set_current_component': 'set the current code component and file path being processed by the StatusVisualizer', 'reset_visualizer': 'reset the StatusVisualizer state and clear the terminal screen', 'get_agent_color': 'get the color for an agent based on whether it is the currently active agent'}
```

## File: facebookresearch_docagent/src/visualizer/web_bridge.py

Prompts

```
['create a ProgressVisualizer instance with components dictionary and topologically sorted order list', 'initialize the ProgressVisualizer to display the terminal header and create a tqdm progress bar', 'update the ProgressVisualizer with a component ID and status to track docstring generation progress', 'finalize the ProgressVisualizer to close the progress bar and print summary statistics', 'show dependency graph statistics including component counts and average dependencies per component', 'create a StatusVisualizer instance to visualize DocAssist agent workflow status in the terminal', 'update the StatusVisualizer to highlight the currently active agent and display a status message', 'set the current code component and file path being processed by the StatusVisualizer', 'reset the StatusVisualizer state and clear the terminal screen', 'get the color for an agent based on whether it is the currently active agent', 'create a singleton WebSocketManager to manage socket.io connections for sending visualization updates', 'emit a status_update event to the web interface with the current active agent and component info', 'patch StatusVisualizer and ProgressVisualizer classes to add web interface support via monkey-patching', 'create a WebStatusAdapter to wrap a StatusVisualizer and send agent status updates to the web', 'create a WebProgressAdapter to wrap a ProgressVisualizer and send component progress updates to the web']
```

Usage

```
{'create_websocket_manager': 'create a singleton WebSocketManager to manage socket.io connections for sending visualization updates', 'emit_status_update': 'emit a status_update event to the web interface with the current active agent and component info', 'patch_visualizers': 'patch StatusVisualizer and ProgressVisualizer classes to add web interface support via monkey-patching', 'create_web_status_adapter': 'create a WebStatusAdapter to wrap a StatusVisualizer and send agent status updates to the web', 'create_web_progress_adapter': 'create a WebProgressAdapter to wrap a ProgressVisualizer and send component progress updates to the web'}
```

