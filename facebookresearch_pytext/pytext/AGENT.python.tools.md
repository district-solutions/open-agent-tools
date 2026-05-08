# Agent Python Tools

- repo: facebookresearch/pytext
- repo_uri: https://github.com/facebookresearch/pytext

## File: facebookresearch_pytext/pytext/builtin_task.py

Prompts

```
['register all built-in PyText task types including classification, regression, and language model tasks', 'dynamically import and register custom task classes from a user-specified directory path', 'review the add_include function that discovers and registers task classes from Python modules in a directory', 'refactor the register_builtin_tasks function to add or remove specific PyText task types from registration', 'summarize the builtin_task module that registers built-in and dynamically loaded PyText task classes', 'train a PyText model from a JSON config file and save the best snapshot', 'test a trained PyText model snapshot against test data with optional TensorBoard metrics', 'generate a default config JSON for a given PyText task with optional component overrides', 'export a PyText model snapshot to Caffe2 or ONNX format for inference', 'extract logits from a trained PyText model snapshot and write them to an output file', 'train a PyText model from a config with optional distributed training and metric channels', 'test a PyText model from a snapshot path against a test dataset and report metrics', 'run batch predictions on a list of examples using a saved PyText model file', 'export a saved PyText model snapshot to Caffe2 format with optional ONNX output']
```

Usage

```
{'register_builtin_tasks': 'register all built-in PyText task types including classification, regression, and language model tasks', 'add_include_dynamic_tasks': 'dynamically import and register custom task classes from a user-specified directory path', 'review_add_include': 'review the add_include function that discovers and registers task classes from Python modules in a directory', 'refactor_register_builtin_tasks': 'refactor the register_builtin_tasks function to add or remove specific PyText task types from registration', 'summarize_builtin_task_module': 'summarize the builtin_task module that registers built-in and dynamically loaded PyText task classes'}
```

## File: facebookresearch_pytext/pytext/main.py

Prompts

```
['register all built-in PyText task types including classification, regression, and language model tasks', 'dynamically import and register custom task classes from a user-specified directory path', 'review the add_include function that discovers and registers task classes from Python modules in a directory', 'refactor the register_builtin_tasks function to add or remove specific PyText task types from registration', 'summarize the builtin_task module that registers built-in and dynamically loaded PyText task classes', 'train a PyText model from a JSON config file and save the best snapshot', 'test a trained PyText model snapshot against test data with optional TensorBoard metrics', 'generate a default config JSON for a given PyText task with optional component overrides', 'export a PyText model snapshot to Caffe2 or ONNX format for inference', 'extract logits from a trained PyText model snapshot and write them to an output file', 'train a PyText model from a config with optional distributed training and metric channels', 'test a PyText model from a snapshot path against a test dataset and report metrics', 'run batch predictions on a list of examples using a saved PyText model file', 'export a saved PyText model snapshot to Caffe2 format with optional ONNX output']
```

Usage

```
{'train_pytext_model': 'train a PyText model from a JSON config file and save the best snapshot', 'test_pytext_model': 'test a trained PyText model snapshot against test data with optional TensorBoard metrics', 'gen_default_config': 'generate a default config JSON for a given PyText task with optional component overrides', 'export_pytext_model': 'export a PyText model snapshot to Caffe2 or ONNX format for inference', 'get_logits': 'extract logits from a trained PyText model snapshot and write them to an output file'}
```

## File: facebookresearch_pytext/pytext/workflow.py

Prompts

```
['register all built-in PyText task types including classification, regression, and language model tasks', 'dynamically import and register custom task classes from a user-specified directory path', 'review the add_include function that discovers and registers task classes from Python modules in a directory', 'refactor the register_builtin_tasks function to add or remove specific PyText task types from registration', 'summarize the builtin_task module that registers built-in and dynamically loaded PyText task classes', 'train a PyText model from a JSON config file and save the best snapshot', 'test a trained PyText model snapshot against test data with optional TensorBoard metrics', 'generate a default config JSON for a given PyText task with optional component overrides', 'export a PyText model snapshot to Caffe2 or ONNX format for inference', 'extract logits from a trained PyText model snapshot and write them to an output file', 'train a PyText model from a config with optional distributed training and metric channels', 'test a PyText model from a snapshot path against a test dataset and report metrics', 'run batch predictions on a list of examples using a saved PyText model file', 'export a saved PyText model snapshot to Caffe2 format with optional ONNX output']
```

Usage

```
{'train_model': 'train a PyText model from a config with optional distributed training and metric channels', 'test_model': 'test a PyText model from a snapshot path against a test dataset and report metrics', 'batch_predict': 'run batch predictions on a list of examples using a saved PyText model file', 'export_saved_model_to_caffe2': 'export a saved PyText model snapshot to Caffe2 format with optional ONNX output', 'get_logits': 'generate model logits from a PyText snapshot and write them to an output file'}
```

