# Agent Python Tools

- repo: facebookresearch/mobile-vision
- repo_uri: https://github.com/facebookresearch/mobile-vision

## File: facebookresearch_mobile-vision/mobile_cv/model_zoo/tasks/task_base.py

Prompts

```
['register a new model type name mapped to a function name in the TaskBase registry', 'get the dictionary of registered model type names and their corresponding function names', 'get a PyTorch model by looking up its registered type name or dynamically constructing the getter method', 'wrap a full PyTorch model in a QuantWrapper to make it quantizable for int8 inference', 'implement a concrete TaskBase subclass by providing get_model and get_dataloader abstract methods', 'use task_factory.get to retrieve a task object by its registered builder name', 'register a new task builder function with TASK_FACTORY.register decorator', 'create a general task by calling task_factory.get with builder name and model args', 'lazy register a task builder by passing a module dot name string to TASK_FACTORY.register', 'list all registered task builder names using TASK_FACTORY.get_names method', 'create a TaskGeneral instance with model and dataset arguments for general model zoo tasks', 'run get_model on TaskGeneral to retrieve a model from the model zoo factory', 'run get_dataloader on TaskGeneral to retrieve a dataloader from the dataset factory', 'review the TaskGeneral constructor to understand how model_args and dataset_args are stored', 'summarize the TaskGeneral class and its delegation pattern for model and dataset retrieval']
```

Usage

```
{'register_model_type': 'register a new model type name mapped to a function name in the TaskBase registry', 'get_model_types': 'get the dictionary of registered model type names and their corresponding function names', 'get_model_by_name': 'get a PyTorch model by looking up its registered type name or dynamically constructing the getter method', 'get_quantizable_model': 'wrap a full PyTorch model in a QuantWrapper to make it quantizable for int8 inference', 'implement_task_subclass': 'implement a concrete TaskBase subclass by providing get_model and get_dataloader abstract methods'}
```

## File: facebookresearch_mobile-vision/mobile_cv/model_zoo/tasks/task_factory.py

Prompts

```
['register a new model type name mapped to a function name in the TaskBase registry', 'get the dictionary of registered model type names and their corresponding function names', 'get a PyTorch model by looking up its registered type name or dynamically constructing the getter method', 'wrap a full PyTorch model in a QuantWrapper to make it quantizable for int8 inference', 'implement a concrete TaskBase subclass by providing get_model and get_dataloader abstract methods', 'use task_factory.get to retrieve a task object by its registered builder name', 'register a new task builder function with TASK_FACTORY.register decorator', 'create a general task by calling task_factory.get with builder name and model args', 'lazy register a task builder by passing a module dot name string to TASK_FACTORY.register', 'list all registered task builder names using TASK_FACTORY.get_names method', 'create a TaskGeneral instance with model and dataset arguments for general model zoo tasks', 'run get_model on TaskGeneral to retrieve a model from the model zoo factory', 'run get_dataloader on TaskGeneral to retrieve a dataloader from the dataset factory', 'review the TaskGeneral constructor to understand how model_args and dataset_args are stored', 'summarize the TaskGeneral class and its delegation pattern for model and dataset retrieval']
```

Usage

```
{'get_task_by_builder': 'use task_factory.get to retrieve a task object by its registered builder name', 'register_task_builder': 'register a new task builder function with TASK_FACTORY.register decorator', 'create_general_task': 'create a general task by calling task_factory.get with builder name and model args', 'register_lazy_task': 'lazy register a task builder by passing a module dot name string to TASK_FACTORY.register', 'list_registered_tasks': 'list all registered task builder names using TASK_FACTORY.get_names method'}
```

## File: facebookresearch_mobile-vision/mobile_cv/model_zoo/tasks/task_general.py

Prompts

```
['register a new model type name mapped to a function name in the TaskBase registry', 'get the dictionary of registered model type names and their corresponding function names', 'get a PyTorch model by looking up its registered type name or dynamically constructing the getter method', 'wrap a full PyTorch model in a QuantWrapper to make it quantizable for int8 inference', 'implement a concrete TaskBase subclass by providing get_model and get_dataloader abstract methods', 'use task_factory.get to retrieve a task object by its registered builder name', 'register a new task builder function with TASK_FACTORY.register decorator', 'create a general task by calling task_factory.get with builder name and model args', 'lazy register a task builder by passing a module dot name string to TASK_FACTORY.register', 'list all registered task builder names using TASK_FACTORY.get_names method', 'create a TaskGeneral instance with model and dataset arguments for general model zoo tasks', 'run get_model on TaskGeneral to retrieve a model from the model zoo factory', 'run get_dataloader on TaskGeneral to retrieve a dataloader from the dataset factory', 'review the TaskGeneral constructor to understand how model_args and dataset_args are stored', 'summarize the TaskGeneral class and its delegation pattern for model and dataset retrieval']
```

Usage

```
{'create_TaskGeneral': 'create a TaskGeneral instance with model and dataset arguments for general model zoo tasks', 'run_get_model': 'run get_model on TaskGeneral to retrieve a model from the model zoo factory', 'run_get_dataloader': 'run get_dataloader on TaskGeneral to retrieve a dataloader from the dataset factory', 'review_TaskGeneral_init': 'review the TaskGeneral constructor to understand how model_args and dataset_args are stored', 'summarize_TaskGeneral': 'summarize the TaskGeneral class and its delegation pattern for model and dataset retrieval'}
```

