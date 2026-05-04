# Agent Python Tools

- repo: facebookresearch/habitat-lab
- repo_uri: https://github.com/facebookresearch/habitat-lab

## File: facebookresearch_habitat-lab/habitat-baselines/habitat_baselines/rl/hrl/hl/fixed_policy.py

Prompts

```
['build a FixedHighLevelPolicy instance that executes a fixed sequence of high-level actions from a PDDL solution', 'parse the PDDL problem solution into a list of action names and argument tuples for execution', 'get the next skill index and arguments from the fixed solution plan for a batch of environments', 'apply a binary mask tensor to reset the next skill index for filtered environments', 'filter and clean up stateful variables to match only the active environments in the policy', 'create a HighLevelPolicy instance with config, PDDL problem, skill mappings, and observation space', 'evaluate actions using observations, hidden states, previous actions, and masks for learning', 'get a binary tensor indicating whether the currently executing skill should terminate', 'setup and return the list of all PDDL actions the agent can execute', 'build a NeuralHighLevelPolicy instance with config, pddl_problem, num_envs, skill_name_to_idx, observation_space, action_space, aux_loss_config, and agent_name', 'review the NeuralHighLevelPolicy forward method that encodes visual and state observations through ResNet and RNN layers', 'test the NeuralHighLevelPolicy evaluate_actions method to compute action log probs, entropy, and critic values', 'refactor the NeuralHighLevelPolicy get_next_skill method to select discrete skills and their arguments from the policy distribution', 'summarize the NeuralHighLevelPolicy get_value method that returns the critic value estimate from the forward pass', 'get the shortest sequence of PDDL actions to reach a specified goal from the current predicate state', 'perform BFS search to find all PlanNodes that satisfy a given PDDL goal from the current state', 'recompute the plan for an environment by selecting a goal and generating the shortest action sequence', 'set the replanning flags for all environments based on whether the planner is reactive or not']
```

Usage

```
{'build_fixed_high_level_policy': 'build a FixedHighLevelPolicy instance that executes a fixed sequence of high-level actions from a PDDL solution', 'parse_solution_actions': 'parse the PDDL problem solution into a list of action names and argument tuples for execution', 'get_next_skill': 'get the next skill index and arguments from the fixed solution plan for a batch of environments', 'apply_mask_to_skill_index': 'apply a binary mask tensor to reset the next skill index for filtered environments', 'filter_envs': 'filter and clean up stateful variables to match only the active environments in the policy'}
```

## File: facebookresearch_habitat-lab/habitat-baselines/habitat_baselines/rl/hrl/hl/high_level_policy.py

Prompts

```
['build a FixedHighLevelPolicy instance that executes a fixed sequence of high-level actions from a PDDL solution', 'parse the PDDL problem solution into a list of action names and argument tuples for execution', 'get the next skill index and arguments from the fixed solution plan for a batch of environments', 'apply a binary mask tensor to reset the next skill index for filtered environments', 'filter and clean up stateful variables to match only the active environments in the policy', 'create a HighLevelPolicy instance with config, PDDL problem, skill mappings, and observation space', 'evaluate actions using observations, hidden states, previous actions, and masks for learning', 'get a binary tensor indicating whether the currently executing skill should terminate', 'setup and return the list of all PDDL actions the agent can execute', 'build a NeuralHighLevelPolicy instance with config, pddl_problem, num_envs, skill_name_to_idx, observation_space, action_space, aux_loss_config, and agent_name', 'review the NeuralHighLevelPolicy forward method that encodes visual and state observations through ResNet and RNN layers', 'test the NeuralHighLevelPolicy evaluate_actions method to compute action log probs, entropy, and critic values', 'refactor the NeuralHighLevelPolicy get_next_skill method to select discrete skills and their arguments from the policy distribution', 'summarize the NeuralHighLevelPolicy get_value method that returns the critic value estimate from the forward pass', 'get the shortest sequence of PDDL actions to reach a specified goal from the current predicate state', 'perform BFS search to find all PlanNodes that satisfy a given PDDL goal from the current state', 'recompute the plan for an environment by selecting a goal and generating the shortest action sequence', 'set the replanning flags for all environments based on whether the planner is reactive or not']
```

Usage

```
{'init_HighLevelPolicy': 'create a HighLevelPolicy instance with config, PDDL problem, skill mappings, and observation space', 'get_next_skill': 'get the next skill to execute given observations, hidden states, and plan masks', 'evaluate_actions': 'evaluate actions using observations, hidden states, previous actions, and masks for learning', 'get_termination': 'get a binary tensor indicating whether the currently executing skill should terminate', 'setup_actions': 'setup and return the list of all PDDL actions the agent can execute'}
```

## File: facebookresearch_habitat-lab/habitat-baselines/habitat_baselines/rl/hrl/hl/neural_policy.py

