# Agent Python Tools

- repo: facebookresearch/reagent
- repo_uri: https://github.com/facebookresearch/reagent

## File: facebookresearch_reagent/reagent/mab/mab_algorithm.py

Prompts

```
['create a GreedyAlgo multi-armed bandit that always chooses the best arm played so far', 'create a RandomActionsAlgo multi-armed bandit that samples actions uniformly at random', 'add batch observations with per-arm counts and reward sums to a MABAlgo instance', 'get the chosen arm id from a MABAlgo by calling get_action on the bandit', 'reindex multiple tensors from batch arm order to full arm order filling missing with zeros', 'create a Bernoulli multi-armed bandit simulation with per-arm success probabilities and max steps', 'run a single bandit algorithm evaluation on a MAB instance and return cumulative pseudo regret', 'run multiple bandit algorithm evaluations across N bandit instances and average cumulative pseudo regret', 'compare multiple MAB algorithm classes on the same bandit and return regret trajectories per algorithm', 'review the abstract MAB base class defining act method and n_arms property for bandit simulations', 'create a BernoulliBetaThompson instance for Thompson Sampling with Bernoulli rewards like CTR', 'create a NormalGammaThompson instance for Thompson Sampling with normally distributed continuous rewards', 'get posterior samples from the Beta distribution in BernoulliBetaThompson for arm selection', 'add a single observation with arm id and reward to NormalGammaThompson posterior', 'add batch observations with counts and reward sums to NormalGammaThompson posterior', 'create a UCB1 multi-armed bandit instance with configurable alpha and variance estimation', 'create a MetricUCB multi-armed bandit for Bernoulli reward distributions with precise confidence radius', 'create a UCB-Tuned multi-armed bandit instance with conservative per-arm variance estimation', 'run get_bernoulli_ucb_tuned_scores to compute UCB-Tuned scores from observation and success tensors', 'review the BaseUCB var property that computes empirical per-arm reward variance']
```

Usage

```
{'create_greedy_mab': 'create a GreedyAlgo multi-armed bandit that always chooses the best arm played so far', 'create_random_mab': 'create a RandomActionsAlgo multi-armed bandit that samples actions uniformly at random', 'add_batch_observations': 'add batch observations with per-arm counts and reward sums to a MABAlgo instance', 'get_action_from_mab': 'get the chosen arm id from a MABAlgo by calling get_action on the bandit', 'reindex_tensors_by_arm_ids': 'reindex multiple tensors from batch arm order to full arm order filling missing with zeros'}
```

## File: facebookresearch_reagent/reagent/mab/simulation.py

Prompts

```
['create a GreedyAlgo multi-armed bandit that always chooses the best arm played so far', 'create a RandomActionsAlgo multi-armed bandit that samples actions uniformly at random', 'add batch observations with per-arm counts and reward sums to a MABAlgo instance', 'get the chosen arm id from a MABAlgo by calling get_action on the bandit', 'reindex multiple tensors from batch arm order to full arm order filling missing with zeros', 'create a Bernoulli multi-armed bandit simulation with per-arm success probabilities and max steps', 'run a single bandit algorithm evaluation on a MAB instance and return cumulative pseudo regret', 'run multiple bandit algorithm evaluations across N bandit instances and average cumulative pseudo regret', 'compare multiple MAB algorithm classes on the same bandit and return regret trajectories per algorithm', 'review the abstract MAB base class defining act method and n_arms property for bandit simulations', 'create a BernoulliBetaThompson instance for Thompson Sampling with Bernoulli rewards like CTR', 'create a NormalGammaThompson instance for Thompson Sampling with normally distributed continuous rewards', 'get posterior samples from the Beta distribution in BernoulliBetaThompson for arm selection', 'add a single observation with arm id and reward to NormalGammaThompson posterior', 'add batch observations with counts and reward sums to NormalGammaThompson posterior', 'create a UCB1 multi-armed bandit instance with configurable alpha and variance estimation', 'create a MetricUCB multi-armed bandit for Bernoulli reward distributions with precise confidence radius', 'create a UCB-Tuned multi-armed bandit instance with conservative per-arm variance estimation', 'run get_bernoulli_ucb_tuned_scores to compute UCB-Tuned scores from observation and success tensors', 'review the BaseUCB var property that computes empirical per-arm reward variance']
```

Usage

```
{'create_BernoilliMAB_bandit': 'create a Bernoulli multi-armed bandit simulation with per-arm success probabilities and max steps', 'run_single_evaluation_bandit_algo': 'run a single bandit algorithm evaluation on a MAB instance and return cumulative pseudo regret', 'run_multiple_evaluations_bandit_algo': 'run multiple bandit algorithm evaluations across N bandit instances and average cumulative pseudo regret', 'compare_bandit_algos': 'compare multiple MAB algorithm classes on the same bandit and return regret trajectories per algorithm', 'review_MAB_abstract_class': 'review the abstract MAB base class defining act method and n_arms property for bandit simulations'}
```

