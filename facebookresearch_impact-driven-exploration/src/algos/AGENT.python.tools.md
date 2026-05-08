# Agent Python Tools

- repo: facebookresearch/impact-driven-exploration
- repo_uri: https://github.com/facebookresearch/impact-driven-exploration

## File: facebookresearch_impact-driven-exploration/src/algos/count.py

Prompts

```
['run the train function to start impact-driven exploration training with intrinsic state count rewards', 'run the learn function to perform a single optimization step using vtrace returns and policy gradient loss', 'review the train function that orchestrates multi-actor PPO training with state count intrinsic rewards', 'review the learn function that computes policy gradient, baseline, and entropy losses with intrinsic rewards', 'refactor the learn function to support a different intrinsic reward computation method', 'run the curiosity-driven RL training loop with multiprocessing actors and intrinsic reward signals', 'run a single learning optimization step computing forward and inverse dynamics losses', 'review the learn function to understand how intrinsic rewards are computed from prediction errors', 'review the train function checkpoint logic that saves model and optimizer state dicts', 'refactor the learn function vtrace return computation to support custom advantage estimation', 'run the train function to start an IMPALA-style RL training loop with episodic count-based intrinsic rewards', 'run the learn function to perform a single VTrace optimization step with intrinsic count rewards', 'review the train function that orchestrates multi-actor multi-learner RL training with checkpointing', 'refactor the learn function to use a different intrinsic reward signal instead of episodic state counts', 'summarize how the learn function computes policy gradient, baseline, and entropy losses using VTrace returns', 'run the RIDE training loop with flags to train a Minigrid or MarioDoom agent', 'review the learn function that computes intrinsic rewards from state embeddings and dynamics models', 'refactor the learn function to modify forward or inverse dynamics loss computation', 'run the RND algorithm training loop with flags for Minigrid or MarioDoom environments']
```

Usage

```
{'run_train': 'run the train function to start impact-driven exploration training with intrinsic state count rewards', 'run_learn': 'run the learn function to perform a single optimization step using vtrace returns and policy gradient loss', 'review_train': 'review the train function that orchestrates multi-actor PPO training with state count intrinsic rewards', 'review_learn': 'review the learn function that computes policy gradient, baseline, and entropy losses with intrinsic rewards', 'refactor_learn': 'refactor the learn function to support a different intrinsic reward computation method'}
```

## File: facebookresearch_impact-driven-exploration/src/algos/curiosity.py

Prompts

```
['run the train function to start impact-driven exploration training with intrinsic state count rewards', 'run the learn function to perform a single optimization step using vtrace returns and policy gradient loss', 'review the train function that orchestrates multi-actor PPO training with state count intrinsic rewards', 'review the learn function that computes policy gradient, baseline, and entropy losses with intrinsic rewards', 'refactor the learn function to support a different intrinsic reward computation method', 'run the curiosity-driven RL training loop with multiprocessing actors and intrinsic reward signals', 'run a single learning optimization step computing forward and inverse dynamics losses', 'review the learn function to understand how intrinsic rewards are computed from prediction errors', 'review the train function checkpoint logic that saves model and optimizer state dicts', 'refactor the learn function vtrace return computation to support custom advantage estimation', 'run the train function to start an IMPALA-style RL training loop with episodic count-based intrinsic rewards', 'run the learn function to perform a single VTrace optimization step with intrinsic count rewards', 'review the train function that orchestrates multi-actor multi-learner RL training with checkpointing', 'refactor the learn function to use a different intrinsic reward signal instead of episodic state counts', 'summarize how the learn function computes policy gradient, baseline, and entropy losses using VTrace returns', 'run the RIDE training loop with flags to train a Minigrid or MarioDoom agent', 'review the learn function that computes intrinsic rewards from state embeddings and dynamics models', 'refactor the learn function to modify forward or inverse dynamics loss computation', 'run the RND algorithm training loop with flags for Minigrid or MarioDoom environments']
```

Usage

```
{'run_train_curiosity': 'run the curiosity-driven RL training loop with multiprocessing actors and intrinsic reward signals', 'run_learn_step': 'run a single learning optimization step computing forward and inverse dynamics losses', 'review_learn_intrinsic_rewards': 'review the learn function to understand how intrinsic rewards are computed from prediction errors', 'review_train_checkpoint': 'review the train function checkpoint logic that saves model and optimizer state dicts', 'refactor_learn_vtrace_returns': 'refactor the learn function vtrace return computation to support custom advantage estimation'}
```

## File: facebookresearch_impact-driven-exploration/src/algos/no_episodic_counts.py

Prompts

