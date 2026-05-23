# Agent Python Tools

- repo: facebookresearch/reagent
- repo_uri: https://github.com/facebookresearch/reagent

## File: facebookresearch_reagent/reagent/training/ranking/helper.py

Prompts

```
['run ips_clamp with universal method to clamp importance sampling weights between 0 and clamp_max', 'run ips_clamp with aggressive method to zero out importance sampling weights exceeding clamp_max', 'run ips_clamp with no clamp config to return a cloned copy of the input tensor', 'review the ips_clamp function and its two clamping strategies for importance sampling weights', 'test the ips_clamp function with universal and aggressive clamp methods on torch tensors', 'build a Seq2SlatePairwiseAttnTrainer with a transformer net, slate size, and policy optimizer', 'train a Seq2Slate model using KL divergence loss on encoder scores and position rewards', 'validate ranking performance by computing DCG, NDCG, mean AP, and AUC metrics on batches', 'configure the policy optimizer and scheduler for the Seq2Slate transformer network parameters', 'review the validation_step method that computes cross-entropy loss and ranking evaluation metrics', 'create a function that computes the swap distance between a product ordering and a target index list', 'build a Seq2SlateSimulationTrainer to train a Seq2Slate model using simulated data with reward networks', 'test the swap_dist_in_slate function that counts swaps needed to sort indices within a slate', 'review the _simulated_training_input method that generates simulated training data using reward network predictions', 'refactor the _load_reward_net function to load TorchScript reward networks from file paths onto GPU or CPU', 'create a Seq2SlateTeacherForcingTrainer with a transformer net, parameters, and policy optimizer', 'configure optimizers for the Seq2Slate network using the policy optimizer scheduler', 'run a training step that computes KL divergence loss between log probs and labels', 'transform target output indices into one-hot encoded labels for KL divergence loss', 'run a validation step that computes slate rank probabilities and optionally evaluates CPE', 'create a Seq2SlateTrainer instance with a Seq2SlateTransformerNet and Seq2SlateParameters for ranking training', 'configure optimizers for the Seq2Slate policy network and optional baseline network', 'compute importance sampling ratios between model propensities and logged propensities with clamping']
```

Usage

```
{'run_ips_clamp_universal': 'run ips_clamp with universal method to clamp importance sampling weights between 0 and clamp_max', 'run_ips_clamp_aggressive': 'run ips_clamp with aggressive method to zero out importance sampling weights exceeding clamp_max', 'run_ips_clamp_no_clamp': 'run ips_clamp with no clamp config to return a cloned copy of the input tensor', 'review_ips_clamp': 'review the ips_clamp function and its two clamping strategies for importance sampling weights', 'test_ips_clamp': 'test the ips_clamp function with universal and aggressive clamp methods on torch tensors'}
```

## File: facebookresearch_reagent/reagent/training/ranking/seq2slate_attn_trainer.py

Prompts

```
['run ips_clamp with universal method to clamp importance sampling weights between 0 and clamp_max', 'run ips_clamp with aggressive method to zero out importance sampling weights exceeding clamp_max', 'run ips_clamp with no clamp config to return a cloned copy of the input tensor', 'review the ips_clamp function and its two clamping strategies for importance sampling weights', 'test the ips_clamp function with universal and aggressive clamp methods on torch tensors', 'build a Seq2SlatePairwiseAttnTrainer with a transformer net, slate size, and policy optimizer', 'train a Seq2Slate model using KL divergence loss on encoder scores and position rewards', 'validate ranking performance by computing DCG, NDCG, mean AP, and AUC metrics on batches', 'configure the policy optimizer and scheduler for the Seq2Slate transformer network parameters', 'review the validation_step method that computes cross-entropy loss and ranking evaluation metrics', 'create a function that computes the swap distance between a product ordering and a target index list', 'build a Seq2SlateSimulationTrainer to train a Seq2Slate model using simulated data with reward networks', 'test the swap_dist_in_slate function that counts swaps needed to sort indices within a slate', 'review the _simulated_training_input method that generates simulated training data using reward network predictions', 'refactor the _load_reward_net function to load TorchScript reward networks from file paths onto GPU or CPU', 'create a Seq2SlateTeacherForcingTrainer with a transformer net, parameters, and policy optimizer', 'configure optimizers for the Seq2Slate network using the policy optimizer scheduler', 'run a training step that computes KL divergence loss between log probs and labels', 'transform target output indices into one-hot encoded labels for KL divergence loss', 'run a validation step that computes slate rank probabilities and optionally evaluates CPE', 'create a Seq2SlateTrainer instance with a Seq2SlateTransformerNet and Seq2SlateParameters for ranking training', 'configure optimizers for the Seq2Slate policy network and optional baseline network', 'compute importance sampling ratios between model propensities and logged propensities with clamping']
```

