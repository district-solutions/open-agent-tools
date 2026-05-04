# Agent Python Tools

- repo: facebookresearch/habitat-lab
- repo_uri: https://github.com/facebookresearch/habitat-lab

## File: facebookresearch_habitat-lab/habitat-hitl/habitat_hitl/environment/controllers/baselines_controller.py

Prompts

```
['create a BaselinesController subclass to manage RL agent inference in a Habitat Gym environment', 'create a SingleAgentBaselinesController to control a single baseline agent with agent-specific observation and action spaces', 'create a MultiAgentBaselinesController to manage multiple baseline agents sharing the full environment observation and action spaces', 'call act on a BaselinesController to get the next action from the agent given an observation', 'use clean_dict to strip agent-specific prefixes from a gym spaces.Dict observation or action space', 'create a subclass of Controller that implements the abstract act method for custom agent behavior', 'implement the act method in a Controller subclass to process observations and return actions', 'override the on_environment_reset method in a Controller subclass to handle environment reset logic', 'create a subclass of GuiController that takes agent_idx, is_multi_agent, and gui_input parameters', 'review the Controller and GuiController abstract base classes to understand the controller interface contract', 'create a ControllerHelper instance to manage multiple agent controllers for a Habitat gym environment', 'get the list of GUI-controlled agent controllers indexed by user index from a ControllerHelper', 'get all agent controllers indexed by agent index from a ControllerHelper instance', 'call update on a ControllerHelper to collect actions from all controllers given an observation', 'call on_environment_reset on a ControllerHelper to reset all registered controllers after environment reset', 'create a GuiRobotController instance to control a robot agent with base velocity actions and camera yaw', 'create a GuiHumanoidController instance to control a humanoid agent with walking, grasping, and throwing', 'use GuiRobotController act method to compute base velocity actions from GUI keyboard input and camera yaw', 'use GuiHumanoidController act method to compute humanoid joint actions including walking, reaching, and object manipulation', 'use angle_from_dir_a_to_b to compute the signed angle between two normalized 3D vectors']
```

Usage

```
{'create_BaselinesController': 'create a BaselinesController subclass to manage RL agent inference in a Habitat Gym environment', 'create_SingleAgentBaselinesController': 'create a SingleAgentBaselinesController to control a single baseline agent with agent-specific observation and action spaces', 'create_MultiAgentBaselinesController': 'create a MultiAgentBaselinesController to manage multiple baseline agents sharing the full environment observation and action spaces', 'act_BaselinesController': 'call act on a BaselinesController to get the next action from the agent given an observation', 'clean_dict_spaces': 'use clean_dict to strip agent-specific prefixes from a gym spaces.Dict observation or action space'}
```

## File: facebookresearch_habitat-lab/habitat-hitl/habitat_hitl/environment/controllers/controller_abc.py

Prompts

```
['create a BaselinesController subclass to manage RL agent inference in a Habitat Gym environment', 'create a SingleAgentBaselinesController to control a single baseline agent with agent-specific observation and action spaces', 'create a MultiAgentBaselinesController to manage multiple baseline agents sharing the full environment observation and action spaces', 'call act on a BaselinesController to get the next action from the agent given an observation', 'use clean_dict to strip agent-specific prefixes from a gym spaces.Dict observation or action space', 'create a subclass of Controller that implements the abstract act method for custom agent behavior', 'implement the act method in a Controller subclass to process observations and return actions', 'override the on_environment_reset method in a Controller subclass to handle environment reset logic', 'create a subclass of GuiController that takes agent_idx, is_multi_agent, and gui_input parameters', 'review the Controller and GuiController abstract base classes to understand the controller interface contract', 'create a ControllerHelper instance to manage multiple agent controllers for a Habitat gym environment', 'get the list of GUI-controlled agent controllers indexed by user index from a ControllerHelper', 'get all agent controllers indexed by agent index from a ControllerHelper instance', 'call update on a ControllerHelper to collect actions from all controllers given an observation', 'call on_environment_reset on a ControllerHelper to reset all registered controllers after environment reset', 'create a GuiRobotController instance to control a robot agent with base velocity actions and camera yaw', 'create a GuiHumanoidController instance to control a humanoid agent with walking, grasping, and throwing', 'use GuiRobotController act method to compute base velocity actions from GUI keyboard input and camera yaw', 'use GuiHumanoidController act method to compute humanoid joint actions including walking, reaching, and object manipulation', 'use angle_from_dir_a_to_b to compute the signed angle between two normalized 3D vectors']
```

Usage

```
{'create_controller_subclass': 'create a subclass of Controller that implements the abstract act method for custom agent behavior', 'implement_act_method': 'implement the act method in a Controller subclass to process observations and return actions', 'override_on_environment_reset': 'override the on_environment_reset method in a Controller subclass to handle environment reset logic', 'create_guicontroller_subclass': 'create a subclass of GuiController that takes agent_idx, is_multi_agent, and gui_input parameters', 'review_controller_abc': 'review the Controller and GuiController abstract base classes to understand the controller interface contract'}
```

