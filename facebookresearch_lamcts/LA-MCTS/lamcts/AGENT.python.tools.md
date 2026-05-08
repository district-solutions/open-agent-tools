# Agent Python Tools

- repo: facebookresearch/lamcts
- repo_uri: https://github.com/facebookresearch/lamcts

## File: facebookresearch_lamcts/LA-MCTS/lamcts/Classifier.py

Prompts

```
['create a Classifier instance with samples, dimensions, and SVM kernel type for Bayesian optimization', 'train the Gaussian Process Regressor on samples to learn the surrogate model', 'propose new samples using Bayesian optimization with expected improvement acquisition function', 'split samples into good and bad clusters using KMeans and SVM boundary learning', 'compute expected improvement values at candidate points using the fitted GPR model', 'create an MCTS optimizer instance with lower bounds, upper bounds, dimensions, initial samples, and an objective function', 'run the MCTS search loop for a given number of iterations using Bayesian optimization or turbo solver', 'dynamic treeify the MCTS tree by bifurcating leaf nodes with over 20 samples into good and bad children', 'select a leaf node from the MCTS tree using UCT scores for exploration and exploitation balance', 'collect and evaluate a sample point, update the current best value, and append to the samples list', 'create a Node instance with optional parent, dimensions, kernel type, and gamma type for LA-MCTS tree search', "update a Node's bag with samples to retrain its classifier and compute mean value and splittability", "propose new samples using Bayesian optimization from a Node's classifier given bounds and existing samples", "train the Node's classifier on its bag and split data into good and bad kid subsets", 'compute the UCT (Upper Confidence Bound for Trees) score for a Node using exploration-exploitation tradeoff', 'generate n Latin Hypercube samples in d dimensions using the latin_hypercube function', 'map points from the unit hypercube to an arbitrary bounding box using from_unit_cube', 'create a Latin Hypercube sampling design for optimization with n samples and dims dimensions', 'transform unit cube points to custom lower and upper bounds using from_unit_cube', 'sample Latin Hypercube points with random perturbation using the latin_hypercube function']
```

Usage

```
{'create_classifier': 'create a Classifier instance with samples, dimensions, and SVM kernel type for Bayesian optimization', 'train_gpr': 'train the Gaussian Process Regressor on samples to learn the surrogate model', 'propose_samples_bo': 'propose new samples using Bayesian optimization with expected improvement acquisition function', 'split_data': 'split samples into good and bad clusters using KMeans and SVM boundary learning', 'expected_improvement': 'compute expected improvement values at candidate points using the fitted GPR model'}
```

## File: facebookresearch_lamcts/LA-MCTS/lamcts/MCTS.py

Prompts

```
['create a Classifier instance with samples, dimensions, and SVM kernel type for Bayesian optimization', 'train the Gaussian Process Regressor on samples to learn the surrogate model', 'propose new samples using Bayesian optimization with expected improvement acquisition function', 'split samples into good and bad clusters using KMeans and SVM boundary learning', 'compute expected improvement values at candidate points using the fitted GPR model', 'create an MCTS optimizer instance with lower bounds, upper bounds, dimensions, initial samples, and an objective function', 'run the MCTS search loop for a given number of iterations using Bayesian optimization or turbo solver', 'dynamic treeify the MCTS tree by bifurcating leaf nodes with over 20 samples into good and bad children', 'select a leaf node from the MCTS tree using UCT scores for exploration and exploitation balance', 'collect and evaluate a sample point, update the current best value, and append to the samples list', 'create a Node instance with optional parent, dimensions, kernel type, and gamma type for LA-MCTS tree search', "update a Node's bag with samples to retrain its classifier and compute mean value and splittability", "propose new samples using Bayesian optimization from a Node's classifier given bounds and existing samples", "train the Node's classifier on its bag and split data into good and bad kid subsets", 'compute the UCT (Upper Confidence Bound for Trees) score for a Node using exploration-exploitation tradeoff', 'generate n Latin Hypercube samples in d dimensions using the latin_hypercube function', 'map points from the unit hypercube to an arbitrary bounding box using from_unit_cube', 'create a Latin Hypercube sampling design for optimization with n samples and dims dimensions', 'transform unit cube points to custom lower and upper bounds using from_unit_cube', 'sample Latin Hypercube points with random perturbation using the latin_hypercube function']
```

Usage

```
{'create_MCTS_optimizer': 'create an MCTS optimizer instance with lower bounds, upper bounds, dimensions, initial samples, and an objective function', 'run_MCTS_search': 'run the MCTS search loop for a given number of iterations using Bayesian optimization or turbo solver', 'dynamic_treeify_MCTS': 'dynamic treeify the MCTS tree by bifurcating leaf nodes with over 20 samples into good and bad children', 'select_MCTS_leaf': 'select a leaf node from the MCTS tree using UCT scores for exploration and exploitation balance', 'collect_MCTS_samples': 'collect and evaluate a sample point, update the current best value, and append to the samples list'}
```

