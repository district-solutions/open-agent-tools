# Agent Python Tools

- repo: facebookresearch/partnr-planner
- repo_uri: https://github.com/facebookresearch/partnr-planner

## File: facebookresearch_partnr-planner/third_party/habitat-lab/habitat-baselines/habitat_baselines/rl/hrl/hl/fixed_policy.py

Prompts

```
['initialize a FixedHighLevelPolicy that parses PDDL solution actions for each environment', 'parse the PDDL problem solution into a list of action names and arguments', 'get the next high-level skill and arguments from the fixed solution plan', 'apply a binary mask to reset the next skill index for selected environments', 'filter and clean up stateful variables to match only active environments', 'review the HighLevelPolicy class which selects from low-level skills in hierarchical RL', 'implement the get_next_skill method to return the next skill to execute for each environment', 'implement the evaluate_actions method to compute action values and log probabilities for training', 'implement the get_value method to return the value estimate from the high-level policy', 'customize the _setup_actions method to filter PDDL actions by robot entity and allowed action names', 'build a NeuralHighLevelPolicy instance with config, PDDL problem, observation space, and action space', 'review the NeuralHighLevelPolicy forward method that processes visual and state observations through RNN encoder', 'test the NeuralHighLevelPolicy evaluate_actions method to get action log probs, entropy, and critic values', 'summarize the NeuralHighLevelPolicy get_next_skill method that selects discrete skills and their arguments from the policy distribution', 'refactor the NeuralHighLevelPolicy get_termination method to customize termination detection from observation keys', 'build a high-level policy that plans a sequence of PDDL actions to rearrange objects in the Habitat environment', 'create a PlanNode dataclass to represent a node in the search tree for planning high-level action paths', 'test the BFS search method that finds PlanNodes satisfying a given PDDL goal from current predicate state', 'refactor the plan action selection method to support custom replanning logic for batched environment steps', 'review the get_next_skill method that returns the next high-level skill and arguments for each environment in the batch']
```

Usage

```
{'init_FixedHighLevelPolicy': 'initialize a FixedHighLevelPolicy that parses PDDL solution actions for each environment', 'parse_solution_actions': 'parse the PDDL problem solution into a list of action names and arguments', 'get_next_skill': 'get the next high-level skill and arguments from the fixed solution plan', 'apply_mask': 'apply a binary mask to reset the next skill index for selected environments', 'filter_envs': 'filter and clean up stateful variables to match only active environments'}
```

## File: facebookresearch_partnr-planner/third_party/habitat-lab/habitat-baselines/habitat_baselines/rl/hrl/hl/high_level_policy.py

Prompts

```
['initialize a FixedHighLevelPolicy that parses PDDL solution actions for each environment', 'parse the PDDL problem solution into a list of action names and arguments', 'get the next high-level skill and arguments from the fixed solution plan', 'apply a binary mask to reset the next skill index for selected environments', 'filter and clean up stateful variables to match only active environments', 'review the HighLevelPolicy class which selects from low-level skills in hierarchical RL', 'implement the get_next_skill method to return the next skill to execute for each environment', 'implement the evaluate_actions method to compute action values and log probabilities for training', 'implement the get_value method to return the value estimate from the high-level policy', 'customize the _setup_actions method to filter PDDL actions by robot entity and allowed action names', 'build a NeuralHighLevelPolicy instance with config, PDDL problem, observation space, and action space', 'review the NeuralHighLevelPolicy forward method that processes visual and state observations through RNN encoder', 'test the NeuralHighLevelPolicy evaluate_actions method to get action log probs, entropy, and critic values', 'summarize the NeuralHighLevelPolicy get_next_skill method that selects discrete skills and their arguments from the policy distribution', 'refactor the NeuralHighLevelPolicy get_termination method to customize termination detection from observation keys', 'build a high-level policy that plans a sequence of PDDL actions to rearrange objects in the Habitat environment', 'create a PlanNode dataclass to represent a node in the search tree for planning high-level action paths', 'test the BFS search method that finds PlanNodes satisfying a given PDDL goal from current predicate state', 'refactor the plan action selection method to support custom replanning logic for batched environment steps', 'review the get_next_skill method that returns the next high-level skill and arguments for each environment in the batch']
```

Usage

```
{'review_HighLevelPolicy_class': 'review the HighLevelPolicy class which selects from low-level skills in hierarchical RL', 'implement_get_next_skill': 'implement the get_next_skill method to return the next skill to execute for each environment', 'implement_evaluate_actions': 'implement the evaluate_actions method to compute action values and log probabilities for training', 'implement_get_value': 'implement the get_value method to return the value estimate from the high-level policy', 'customize_setup_actions': 'customize the _setup_actions method to filter PDDL actions by robot entity and allowed action names'}
```

## File: facebookresearch_partnr-planner/third_party/habitat-lab/habitat-baselines/habitat_baselines/rl/hrl/hl/neural_policy.py

