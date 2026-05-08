# Agent Python Tools

- repo: facebookresearch/reagent
- repo_uri: https://github.com/facebookresearch/reagent

## File: facebookresearch_reagent/reagent/gym/envs/wrappers/recsim.py

Prompts

```
['create a ValueWrapper that augments a RecSim gym environment observations with document value scores', 'build a value function that computes document relevance for a user and wrap it with ValueWrapper', 'test the ValueWrapper observation method to verify augmentation keys are added to each document', 'review the ValueWrapper observation_space property to understand how augmentation spaces are constructed', 'refactor the ValueWrapper KEY constant to use a custom augmentation key name instead of value', 'create a SimpleObsWrapper instance that wraps a gym MiniGrid environment to encode agent position and direction', 'build a SimpleObsWrapper that defines a one-hot observation space based on grid width, height, and direction count', 'test the SimpleObsWrapper observation method to verify it returns a one-hot vector encoding agent position and direction', 'review the SimpleObsWrapper class to understand how it encodes agent state into a flattened one-hot observation vector', 'refactor the SimpleObsWrapper observation method to customize the one-hot encoding formula for agent position and direction']
```

Usage

```
{'create_value_wrapper': 'create a ValueWrapper that augments a RecSim gym environment observations with document value scores', 'build_value_fn_augmentation': 'build a value function that computes document relevance for a user and wrap it with ValueWrapper', 'test_value_wrapper_observation': 'test the ValueWrapper observation method to verify augmentation keys are added to each document', 'review_value_wrapper_observation_space': 'review the ValueWrapper observation_space property to understand how augmentation spaces are constructed', 'refactor_value_wrapper_key': 'refactor the ValueWrapper KEY constant to use a custom augmentation key name instead of value'}
```

## File: facebookresearch_reagent/reagent/gym/envs/wrappers/simple_minigrid.py

Prompts

```
['create a ValueWrapper that augments a RecSim gym environment observations with document value scores', 'build a value function that computes document relevance for a user and wrap it with ValueWrapper', 'test the ValueWrapper observation method to verify augmentation keys are added to each document', 'review the ValueWrapper observation_space property to understand how augmentation spaces are constructed', 'refactor the ValueWrapper KEY constant to use a custom augmentation key name instead of value', 'create a SimpleObsWrapper instance that wraps a gym MiniGrid environment to encode agent position and direction', 'build a SimpleObsWrapper that defines a one-hot observation space based on grid width, height, and direction count', 'test the SimpleObsWrapper observation method to verify it returns a one-hot vector encoding agent position and direction', 'review the SimpleObsWrapper class to understand how it encodes agent state into a flattened one-hot observation vector', 'refactor the SimpleObsWrapper observation method to customize the one-hot encoding formula for agent position and direction']
```

Usage

```
{'create_SimpleObsWrapper': 'create a SimpleObsWrapper instance that wraps a gym MiniGrid environment to encode agent position and direction', 'build_SimpleObsWrapper_observation_space': 'build a SimpleObsWrapper that defines a one-hot observation space based on grid width, height, and direction count', 'test_SimpleObsWrapper_observation': 'test the SimpleObsWrapper observation method to verify it returns a one-hot vector encoding agent position and direction', 'review_SimpleObsWrapper': 'review the SimpleObsWrapper class to understand how it encodes agent state into a flattened one-hot observation vector', 'refactor_SimpleObsWrapper_observation': 'refactor the SimpleObsWrapper observation method to customize the one-hot encoding formula for agent position and direction'}
```

