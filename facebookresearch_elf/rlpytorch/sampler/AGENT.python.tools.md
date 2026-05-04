# Agent Python Tools

- repo: facebookresearch/elf
- repo_uri: https://github.com/facebookresearch/elf

## File: facebookresearch_elf/rlpytorch/sampler/sample_methods.py

Prompts

```
['sample actions with uniform probability across a given number of actions using PyTorch', 'multinomial sample from a probability tensor with out-of-bound validation and optional greedy mode', 'multinomial sample from probabilities with epsilon exploration and out-of-bound validation checks', 'sample actions from a policy node in the current state using epsilon-greedy multinomial sampling', 'sample actions using epsilon-greedy strategy by selecting the maximum probability action from the policy', 'build a python module that initializes a Sampler with epsilon-greedy, multinomial, or uniform sample policy', 'create a function that samples actions from a state distribution using epsilon-greedy or multinomial methods', 'test the Sampler class initialization with custom sample_policy, greedy, epsilon, and sample_nodes arguments', 'review the Sampler _on_get_args method that parses semicolon-separated sample_nodes into policy-action tuples', 'refactor the Sampler sample method to support uniform and original_distribution sampling policies']
```

Usage

```
{'sample_uniform_multinomial': 'sample actions with uniform probability across a given number of actions using PyTorch', 'sample_with_check': 'multinomial sample from a probability tensor with out-of-bound validation and optional greedy mode', 'sample_eps_with_check': 'multinomial sample from probabilities with epsilon exploration and out-of-bound validation checks', 'sample_multinomial': 'sample actions from a policy node in the current state using epsilon-greedy multinomial sampling', 'epsilon_greedy_sample': 'sample actions using epsilon-greedy strategy by selecting the maximum probability action from the policy'}
```

## File: facebookresearch_elf/rlpytorch/sampler/sampler.py

Prompts

```
['sample actions with uniform probability across a given number of actions using PyTorch', 'multinomial sample from a probability tensor with out-of-bound validation and optional greedy mode', 'multinomial sample from probabilities with epsilon exploration and out-of-bound validation checks', 'sample actions from a policy node in the current state using epsilon-greedy multinomial sampling', 'sample actions using epsilon-greedy strategy by selecting the maximum probability action from the policy', 'build a python module that initializes a Sampler with epsilon-greedy, multinomial, or uniform sample policy', 'create a function that samples actions from a state distribution using epsilon-greedy or multinomial methods', 'test the Sampler class initialization with custom sample_policy, greedy, epsilon, and sample_nodes arguments', 'review the Sampler _on_get_args method that parses semicolon-separated sample_nodes into policy-action tuples', 'refactor the Sampler sample method to support uniform and original_distribution sampling policies']
```

Usage

```
{'build_Sampler_class': 'build a python module that initializes a Sampler with epsilon-greedy, multinomial, or uniform sample policy', 'create_Sampler_sample': 'create a function that samples actions from a state distribution using epsilon-greedy or multinomial methods', 'test_Sampler_init': 'test the Sampler class initialization with custom sample_policy, greedy, epsilon, and sample_nodes arguments', 'review_Sampler_on_get_args': 'review the Sampler _on_get_args method that parses semicolon-separated sample_nodes into policy-action tuples', 'refactor_Sampler_sample': 'refactor the Sampler sample method to support uniform and original_distribution sampling policies'}
```

