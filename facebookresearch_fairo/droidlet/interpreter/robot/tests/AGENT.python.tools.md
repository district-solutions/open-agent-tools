# Agent Python Tools

- repo: facebookresearch/fairo
- repo_uri: https://github.com/facebookresearch/fairo

## File: facebookresearch_fairo/droidlet/interpreter/robot/tests/base_fakeagent_test_case.py

Prompts

```
['test the BaseFakeAgentTestCase handle_logical_form method to process a logical form and flush agent steps', 'test the BaseFakeAgentTestCase flush method to run agent steps until task and dialogue stacks are empty', 'test the BaseFakeAgentTestCase add_incoming_chat method to simulate a speaker sending a chat message', 'test the BaseFakeAgentTestCase set_looking_at method to mock the agent line of sight return value', 'test the BaseFakeAgentTestCase agent_should_stop method to check if the agent should halt execution', 'create a FakeAgent instance with a world and optional speed parameters for simulated robot testing', 'test robot movement commands like MoveAbsolute, Turn, GrabNearbyObject, Drop, LookAt, and SendChat via FakeMover', 'refactor FakeMoverCommand subclasses to add new simulated robot actions with step-based execution logic', 'review the FakeDetectorPerception class for simulated object detection and adding detected objects to agent memory', 'summarize how FakeAgent perceives the world via logical form injection, self-perception, and fake vision modules', 'create a SimpleHuman agent with randomized name, speed, and direction change probability using make_human_opts', 'create a World instance with players and agent data from a spec dictionary and opts config', 'test the SimpleHuman step method to simulate movement, loitering, and direction changes in the world', 'test the World get_line_of_sight method to find the nearest player or object in a given direction', 'test the World add_incoming_chat method to log chat messages with speaker names into the chat log']
```

Usage

```
{'test_fakeagent_logical_form': 'test the BaseFakeAgentTestCase handle_logical_form method to process a logical form and flush agent steps', 'test_fakeagent_flush': 'test the BaseFakeAgentTestCase flush method to run agent steps until task and dialogue stacks are empty', 'test_fakeagent_incoming_chat': 'test the BaseFakeAgentTestCase add_incoming_chat method to simulate a speaker sending a chat message', 'test_fakeagent_looking_at': 'test the BaseFakeAgentTestCase set_looking_at method to mock the agent line of sight return value', 'test_fakeagent_stop_condition': 'test the BaseFakeAgentTestCase agent_should_stop method to check if the agent should halt execution'}
```

## File: facebookresearch_fairo/droidlet/interpreter/robot/tests/fake_agent.py

Prompts

```
['test the BaseFakeAgentTestCase handle_logical_form method to process a logical form and flush agent steps', 'test the BaseFakeAgentTestCase flush method to run agent steps until task and dialogue stacks are empty', 'test the BaseFakeAgentTestCase add_incoming_chat method to simulate a speaker sending a chat message', 'test the BaseFakeAgentTestCase set_looking_at method to mock the agent line of sight return value', 'test the BaseFakeAgentTestCase agent_should_stop method to check if the agent should halt execution', 'create a FakeAgent instance with a world and optional speed parameters for simulated robot testing', 'test robot movement commands like MoveAbsolute, Turn, GrabNearbyObject, Drop, LookAt, and SendChat via FakeMover', 'refactor FakeMoverCommand subclasses to add new simulated robot actions with step-based execution logic', 'review the FakeDetectorPerception class for simulated object detection and adding detected objects to agent memory', 'summarize how FakeAgent perceives the world via logical form injection, self-perception, and fake vision modules', 'create a SimpleHuman agent with randomized name, speed, and direction change probability using make_human_opts', 'create a World instance with players and agent data from a spec dictionary and opts config', 'test the SimpleHuman step method to simulate movement, loitering, and direction changes in the world', 'test the World get_line_of_sight method to find the nearest player or object in a given direction', 'test the World add_incoming_chat method to log chat messages with speaker names into the chat log']
```

Usage

```
{'create_FakeAgent': 'create a FakeAgent instance with a world and optional speed parameters for simulated robot testing', 'test_FakeMover_commands': 'test robot movement commands like MoveAbsolute, Turn, GrabNearbyObject, Drop, LookAt, and SendChat via FakeMover', 'refactor_FakeMoverCommand_subclasses': 'refactor FakeMoverCommand subclasses to add new simulated robot actions with step-based execution logic', 'review_FakeDetectorPerception': 'review the FakeDetectorPerception class for simulated object detection and adding detected objects to agent memory', 'summarize_FakeAgent_perception': 'summarize how FakeAgent perceives the world via logical form injection, self-perception, and fake vision modules'}
```

## File: facebookresearch_fairo/droidlet/interpreter/robot/tests/world.py

Prompts

```
['test the BaseFakeAgentTestCase handle_logical_form method to process a logical form and flush agent steps', 'test the BaseFakeAgentTestCase flush method to run agent steps until task and dialogue stacks are empty', 'test the BaseFakeAgentTestCase add_incoming_chat method to simulate a speaker sending a chat message', 'test the BaseFakeAgentTestCase set_looking_at method to mock the agent line of sight return value', 'test the BaseFakeAgentTestCase agent_should_stop method to check if the agent should halt execution', 'create a FakeAgent instance with a world and optional speed parameters for simulated robot testing', 'test robot movement commands like MoveAbsolute, Turn, GrabNearbyObject, Drop, LookAt, and SendChat via FakeMover', 'refactor FakeMoverCommand subclasses to add new simulated robot actions with step-based execution logic', 'review the FakeDetectorPerception class for simulated object detection and adding detected objects to agent memory', 'summarize how FakeAgent perceives the world via logical form injection, self-perception, and fake vision modules', 'create a SimpleHuman agent with randomized name, speed, and direction change probability using make_human_opts', 'create a World instance with players and agent data from a spec dictionary and opts config', 'test the SimpleHuman step method to simulate movement, loitering, and direction changes in the world', 'test the World get_line_of_sight method to find the nearest player or object in a given direction', 'test the World add_incoming_chat method to log chat messages with speaker names into the chat log']
```

Usage

```
{'create_SimpleHuman': 'create a SimpleHuman agent with randomized name, speed, and direction change probability using make_human_opts', 'create_World': 'create a World instance with players and agent data from a spec dictionary and opts config', 'test_SimpleHuman_step': 'test the SimpleHuman step method to simulate movement, loitering, and direction changes in the world', 'test_World_get_line_of_sight': 'test the World get_line_of_sight method to find the nearest player or object in a given direction', 'test_World_add_incoming_chat': 'test the World add_incoming_chat method to log chat messages with speaker names into the chat log'}
```

