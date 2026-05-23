# Agent Python Tools

- repo: facebookresearch/partnr-planner
- repo_uri: https://github.com/facebookresearch/partnr-planner

## File: facebookresearch_partnr-planner/third_party/habitat-lab/habitat-hitl/habitat_hitl/environment/controllers/baselines_controller.py

Prompts

```
['create a SingleAgentBaselinesController to manage a single baseline agent with observation transforms and action spaces', 'create a MultiAgentBaselinesController to manage multiple baseline agents in a Habitat environment', "call the act method on a BaselinesController to get an action from the agent's policy network", 'use clean_dict to strip agent prefixes from a gym.spaces.Dict observation or action space', 'load a trained agent checkpoint from a saved file into the BaselinesController for evaluation', 'review the Controller abstract base class and its act method signature', 'review the GuiController class that extends Controller for GUI agents', 'implement a concrete subclass of Controller with a custom act method', 'implement a concrete subclass of GuiController with custom GUI input handling', 'refactor the Controller act method to support additional observation types', 'create a ControllerHelper instance wrapping a GymHabitatEnv with config, hitl_config, gui_input, and recorder', 'get the list of GUI-controlled agent controllers indexed by user index from the ControllerHelper', 'get all agent controllers indexed by agent index from the ControllerHelper instance', 'call update on the ControllerHelper with observations to get concatenated actions from all controllers', 'call on_environment_reset on the ControllerHelper to reset all registered controllers when the environment resets', 'create a GuiRobotController instance to control a robot agent via GUI input and base velocity actions', 'create a GuiHumanoidController instance to control a humanoid agent with walking, grasping, and throwing', 'test the GuiRobotController act method to compute base velocity actions from GUI keyboard input', 'test the GuiHumanoidController act method to compute joint actions for walking, reaching, and object manipulation', 'review the GuiRobotController angle_from_dir_a_to_b method that computes signed angle between two normalized 3D vectors']
```

Usage

```
{'create_single_agent_controller': 'create a SingleAgentBaselinesController to manage a single baseline agent with observation transforms and action spaces', 'create_multi_agent_controller': 'create a MultiAgentBaselinesController to manage multiple baseline agents in a Habitat environment', 'act_with_baselines_controller': "call the act method on a BaselinesController to get an action from the agent's policy network", 'clean_dict_observation_space': 'use clean_dict to strip agent prefixes from a gym.spaces.Dict observation or action space', 'load_agent_checkpoint': 'load a trained agent checkpoint from a saved file into the BaselinesController for evaluation'}
```

## File: facebookresearch_partnr-planner/third_party/habitat-lab/habitat-hitl/habitat_hitl/environment/controllers/controller_abc.py

Prompts

```
['create a SingleAgentBaselinesController to manage a single baseline agent with observation transforms and action spaces', 'create a MultiAgentBaselinesController to manage multiple baseline agents in a Habitat environment', "call the act method on a BaselinesController to get an action from the agent's policy network", 'use clean_dict to strip agent prefixes from a gym.spaces.Dict observation or action space', 'load a trained agent checkpoint from a saved file into the BaselinesController for evaluation', 'review the Controller abstract base class and its act method signature', 'review the GuiController class that extends Controller for GUI agents', 'implement a concrete subclass of Controller with a custom act method', 'implement a concrete subclass of GuiController with custom GUI input handling', 'refactor the Controller act method to support additional observation types', 'create a ControllerHelper instance wrapping a GymHabitatEnv with config, hitl_config, gui_input, and recorder', 'get the list of GUI-controlled agent controllers indexed by user index from the ControllerHelper', 'get all agent controllers indexed by agent index from the ControllerHelper instance', 'call update on the ControllerHelper with observations to get concatenated actions from all controllers', 'call on_environment_reset on the ControllerHelper to reset all registered controllers when the environment resets', 'create a GuiRobotController instance to control a robot agent via GUI input and base velocity actions', 'create a GuiHumanoidController instance to control a humanoid agent with walking, grasping, and throwing', 'test the GuiRobotController act method to compute base velocity actions from GUI keyboard input', 'test the GuiHumanoidController act method to compute joint actions for walking, reaching, and object manipulation', 'review the GuiRobotController angle_from_dir_a_to_b method that computes signed angle between two normalized 3D vectors']
```

Usage

```
{'review_Controller_class': 'review the Controller abstract base class and its act method signature', 'review_GuiController_class': 'review the GuiController class that extends Controller for GUI agents', 'implement_Controller_subclass': 'implement a concrete subclass of Controller with a custom act method', 'implement_GuiController_subclass': 'implement a concrete subclass of GuiController with custom GUI input handling', 'refactor_Controller_act': 'refactor the Controller act method to support additional observation types'}
```

