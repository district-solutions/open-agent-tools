# Agent Python Tools

- repo: google-deepmind/dmrobotics
- repo_uri: https://github.com/google-deepmind/dm_robotics

## File: google-deepmind_dmrobotics/py/agentflow/subtasks/integration_test.py

Prompts

```
['run the IntegrationTest suite to verify parameterized subtask and termination component behavior', 'test that the agent sees correct rewards and discounts when terminating with sparse reward mode', 'test that the agent sees correct rewards and discounts when violating workspace boundary limits', 'test that the agent sees correct rewards and discounts when the max step limit is reached', 'build a CompositeTimestepPreprocessor chaining MaxStepsTermination, LeavingWorkspaceTermination, ThresholdedL2Reward, and RewardThresholdTermination', 'create a ParameterizedSubTask with a parent spec, action space, and optional timestep preprocessor', 'build a ParameterizedSubTask that uses a timestep preprocessor to transform environment observations for the agent', 'test the agent_to_parent_action method to project agent actions through the action space', 'review the parent_to_agent_timestep method that applies preprocessors to generate agent-side timesteps', 'refactor the set_timestep_preprocessor method to dynamically swap preprocessors and update the subtask spec', 'test the ParameterizedSubTask class to verify pterm and result caching from the timestep preprocessor', 'test the ParameterizedSubTask agent_to_parent_action method to verify action space projection is called', 'run the absltest suite for ParameterizedSubTask to validate pterm caching and action projection behavior', 'review the ParameterizedSubtaskTest class and its test methods for pterm caching and action projection assertions', 'refactor the ParameterizedSubtaskTest class to add additional test cases for edge cases in result caching', 'test MaxStepsTermination to terminate episodes after a fixed number of steps with failure result', 'test RewardThresholdTermination to terminate episodes when reward exceeds a scalar or array threshold', 'test LeavingWorkspaceTermination to terminate episodes when the robot TCP position leaves a spherical workspace', 'test LeavingWorkspaceBoxTermination to terminate episodes when the robot TCP pose leaves a box-shaped workspace', 'test JointLimitsTermination to terminate episodes when robot joint positions exceed min or max limits']
```

Usage

```
{'run_integration_test_parameterized_subtask': 'run the IntegrationTest suite to verify parameterized subtask and termination component behavior', 'test_sparse_reward_termination': 'test that the agent sees correct rewards and discounts when terminating with sparse reward mode', 'test_out_of_bounds_termination': 'test that the agent sees correct rewards and discounts when violating workspace boundary limits', 'test_max_steps_termination': 'test that the agent sees correct rewards and discounts when the max step limit is reached', 'build_composite_timestep_preprocessor': 'build a CompositeTimestepPreprocessor chaining MaxStepsTermination, LeavingWorkspaceTermination, ThresholdedL2Reward, and RewardThresholdTermination'}
```

## File: google-deepmind_dmrobotics/py/agentflow/subtasks/parameterized_subtask.py

Prompts

```
['run the IntegrationTest suite to verify parameterized subtask and termination component behavior', 'test that the agent sees correct rewards and discounts when terminating with sparse reward mode', 'test that the agent sees correct rewards and discounts when violating workspace boundary limits', 'test that the agent sees correct rewards and discounts when the max step limit is reached', 'build a CompositeTimestepPreprocessor chaining MaxStepsTermination, LeavingWorkspaceTermination, ThresholdedL2Reward, and RewardThresholdTermination', 'create a ParameterizedSubTask with a parent spec, action space, and optional timestep preprocessor', 'build a ParameterizedSubTask that uses a timestep preprocessor to transform environment observations for the agent', 'test the agent_to_parent_action method to project agent actions through the action space', 'review the parent_to_agent_timestep method that applies preprocessors to generate agent-side timesteps', 'refactor the set_timestep_preprocessor method to dynamically swap preprocessors and update the subtask spec', 'test the ParameterizedSubTask class to verify pterm and result caching from the timestep preprocessor', 'test the ParameterizedSubTask agent_to_parent_action method to verify action space projection is called', 'run the absltest suite for ParameterizedSubTask to validate pterm caching and action projection behavior', 'review the ParameterizedSubtaskTest class and its test methods for pterm caching and action projection assertions', 'refactor the ParameterizedSubtaskTest class to add additional test cases for edge cases in result caching', 'test MaxStepsTermination to terminate episodes after a fixed number of steps with failure result', 'test RewardThresholdTermination to terminate episodes when reward exceeds a scalar or array threshold', 'test LeavingWorkspaceTermination to terminate episodes when the robot TCP position leaves a spherical workspace', 'test LeavingWorkspaceBoxTermination to terminate episodes when the robot TCP pose leaves a box-shaped workspace', 'test JointLimitsTermination to terminate episodes when robot joint positions exceed min or max limits']
```

Usage

```
{'create_parameterized_subtask': 'create a ParameterizedSubTask with a parent spec, action space, and optional timestep preprocessor', 'build_subtask_with_preprocessor': 'build a ParameterizedSubTask that uses a timestep preprocessor to transform environment observations for the agent', 'test_agent_to_parent_action': 'test the agent_to_parent_action method to project agent actions through the action space', 'review_parent_to_agent_timestep': 'review the parent_to_agent_timestep method that applies preprocessors to generate agent-side timesteps', 'refactor_set_timestep_preprocessor': 'refactor the set_timestep_preprocessor method to dynamically swap preprocessors and update the subtask spec'}
```

