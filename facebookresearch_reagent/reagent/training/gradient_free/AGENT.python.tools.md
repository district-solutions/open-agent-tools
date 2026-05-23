# Agent Python Tools

- repo: facebookresearch/reagent
- repo_uri: https://github.com/facebookresearch/reagent

## File: facebookresearch_reagent/reagent/training/gradient_free/ars_util.py

Prompts

```
['create an ARSOptimizer instance with feature_dim, n_pert, alpha step size, and noise level parameters', 'sample positive and negative perturbed parameter tuples from the ARSOptimizer for evaluation', 'update ARS optimizer parameters using a reward tensor from evaluated perturbed parameters', 'run an ARS training loop by sampling perturbations, computing rewards, and updating parameters each generation', 'review the ARSOptimizer class and its gradient-free optimization approach for reinforcement learning', 'create an EsWorker instance with an EvolutionPool, EvolutionParameters, ProcessGroup, and number of nodes', 'run an evolution strategy epoch to compute rewards across distributed machines and return the new parent reward', 'review the EsWorker class and its distributed reward computation logic for evolution strategy training', 'summarize the EsWorker constructor that initializes iteration counter, individual pool, and process group references', 'test the EsWorker run_epoch method to verify distributed reward aggregation and parent reward computation', 'create an EvolutionPool instance with a seed, ES parameters, and tensor sizes dictionary', 'populate child individuals in the evolution pool by mutating parent tensors with Gaussian noise', 'apply normalized rewards to parent tensors and update gradients using the Adam optimizer', 'compute and return a tensor of local rewards for all individuals in the population', 'create a OneMaxEvolutionPool that rewards tensors approaching alternating positive and negative infinity']
```

Usage

```
{'create_ars_optimizer': 'create an ARSOptimizer instance with feature_dim, n_pert, alpha step size, and noise level parameters', 'sample_perturbed_params': 'sample positive and negative perturbed parameter tuples from the ARSOptimizer for evaluation', 'update_ars_params': 'update ARS optimizer parameters using a reward tensor from evaluated perturbed parameters', 'run_ars_training_loop': 'run an ARS training loop by sampling perturbations, computing rewards, and updating parameters each generation', 'review_ars_optimizer_class': 'review the ARSOptimizer class and its gradient-free optimization approach for reinforcement learning'}
```

## File: facebookresearch_reagent/reagent/training/gradient_free/es_worker.py

Prompts

```
['create an ARSOptimizer instance with feature_dim, n_pert, alpha step size, and noise level parameters', 'sample positive and negative perturbed parameter tuples from the ARSOptimizer for evaluation', 'update ARS optimizer parameters using a reward tensor from evaluated perturbed parameters', 'run an ARS training loop by sampling perturbations, computing rewards, and updating parameters each generation', 'review the ARSOptimizer class and its gradient-free optimization approach for reinforcement learning', 'create an EsWorker instance with an EvolutionPool, EvolutionParameters, ProcessGroup, and number of nodes', 'run an evolution strategy epoch to compute rewards across distributed machines and return the new parent reward', 'review the EsWorker class and its distributed reward computation logic for evolution strategy training', 'summarize the EsWorker constructor that initializes iteration counter, individual pool, and process group references', 'test the EsWorker run_epoch method to verify distributed reward aggregation and parent reward computation', 'create an EvolutionPool instance with a seed, ES parameters, and tensor sizes dictionary', 'populate child individuals in the evolution pool by mutating parent tensors with Gaussian noise', 'apply normalized rewards to parent tensors and update gradients using the Adam optimizer', 'compute and return a tensor of local rewards for all individuals in the population', 'create a OneMaxEvolutionPool that rewards tensors approaching alternating positive and negative infinity']
```

Usage

```
{'create_es_worker': 'create an EsWorker instance with an EvolutionPool, EvolutionParameters, ProcessGroup, and number of nodes', 'run_es_epoch': 'run an evolution strategy epoch to compute rewards across distributed machines and return the new parent reward', 'review_es_worker_class': 'review the EsWorker class and its distributed reward computation logic for evolution strategy training', 'summarize_es_worker_init': 'summarize the EsWorker constructor that initializes iteration counter, individual pool, and process group references', 'test_es_worker_run_epoch': 'test the EsWorker run_epoch method to verify distributed reward aggregation and parent reward computation'}
```

## File: facebookresearch_reagent/reagent/training/gradient_free/evolution_pool.py

Prompts

```
['create an ARSOptimizer instance with feature_dim, n_pert, alpha step size, and noise level parameters', 'sample positive and negative perturbed parameter tuples from the ARSOptimizer for evaluation', 'update ARS optimizer parameters using a reward tensor from evaluated perturbed parameters', 'run an ARS training loop by sampling perturbations, computing rewards, and updating parameters each generation', 'review the ARSOptimizer class and its gradient-free optimization approach for reinforcement learning', 'create an EsWorker instance with an EvolutionPool, EvolutionParameters, ProcessGroup, and number of nodes', 'run an evolution strategy epoch to compute rewards across distributed machines and return the new parent reward', 'review the EsWorker class and its distributed reward computation logic for evolution strategy training', 'summarize the EsWorker constructor that initializes iteration counter, individual pool, and process group references', 'test the EsWorker run_epoch method to verify distributed reward aggregation and parent reward computation', 'create an EvolutionPool instance with a seed, ES parameters, and tensor sizes dictionary', 'populate child individuals in the evolution pool by mutating parent tensors with Gaussian noise', 'apply normalized rewards to parent tensors and update gradients using the Adam optimizer', 'compute and return a tensor of local rewards for all individuals in the population', 'create a OneMaxEvolutionPool that rewards tensors approaching alternating positive and negative infinity']
```

Usage

```
{'create_evolution_pool': 'create an EvolutionPool instance with a seed, ES parameters, and tensor sizes dictionary', 'populate_children': 'populate child individuals in the evolution pool by mutating parent tensors with Gaussian noise', 'apply_global_reward': 'apply normalized rewards to parent tensors and update gradients using the Adam optimizer', 'compute_all_local_rewards': 'compute and return a tensor of local rewards for all individuals in the population', 'create_onemax_evolution_pool': 'create a OneMaxEvolutionPool that rewards tensors approaching alternating positive and negative infinity'}
```