Prompts

```
['initialize a FixedHighLevelPolicy that parses PDDL solution actions for each environment', 'parse the PDDL problem solution into a list of action names and arguments', 'get the next high-level skill and arguments from the fixed solution plan', 'apply a binary mask to reset the next skill index for selected environments', 'filter and clean up stateful variables to match only active environments', 'review the HighLevelPolicy class which selects from low-level skills in hierarchical RL', 'implement the get_next_skill method to return the next skill to execute for each environment', 'implement the evaluate_actions method to compute action values and log probabilities for training', 'implement the get_value method to return the value estimate from the high-level policy', 'customize the _setup_actions method to filter PDDL actions by robot entity and allowed action names', 'build a NeuralHighLevelPolicy instance with config, PDDL problem, observation space, and action space', 'review the NeuralHighLevelPolicy forward method that processes visual and state observations through RNN encoder', 'test the NeuralHighLevelPolicy evaluate_actions method to get action log probs, entropy, and critic values', 'summarize the NeuralHighLevelPolicy get_next_skill method that selects discrete skills and their arguments from the policy distribution', 'refactor the NeuralHighLevelPolicy get_termination method to customize termination detection from observation keys', 'build a high-level policy that plans a sequence of PDDL actions to rearrange objects in the Habitat environment', 'create a PlanNode dataclass to represent a node in the search tree for planning high-level action paths', 'test the BFS search method that finds PlanNodes satisfying a given PDDL goal from current predicate state', 'refactor the plan action selection method to support custom replanning logic for batched environment steps', 'review the get_next_skill method that returns the next high-level skill and arguments for each environment in the batch']
```

Usage

```
{'build_NeuralHighLevelPolicy': 'build a NeuralHighLevelPolicy instance with config, PDDL problem, observation space, and action space', 'review_NeuralHighLevelPolicy_forward': 'review the NeuralHighLevelPolicy forward method that processes visual and state observations through RNN encoder', 'test_NeuralHighLevelPolicy_evaluate_actions': 'test the NeuralHighLevelPolicy evaluate_actions method to get action log probs, entropy, and critic values', 'summarize_NeuralHighLevelPolicy_get_next_skill': 'summarize the NeuralHighLevelPolicy get_next_skill method that selects discrete skills and their arguments from the policy distribution', 'refactor_NeuralHighLevelPolicy_get_termination': 'refactor the NeuralHighLevelPolicy get_termination method to customize termination detection from observation keys'}
```

## File: facebookresearch_partnr-planner/third_party/habitat-lab/habitat-baselines/habitat_baselines/rl/hrl/hl/planner_policy.py

Prompts

```
['initialize a FixedHighLevelPolicy that parses PDDL solution actions for each environment', 'parse the PDDL problem solution into a list of action names and arguments', 'get the next high-level skill and arguments from the fixed solution plan', 'apply a binary mask to reset the next skill index for selected environments', 'filter and clean up stateful variables to match only active environments', 'review the HighLevelPolicy class which selects from low-level skills in hierarchical RL', 'implement the get_next_skill method to return the next skill to execute for each environment', 'implement the evaluate_actions method to compute action values and log probabilities for training', 'implement the get_value method to return the value estimate from the high-level policy', 'customize the _setup_actions method to filter PDDL actions by robot entity and allowed action names', 'build a NeuralHighLevelPolicy instance with config, PDDL problem, observation space, and action space', 'review the NeuralHighLevelPolicy forward method that processes visual and state observations through RNN encoder', 'test the NeuralHighLevelPolicy evaluate_actions method to get action log probs, entropy, and critic values', 'summarize the NeuralHighLevelPolicy get_next_skill method that selects discrete skills and their arguments from the policy distribution', 'refactor the NeuralHighLevelPolicy get_termination method to customize termination detection from observation keys', 'build a high-level policy that plans a sequence of PDDL actions to rearrange objects in the Habitat environment', 'create a PlanNode dataclass to represent a node in the search tree for planning high-level action paths', 'test the BFS search method that finds PlanNodes satisfying a given PDDL goal from current predicate state', 'refactor the plan action selection method to support custom replanning logic for batched environment steps', 'review the get_next_skill method that returns the next high-level skill and arguments for each environment in the batch']
```

Usage

```
{'build_PlannerHighLevelPolicy': 'build a high-level policy that plans a sequence of PDDL actions to rearrange objects in the Habitat environment', 'create_PlanNode': 'create a PlanNode dataclass to represent a node in the search tree for planning high-level action paths', 'test_get_solution_nodes': 'test the BFS search method that finds PlanNodes satisfying a given PDDL goal from current predicate state', 'refactor_get_plan_action': 'refactor the plan action selection method to support custom replanning logic for batched environment steps', 'review_get_next_skill': 'review the get_next_skill method that returns the next high-level skill and arguments for each environment in the batch'}
```

