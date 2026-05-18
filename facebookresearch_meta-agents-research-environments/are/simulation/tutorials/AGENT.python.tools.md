# Agent Python Tools

- repo: facebookresearch/meta-agents-research-environments
- repo_uri: https://github.com/facebookresearch/meta-agents-research-environments

## File: facebookresearch_meta-agents-research-environments/are/simulation/tutorials/environment.py

Prompts

```
['run a simulation environment with a configurable duration and time increment', 'create an EnvironmentConfig with start_time, duration, and time_increment_in_seconds parameters', 'start the simulation environment event loop in a non-blocking background thread', 'pause the running simulation environment and check elapsed time via time_manager', 'resume a paused simulation environment and verify time passed after resuming', 'run an Environment with EnvironmentConfig to simulate agent interactions over a 60 second duration', 'create a directed acyclic graph of Events using depends_on to schedule email and UI events', 'build a ConditionCheckEvent from a condition function that checks inbox email count after agent notification', 'create an AgentValidationEvent with milestone functions to validate agent sends correct messages to user', 'run EventRegisterer capture mode to record app function calls as schedulable events with unique IDs', 'run a simulation environment that schedules email events to occur at specific times after start', 'create conditional events that trigger when a custom condition on the environment event log is met', 'schedule an event using Event.from_function with a delayed or absolute time syntax', 'capture agent events using EventRegisterer capture mode to record App API calls as events', 'start the simulation environment, interact with registered apps, then pause and inspect the event log', 'run a simulation that schedules email events with dependencies and delays between them', 'create a ConditionCheckEvent from a lambda condition that triggers when random value exceeds threshold', 'build an AgentValidationEvent with milestones and timeout to verify agent actions after dependent events', 'schedule events using EventRegisterer capture mode to record app function calls as schedulable events', 'review the event log list view after running a simulation to inspect executed events']
```

Usage

```
{'run_environment_simulation': 'run a simulation environment with a configurable duration and time increment', 'create_environment_config': 'create an EnvironmentConfig with start_time, duration, and time_increment_in_seconds parameters', 'start_environment': 'start the simulation environment event loop in a non-blocking background thread', 'pause_environment': 'pause the running simulation environment and check elapsed time via time_manager', 'resume_environment': 'resume a paused simulation environment and verify time passed after resuming'}
```

## File: facebookresearch_meta-agents-research-environments/are/simulation/tutorials/event_dag.py

Prompts

```
['run a simulation environment with a configurable duration and time increment', 'create an EnvironmentConfig with start_time, duration, and time_increment_in_seconds parameters', 'start the simulation environment event loop in a non-blocking background thread', 'pause the running simulation environment and check elapsed time via time_manager', 'resume a paused simulation environment and verify time passed after resuming', 'run an Environment with EnvironmentConfig to simulate agent interactions over a 60 second duration', 'create a directed acyclic graph of Events using depends_on to schedule email and UI events', 'build a ConditionCheckEvent from a condition function that checks inbox email count after agent notification', 'create an AgentValidationEvent with milestone functions to validate agent sends correct messages to user', 'run EventRegisterer capture mode to record app function calls as schedulable events with unique IDs', 'run a simulation environment that schedules email events to occur at specific times after start', 'create conditional events that trigger when a custom condition on the environment event log is met', 'schedule an event using Event.from_function with a delayed or absolute time syntax', 'capture agent events using EventRegisterer capture mode to record App API calls as events', 'start the simulation environment, interact with registered apps, then pause and inspect the event log', 'run a simulation that schedules email events with dependencies and delays between them', 'create a ConditionCheckEvent from a lambda condition that triggers when random value exceeds threshold', 'build an AgentValidationEvent with milestones and timeout to verify agent actions after dependent events', 'schedule events using EventRegisterer capture mode to record app function calls as schedulable events', 'review the event log list view after running a simulation to inspect executed events']
```

Usage

```
{'run_simulation_environment': 'run an Environment with EnvironmentConfig to simulate agent interactions over a 60 second duration', 'create_event_dag': 'create a directed acyclic graph of Events using depends_on to schedule email and UI events', 'build_condition_check_event': 'build a ConditionCheckEvent from a condition function that checks inbox email count after agent notification', 'create_agent_validation_event': 'create an AgentValidationEvent with milestone functions to validate agent sends correct messages to user', 'run_capture_mode_events': 'run EventRegisterer capture mode to record app function calls as schedulable events with unique IDs'}
```