```
['run the train function to start impact-driven exploration training with intrinsic state count rewards', 'run the learn function to perform a single optimization step using vtrace returns and policy gradient loss', 'review the train function that orchestrates multi-actor PPO training with state count intrinsic rewards', 'review the learn function that computes policy gradient, baseline, and entropy losses with intrinsic rewards', 'refactor the learn function to support a different intrinsic reward computation method', 'run the curiosity-driven RL training loop with multiprocessing actors and intrinsic reward signals', 'run a single learning optimization step computing forward and inverse dynamics losses', 'review the learn function to understand how intrinsic rewards are computed from prediction errors', 'review the train function checkpoint logic that saves model and optimizer state dicts', 'refactor the learn function vtrace return computation to support custom advantage estimation', 'run the train function to start an IMPALA-style RL training loop with episodic count-based intrinsic rewards', 'run the learn function to perform a single VTrace optimization step with intrinsic count rewards', 'review the train function that orchestrates multi-actor multi-learner RL training with checkpointing', 'refactor the learn function to use a different intrinsic reward signal instead of episodic state counts', 'summarize how the learn function computes policy gradient, baseline, and entropy losses using VTrace returns', 'run the RIDE training loop with flags to train a Minigrid or MarioDoom agent', 'review the learn function that computes intrinsic rewards from state embeddings and dynamics models', 'refactor the learn function to modify forward or inverse dynamics loss computation', 'run the RND algorithm training loop with flags for Minigrid or MarioDoom environments']
```

Usage

```
{'run_train': 'run the train function to start impact-driven exploration training with intrinsic rewards on MiniGrid or Doom environments', 'run_learn': 'run the learn function to perform a single optimization step computing forward and inverse dynamics losses', 'review_learn': 'review the learn function to understand how intrinsic rewards are computed from state embedding differences', 'review_train': 'review the train function to understand the multi-actor multi-learner training loop with vtrace returns', 'refactor_learn': 'refactor the learn function to support additional dynamics loss types beyond forward and inverse models'}
```

## File: facebookresearch_impact-driven-exploration/src/algos/only_episodic_counts.py

Prompts

```
['run the train function to start impact-driven exploration training with intrinsic state count rewards', 'run the learn function to perform a single optimization step using vtrace returns and policy gradient loss', 'review the train function that orchestrates multi-actor PPO training with state count intrinsic rewards', 'review the learn function that computes policy gradient, baseline, and entropy losses with intrinsic rewards', 'refactor the learn function to support a different intrinsic reward computation method', 'run the curiosity-driven RL training loop with multiprocessing actors and intrinsic reward signals', 'run a single learning optimization step computing forward and inverse dynamics losses', 'review the learn function to understand how intrinsic rewards are computed from prediction errors', 'review the train function checkpoint logic that saves model and optimizer state dicts', 'refactor the learn function vtrace return computation to support custom advantage estimation', 'run the train function to start an IMPALA-style RL training loop with episodic count-based intrinsic rewards', 'run the learn function to perform a single VTrace optimization step with intrinsic count rewards', 'review the train function that orchestrates multi-actor multi-learner RL training with checkpointing', 'refactor the learn function to use a different intrinsic reward signal instead of episodic state counts', 'summarize how the learn function computes policy gradient, baseline, and entropy losses using VTrace returns', 'run the RIDE training loop with flags to train a Minigrid or MarioDoom agent', 'review the learn function that computes intrinsic rewards from state embeddings and dynamics models', 'refactor the learn function to modify forward or inverse dynamics loss computation', 'run the RND algorithm training loop with flags for Minigrid or MarioDoom environments']
```

Usage

```
{'train_episodic_counts_rl_agent': 'run the train function to start an IMPALA-style RL training loop with episodic count-based intrinsic rewards', 'learn_optimization_step': 'run the learn function to perform a single VTrace optimization step with intrinsic count rewards', 'review_train_function': 'review the train function that orchestrates multi-actor multi-learner RL training with checkpointing', 'refactor_learn_intrinsic_rewards': 'refactor the learn function to use a different intrinsic reward signal instead of episodic state counts', 'summarize_vtrace_loss_computation': 'summarize how the learn function computes policy gradient, baseline, and entropy losses using VTrace returns'}
```

## File: facebookresearch_impact-driven-exploration/src/algos/ride.py

Prompts

```
['run the train function to start impact-driven exploration training with intrinsic state count rewards', 'run the learn function to perform a single optimization step using vtrace returns and policy gradient loss', 'review the train function that orchestrates multi-actor PPO training with state count intrinsic rewards', 'review the learn function that computes policy gradient, baseline, and entropy losses with intrinsic rewards', 'refactor the learn function to support a different intrinsic reward computation method', 'run the curiosity-driven RL training loop with multiprocessing actors and intrinsic reward signals', 'run a single learning optimization step computing forward and inverse dynamics losses', 'review the learn function to understand how intrinsic rewards are computed from prediction errors', 'review the train function checkpoint logic that saves model and optimizer state dicts', 'refactor the learn function vtrace return computation to support custom advantage estimation', 'run the train function to start an IMPALA-style RL training loop with episodic count-based intrinsic rewards', 'run the learn function to perform a single VTrace optimization step with intrinsic count rewards', 'review the train function that orchestrates multi-actor multi-learner RL training with checkpointing', 'refactor the learn function to use a different intrinsic reward signal instead of episodic state counts', 'summarize how the learn function computes policy gradient, baseline, and entropy losses using VTrace returns', 'run the RIDE training loop with flags to train a Minigrid or MarioDoom agent', 'review the learn function that computes intrinsic rewards from state embeddings and dynamics models', 'refactor the learn function to modify forward or inverse dynamics loss computation', 'run the RND algorithm training loop with flags for Minigrid or MarioDoom environments']
```

