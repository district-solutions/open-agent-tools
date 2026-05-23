# Agent Python Tools

- repo: facebookresearch/reagent
- repo_uri: https://github.com/facebookresearch/reagent

## File: facebookresearch_reagent/reagent/ope/trainers/linear_trainers.py

Prompts

```
['train a Lasso regression model with hyperparameter search over alpha values on training data', 'train a DecisionTreeRegressor with max depth search on validation data for regression tasks', 'train a DecisionTreeClassifier with entropy criterion and depth search for classification tasks', 'train a LogisticRegression model with C hyperparameter search using lbfgs solver', 'train a LinearNet neural network with Adam optimizer and learning rate scheduling', 'train a DPTrainer on an environment and TabularPolicy to converge the optimal policy using dynamic programming', 'train a MonteCarloTrainer on an environment and TabularPolicy with iterations and gamma discount factor', 'create a TabularPolicy with an action space and epsilon greedy exploration rate for state action distributions', 'save a TabularPolicy state space to a pickle file and load it back for persistence', 'evaluate a DPValueFunction on states using iterative value updates until convergence threshold is met']
```

Usage

```
{'train_lasso_model': 'train a Lasso regression model with hyperparameter search over alpha values on training data', 'train_decision_tree_regressor': 'train a DecisionTreeRegressor with max depth search on validation data for regression tasks', 'train_decision_tree_classifier': 'train a DecisionTreeClassifier with entropy criterion and depth search for classification tasks', 'train_logistic_regression': 'train a LogisticRegression model with C hyperparameter search using lbfgs solver', 'train_neural_network': 'train a LinearNet neural network with Adam optimizer and learning rate scheduling'}
```

## File: facebookresearch_reagent/reagent/ope/trainers/rl_tabular_trainers.py

Prompts

```
['train a Lasso regression model with hyperparameter search over alpha values on training data', 'train a DecisionTreeRegressor with max depth search on validation data for regression tasks', 'train a DecisionTreeClassifier with entropy criterion and depth search for classification tasks', 'train a LogisticRegression model with C hyperparameter search using lbfgs solver', 'train a LinearNet neural network with Adam optimizer and learning rate scheduling', 'train a DPTrainer on an environment and TabularPolicy to converge the optimal policy using dynamic programming', 'train a MonteCarloTrainer on an environment and TabularPolicy with iterations and gamma discount factor', 'create a TabularPolicy with an action space and epsilon greedy exploration rate for state action distributions', 'save a TabularPolicy state space to a pickle file and load it back for persistence', 'evaluate a DPValueFunction on states using iterative value updates until convergence threshold is met']
```

Usage

```
{'train_DPTrainer': 'train a DPTrainer on an environment and TabularPolicy to converge the optimal policy using dynamic programming', 'train_MonteCarloTrainer': 'train a MonteCarloTrainer on an environment and TabularPolicy with iterations and gamma discount factor', 'create_TabularPolicy': 'create a TabularPolicy with an action space and epsilon greedy exploration rate for state action distributions', 'save_load_TabularPolicy': 'save a TabularPolicy state space to a pickle file and load it back for persistence', 'evaluate_DPValueFunction': 'evaluate a DPValueFunction on states using iterative value updates until convergence threshold is met'}
```

