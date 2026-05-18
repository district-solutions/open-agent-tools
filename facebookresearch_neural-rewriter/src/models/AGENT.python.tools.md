# Agent Python Tools

- repo: facebookresearch/neural-rewriter
- repo_uri: https://github.com/facebookresearch/neural-rewriter

## File: facebookresearch_neural-rewriter/src/models/BaseModel.py

Prompts

```
['create a BaseModel instance with argparse args for batch size, LSTM hidden size, and learning rate', 'initialize all model parameters with uniform random weights between negative and positive param_init values', 'decay the learning rate by multiplying it with lr_decay_rate and update all optimizer param groups', 'clip gradients if enabled then perform an optimizer step to update model parameters', 'review the BaseModel class and its methods for gradient clipping, weight initialization, and learning rate decay', 'build a HalideModel instance with args, term and op vocabularies for expression simplification', 'run the rewrite method to apply candidate rewrite operations on a single tree manager', 'run batch_rewrite to apply rewrite operations across multiple tree managers in parallel', 'review calc_dependency to recursively compute dependency parent relationships and non-terminal indices in a tree', 'run the forward method to encode inputs, iteratively rewrite expressions, and compute policy and value losses', 'build a job scheduling model using jspModel with args for optimizer, input format, and resource size', 'review the jspModel class initialization to understand input encoder selection, policy networks, and optimizer configuration', 'build a vehicle routing problem model with LSTM encoder, MLP policy, and value estimator networks', 'run the rewrite method to sample and apply route improvement operations on a single VRP instance', 'run batch rewrite to apply route improvement operations across multiple VRP instances in parallel', 'run the forward pass to iteratively optimize VRP routes using policy gradient and value estimation', 'review the vrpModel constructor to configure optimizer, embedding size, attention size, and network components']
```

Usage

```
{'init_BaseModel': 'create a BaseModel instance with argparse args for batch size, LSTM hidden size, and learning rate', 'init_weights_BaseModel': 'initialize all model parameters with uniform random weights between negative and positive param_init values', 'lr_decay_BaseModel': 'decay the learning rate by multiplying it with lr_decay_rate and update all optimizer param groups', 'train_BaseModel': 'clip gradients if enabled then perform an optimizer step to update model parameters', 'review_BaseModel': 'review the BaseModel class and its methods for gradient clipping, weight initialization, and learning rate decay'}
```

## File: facebookresearch_neural-rewriter/src/models/HalideModel.py

Prompts

```
['create a BaseModel instance with argparse args for batch size, LSTM hidden size, and learning rate', 'initialize all model parameters with uniform random weights between negative and positive param_init values', 'decay the learning rate by multiplying it with lr_decay_rate and update all optimizer param groups', 'clip gradients if enabled then perform an optimizer step to update model parameters', 'review the BaseModel class and its methods for gradient clipping, weight initialization, and learning rate decay', 'build a HalideModel instance with args, term and op vocabularies for expression simplification', 'run the rewrite method to apply candidate rewrite operations on a single tree manager', 'run batch_rewrite to apply rewrite operations across multiple tree managers in parallel', 'review calc_dependency to recursively compute dependency parent relationships and non-terminal indices in a tree', 'run the forward method to encode inputs, iteratively rewrite expressions, and compute policy and value losses', 'build a job scheduling model using jspModel with args for optimizer, input format, and resource size', 'review the jspModel class initialization to understand input encoder selection, policy networks, and optimizer configuration', 'build a vehicle routing problem model with LSTM encoder, MLP policy, and value estimator networks', 'run the rewrite method to sample and apply route improvement operations on a single VRP instance', 'run batch rewrite to apply route improvement operations across multiple VRP instances in parallel', 'run the forward pass to iteratively optimize VRP routes using policy gradient and value estimation', 'review the vrpModel constructor to configure optimizer, embedding size, attention size, and network components']
```

Usage

```
{'build_HalideModel': 'build a HalideModel instance with args, term and op vocabularies for expression simplification', 'run_rewrite': 'run the rewrite method to apply candidate rewrite operations on a single tree manager', 'run_batch_rewrite': 'run batch_rewrite to apply rewrite operations across multiple tree managers in parallel', 'review_calc_dependency': 'review calc_dependency to recursively compute dependency parent relationships and non-terminal indices in a tree', 'run_forward': 'run the forward method to encode inputs, iteratively rewrite expressions, and compute policy and value losses'}
```

