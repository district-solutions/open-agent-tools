# Agent Python Tools

- repo: facebookresearch/pearl
- repo_uri: https://github.com/facebookresearch/pearl

## File: facebookresearch_pearl/pearl/api/action_result.py

Prompts

```
['create an ActionResult with observation, reward, terminated, and truncated fields', 'create an ActionResult instance that includes an optional cost value', 'create an ActionResult instance that includes an optional info dictionary', 'check if an ActionResult is done by accessing its done property', 'create an ActionResult that includes an available action space', 'review the ActionSpace abstract base class and its action_dim property for RL agent design', 'summarize the ActionSpace class which defines the interface for agent action spaces', 'review the abstract action_dim property that returns the dimensionality of an Action element', 'summarize the action_dim property used to get the dimensionality of actions from this space', 'review how ActionSpace inherits from Space to represent the set of all possible agent actions', 'create a concrete Agent subclass that implements act, observe, learn, reset, and compare methods', "implement the act method to return an Action based on the agent's current policy", "implement the observe method to process an ActionResult and update the agent's internal state", 'implement the learn method to perform a training step and return a learning summary object', 'implement the compare method to return a string describing differences between two Agent instances', 'implement a concrete subclass of Environment that overrides reset and step methods for a custom RL task', 'override the action_space property in an Environment subclass to return a custom ActionSpace instance', 'override the observation_space property in an Environment subclass to return a custom Space instance', 'implement the reset method in an Environment subclass to return initial observation and action space with optional seed', 'implement the step method in an Environment subclass to process an Action and return an ActionResult', 'review the abstract Space base class for action and observation spaces in Pearl', 'review the abstract sample method that samples an element from the Space', 'review the abstract shape property that returns the torch.Size of an element', 'review the abstract is_continuous property that checks if the Space is continuous', 'build a concrete subclass of Space implementing sample, shape, and is_continuous']
```

Usage

```
{'create_action_result': 'create an ActionResult with observation, reward, terminated, and truncated fields', 'create_action_result_with_cost': 'create an ActionResult instance that includes an optional cost value', 'create_action_result_with_info': 'create an ActionResult instance that includes an optional info dictionary', 'check_action_result_done': 'check if an ActionResult is done by accessing its done property', 'create_action_result_with_action_space': 'create an ActionResult that includes an available action space'}
```

## File: facebookresearch_pearl/pearl/api/action_space.py

Prompts

```
['create an ActionResult with observation, reward, terminated, and truncated fields', 'create an ActionResult instance that includes an optional cost value', 'create an ActionResult instance that includes an optional info dictionary', 'check if an ActionResult is done by accessing its done property', 'create an ActionResult that includes an available action space', 'review the ActionSpace abstract base class and its action_dim property for RL agent design', 'summarize the ActionSpace class which defines the interface for agent action spaces', 'review the abstract action_dim property that returns the dimensionality of an Action element', 'summarize the action_dim property used to get the dimensionality of actions from this space', 'review how ActionSpace inherits from Space to represent the set of all possible agent actions', 'create a concrete Agent subclass that implements act, observe, learn, reset, and compare methods', "implement the act method to return an Action based on the agent's current policy", "implement the observe method to process an ActionResult and update the agent's internal state", 'implement the learn method to perform a training step and return a learning summary object', 'implement the compare method to return a string describing differences between two Agent instances', 'implement a concrete subclass of Environment that overrides reset and step methods for a custom RL task', 'override the action_space property in an Environment subclass to return a custom ActionSpace instance', 'override the observation_space property in an Environment subclass to return a custom Space instance', 'implement the reset method in an Environment subclass to return initial observation and action space with optional seed', 'implement the step method in an Environment subclass to process an Action and return an ActionResult', 'review the abstract Space base class for action and observation spaces in Pearl', 'review the abstract sample method that samples an element from the Space', 'review the abstract shape property that returns the torch.Size of an element', 'review the abstract is_continuous property that checks if the Space is continuous', 'build a concrete subclass of Space implementing sample, shape, and is_continuous']
```

Usage

```
{'review_ActionSpace_class': 'review the ActionSpace abstract base class and its action_dim property for RL agent design', 'summarize_ActionSpace_class': 'summarize the ActionSpace class which defines the interface for agent action spaces', 'review_action_dim_property': 'review the abstract action_dim property that returns the dimensionality of an Action element', 'summarize_action_dim_property': 'summarize the action_dim property used to get the dimensionality of actions from this space', 'review_Space_inheritance': 'review how ActionSpace inherits from Space to represent the set of all possible agent actions'}
```

## File: facebookresearch_pearl/pearl/api/agent.py

Prompts

```
['create an ActionResult with observation, reward, terminated, and truncated fields', 'create an ActionResult instance that includes an optional cost value', 'create an ActionResult instance that includes an optional info dictionary', 'check if an ActionResult is done by accessing its done property', 'create an ActionResult that includes an available action space', 'review the ActionSpace abstract base class and its action_dim property for RL agent design', 'summarize the ActionSpace class which defines the interface for agent action spaces', 'review the abstract action_dim property that returns the dimensionality of an Action element', 'summarize the action_dim property used to get the dimensionality of actions from this space', 'review how ActionSpace inherits from Space to represent the set of all possible agent actions', 'create a concrete Agent subclass that implements act, observe, learn, reset, and compare methods', "implement the act method to return an Action based on the agent's current policy", "implement the observe method to process an ActionResult and update the agent's internal state", 'implement the learn method to perform a training step and return a learning summary object', 'implement the compare method to return a string describing differences between two Agent instances', 'implement a concrete subclass of Environment that overrides reset and step methods for a custom RL task', 'override the action_space property in an Environment subclass to return a custom ActionSpace instance', 'override the observation_space property in an Environment subclass to return a custom Space instance', 'implement the reset method in an Environment subclass to return initial observation and action space with optional seed', 'implement the step method in an Environment subclass to process an Action and return an ActionResult', 'review the abstract Space base class for action and observation spaces in Pearl', 'review the abstract sample method that samples an element from the Space', 'review the abstract shape property that returns the torch.Size of an element', 'review the abstract is_continuous property that checks if the Space is continuous', 'build a concrete subclass of Space implementing sample, shape, and is_continuous']
```

