# Agent Python Tools

- repo: facebookresearch/fairo
- repo_uri: https://github.com/facebookresearch/fairo

## File: facebookresearch_fairo/droidlet/lowlevel/locobot/remote/policy/utils/distributions.py

Prompts

```
['create a DiagGaussian module that outputs a diagonal Gaussian distribution from input features', 'use FixedNormal.log_probs to compute summed log probabilities of actions under a Normal distribution', 'use FixedNormal.entropy to compute the summed entropy of a Normal distribution', 'use FixedNormal.mode to get the mean as the mode of a Normal distribution', 'review the DiagGaussian forward pass that returns a FixedNormal distribution with learned mean and logstd', 'create an AddBias nn.Module that adds a learnable bias to 2D or 4D tensors', 'create a Flatten nn.Module that flattens all dimensions except the batch dimension', 'build an NNBase subclass with a GRUCell for recurrent policy networks with orthogonal init', 'review the NNBase _forward_gru method that handles single-step and sequence GRU forward passes with masks', 'summarize the NNBase is_recurrent, rec_state_size, and output_size properties for recurrent state metadata']
```

Usage

```
{'create_diag_gaussian_module': 'create a DiagGaussian module that outputs a diagonal Gaussian distribution from input features', 'use_fixed_normal_log_probs': 'use FixedNormal.log_probs to compute summed log probabilities of actions under a Normal distribution', 'use_fixed_normal_entropy': 'use FixedNormal.entropy to compute the summed entropy of a Normal distribution', 'use_fixed_normal_mode': 'use FixedNormal.mode to get the mean as the mode of a Normal distribution', 'review_diag_gaussian_forward': 'review the DiagGaussian forward pass that returns a FixedNormal distribution with learned mean and logstd'}
```

## File: facebookresearch_fairo/droidlet/lowlevel/locobot/remote/policy/utils/model.py

Prompts

```
['create a DiagGaussian module that outputs a diagonal Gaussian distribution from input features', 'use FixedNormal.log_probs to compute summed log probabilities of actions under a Normal distribution', 'use FixedNormal.entropy to compute the summed entropy of a Normal distribution', 'use FixedNormal.mode to get the mean as the mode of a Normal distribution', 'review the DiagGaussian forward pass that returns a FixedNormal distribution with learned mean and logstd', 'create an AddBias nn.Module that adds a learnable bias to 2D or 4D tensors', 'create a Flatten nn.Module that flattens all dimensions except the batch dimension', 'build an NNBase subclass with a GRUCell for recurrent policy networks with orthogonal init', 'review the NNBase _forward_gru method that handles single-step and sequence GRU forward passes with masks', 'summarize the NNBase is_recurrent, rec_state_size, and output_size properties for recurrent state metadata']
```

Usage

```
{'create_AddBias_module': 'create an AddBias nn.Module that adds a learnable bias to 2D or 4D tensors', 'create_Flatten_module': 'create a Flatten nn.Module that flattens all dimensions except the batch dimension', 'build_NNBase_with_gru': 'build an NNBase subclass with a GRUCell for recurrent policy networks with orthogonal init', 'review_NNBase_forward_gru': 'review the NNBase _forward_gru method that handles single-step and sequence GRU forward passes with masks', 'summarize_NNBase_properties': 'summarize the NNBase is_recurrent, rec_state_size, and output_size properties for recurrent state metadata'}
```