Prompts

```
['build a FixedHighLevelPolicy instance that executes a fixed sequence of high-level actions from a PDDL solution', 'parse the PDDL problem solution into a list of action names and argument tuples for execution', 'get the next skill index and arguments from the fixed solution plan for a batch of environments', 'apply a binary mask tensor to reset the next skill index for filtered environments', 'filter and clean up stateful variables to match only the active environments in the policy', 'create a HighLevelPolicy instance with config, PDDL problem, skill mappings, and observation space', 'evaluate actions using observations, hidden states, previous actions, and masks for learning', 'get a binary tensor indicating whether the currently executing skill should terminate', 'setup and return the list of all PDDL actions the agent can execute', 'build a NeuralHighLevelPolicy instance with config, pddl_problem, num_envs, skill_name_to_idx, observation_space, action_space, aux_loss_config, and agent_name', 'review the NeuralHighLevelPolicy forward method that encodes visual and state observations through ResNet and RNN layers', 'test the NeuralHighLevelPolicy evaluate_actions method to compute action log probs, entropy, and critic values', 'refactor the NeuralHighLevelPolicy get_next_skill method to select discrete skills and their arguments from the policy distribution', 'summarize the NeuralHighLevelPolicy get_value method that returns the critic value estimate from the forward pass', 'get the shortest sequence of PDDL actions to reach a specified goal from the current predicate state', 'perform BFS search to find all PlanNodes that satisfy a given PDDL goal from the current state', 'recompute the plan for an environment by selecting a goal and generating the shortest action sequence', 'set the replanning flags for all environments based on whether the planner is reactive or not']
```

Usage

```
{'build_NeuralHighLevelPolicy': 'build a NeuralHighLevelPolicy instance with config, pddl_problem, num_envs, skill_name_to_idx, observation_space, action_space, aux_loss_config, and agent_name', 'review_NeuralHighLevelPolicy_forward': 'review the NeuralHighLevelPolicy forward method that encodes visual and state observations through ResNet and RNN layers', 'test_NeuralHighLevelPolicy_evaluate_actions': 'test the NeuralHighLevelPolicy evaluate_actions method to compute action log probs, entropy, and critic values', 'refactor_NeuralHighLevelPolicy_get_next_skill': 'refactor the NeuralHighLevelPolicy get_next_skill method to select discrete skills and their arguments from the policy distribution', 'summarize_NeuralHighLevelPolicy_get_value': 'summarize the NeuralHighLevelPolicy get_value method that returns the critic value estimate from the forward pass'}
```

## File: facebookresearch_habitat-lab/habitat-baselines/habitat_baselines/rl/hrl/hl/planner_policy.py

Prompts

```
['build a FixedHighLevelPolicy instance that executes a fixed sequence of high-level actions from a PDDL solution', 'parse the PDDL problem solution into a list of action names and argument tuples for execution', 'get the next skill index and arguments from the fixed solution plan for a batch of environments', 'apply a binary mask tensor to reset the next skill index for filtered environments', 'filter and clean up stateful variables to match only the active environments in the policy', 'create a HighLevelPolicy instance with config, PDDL problem, skill mappings, and observation space', 'evaluate actions using observations, hidden states, previous actions, and masks for learning', 'get a binary tensor indicating whether the currently executing skill should terminate', 'setup and return the list of all PDDL actions the agent can execute', 'build a NeuralHighLevelPolicy instance with config, pddl_problem, num_envs, skill_name_to_idx, observation_space, action_space, aux_loss_config, and agent_name', 'review the NeuralHighLevelPolicy forward method that encodes visual and state observations through ResNet and RNN layers', 'test the NeuralHighLevelPolicy evaluate_actions method to compute action log probs, entropy, and critic values', 'refactor the NeuralHighLevelPolicy get_next_skill method to select discrete skills and their arguments from the policy distribution', 'summarize the NeuralHighLevelPolicy get_value method that returns the critic value estimate from the forward pass', 'get the shortest sequence of PDDL actions to reach a specified goal from the current predicate state', 'perform BFS search to find all PlanNodes that satisfy a given PDDL goal from the current state', 'recompute the plan for an environment by selecting a goal and generating the shortest action sequence', 'set the replanning flags for all environments based on whether the planner is reactive or not']
```

Usage

```
{'get_next_skill': 'get the next high-level skill and action arguments for a batch of environments using the planner policy', 'get_plan': 'get the shortest sequence of PDDL actions to reach a specified goal from the current predicate state', 'get_solution_nodes': 'perform BFS search to find all PlanNodes that satisfy a given PDDL goal from the current state', 'replan': 'recompute the plan for an environment by selecting a goal and generating the shortest action sequence', 'apply_mask': 'set the replanning flags for all environments based on whether the planner is reactive or not'}
```

