# Agent Python Tools

- repo: facebookresearch/mephisto
- repo_uri: https://github.com/facebookresearch/mephisto

## File: facebookresearch_mephisto/mephisto/abstractions/_subcomponents/agent_state.py

Prompts

```
['create a subclass of AgentState that implements _set_init_state, get_init_state, _load_data, get_data, _save_data, update_data, and _update_submit methods', 'get the list of immutable agent statuses that cannot be changed under normal operation using AgentState.immutable()', 'convert an agent state string to its corresponding AssignmentState using AgentState.to_assignment_state()', 'update an agent state metadata property by calling update_metadata with a property name and value', 'load persisted agent state data from file with load_data and save changes with save_data', 'create a subclass of Channel that implements is_closed, close, is_alive, open, and enqueue_send abstract methods', 'implement the open method in a Channel subclass to connect the socket to the server', 'enqueue and send a Packet to the intended recipient via the Channel enqueue_send method', 'check if a Channel is alive or closed using the is_alive and is_closed methods', 'close a Channel and clean up all threads and surrounding resources using the close method', 'review the TaskBuilder abstract base class and its factory pattern for building deployable tasks', 'review the TaskBuilder __new__ factory method that resolves the correct subclass from the blueprint registry', 'review the abstract build_in_dir method that builds a task server into a provided directory', 'refactor a TaskBuilder subclass to implement build_in_dir for a new task type', 'create a new TaskBuilder subclass that implements build_in_dir for a custom task type', 'execute an onboarding agent in a background thread with cleanup handling', 'execute a unit task for an agent in a background thread', 'execute an assignment task with multiple agents in a background thread', 'shutdown all running units, assignments, and onboardings and join their threads', 'filter a list of units to return only those eligible for a given worker']
```

Usage

```
{'create_agent_state_subclass': 'create a subclass of AgentState that implements _set_init_state, get_init_state, _load_data, get_data, _save_data, update_data, and _update_submit methods', 'get_immutable_statuses': 'get the list of immutable agent statuses that cannot be changed under normal operation using AgentState.immutable()', 'map_agent_to_assignment_state': 'convert an agent state string to its corresponding AssignmentState using AgentState.to_assignment_state()', 'update_agent_metadata': 'update an agent state metadata property by calling update_metadata with a property name and value', 'load_and_save_agent_data': 'load persisted agent state data from file with load_data and save changes with save_data'}
```

## File: facebookresearch_mephisto/mephisto/abstractions/_subcomponents/channel.py

Prompts

```
['create a subclass of AgentState that implements _set_init_state, get_init_state, _load_data, get_data, _save_data, update_data, and _update_submit methods', 'get the list of immutable agent statuses that cannot be changed under normal operation using AgentState.immutable()', 'convert an agent state string to its corresponding AssignmentState using AgentState.to_assignment_state()', 'update an agent state metadata property by calling update_metadata with a property name and value', 'load persisted agent state data from file with load_data and save changes with save_data', 'create a subclass of Channel that implements is_closed, close, is_alive, open, and enqueue_send abstract methods', 'implement the open method in a Channel subclass to connect the socket to the server', 'enqueue and send a Packet to the intended recipient via the Channel enqueue_send method', 'check if a Channel is alive or closed using the is_alive and is_closed methods', 'close a Channel and clean up all threads and surrounding resources using the close method', 'review the TaskBuilder abstract base class and its factory pattern for building deployable tasks', 'review the TaskBuilder __new__ factory method that resolves the correct subclass from the blueprint registry', 'review the abstract build_in_dir method that builds a task server into a provided directory', 'refactor a TaskBuilder subclass to implement build_in_dir for a new task type', 'create a new TaskBuilder subclass that implements build_in_dir for a custom task type', 'execute an onboarding agent in a background thread with cleanup handling', 'execute a unit task for an agent in a background thread', 'execute an assignment task with multiple agents in a background thread', 'shutdown all running units, assignments, and onboardings and join their threads', 'filter a list of units to return only those eligible for a given worker']
```

Usage

```
{'create_channel_subclass': 'create a subclass of Channel that implements is_closed, close, is_alive, open, and enqueue_send abstract methods', 'implement_channel_open': 'implement the open method in a Channel subclass to connect the socket to the server', 'enqueue_send_packet': 'enqueue and send a Packet to the intended recipient via the Channel enqueue_send method', 'check_channel_status': 'check if a Channel is alive or closed using the is_alive and is_closed methods', 'close_channel_resources': 'close a Channel and clean up all threads and surrounding resources using the close method'}
```