## File: google-deepmind_dmrobotics/py/agentflow/subtasks/parameterized_subtask_test.py

Prompts

```
['run the IntegrationTest suite to verify parameterized subtask and termination component behavior', 'test that the agent sees correct rewards and discounts when terminating with sparse reward mode', 'test that the agent sees correct rewards and discounts when violating workspace boundary limits', 'test that the agent sees correct rewards and discounts when the max step limit is reached', 'build a CompositeTimestepPreprocessor chaining MaxStepsTermination, LeavingWorkspaceTermination, ThresholdedL2Reward, and RewardThresholdTermination', 'create a ParameterizedSubTask with a parent spec, action space, and optional timestep preprocessor', 'build a ParameterizedSubTask that uses a timestep preprocessor to transform environment observations for the agent', 'test the agent_to_parent_action method to project agent actions through the action space', 'review the parent_to_agent_timestep method that applies preprocessors to generate agent-side timesteps', 'refactor the set_timestep_preprocessor method to dynamically swap preprocessors and update the subtask spec', 'test the ParameterizedSubTask class to verify pterm and result caching from the timestep preprocessor', 'test the ParameterizedSubTask agent_to_parent_action method to verify action space projection is called', 'run the absltest suite for ParameterizedSubTask to validate pterm caching and action projection behavior', 'review the ParameterizedSubtaskTest class and its test methods for pterm caching and action projection assertions', 'refactor the ParameterizedSubtaskTest class to add additional test cases for edge cases in result caching', 'test MaxStepsTermination to terminate episodes after a fixed number of steps with failure result', 'test RewardThresholdTermination to terminate episodes when reward exceeds a scalar or array threshold', 'test LeavingWorkspaceTermination to terminate episodes when the robot TCP position leaves a spherical workspace', 'test LeavingWorkspaceBoxTermination to terminate episodes when the robot TCP pose leaves a box-shaped workspace', 'test JointLimitsTermination to terminate episodes when robot joint positions exceed min or max limits']
```

Usage

```
{'test_parameterized_subtask_pterm_caching': 'test the ParameterizedSubTask class to verify pterm and result caching from the timestep preprocessor', 'test_parameterized_subtask_action_projection': 'test the ParameterizedSubTask agent_to_parent_action method to verify action space projection is called', 'run_parameterized_subtask_tests': 'run the absltest suite for ParameterizedSubTask to validate pterm caching and action projection behavior', 'review_parameterized_subtask_test': 'review the ParameterizedSubtaskTest class and its test methods for pterm caching and action projection assertions', 'refactor_parameterized_subtask_test': 'refactor the ParameterizedSubtaskTest class to add additional test cases for edge cases in result caching'}
```

## File: google-deepmind_dmrobotics/py/agentflow/subtasks/subtask_termination_test.py

Prompts

```
['run the IntegrationTest suite to verify parameterized subtask and termination component behavior', 'test that the agent sees correct rewards and discounts when terminating with sparse reward mode', 'test that the agent sees correct rewards and discounts when violating workspace boundary limits', 'test that the agent sees correct rewards and discounts when the max step limit is reached', 'build a CompositeTimestepPreprocessor chaining MaxStepsTermination, LeavingWorkspaceTermination, ThresholdedL2Reward, and RewardThresholdTermination', 'create a ParameterizedSubTask with a parent spec, action space, and optional timestep preprocessor', 'build a ParameterizedSubTask that uses a timestep preprocessor to transform environment observations for the agent', 'test the agent_to_parent_action method to project agent actions through the action space', 'review the parent_to_agent_timestep method that applies preprocessors to generate agent-side timesteps', 'refactor the set_timestep_preprocessor method to dynamically swap preprocessors and update the subtask spec', 'test the ParameterizedSubTask class to verify pterm and result caching from the timestep preprocessor', 'test the ParameterizedSubTask agent_to_parent_action method to verify action space projection is called', 'run the absltest suite for ParameterizedSubTask to validate pterm caching and action projection behavior', 'review the ParameterizedSubtaskTest class and its test methods for pterm caching and action projection assertions', 'refactor the ParameterizedSubtaskTest class to add additional test cases for edge cases in result caching', 'test MaxStepsTermination to terminate episodes after a fixed number of steps with failure result', 'test RewardThresholdTermination to terminate episodes when reward exceeds a scalar or array threshold', 'test LeavingWorkspaceTermination to terminate episodes when the robot TCP position leaves a spherical workspace', 'test LeavingWorkspaceBoxTermination to terminate episodes when the robot TCP pose leaves a box-shaped workspace', 'test JointLimitsTermination to terminate episodes when robot joint positions exceed min or max limits']
```

Usage

```
{'test_MaxStepsTermination': 'test MaxStepsTermination to terminate episodes after a fixed number of steps with failure result', 'test_RewardThresholdTermination': 'test RewardThresholdTermination to terminate episodes when reward exceeds a scalar or array threshold', 'test_LeavingWorkspaceTermination': 'test LeavingWorkspaceTermination to terminate episodes when the robot TCP position leaves a spherical workspace', 'test_LeavingWorkspaceBoxTermination': 'test LeavingWorkspaceBoxTermination to terminate episodes when the robot TCP pose leaves a box-shaped workspace', 'test_JointLimitsTermination': 'test JointLimitsTermination to terminate episodes when robot joint positions exceed min or max limits'}
```