Usage

```
{'run_train_RIDE': 'run the RIDE training loop with flags to train a Minigrid or MarioDoom agent', 'run_learn_step': 'run a single RIDE learning step computing policy gradient and dynamics losses', 'review_learn_function': 'review the learn function that computes intrinsic rewards from state embeddings and dynamics models', 'review_train_function': 'review the train function that spawns actor processes and learner threads for distributed RL', 'refactor_learn_dynamics_loss': 'refactor the learn function to modify forward or inverse dynamics loss computation'}
```

## File: facebookresearch_impact-driven-exploration/src/algos/rnd.py

Prompts

```
['run the train function to start impact-driven exploration training with intrinsic state count rewards', 'run the learn function to perform a single optimization step using vtrace returns and policy gradient loss', 'review the train function that orchestrates multi-actor PPO training with state count intrinsic rewards', 'review the learn function that computes policy gradient, baseline, and entropy losses with intrinsic rewards', 'refactor the learn function to support a different intrinsic reward computation method', 'run the curiosity-driven RL training loop with multiprocessing actors and intrinsic reward signals', 'run a single learning optimization step computing forward and inverse dynamics losses', 'review the learn function to understand how intrinsic rewards are computed from prediction errors', 'review the train function checkpoint logic that saves model and optimizer state dicts', 'refactor the learn function vtrace return computation to support custom advantage estimation', 'run the train function to start an IMPALA-style RL training loop with episodic count-based intrinsic rewards', 'run the learn function to perform a single VTrace optimization step with intrinsic count rewards', 'review the train function that orchestrates multi-actor multi-learner RL training with checkpointing', 'refactor the learn function to use a different intrinsic reward signal instead of episodic state counts', 'summarize how the learn function computes policy gradient, baseline, and entropy losses using VTrace returns', 'run the RIDE training loop with flags to train a Minigrid or MarioDoom agent', 'review the learn function that computes intrinsic rewards from state embeddings and dynamics models', 'refactor the learn function to modify forward or inverse dynamics loss computation', 'run the RND algorithm training loop with flags for Minigrid or MarioDoom environments']
```

Usage

```
{'run_RND_training': 'run the RND algorithm training loop with flags for Minigrid or MarioDoom environments', 'run_learn_step': 'run a single RND learning step computing intrinsic rewards and policy gradient loss', 'review_learn_function': 'review the learn function that computes RND loss, VTrace returns, and updates model parameters', 'review_train_function': 'review the train function that sets up actors, learners, and the training loop with checkpoints', 'refactor_learn_intrinsic_rewards': 'refactor the learn function to modify how intrinsic rewards are computed from random and predictor network embeddings'}
```

## File: facebookresearch_impact-driven-exploration/src/algos/torchbeast.py

Prompts

```
['run the train function to start impact-driven exploration training with intrinsic state count rewards', 'run the learn function to perform a single optimization step using vtrace returns and policy gradient loss', 'review the train function that orchestrates multi-actor PPO training with state count intrinsic rewards', 'review the learn function that computes policy gradient, baseline, and entropy losses with intrinsic rewards', 'refactor the learn function to support a different intrinsic reward computation method', 'run the curiosity-driven RL training loop with multiprocessing actors and intrinsic reward signals', 'run a single learning optimization step computing forward and inverse dynamics losses', 'review the learn function to understand how intrinsic rewards are computed from prediction errors', 'review the train function checkpoint logic that saves model and optimizer state dicts', 'refactor the learn function vtrace return computation to support custom advantage estimation', 'run the train function to start an IMPALA-style RL training loop with episodic count-based intrinsic rewards', 'run the learn function to perform a single VTrace optimization step with intrinsic count rewards', 'review the train function that orchestrates multi-actor multi-learner RL training with checkpointing', 'refactor the learn function to use a different intrinsic reward signal instead of episodic state counts', 'summarize how the learn function computes policy gradient, baseline, and entropy losses using VTrace returns', 'run the RIDE training loop with flags to train a Minigrid or MarioDoom agent', 'review the learn function that computes intrinsic rewards from state embeddings and dynamics models', 'refactor the learn function to modify forward or inverse dynamics loss computation', 'run the RND algorithm training loop with flags for Minigrid or MarioDoom environments']
```

Usage

```
{'run_train': 'run the torchbeast PPO training loop with vtrace corrections for a given environment and flags config', 'run_learn': 'run a single learning step computing policy gradient, baseline, and entropy loss with vtrace returns', 'review_learn': 'review the learn function that performs optimization using vtrace returns and RMSprop with gradient clipping', 'review_train': 'review the train function that spawns actor processes and learner threads for distributed RL training', 'refactor_learn': 'refactor the learn function to support a different loss computation or optimizer configuration'}
```