Usage

```
{'implement_agent_subclass': 'create a concrete Agent subclass that implements act, observe, learn, reset, and compare methods', 'implement_act_method': "implement the act method to return an Action based on the agent's current policy", 'implement_observe_method': "implement the observe method to process an ActionResult and update the agent's internal state", 'implement_learn_method': 'implement the learn method to perform a training step and return a learning summary object', 'implement_compare_method': 'implement the compare method to return a string describing differences between two Agent instances'}
```

## File: facebookresearch_pearl/pearl/api/environment.py

Prompts

```
['create an ActionResult with observation, reward, terminated, and truncated fields', 'create an ActionResult instance that includes an optional cost value', 'create an ActionResult instance that includes an optional info dictionary', 'check if an ActionResult is done by accessing its done property', 'create an ActionResult that includes an available action space', 'review the ActionSpace abstract base class and its action_dim property for RL agent design', 'summarize the ActionSpace class which defines the interface for agent action spaces', 'review the abstract action_dim property that returns the dimensionality of an Action element', 'summarize the action_dim property used to get the dimensionality of actions from this space', 'review how ActionSpace inherits from Space to represent the set of all possible agent actions', 'create a concrete Agent subclass that implements act, observe, learn, reset, and compare methods', "implement the act method to return an Action based on the agent's current policy", "implement the observe method to process an ActionResult and update the agent's internal state", 'implement the learn method to perform a training step and return a learning summary object', 'implement the compare method to return a string describing differences between two Agent instances', 'implement a concrete subclass of Environment that overrides reset and step methods for a custom RL task', 'override the action_space property in an Environment subclass to return a custom ActionSpace instance', 'override the observation_space property in an Environment subclass to return a custom Space instance', 'implement the reset method in an Environment subclass to return initial observation and action space with optional seed', 'implement the step method in an Environment subclass to process an Action and return an ActionResult', 'review the abstract Space base class for action and observation spaces in Pearl', 'review the abstract sample method that samples an element from the Space', 'review the abstract shape property that returns the torch.Size of an element', 'review the abstract is_continuous property that checks if the Space is continuous', 'build a concrete subclass of Space implementing sample, shape, and is_continuous']
```

Usage

```
{'implement_environment_subclass': 'implement a concrete subclass of Environment that overrides reset and step methods for a custom RL task', 'override_action_space_property': 'override the action_space property in an Environment subclass to return a custom ActionSpace instance', 'override_observation_space_property': 'override the observation_space property in an Environment subclass to return a custom Space instance', 'implement_reset_method': 'implement the reset method in an Environment subclass to return initial observation and action space with optional seed', 'implement_step_method': 'implement the step method in an Environment subclass to process an Action and return an ActionResult'}
```

## File: facebookresearch_pearl/pearl/api/space.py

Prompts

```
['create an ActionResult with observation, reward, terminated, and truncated fields', 'create an ActionResult instance that includes an optional cost value', 'create an ActionResult instance that includes an optional info dictionary', 'check if an ActionResult is done by accessing its done property', 'create an ActionResult that includes an available action space', 'review the ActionSpace abstract base class and its action_dim property for RL agent design', 'summarize the ActionSpace class which defines the interface for agent action spaces', 'review the abstract action_dim property that returns the dimensionality of an Action element', 'summarize the action_dim property used to get the dimensionality of actions from this space', 'review how ActionSpace inherits from Space to represent the set of all possible agent actions', 'create a concrete Agent subclass that implements act, observe, learn, reset, and compare methods', "implement the act method to return an Action based on the agent's current policy", "implement the observe method to process an ActionResult and update the agent's internal state", 'implement the learn method to perform a training step and return a learning summary object', 'implement the compare method to return a string describing differences between two Agent instances', 'implement a concrete subclass of Environment that overrides reset and step methods for a custom RL task', 'override the action_space property in an Environment subclass to return a custom ActionSpace instance', 'override the observation_space property in an Environment subclass to return a custom Space instance', 'implement the reset method in an Environment subclass to return initial observation and action space with optional seed', 'implement the step method in an Environment subclass to process an Action and return an ActionResult', 'review the abstract Space base class for action and observation spaces in Pearl', 'review the abstract sample method that samples an element from the Space', 'review the abstract shape property that returns the torch.Size of an element', 'review the abstract is_continuous property that checks if the Space is continuous', 'build a concrete subclass of Space implementing sample, shape, and is_continuous']
```

Usage

```
{'review_Space_class': 'review the abstract Space base class for action and observation spaces in Pearl', 'review_Space_sample_method': 'review the abstract sample method that samples an element from the Space', 'review_Space_shape_property': 'review the abstract shape property that returns the torch.Size of an element', 'review_Space_is_continuous_property': 'review the abstract is_continuous property that checks if the Space is continuous', 'build_Space_subclass': 'build a concrete subclass of Space implementing sample, shape, and is_continuous'}
```