## File: facebookresearch_lamcts/LA-MCTS/lamcts/Node.py

Prompts

```
['create a Classifier instance with samples, dimensions, and SVM kernel type for Bayesian optimization', 'train the Gaussian Process Regressor on samples to learn the surrogate model', 'propose new samples using Bayesian optimization with expected improvement acquisition function', 'split samples into good and bad clusters using KMeans and SVM boundary learning', 'compute expected improvement values at candidate points using the fitted GPR model', 'create an MCTS optimizer instance with lower bounds, upper bounds, dimensions, initial samples, and an objective function', 'run the MCTS search loop for a given number of iterations using Bayesian optimization or turbo solver', 'dynamic treeify the MCTS tree by bifurcating leaf nodes with over 20 samples into good and bad children', 'select a leaf node from the MCTS tree using UCT scores for exploration and exploitation balance', 'collect and evaluate a sample point, update the current best value, and append to the samples list', 'create a Node instance with optional parent, dimensions, kernel type, and gamma type for LA-MCTS tree search', "update a Node's bag with samples to retrain its classifier and compute mean value and splittability", "propose new samples using Bayesian optimization from a Node's classifier given bounds and existing samples", "train the Node's classifier on its bag and split data into good and bad kid subsets", 'compute the UCT (Upper Confidence Bound for Trees) score for a Node using exploration-exploitation tradeoff', 'generate n Latin Hypercube samples in d dimensions using the latin_hypercube function', 'map points from the unit hypercube to an arbitrary bounding box using from_unit_cube', 'create a Latin Hypercube sampling design for optimization with n samples and dims dimensions', 'transform unit cube points to custom lower and upper bounds using from_unit_cube', 'sample Latin Hypercube points with random perturbation using the latin_hypercube function']
```

Usage

```
{'create_Node': 'create a Node instance with optional parent, dimensions, kernel type, and gamma type for LA-MCTS tree search', 'update_bag_Node': "update a Node's bag with samples to retrain its classifier and compute mean value and splittability", 'propose_samples_bo_Node': "propose new samples using Bayesian optimization from a Node's classifier given bounds and existing samples", 'train_and_split_Node': "train the Node's classifier on its bag and split data into good and bad kid subsets", 'get_uct_Node': 'compute the UCT (Upper Confidence Bound for Trees) score for a Node using exploration-exploitation tradeoff'}
```

## File: facebookresearch_lamcts/LA-MCTS/lamcts/utils.py

Prompts

```
['create a Classifier instance with samples, dimensions, and SVM kernel type for Bayesian optimization', 'train the Gaussian Process Regressor on samples to learn the surrogate model', 'propose new samples using Bayesian optimization with expected improvement acquisition function', 'split samples into good and bad clusters using KMeans and SVM boundary learning', 'compute expected improvement values at candidate points using the fitted GPR model', 'create an MCTS optimizer instance with lower bounds, upper bounds, dimensions, initial samples, and an objective function', 'run the MCTS search loop for a given number of iterations using Bayesian optimization or turbo solver', 'dynamic treeify the MCTS tree by bifurcating leaf nodes with over 20 samples into good and bad children', 'select a leaf node from the MCTS tree using UCT scores for exploration and exploitation balance', 'collect and evaluate a sample point, update the current best value, and append to the samples list', 'create a Node instance with optional parent, dimensions, kernel type, and gamma type for LA-MCTS tree search', "update a Node's bag with samples to retrain its classifier and compute mean value and splittability", "propose new samples using Bayesian optimization from a Node's classifier given bounds and existing samples", "train the Node's classifier on its bag and split data into good and bad kid subsets", 'compute the UCT (Upper Confidence Bound for Trees) score for a Node using exploration-exploitation tradeoff', 'generate n Latin Hypercube samples in d dimensions using the latin_hypercube function', 'map points from the unit hypercube to an arbitrary bounding box using from_unit_cube', 'create a Latin Hypercube sampling design for optimization with n samples and dims dimensions', 'transform unit cube points to custom lower and upper bounds using from_unit_cube', 'sample Latin Hypercube points with random perturbation using the latin_hypercube function']
```

Usage

```
{'generate_latin_hypercube_samples': 'generate n Latin Hypercube samples in d dimensions using the latin_hypercube function', 'map_points_from_unit_cube': 'map points from the unit hypercube to an arbitrary bounding box using from_unit_cube', 'create_lhs_design_for_optimization': 'create a Latin Hypercube sampling design for optimization with n samples and dims dimensions', 'transform_unit_cube_to_bounds': 'transform unit cube points to custom lower and upper bounds using from_unit_cube', 'sample_lhs_with_perturbation': 'sample Latin Hypercube points with random perturbation using the latin_hypercube function'}
```