## File: facebookresearch_mephisto/mephisto/abstractions/_subcomponents/task_builder.py

Prompts

```
['create a subclass of AgentState that implements _set_init_state, get_init_state, _load_data, get_data, _save_data, update_data, and _update_submit methods', 'get the list of immutable agent statuses that cannot be changed under normal operation using AgentState.immutable()', 'convert an agent state string to its corresponding AssignmentState using AgentState.to_assignment_state()', 'update an agent state metadata property by calling update_metadata with a property name and value', 'load persisted agent state data from file with load_data and save changes with save_data', 'create a subclass of Channel that implements is_closed, close, is_alive, open, and enqueue_send abstract methods', 'implement the open method in a Channel subclass to connect the socket to the server', 'enqueue and send a Packet to the intended recipient via the Channel enqueue_send method', 'check if a Channel is alive or closed using the is_alive and is_closed methods', 'close a Channel and clean up all threads and surrounding resources using the close method', 'review the TaskBuilder abstract base class and its factory pattern for building deployable tasks', 'review the TaskBuilder __new__ factory method that resolves the correct subclass from the blueprint registry', 'review the abstract build_in_dir method that builds a task server into a provided directory', 'refactor a TaskBuilder subclass to implement build_in_dir for a new task type', 'create a new TaskBuilder subclass that implements build_in_dir for a custom task type', 'execute an onboarding agent in a background thread with cleanup handling', 'execute a unit task for an agent in a background thread', 'execute an assignment task with multiple agents in a background thread', 'shutdown all running units, assignments, and onboardings and join their threads', 'filter a list of units to return only those eligible for a given worker']
```

Usage

```
{'review_TaskBuilder_class': 'review the TaskBuilder abstract base class and its factory pattern for building deployable tasks', 'review_TaskBuilder_new': 'review the TaskBuilder __new__ factory method that resolves the correct subclass from the blueprint registry', 'review_TaskBuilder_build_in_dir': 'review the abstract build_in_dir method that builds a task server into a provided directory', 'refactor_TaskBuilder_subclass': 'refactor a TaskBuilder subclass to implement build_in_dir for a new task type', 'create_TaskBuilder_subclass': 'create a new TaskBuilder subclass that implements build_in_dir for a custom task type'}
```

## File: facebookresearch_mephisto/mephisto/abstractions/_subcomponents/task_runner.py

Prompts

```
['create a subclass of AgentState that implements _set_init_state, get_init_state, _load_data, get_data, _save_data, update_data, and _update_submit methods', 'get the list of immutable agent statuses that cannot be changed under normal operation using AgentState.immutable()', 'convert an agent state string to its corresponding AssignmentState using AgentState.to_assignment_state()', 'update an agent state metadata property by calling update_metadata with a property name and value', 'load persisted agent state data from file with load_data and save changes with save_data', 'create a subclass of Channel that implements is_closed, close, is_alive, open, and enqueue_send abstract methods', 'implement the open method in a Channel subclass to connect the socket to the server', 'enqueue and send a Packet to the intended recipient via the Channel enqueue_send method', 'check if a Channel is alive or closed using the is_alive and is_closed methods', 'close a Channel and clean up all threads and surrounding resources using the close method', 'review the TaskBuilder abstract base class and its factory pattern for building deployable tasks', 'review the TaskBuilder __new__ factory method that resolves the correct subclass from the blueprint registry', 'review the abstract build_in_dir method that builds a task server into a provided directory', 'refactor a TaskBuilder subclass to implement build_in_dir for a new task type', 'create a new TaskBuilder subclass that implements build_in_dir for a custom task type', 'execute an onboarding agent in a background thread with cleanup handling', 'execute a unit task for an agent in a background thread', 'execute an assignment task with multiple agents in a background thread', 'shutdown all running units, assignments, and onboardings and join their threads', 'filter a list of units to return only those eligible for a given worker']
```

Usage

```
{'execute_onboarding_agent': 'execute an onboarding agent in a background thread with cleanup handling', 'execute_unit_task': 'execute a unit task for an agent in a background thread', 'execute_assignment_task': 'execute an assignment task with multiple agents in a background thread', 'shutdown_task_runner': 'shutdown all running units, assignments, and onboardings and join their threads', 'filter_units_for_worker': 'filter a list of units to return only those eligible for a given worker'}
```

