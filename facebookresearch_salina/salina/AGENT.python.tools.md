# Agent Python Tools

- repo: facebookresearch/salina
- repo_uri: https://github.com/facebookresearch/salina

## File: facebookresearch_salina/salina/agent.py

Prompts

```
['create a subclass of Agent that overrides forward to read and write workspace variables', 'call an Agent instance with a salina.Workspace to execute its forward logic', 'clone an Agent instance to get a deep copy with zeroed gradients', 'get a variable from the agent workspace by name or by name and time index', 'set a variable in the agent workspace by name or by name and time index', 'create a TFLogger instance to log scalars, images, and videos to TensorBoard and pickle files', 'create a WandbLogger instance to log scalars and hyperparameters to Weights and Biases', 'read a training log directory and return a Logs object with parsed hyperparameters and values', 'convert a Log object to a pandas DataFrame with optional hyperparameters included as columns', 'plot a DataFrame using seaborn with configurable x, y, hue, style, row, and col parameters', 'create a Workspace to store and manage a collection of temporal tensors with batch dimensions', 'sample a subworkspace by selecting random time windows and batch elements using sample_subworkspace', 'select specific batch elements from a Workspace using select_batch with a tensor of indexes']
```

Usage

```
{'create_agent_subclass': 'create a subclass of Agent that overrides forward to read and write workspace variables', 'execute_agent_on_workspace': 'call an Agent instance with a salina.Workspace to execute its forward logic', 'clone_agent': 'clone an Agent instance to get a deep copy with zeroed gradients', 'get_workspace_variable': 'get a variable from the agent workspace by name or by name and time index', 'set_workspace_variable': 'set a variable in the agent workspace by name or by name and time index'}
```

## File: facebookresearch_salina/salina/logger.py

Prompts

```
['create a subclass of Agent that overrides forward to read and write workspace variables', 'call an Agent instance with a salina.Workspace to execute its forward logic', 'clone an Agent instance to get a deep copy with zeroed gradients', 'get a variable from the agent workspace by name or by name and time index', 'set a variable in the agent workspace by name or by name and time index', 'create a TFLogger instance to log scalars, images, and videos to TensorBoard and pickle files', 'create a WandbLogger instance to log scalars and hyperparameters to Weights and Biases', 'read a training log directory and return a Logs object with parsed hyperparameters and values', 'convert a Log object to a pandas DataFrame with optional hyperparameters included as columns', 'plot a DataFrame using seaborn with configurable x, y, hue, style, row, and col parameters', 'create a Workspace to store and manage a collection of temporal tensors with batch dimensions', 'sample a subworkspace by selecting random time windows and batch elements using sample_subworkspace', 'select specific batch elements from a Workspace using select_batch with a tensor of indexes']
```

Usage

```
{'create_tf_logger': 'create a TFLogger instance to log scalars, images, and videos to TensorBoard and pickle files', 'create_wandb_logger': 'create a WandbLogger instance to log scalars and hyperparameters to Weights and Biases', 'read_log_directory': 'read a training log directory and return a Logs object with parsed hyperparameters and values', 'log_to_dataframe': 'convert a Log object to a pandas DataFrame with optional hyperparameters included as columns', 'plot_dataframe': 'plot a DataFrame using seaborn with configurable x, y, hue, style, row, and col parameters'}
```

## File: facebookresearch_salina/salina/workspace.py

Prompts

```
['create a subclass of Agent that overrides forward to read and write workspace variables', 'call an Agent instance with a salina.Workspace to execute its forward logic', 'clone an Agent instance to get a deep copy with zeroed gradients', 'get a variable from the agent workspace by name or by name and time index', 'set a variable in the agent workspace by name or by name and time index', 'create a TFLogger instance to log scalars, images, and videos to TensorBoard and pickle files', 'create a WandbLogger instance to log scalars and hyperparameters to Weights and Biases', 'read a training log directory and return a Logs object with parsed hyperparameters and values', 'convert a Log object to a pandas DataFrame with optional hyperparameters included as columns', 'plot a DataFrame using seaborn with configurable x, y, hue, style, row, and col parameters', 'create a Workspace to store and manage a collection of temporal tensors with batch dimensions', 'sample a subworkspace by selecting random time windows and batch elements using sample_subworkspace', 'select specific batch elements from a Workspace using select_batch with a tensor of indexes']
```

Usage

```
{'create_workspace': 'create a Workspace to store and manage a collection of temporal tensors with batch dimensions', 'set_workspace_variable': 'set a variable in the Workspace at a specific timestep using set or set_full methods', 'get_workspace_variable': 'get the full tensor for a variable from the Workspace using get_full or get at a specific timestep', 'sample_subworkspace': 'sample a subworkspace by selecting random time windows and batch elements using sample_subworkspace', 'select_batch_workspace': 'select specific batch elements from a Workspace using select_batch with a tensor of indexes'}
```

