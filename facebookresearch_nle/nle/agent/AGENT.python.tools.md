# Agent Python Tools

- repo: facebookresearch/nle
- repo_uri: https://github.com/facebookresearch/nle

## File: facebookresearch_nle/nle/agent/agent.py

Prompts

```
['train a NetHack agent using the PyTorch scalable agent with --mode train and --num_actors 4', 'test a trained NetHack agent by loading a checkpoint with --mode test and --savedir path', 'build a NetHackNet model with CNN layers and optional LSTM for NetHack observation processing', 'create a ResettingEnvironment wrapper that auto-resets a Gym environment on episode completion', 'run an actor process that collects rollouts and writes them to shared-memory buffers', 'compute V-trace off-policy actor-critic targets from behavior and target policy logits with rewards and values', 'compute V-trace targets from log importance weights, discounts, rewards, and values without gradient tracking', 'compute the log probabilities of taken actions given policy logits using negative log-likelihood loss', 'review the VTraceFromLogitsReturns namedtuple structure containing vs, pg_advantages, log_rhos, and action log probs', 'review the VTraceReturns namedtuple structure containing vs values and policy gradient advantages']
```

Usage

```
{'train_agent': 'train a NetHack agent using the PyTorch scalable agent with --mode train and --num_actors 4', 'test_agent': 'test a trained NetHack agent by loading a checkpoint with --mode test and --savedir path', 'build_NetHackNet': 'build a NetHackNet model with CNN layers and optional LSTM for NetHack observation processing', 'create_ResettingEnvironment': 'create a ResettingEnvironment wrapper that auto-resets a Gym environment on episode completion', 'run_actor_process': 'run an actor process that collects rollouts and writes them to shared-memory buffers'}
```

## File: facebookresearch_nle/nle/agent/vtrace.py

Prompts

```
['train a NetHack agent using the PyTorch scalable agent with --mode train and --num_actors 4', 'test a trained NetHack agent by loading a checkpoint with --mode test and --savedir path', 'build a NetHackNet model with CNN layers and optional LSTM for NetHack observation processing', 'create a ResettingEnvironment wrapper that auto-resets a Gym environment on episode completion', 'run an actor process that collects rollouts and writes them to shared-memory buffers', 'compute V-trace off-policy actor-critic targets from behavior and target policy logits with rewards and values', 'compute V-trace targets from log importance weights, discounts, rewards, and values without gradient tracking', 'compute the log probabilities of taken actions given policy logits using negative log-likelihood loss', 'review the VTraceFromLogitsReturns namedtuple structure containing vs, pg_advantages, log_rhos, and action log probs', 'review the VTraceReturns namedtuple structure containing vs values and policy gradient advantages']
```

Usage

```
{'compute_vtrace_from_logits': 'compute V-trace off-policy actor-critic targets from behavior and target policy logits with rewards and values', 'compute_vtrace_from_importance_weights': 'compute V-trace targets from log importance weights, discounts, rewards, and values without gradient tracking', 'compute_action_log_probs': 'compute the log probabilities of taken actions given policy logits using negative log-likelihood loss', 'review_VTraceFromLogitsReturns': 'review the VTraceFromLogitsReturns namedtuple structure containing vs, pg_advantages, log_rhos, and action log probs', 'review_VTraceReturns': 'review the VTraceReturns namedtuple structure containing vs values and policy gradient advantages'}
```

