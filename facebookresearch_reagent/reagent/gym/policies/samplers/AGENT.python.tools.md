# Agent Python Tools

- repo: facebookresearch/reagent
- repo_uri: https://github.com/facebookresearch/reagent

## File: facebookresearch_reagent/reagent/gym/policies/samplers/continuous_sampler.py

Prompts

```
['create a GaussianSampler instance with an actor network for continuous action sampling', 'sample actions from a Gaussian distribution using the GaussianSampler sample_action method', 'compute the log probability of squashed actions using the GaussianSampler log_prob method', 'review the GaussianSampler class implementation for continuous action sampling with tanh squashing', 'refactor the GaussianSampler sample_action method to support custom action scaling', 'create a SoftmaxActionSampler with temperature and decay to sample actions from logits', 'sample actions from action scores using a SoftmaxActionSampler with temperature-based softmax distribution', 'create a GreedyActionSampler to always select the highest scoring action from scores', 'create an EpsilonGreedyActionSampler with epsilon decay for exploration-exploitation tradeoff', 'update a SoftmaxActionSampler or EpsilonGreedyActionSampler to decay temperature or epsilon over time', 'create a TopKSampler instance with a specified k value for top-k action sampling', 'sample actions from a scores tensor using TopKSampler to get top-k action indices', 'review the TopKSampler class that implements the Sampler interface for top-k action selection', 'summarize the sample_action method that uses torch.topk to select top-k actions from scores', 'test the TopKSampler class to verify it correctly samples top-k actions from input score tensors']
```

Usage

```
{'create_GaussianSampler': 'create a GaussianSampler instance with an actor network for continuous action sampling', 'sample_action_GaussianSampler': 'sample actions from a Gaussian distribution using the GaussianSampler sample_action method', 'log_prob_GaussianSampler': 'compute the log probability of squashed actions using the GaussianSampler log_prob method', 'review_GaussianSampler_class': 'review the GaussianSampler class implementation for continuous action sampling with tanh squashing', 'refactor_GaussianSampler_sample_action': 'refactor the GaussianSampler sample_action method to support custom action scaling'}
```

## File: facebookresearch_reagent/reagent/gym/policies/samplers/discrete_sampler.py

Prompts

```
['create a GaussianSampler instance with an actor network for continuous action sampling', 'sample actions from a Gaussian distribution using the GaussianSampler sample_action method', 'compute the log probability of squashed actions using the GaussianSampler log_prob method', 'review the GaussianSampler class implementation for continuous action sampling with tanh squashing', 'refactor the GaussianSampler sample_action method to support custom action scaling', 'create a SoftmaxActionSampler with temperature and decay to sample actions from logits', 'sample actions from action scores using a SoftmaxActionSampler with temperature-based softmax distribution', 'create a GreedyActionSampler to always select the highest scoring action from scores', 'create an EpsilonGreedyActionSampler with epsilon decay for exploration-exploitation tradeoff', 'update a SoftmaxActionSampler or EpsilonGreedyActionSampler to decay temperature or epsilon over time', 'create a TopKSampler instance with a specified k value for top-k action sampling', 'sample actions from a scores tensor using TopKSampler to get top-k action indices', 'review the TopKSampler class that implements the Sampler interface for top-k action selection', 'summarize the sample_action method that uses torch.topk to select top-k actions from scores', 'test the TopKSampler class to verify it correctly samples top-k actions from input score tensors']
```

Usage

```
{'create_softmax_action_sampler': 'create a SoftmaxActionSampler with temperature and decay to sample actions from logits', 'sample_action_softmax': 'sample actions from action scores using a SoftmaxActionSampler with temperature-based softmax distribution', 'create_greedy_action_sampler': 'create a GreedyActionSampler to always select the highest scoring action from scores', 'create_epsilon_greedy_sampler': 'create an EpsilonGreedyActionSampler with epsilon decay for exploration-exploitation tradeoff', 'update_sampler_temperature': 'update a SoftmaxActionSampler or EpsilonGreedyActionSampler to decay temperature or epsilon over time'}
```

## File: facebookresearch_reagent/reagent/gym/policies/samplers/top_k_sampler.py

Prompts

```
['create a GaussianSampler instance with an actor network for continuous action sampling', 'sample actions from a Gaussian distribution using the GaussianSampler sample_action method', 'compute the log probability of squashed actions using the GaussianSampler log_prob method', 'review the GaussianSampler class implementation for continuous action sampling with tanh squashing', 'refactor the GaussianSampler sample_action method to support custom action scaling', 'create a SoftmaxActionSampler with temperature and decay to sample actions from logits', 'sample actions from action scores using a SoftmaxActionSampler with temperature-based softmax distribution', 'create a GreedyActionSampler to always select the highest scoring action from scores', 'create an EpsilonGreedyActionSampler with epsilon decay for exploration-exploitation tradeoff', 'update a SoftmaxActionSampler or EpsilonGreedyActionSampler to decay temperature or epsilon over time', 'create a TopKSampler instance with a specified k value for top-k action sampling', 'sample actions from a scores tensor using TopKSampler to get top-k action indices', 'review the TopKSampler class that implements the Sampler interface for top-k action selection', 'summarize the sample_action method that uses torch.topk to select top-k actions from scores', 'test the TopKSampler class to verify it correctly samples top-k actions from input score tensors']
```

Usage

```
{'create_TopKSampler': 'create a TopKSampler instance with a specified k value for top-k action sampling', 'sample_action_TopKSampler': 'sample actions from a scores tensor using TopKSampler to get top-k action indices', 'review_TopKSampler_class': 'review the TopKSampler class that implements the Sampler interface for top-k action selection', 'summarize_TopKSampler_sample_action': 'summarize the sample_action method that uses torch.topk to select top-k actions from scores', 'test_TopKSampler': 'test the TopKSampler class to verify it correctly samples top-k actions from input score tensors'}
```

