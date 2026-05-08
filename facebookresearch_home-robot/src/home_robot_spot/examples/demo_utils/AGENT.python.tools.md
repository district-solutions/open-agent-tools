# Agent Python Tools

- repo: facebookresearch/home-robot
- repo_uri: https://github.com/facebookresearch/home-robot

## File: facebookresearch_home-robot/src/home_robot_spot/examples/demo_utils/demo_ui.py

Prompts

```
['start the demo UI server as a separate subprocess using python server.py in the scannet offline eval demo directory', 'stop the demo UI server by finding and killing the python server.py process using psutil', 'run the demo UI server start and stop lifecycle for the scannet offline eval demo project', 'review the demo UI start and stop functions that manage the server subprocess lifecycle', 'refactor the demo UI server start and stop functions to support configurable server paths and process matching', 'run the MockSpotDemoAgent offline using a pickled voxel map and VLM RPC stub', 'confirm or reject a robot action plan through the MockSpotDemoAgent confirm_plan method', 'wrap an object with MockWrapper to record all method calls and attribute accesses', 'replay recorded method calls and attribute accesses on a target object using MockWrapper', 'save recorded calls to a pickle file and load them back for later replay']
```

Usage

```
{'start_demo_ui_server': 'start the demo UI server as a separate subprocess using python server.py in the scannet offline eval demo directory', 'stop_demo_ui_server': 'stop the demo UI server by finding and killing the python server.py process using psutil', 'run_demo_ui_lifecycle': 'run the demo UI server start and stop lifecycle for the scannet offline eval demo project', 'review_demo_ui_functions': 'review the demo UI start and stop functions that manage the server subprocess lifecycle', 'refactor_demo_ui_server': 'refactor the demo UI server start and stop functions to support configurable server paths and process matching'}
```

## File: facebookresearch_home-robot/src/home_robot_spot/examples/demo_utils/mock_agent.py

Prompts

```
['start the demo UI server as a separate subprocess using python server.py in the scannet offline eval demo directory', 'stop the demo UI server by finding and killing the python server.py process using psutil', 'run the demo UI server start and stop lifecycle for the scannet offline eval demo project', 'review the demo UI start and stop functions that manage the server subprocess lifecycle', 'refactor the demo UI server start and stop functions to support configurable server paths and process matching', 'run the MockSpotDemoAgent offline using a pickled voxel map and VLM RPC stub', 'confirm or reject a robot action plan through the MockSpotDemoAgent confirm_plan method', 'wrap an object with MockWrapper to record all method calls and attribute accesses', 'replay recorded method calls and attribute accesses on a target object using MockWrapper', 'save recorded calls to a pickle file and load them back for later replay']
```

Usage

```
{'run_mock_spot_agent': 'run the MockSpotDemoAgent offline using a pickled voxel map and VLM RPC stub', 'confirm_plan_mock_agent': 'confirm or reject a robot action plan through the MockSpotDemoAgent confirm_plan method', 'mock_wrapper_record_calls': 'wrap an object with MockWrapper to record all method calls and attribute accesses', 'mock_wrapper_replay_calls': 'replay recorded method calls and attribute accesses on a target object using MockWrapper', 'mock_wrapper_save_load': 'save recorded calls to a pickle file and load them back for later replay'}
```