## File: facebookresearch_reagent/reagent/mab/thompson_sampling.py

Prompts

```
['create a GreedyAlgo multi-armed bandit that always chooses the best arm played so far', 'create a RandomActionsAlgo multi-armed bandit that samples actions uniformly at random', 'add batch observations with per-arm counts and reward sums to a MABAlgo instance', 'get the chosen arm id from a MABAlgo by calling get_action on the bandit', 'reindex multiple tensors from batch arm order to full arm order filling missing with zeros', 'create a Bernoulli multi-armed bandit simulation with per-arm success probabilities and max steps', 'run a single bandit algorithm evaluation on a MAB instance and return cumulative pseudo regret', 'run multiple bandit algorithm evaluations across N bandit instances and average cumulative pseudo regret', 'compare multiple MAB algorithm classes on the same bandit and return regret trajectories per algorithm', 'review the abstract MAB base class defining act method and n_arms property for bandit simulations', 'create a BernoulliBetaThompson instance for Thompson Sampling with Bernoulli rewards like CTR', 'create a NormalGammaThompson instance for Thompson Sampling with normally distributed continuous rewards', 'get posterior samples from the Beta distribution in BernoulliBetaThompson for arm selection', 'add a single observation with arm id and reward to NormalGammaThompson posterior', 'add batch observations with counts and reward sums to NormalGammaThompson posterior', 'create a UCB1 multi-armed bandit instance with configurable alpha and variance estimation', 'create a MetricUCB multi-armed bandit for Bernoulli reward distributions with precise confidence radius', 'create a UCB-Tuned multi-armed bandit instance with conservative per-arm variance estimation', 'run get_bernoulli_ucb_tuned_scores to compute UCB-Tuned scores from observation and success tensors', 'review the BaseUCB var property that computes empirical per-arm reward variance']
```

Usage

```
{'create_bernoulli_beta_thompson': 'create a BernoulliBetaThompson instance for Thompson Sampling with Bernoulli rewards like CTR', 'create_normal_gamma_thompson': 'create a NormalGammaThompson instance for Thompson Sampling with normally distributed continuous rewards', 'get_posterior_samples_bernoulli': 'get posterior samples from the Beta distribution in BernoulliBetaThompson for arm selection', 'add_single_observation_normal_gamma': 'add a single observation with arm id and reward to NormalGammaThompson posterior', 'add_batch_observations_normal_gamma': 'add batch observations with counts and reward sums to NormalGammaThompson posterior'}
```

## File: facebookresearch_reagent/reagent/mab/ucb.py

Prompts

```
['create a GreedyAlgo multi-armed bandit that always chooses the best arm played so far', 'create a RandomActionsAlgo multi-armed bandit that samples actions uniformly at random', 'add batch observations with per-arm counts and reward sums to a MABAlgo instance', 'get the chosen arm id from a MABAlgo by calling get_action on the bandit', 'reindex multiple tensors from batch arm order to full arm order filling missing with zeros', 'create a Bernoulli multi-armed bandit simulation with per-arm success probabilities and max steps', 'run a single bandit algorithm evaluation on a MAB instance and return cumulative pseudo regret', 'run multiple bandit algorithm evaluations across N bandit instances and average cumulative pseudo regret', 'compare multiple MAB algorithm classes on the same bandit and return regret trajectories per algorithm', 'review the abstract MAB base class defining act method and n_arms property for bandit simulations', 'create a BernoulliBetaThompson instance for Thompson Sampling with Bernoulli rewards like CTR', 'create a NormalGammaThompson instance for Thompson Sampling with normally distributed continuous rewards', 'get posterior samples from the Beta distribution in BernoulliBetaThompson for arm selection', 'add a single observation with arm id and reward to NormalGammaThompson posterior', 'add batch observations with counts and reward sums to NormalGammaThompson posterior', 'create a UCB1 multi-armed bandit instance with configurable alpha and variance estimation', 'create a MetricUCB multi-armed bandit for Bernoulli reward distributions with precise confidence radius', 'create a UCB-Tuned multi-armed bandit instance with conservative per-arm variance estimation', 'run get_bernoulli_ucb_tuned_scores to compute UCB-Tuned scores from observation and success tensors', 'review the BaseUCB var property that computes empirical per-arm reward variance']
```

Usage

```
{'create_ucb1_mab': 'create a UCB1 multi-armed bandit instance with configurable alpha and variance estimation', 'create_metric_ucb_mab': 'create a MetricUCB multi-armed bandit for Bernoulli reward distributions with precise confidence radius', 'create_ucb_tuned_mab': 'create a UCB-Tuned multi-armed bandit instance with conservative per-arm variance estimation', 'run_get_bernoulli_ucb_tuned_scores': 'run get_bernoulli_ucb_tuned_scores to compute UCB-Tuned scores from observation and success tensors', 'review_baseucb_var_property': 'review the BaseUCB var property that computes empirical per-arm reward variance'}
```