Usage

```
{'build_seq2slate_trainer': 'build a Seq2SlatePairwiseAttnTrainer with a transformer net, slate size, and policy optimizer', 'train_seq2slate_model': 'train a Seq2Slate model using KL divergence loss on encoder scores and position rewards', 'validate_ranking_metrics': 'validate ranking performance by computing DCG, NDCG, mean AP, and AUC metrics on batches', 'configure_optimizer': 'configure the policy optimizer and scheduler for the Seq2Slate transformer network parameters', 'review_validation_step': 'review the validation_step method that computes cross-entropy loss and ranking evaluation metrics'}
```

## File: facebookresearch_reagent/reagent/training/ranking/seq2slate_sim_trainer.py

Prompts

```
['run ips_clamp with universal method to clamp importance sampling weights between 0 and clamp_max', 'run ips_clamp with aggressive method to zero out importance sampling weights exceeding clamp_max', 'run ips_clamp with no clamp config to return a cloned copy of the input tensor', 'review the ips_clamp function and its two clamping strategies for importance sampling weights', 'test the ips_clamp function with universal and aggressive clamp methods on torch tensors', 'build a Seq2SlatePairwiseAttnTrainer with a transformer net, slate size, and policy optimizer', 'train a Seq2Slate model using KL divergence loss on encoder scores and position rewards', 'validate ranking performance by computing DCG, NDCG, mean AP, and AUC metrics on batches', 'configure the policy optimizer and scheduler for the Seq2Slate transformer network parameters', 'review the validation_step method that computes cross-entropy loss and ranking evaluation metrics', 'create a function that computes the swap distance between a product ordering and a target index list', 'build a Seq2SlateSimulationTrainer to train a Seq2Slate model using simulated data with reward networks', 'test the swap_dist_in_slate function that counts swaps needed to sort indices within a slate', 'review the _simulated_training_input method that generates simulated training data using reward network predictions', 'refactor the _load_reward_net function to load TorchScript reward networks from file paths onto GPU or CPU', 'create a Seq2SlateTeacherForcingTrainer with a transformer net, parameters, and policy optimizer', 'configure optimizers for the Seq2Slate network using the policy optimizer scheduler', 'run a training step that computes KL divergence loss between log probs and labels', 'transform target output indices into one-hot encoded labels for KL divergence loss', 'run a validation step that computes slate rank probabilities and optionally evaluates CPE', 'create a Seq2SlateTrainer instance with a Seq2SlateTransformerNet and Seq2SlateParameters for ranking training', 'configure optimizers for the Seq2Slate policy network and optional baseline network', 'compute importance sampling ratios between model propensities and logged propensities with clamping']
```

Usage

```
{'create_swap_dist': 'create a function that computes the swap distance between a product ordering and a target index list', 'build_seq2slate_simulation_trainer': 'build a Seq2SlateSimulationTrainer to train a Seq2Slate model using simulated data with reward networks', 'test_swap_dist_in_slate': 'test the swap_dist_in_slate function that counts swaps needed to sort indices within a slate', 'review_simulated_training_input': 'review the _simulated_training_input method that generates simulated training data using reward network predictions', 'refactor_load_reward_net': 'refactor the _load_reward_net function to load TorchScript reward networks from file paths onto GPU or CPU'}
```

## File: facebookresearch_reagent/reagent/training/ranking/seq2slate_tf_trainer.py

Prompts

