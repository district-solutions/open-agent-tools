# Agent Python Tools

- repo: facebookresearch/labgraph
- repo_uri: https://github.com/facebookresearch/labgraph

## File: facebookresearch_labgraph/signal_processing/nodes/faucet/iir_filter_node.py

Prompts

```
['create a CausalButterFilterNodeConfig with custom sample rate, highpass cutoff, and lowpass cutoffs', 'create a DefaultBandpassConfigGenerator to get default bandpass filter configuration for causal filtering', 'run the CausalButterFilterNode labgraph node to apply causal IIR filtering on signal samples', 'review the CausalButterFilterNode run_filter method that processes samples through a cascaded filter chain', 'refactor the CausalButterFilterNode _init_filter_class method to customize sample rate estimation logic']
```

Usage

```
{'create_CausalButterFilterNodeConfig': 'create a CausalButterFilterNodeConfig with custom sample rate, highpass cutoff, and lowpass cutoffs', 'create_DefaultBandpassConfigGenerator': 'create a DefaultBandpassConfigGenerator to get default bandpass filter configuration for causal filtering', 'run_CausalButterFilterNode': 'run the CausalButterFilterNode labgraph node to apply causal IIR filtering on signal samples', 'review_CausalButterFilterNode_run_filter': 'review the CausalButterFilterNode run_filter method that processes samples through a cascaded filter chain', 'refactor_CausalButterFilterNode_init_filter_class': 'refactor the CausalButterFilterNode _init_filter_class method to customize sample rate estimation logic'}
```