## File: facebookresearch_meta-agents-research-environments/are/simulation/tutorials/events.py

Prompts

```
['run a simulation environment with a configurable duration and time increment', 'create an EnvironmentConfig with start_time, duration, and time_increment_in_seconds parameters', 'start the simulation environment event loop in a non-blocking background thread', 'pause the running simulation environment and check elapsed time via time_manager', 'resume a paused simulation environment and verify time passed after resuming', 'run an Environment with EnvironmentConfig to simulate agent interactions over a 60 second duration', 'create a directed acyclic graph of Events using depends_on to schedule email and UI events', 'build a ConditionCheckEvent from a condition function that checks inbox email count after agent notification', 'create an AgentValidationEvent with milestone functions to validate agent sends correct messages to user', 'run EventRegisterer capture mode to record app function calls as schedulable events with unique IDs', 'run a simulation environment that schedules email events to occur at specific times after start', 'create conditional events that trigger when a custom condition on the environment event log is met', 'schedule an event using Event.from_function with a delayed or absolute time syntax', 'capture agent events using EventRegisterer capture mode to record App API calls as events', 'start the simulation environment, interact with registered apps, then pause and inspect the event log', 'run a simulation that schedules email events with dependencies and delays between them', 'create a ConditionCheckEvent from a lambda condition that triggers when random value exceeds threshold', 'build an AgentValidationEvent with milestones and timeout to verify agent actions after dependent events', 'schedule events using EventRegisterer capture mode to record app function calls as schedulable events', 'review the event log list view after running a simulation to inspect executed events']
```

Usage

```
{'run_scheduled_events': 'run a simulation environment that schedules email events to occur at specific times after start', 'create_conditional_events': 'create conditional events that trigger when a custom condition on the environment event log is met', 'schedule_event_from_function': 'schedule an event using Event.from_function with a delayed or absolute time syntax', 'capture_agent_events': 'capture agent events using EventRegisterer capture mode to record App API calls as events', 'start_and_pause_environment': 'start the simulation environment, interact with registered apps, then pause and inspect the event log'}
```

## File: facebookresearch_meta-agents-research-environments/are/simulation/tutorials/events_advanced.py

Prompts

```
['run a simulation environment with a configurable duration and time increment', 'create an EnvironmentConfig with start_time, duration, and time_increment_in_seconds parameters', 'start the simulation environment event loop in a non-blocking background thread', 'pause the running simulation environment and check elapsed time via time_manager', 'resume a paused simulation environment and verify time passed after resuming', 'run an Environment with EnvironmentConfig to simulate agent interactions over a 60 second duration', 'create a directed acyclic graph of Events using depends_on to schedule email and UI events', 'build a ConditionCheckEvent from a condition function that checks inbox email count after agent notification', 'create an AgentValidationEvent with milestone functions to validate agent sends correct messages to user', 'run EventRegisterer capture mode to record app function calls as schedulable events with unique IDs', 'run a simulation environment that schedules email events to occur at specific times after start', 'create conditional events that trigger when a custom condition on the environment event log is met', 'schedule an event using Event.from_function with a delayed or absolute time syntax', 'capture agent events using EventRegisterer capture mode to record App API calls as events', 'start the simulation environment, interact with registered apps, then pause and inspect the event log', 'run a simulation that schedules email events with dependencies and delays between them', 'create a ConditionCheckEvent from a lambda condition that triggers when random value exceeds threshold', 'build an AgentValidationEvent with milestones and timeout to verify agent actions after dependent events', 'schedule events using EventRegisterer capture mode to record app function calls as schedulable events', 'review the event log list view after running a simulation to inspect executed events']
```

Usage

```
{'run_simulation_with_event_dependencies': 'run a simulation that schedules email events with dependencies and delays between them', 'create_condition_check_event': 'create a ConditionCheckEvent from a lambda condition that triggers when random value exceeds threshold', 'build_agent_validation_event': 'build an AgentValidationEvent with milestones and timeout to verify agent actions after dependent events', 'schedule_events_with_capture_mode': 'schedule events using EventRegisterer capture mode to record app function calls as schedulable events', 'review_event_log_after_simulation': 'review the event log list view after running a simulation to inspect executed events'}
```