```
['run ips_clamp with universal method to clamp importance sampling weights between 0 and clamp_max', 'run ips_clamp with aggressive method to zero out importance sampling weights exceeding clamp_max', 'run ips_clamp with no clamp config to return a cloned copy of the input tensor', 'review the ips_clamp function and its two clamping strategies for importance sampling weights', 'test the ips_clamp function with universal and aggressive clamp methods on torch tensors', 'build a Seq2SlatePairwiseAttnTrainer with a transformer net, slate size, and policy optimizer', 'train a Seq2Slate model using KL divergence loss on encoder scores and position rewards', 'validate ranking performance by computing DCG, NDCG, mean AP, and AUC metrics on batches', 'configure the policy optimizer and scheduler for the Seq2Slate transformer network parameters', 'review the validation_step method that computes cross-entropy loss and ranking evaluation metrics', 'create a function that computes the swap distance between a product ordering and a target index list', 'build a Seq2SlateSimulationTrainer to train a Seq2Slate model using simulated data with reward networks', 'test the swap_dist_in_slate function that counts swaps needed to sort indices within a slate', 'review the _simulated_training_input method that generates simulated training data using reward network predictions', 'refactor the _load_reward_net function to load TorchScript reward networks from file paths onto GPU or CPU', 'create a Seq2SlateTeacherForcingTrainer with a transformer net, parameters, and policy optimizer', 'configure optimizers for the Seq2Slate network using the policy optimizer scheduler', 'run a training step that computes KL divergence loss between log probs and labels', 'transform target output indices into one-hot encoded labels for KL divergence loss', 'run a validation step that computes slate rank probabilities and optionally evaluates CPE', 'create a Seq2SlateTrainer instance with a Seq2SlateTransformerNet and Seq2SlateParameters for ranking training', 'configure optimizers for the Seq2Slate policy network and optional baseline network', 'compute importance sampling ratios between model propensities and logged propensities with clamping']
```

Usage

```
{'create_seq2slate_teacher_forcing_trainer': 'create a Seq2SlateTeacherForcingTrainer with a transformer net, parameters, and policy optimizer', 'configure_seq2slate_optimizers': 'configure optimizers for the Seq2Slate network using the policy optimizer scheduler', 'run_training_step': 'run a training step that computes KL divergence loss between log probs and labels', 'transform_label_one_hot': 'transform target output indices into one-hot encoded labels for KL divergence loss', 'run_validation_step': 'run a validation step that computes slate rank probabilities and optionally evaluates CPE'}
```

## File: facebookresearch_reagent/reagent/training/ranking/seq2slate_trainer.py

Prompts

```
['run ips_clamp with universal method to clamp importance sampling weights between 0 and clamp_max', 'run ips_clamp with aggressive method to zero out importance sampling weights exceeding clamp_max', 'run ips_clamp with no clamp config to return a cloned copy of the input tensor', 'review the ips_clamp function and its two clamping strategies for importance sampling weights', 'test the ips_clamp function with universal and aggressive clamp methods on torch tensors', 'build a Seq2SlatePairwiseAttnTrainer with a transformer net, slate size, and policy optimizer', 'train a Seq2Slate model using KL divergence loss on encoder scores and position rewards', 'validate ranking performance by computing DCG, NDCG, mean AP, and AUC metrics on batches', 'configure the policy optimizer and scheduler for the Seq2Slate transformer network parameters', 'review the validation_step method that computes cross-entropy loss and ranking evaluation metrics', 'create a function that computes the swap distance between a product ordering and a target index list', 'build a Seq2SlateSimulationTrainer to train a Seq2Slate model using simulated data with reward networks', 'test the swap_dist_in_slate function that counts swaps needed to sort indices within a slate', 'review the _simulated_training_input method that generates simulated training data using reward network predictions', 'refactor the _load_reward_net function to load TorchScript reward networks from file paths onto GPU or CPU', 'create a Seq2SlateTeacherForcingTrainer with a transformer net, parameters, and policy optimizer', 'configure optimizers for the Seq2Slate network using the policy optimizer scheduler', 'run a training step that computes KL divergence loss between log probs and labels', 'transform target output indices into one-hot encoded labels for KL divergence loss', 'run a validation step that computes slate rank probabilities and optionally evaluates CPE', 'create a Seq2SlateTrainer instance with a Seq2SlateTransformerNet and Seq2SlateParameters for ranking training', 'configure optimizers for the Seq2Slate policy network and optional baseline network', 'compute importance sampling ratios between model propensities and logged propensities with clamping']
```

Usage

```
{'create_seq2slate_trainer': 'create a Seq2SlateTrainer instance with a Seq2SlateTransformerNet and Seq2SlateParameters for ranking training', 'configure_optimizers': 'configure optimizers for the Seq2Slate policy network and optional baseline network', 'compute_impt_smpl': 'compute importance sampling ratios between model propensities and logged propensities with clamping', 'run_training_step': 'run a training step using REINFORCE policy gradient with baseline subtraction and importance sampling', 'run_validation_step': 'run a validation step to evaluate Seq2Slate ranking performance and compute CPE metrics'}
```