## File: facebookresearch_habitat-lab/habitat-hitl/habitat_hitl/environment/controllers/controller_helper.py

Prompts

```
['create a BaselinesController subclass to manage RL agent inference in a Habitat Gym environment', 'create a SingleAgentBaselinesController to control a single baseline agent with agent-specific observation and action spaces', 'create a MultiAgentBaselinesController to manage multiple baseline agents sharing the full environment observation and action spaces', 'call act on a BaselinesController to get the next action from the agent given an observation', 'use clean_dict to strip agent-specific prefixes from a gym spaces.Dict observation or action space', 'create a subclass of Controller that implements the abstract act method for custom agent behavior', 'implement the act method in a Controller subclass to process observations and return actions', 'override the on_environment_reset method in a Controller subclass to handle environment reset logic', 'create a subclass of GuiController that takes agent_idx, is_multi_agent, and gui_input parameters', 'review the Controller and GuiController abstract base classes to understand the controller interface contract', 'create a ControllerHelper instance to manage multiple agent controllers for a Habitat gym environment', 'get the list of GUI-controlled agent controllers indexed by user index from a ControllerHelper', 'get all agent controllers indexed by agent index from a ControllerHelper instance', 'call update on a ControllerHelper to collect actions from all controllers given an observation', 'call on_environment_reset on a ControllerHelper to reset all registered controllers after environment reset', 'create a GuiRobotController instance to control a robot agent with base velocity actions and camera yaw', 'create a GuiHumanoidController instance to control a humanoid agent with walking, grasping, and throwing', 'use GuiRobotController act method to compute base velocity actions from GUI keyboard input and camera yaw', 'use GuiHumanoidController act method to compute humanoid joint actions including walking, reaching, and object manipulation', 'use angle_from_dir_a_to_b to compute the signed angle between two normalized 3D vectors']
```

Usage

```
{'init_ControllerHelper': 'create a ControllerHelper instance to manage multiple agent controllers for a Habitat gym environment', 'get_gui_agent_controllers': 'get the list of GUI-controlled agent controllers indexed by user index from a ControllerHelper', 'get_all_agent_controllers': 'get all agent controllers indexed by agent index from a ControllerHelper instance', 'update_ControllerHelper': 'call update on a ControllerHelper to collect actions from all controllers given an observation', 'on_environment_reset_ControllerHelper': 'call on_environment_reset on a ControllerHelper to reset all registered controllers after environment reset'}
```

## File: facebookresearch_habitat-lab/habitat-hitl/habitat_hitl/environment/controllers/gui_controller.py

Prompts

```
['create a BaselinesController subclass to manage RL agent inference in a Habitat Gym environment', 'create a SingleAgentBaselinesController to control a single baseline agent with agent-specific observation and action spaces', 'create a MultiAgentBaselinesController to manage multiple baseline agents sharing the full environment observation and action spaces', 'call act on a BaselinesController to get the next action from the agent given an observation', 'use clean_dict to strip agent-specific prefixes from a gym spaces.Dict observation or action space', 'create a subclass of Controller that implements the abstract act method for custom agent behavior', 'implement the act method in a Controller subclass to process observations and return actions', 'override the on_environment_reset method in a Controller subclass to handle environment reset logic', 'create a subclass of GuiController that takes agent_idx, is_multi_agent, and gui_input parameters', 'review the Controller and GuiController abstract base classes to understand the controller interface contract', 'create a ControllerHelper instance to manage multiple agent controllers for a Habitat gym environment', 'get the list of GUI-controlled agent controllers indexed by user index from a ControllerHelper', 'get all agent controllers indexed by agent index from a ControllerHelper instance', 'call update on a ControllerHelper to collect actions from all controllers given an observation', 'call on_environment_reset on a ControllerHelper to reset all registered controllers after environment reset', 'create a GuiRobotController instance to control a robot agent with base velocity actions and camera yaw', 'create a GuiHumanoidController instance to control a humanoid agent with walking, grasping, and throwing', 'use GuiRobotController act method to compute base velocity actions from GUI keyboard input and camera yaw', 'use GuiHumanoidController act method to compute humanoid joint actions including walking, reaching, and object manipulation', 'use angle_from_dir_a_to_b to compute the signed angle between two normalized 3D vectors']
```

Usage

```
{'create_GuiRobotController': 'create a GuiRobotController instance to control a robot agent with base velocity actions and camera yaw', 'create_GuiHumanoidController': 'create a GuiHumanoidController instance to control a humanoid agent with walking, grasping, and throwing', 'use_GuiRobotController_act': 'use GuiRobotController act method to compute base velocity actions from GUI keyboard input and camera yaw', 'use_GuiHumanoidController_act': 'use GuiHumanoidController act method to compute humanoid joint actions including walking, reaching, and object manipulation', 'use_angle_from_dir_a_to_b': 'use angle_from_dir_a_to_b to compute the signed angle between two normalized 3D vectors'}
```

