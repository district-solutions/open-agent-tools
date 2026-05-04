# Agent Python Tools

- repo: facebookresearch/diplomacycicero
- repo_uri: https://github.com/facebookresearch/diplomacy_cicero

## File: facebookresearch_diplomacycicero/fairdiplomacy/selfplay/pg/data_loader.py

Prompts

```
['create a DataLoader to start rollout processes and inference servers for generating selfplay training data', 'build an alliance map tensor for a given alliance type grouping Diplomacy powers together', 'compute reward tensors from an ExploitRollout using score name, differential reward, and alliance settings', 'queue RolloutBatch items into a multiprocessing queue from yielded rewarded rollouts in a worker process', 'extract and aggregate scores from the Evaler rollout queue across all evaluation processes', 'run non-stop Diplomacy game rollouts yielding ExploitRollout tuples for exploit vs blueprint agents', 'create a pool of postman model servers across GPUs for parallel inference requests', 'call a model server synchronously with DataFields inputs and a softmax temperature', 'compute action log probabilities from order logits and order ID tensors using nll loss', 'convert a tensor of global order indices into human-readable string order lists per power', 'compute V-trace actor critic targets from behavior and target policy logits for IMPALA off-policy RL training', 'compute V-trace targets from log importance sampling weights, rewards, discounts, and value estimates', 'compute the log probabilities of taken actions given policy logits and an action mask tensor', 'review the VTraceFromLogitsReturns namedtuple structure containing vs, pg_advantages, log_rhos, and action log probabilities', 'review the VTraceReturns namedtuple structure containing vs, pg_advantages, rhos, and clipped_rhos fields']
```

Usage

```
{'create_Dataloader': 'create a DataLoader to start rollout processes and inference servers for generating selfplay training data', 'build_alliance_map': 'build an alliance map tensor for a given alliance type grouping Diplomacy powers together', 'compute_reward': 'compute reward tensors from an ExploitRollout using score name, differential reward, and alliance settings', 'queue_rollouts': 'queue RolloutBatch items into a multiprocessing queue from yielded rewarded rollouts in a worker process', 'Evaler_extract_scores': 'extract and aggregate scores from the Evaler rollout queue across all evaluation processes'}
```

## File: facebookresearch_diplomacycicero/fairdiplomacy/selfplay/pg/rollout.py

Prompts

```
['create a DataLoader to start rollout processes and inference servers for generating selfplay training data', 'build an alliance map tensor for a given alliance type grouping Diplomacy powers together', 'compute reward tensors from an ExploitRollout using score name, differential reward, and alliance settings', 'queue RolloutBatch items into a multiprocessing queue from yielded rewarded rollouts in a worker process', 'extract and aggregate scores from the Evaler rollout queue across all evaluation processes', 'run non-stop Diplomacy game rollouts yielding ExploitRollout tuples for exploit vs blueprint agents', 'create a pool of postman model servers across GPUs for parallel inference requests', 'call a model server synchronously with DataFields inputs and a softmax temperature', 'compute action log probabilities from order logits and order ID tensors using nll loss', 'convert a tensor of global order indices into human-readable string order lists per power', 'compute V-trace actor critic targets from behavior and target policy logits for IMPALA off-policy RL training', 'compute V-trace targets from log importance sampling weights, rewards, discounts, and value estimates', 'compute the log probabilities of taken actions given policy logits and an action mask tensor', 'review the VTraceFromLogitsReturns namedtuple structure containing vs, pg_advantages, log_rhos, and action log probabilities', 'review the VTraceReturns namedtuple structure containing vs, pg_advantages, rhos, and clipped_rhos fields']
```

Usage

```
{'run_yield_rollouts': 'run non-stop Diplomacy game rollouts yielding ExploitRollout tuples for exploit vs blueprint agents', 'create_InferencePool': 'create a pool of postman model servers across GPUs for parallel inference requests', 'call_do_model_request': 'call a model server synchronously with DataFields inputs and a softmax temperature', 'compute_order_logits_to_action_logprobs': 'compute action log probabilities from order logits and order ID tensors using nll loss', 'convert_strigify_orders_idxs': 'convert a tensor of global order indices into human-readable string order lists per power'}
```

## File: facebookresearch_diplomacycicero/fairdiplomacy/selfplay/pg/vtrace.py

Prompts

```
['create a DataLoader to start rollout processes and inference servers for generating selfplay training data', 'build an alliance map tensor for a given alliance type grouping Diplomacy powers together', 'compute reward tensors from an ExploitRollout using score name, differential reward, and alliance settings', 'queue RolloutBatch items into a multiprocessing queue from yielded rewarded rollouts in a worker process', 'extract and aggregate scores from the Evaler rollout queue across all evaluation processes', 'run non-stop Diplomacy game rollouts yielding ExploitRollout tuples for exploit vs blueprint agents', 'create a pool of postman model servers across GPUs for parallel inference requests', 'call a model server synchronously with DataFields inputs and a softmax temperature', 'compute action log probabilities from order logits and order ID tensors using nll loss', 'convert a tensor of global order indices into human-readable string order lists per power', 'compute V-trace actor critic targets from behavior and target policy logits for IMPALA off-policy RL training', 'compute V-trace targets from log importance sampling weights, rewards, discounts, and value estimates', 'compute the log probabilities of taken actions given policy logits and an action mask tensor', 'review the VTraceFromLogitsReturns namedtuple structure containing vs, pg_advantages, log_rhos, and action log probabilities', 'review the VTraceReturns namedtuple structure containing vs, pg_advantages, rhos, and clipped_rhos fields']
```

Usage

```
{'compute_vtrace_from_logits': 'compute V-trace actor critic targets from behavior and target policy logits for IMPALA off-policy RL training', 'compute_vtrace_from_importance_weights': 'compute V-trace targets from log importance sampling weights, rewards, discounts, and value estimates', 'compute_action_log_probs': 'compute the log probabilities of taken actions given policy logits and an action mask tensor', 'review_VTraceFromLogitsReturns_namedtuple': 'review the VTraceFromLogitsReturns namedtuple structure containing vs, pg_advantages, log_rhos, and action log probabilities', 'review_VTraceReturns_namedtuple': 'review the VTraceReturns namedtuple structure containing vs, pg_advantages, rhos, and clipped_rhos fields'}
```

