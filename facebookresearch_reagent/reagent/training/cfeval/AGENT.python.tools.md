# Agent Python Tools

- repo: facebookresearch/reagent
- repo_uri: https://github.com/facebookresearch/reagent

## File: facebookresearch_reagent/reagent/training/cfeval/bandit_reward_network_trainer.py

Prompts

```
['create a BanditRewardNetTrainer instance with a reward network, optimizer, and loss function type', 'run the train_step_gen method to compute loss and log metrics for a training batch', 'run the validation_step method to evaluate predicted rewards and compute loss on a validation batch', 'review the configure_optimizers method that creates optimizer schedulers for the reward network parameters', 'refactor the _get_predicted_reward method to extract predicted rewards for logged actions from the model output', 'train a BayesByBackpropTrainer model using the train_step_gen method with a BanditRewardModelInput batch', 'validate a BayesByBackpropTrainer model using the validation_step method with a BanditRewardModelInput batch', 'review the BayesByBackpropTrainer train_step_gen method that computes ELBO loss via sample_elbo on the reward network', 'review the BayesByBackpropTrainer validation_step method that computes ELBO loss and logs eval_loss to the reporter', 'refactor the BayesByBackpropTrainer to implement sample weight handling instead of raising NotImplementedError']
```

Usage

```
{'create_BanditRewardNetTrainer': 'create a BanditRewardNetTrainer instance with a reward network, optimizer, and loss function type', 'run_train_step_gen': 'run the train_step_gen method to compute loss and log metrics for a training batch', 'run_validation_step': 'run the validation_step method to evaluate predicted rewards and compute loss on a validation batch', 'review_configure_optimizers': 'review the configure_optimizers method that creates optimizer schedulers for the reward network parameters', 'refactor_get_predicted_reward': 'refactor the _get_predicted_reward method to extract predicted rewards for logged actions from the model output'}
```

## File: facebookresearch_reagent/reagent/training/cfeval/bayes_by_backprop_trainer.py

Prompts

```
['create a BanditRewardNetTrainer instance with a reward network, optimizer, and loss function type', 'run the train_step_gen method to compute loss and log metrics for a training batch', 'run the validation_step method to evaluate predicted rewards and compute loss on a validation batch', 'review the configure_optimizers method that creates optimizer schedulers for the reward network parameters', 'refactor the _get_predicted_reward method to extract predicted rewards for logged actions from the model output', 'train a BayesByBackpropTrainer model using the train_step_gen method with a BanditRewardModelInput batch', 'validate a BayesByBackpropTrainer model using the validation_step method with a BanditRewardModelInput batch', 'review the BayesByBackpropTrainer train_step_gen method that computes ELBO loss via sample_elbo on the reward network', 'review the BayesByBackpropTrainer validation_step method that computes ELBO loss and logs eval_loss to the reporter', 'refactor the BayesByBackpropTrainer to implement sample weight handling instead of raising NotImplementedError']
```

Usage

```
{'train_BayesByBackpropTrainer': 'train a BayesByBackpropTrainer model using the train_step_gen method with a BanditRewardModelInput batch', 'validate_BayesByBackpropTrainer': 'validate a BayesByBackpropTrainer model using the validation_step method with a BanditRewardModelInput batch', 'review_BayesByBackpropTrainer_train_step_gen': 'review the BayesByBackpropTrainer train_step_gen method that computes ELBO loss via sample_elbo on the reward network', 'review_BayesByBackpropTrainer_validation_step': 'review the BayesByBackpropTrainer validation_step method that computes ELBO loss and logs eval_loss to the reporter', 'refactor_BayesByBackpropTrainer_weight_handling': 'refactor the BayesByBackpropTrainer to implement sample weight handling instead of raising NotImplementedError'}
```