## File: facebookresearch_neural-rewriter/src/models/jspModel.py

Prompts

```
['create a BaseModel instance with argparse args for batch size, LSTM hidden size, and learning rate', 'initialize all model parameters with uniform random weights between negative and positive param_init values', 'decay the learning rate by multiplying it with lr_decay_rate and update all optimizer param groups', 'clip gradients if enabled then perform an optimizer step to update model parameters', 'review the BaseModel class and its methods for gradient clipping, weight initialization, and learning rate decay', 'build a HalideModel instance with args, term and op vocabularies for expression simplification', 'run the rewrite method to apply candidate rewrite operations on a single tree manager', 'run batch_rewrite to apply rewrite operations across multiple tree managers in parallel', 'review calc_dependency to recursively compute dependency parent relationships and non-terminal indices in a tree', 'run the forward method to encode inputs, iteratively rewrite expressions, and compute policy and value losses', 'build a job scheduling model using jspModel with args for optimizer, input format, and resource size', 'review the jspModel class initialization to understand input encoder selection, policy networks, and optimizer configuration', 'build a vehicle routing problem model with LSTM encoder, MLP policy, and value estimator networks', 'run the rewrite method to sample and apply route improvement operations on a single VRP instance', 'run batch rewrite to apply route improvement operations across multiple VRP instances in parallel', 'run the forward pass to iteratively optimize VRP routes using policy gradient and value estimation', 'review the vrpModel constructor to configure optimizer, embedding size, attention size, and network components']
```

Usage

```
{'build_jspModel': 'build a job scheduling model using jspModel with args for optimizer, input format, and resource size', 'run_rewrite': 'run the rewrite method on a dag manager to sample and apply candidate rewrites with reward thresholds', 'run_batch_rewrite': 'run batch_rewrite on multiple dag managers to apply candidate rewrites across a batch of scheduling problems', 'run_forward': 'run forward pass on batch data to compute policy loss, value loss, reward, and completion time metrics', 'review_jspModel_init': 'review the jspModel class initialization to understand input encoder selection, policy networks, and optimizer configuration'}
```

## File: facebookresearch_neural-rewriter/src/models/vrpModel.py

Prompts

```
['create a BaseModel instance with argparse args for batch size, LSTM hidden size, and learning rate', 'initialize all model parameters with uniform random weights between negative and positive param_init values', 'decay the learning rate by multiplying it with lr_decay_rate and update all optimizer param groups', 'clip gradients if enabled then perform an optimizer step to update model parameters', 'review the BaseModel class and its methods for gradient clipping, weight initialization, and learning rate decay', 'build a HalideModel instance with args, term and op vocabularies for expression simplification', 'run the rewrite method to apply candidate rewrite operations on a single tree manager', 'run batch_rewrite to apply rewrite operations across multiple tree managers in parallel', 'review calc_dependency to recursively compute dependency parent relationships and non-terminal indices in a tree', 'run the forward method to encode inputs, iteratively rewrite expressions, and compute policy and value losses', 'build a job scheduling model using jspModel with args for optimizer, input format, and resource size', 'review the jspModel class initialization to understand input encoder selection, policy networks, and optimizer configuration', 'build a vehicle routing problem model with LSTM encoder, MLP policy, and value estimator networks', 'run the rewrite method to sample and apply route improvement operations on a single VRP instance', 'run batch rewrite to apply route improvement operations across multiple VRP instances in parallel', 'run the forward pass to iteratively optimize VRP routes using policy gradient and value estimation', 'review the vrpModel constructor to configure optimizer, embedding size, attention size, and network components']
```

Usage

```
{'build_vrpModel': 'build a vehicle routing problem model with LSTM encoder, MLP policy, and value estimator networks', 'run_vrpModel_rewrite': 'run the rewrite method to sample and apply route improvement operations on a single VRP instance', 'run_vrpModel_batch_rewrite': 'run batch rewrite to apply route improvement operations across multiple VRP instances in parallel', 'run_vrpModel_forward': 'run the forward pass to iteratively optimize VRP routes using policy gradient and value estimation', 'review_vrpModel_init': 'review the vrpModel constructor to configure optimizer, embedding size, attention size, and network components'}
```