## File: facebookresearch_partnr-planner/third_party/habitat-lab/habitat-hitl/habitat_hitl/environment/controllers/controller_helper.py

Prompts

```
['create a SingleAgentBaselinesController to manage a single baseline agent with observation transforms and action spaces', 'create a MultiAgentBaselinesController to manage multiple baseline agents in a Habitat environment', "call the act method on a BaselinesController to get an action from the agent's policy network", 'use clean_dict to strip agent prefixes from a gym.spaces.Dict observation or action space', 'load a trained agent checkpoint from a saved file into the BaselinesController for evaluation', 'review the Controller abstract base class and its act method signature', 'review the GuiController class that extends Controller for GUI agents', 'implement a concrete subclass of Controller with a custom act method', 'implement a concrete subclass of GuiController with custom GUI input handling', 'refactor the Controller act method to support additional observation types', 'create a ControllerHelper instance wrapping a GymHabitatEnv with config, hitl_config, gui_input, and recorder', 'get the list of GUI-controlled agent controllers indexed by user index from the ControllerHelper', 'get all agent controllers indexed by agent index from the ControllerHelper instance', 'call update on the ControllerHelper with observations to get concatenated actions from all controllers', 'call on_environment_reset on the ControllerHelper to reset all registered controllers when the environment resets', 'create a GuiRobotController instance to control a robot agent via GUI input and base velocity actions', 'create a GuiHumanoidController instance to control a humanoid agent with walking, grasping, and throwing', 'test the GuiRobotController act method to compute base velocity actions from GUI keyboard input', 'test the GuiHumanoidController act method to compute joint actions for walking, reaching, and object manipulation', 'review the GuiRobotController angle_from_dir_a_to_b method that computes signed angle between two normalized 3D vectors']
```

Usage

```
{'create_ControllerHelper': 'create a ControllerHelper instance wrapping a GymHabitatEnv with config, hitl_config, gui_input, and recorder', 'get_gui_agent_controllers': 'get the list of GUI-controlled agent controllers indexed by user index from the ControllerHelper', 'get_all_agent_controllers': 'get all agent controllers indexed by agent index from the ControllerHelper instance', 'update_actions': 'call update on the ControllerHelper with observations to get concatenated actions from all controllers', 'on_environment_reset': 'call on_environment_reset on the ControllerHelper to reset all registered controllers when the environment resets'}
```

## File: facebookresearch_partnr-planner/third_party/habitat-lab/habitat-hitl/habitat_hitl/environment/controllers/gui_controller.py

Prompts

```
['create a SingleAgentBaselinesController to manage a single baseline agent with observation transforms and action spaces', 'create a MultiAgentBaselinesController to manage multiple baseline agents in a Habitat environment', "call the act method on a BaselinesController to get an action from the agent's policy network", 'use clean_dict to strip agent prefixes from a gym.spaces.Dict observation or action space', 'load a trained agent checkpoint from a saved file into the BaselinesController for evaluation', 'review the Controller abstract base class and its act method signature', 'review the GuiController class that extends Controller for GUI agents', 'implement a concrete subclass of Controller with a custom act method', 'implement a concrete subclass of GuiController with custom GUI input handling', 'refactor the Controller act method to support additional observation types', 'create a ControllerHelper instance wrapping a GymHabitatEnv with config, hitl_config, gui_input, and recorder', 'get the list of GUI-controlled agent controllers indexed by user index from the ControllerHelper', 'get all agent controllers indexed by agent index from the ControllerHelper instance', 'call update on the ControllerHelper with observations to get concatenated actions from all controllers', 'call on_environment_reset on the ControllerHelper to reset all registered controllers when the environment resets', 'create a GuiRobotController instance to control a robot agent via GUI input and base velocity actions', 'create a GuiHumanoidController instance to control a humanoid agent with walking, grasping, and throwing', 'test the GuiRobotController act method to compute base velocity actions from GUI keyboard input', 'test the GuiHumanoidController act method to compute joint actions for walking, reaching, and object manipulation', 'review the GuiRobotController angle_from_dir_a_to_b method that computes signed angle between two normalized 3D vectors']
```

Usage

```
{'create_GuiRobotController': 'create a GuiRobotController instance to control a robot agent via GUI input and base velocity actions', 'create_GuiHumanoidController': 'create a GuiHumanoidController instance to control a humanoid agent with walking, grasping, and throwing', 'test_GuiRobotController_act': 'test the GuiRobotController act method to compute base velocity actions from GUI keyboard input', 'test_GuiHumanoidController_act': 'test the GuiHumanoidController act method to compute joint actions for walking, reaching, and object manipulation', 'review_angle_from_dir_a_to_b': 'review the GuiRobotController angle_from_dir_a_to_b method that computes signed angle between two normalized 3D vectors'}
```

