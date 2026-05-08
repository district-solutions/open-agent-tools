# Agent Python Tools

- repo: facebookresearch/ctrlbenchmark
- repo_uri: https://github.com/facebookresearch/ctrlbenchmark

## File: facebookresearch_ctrlbenchmark/ctrl/tasks/task.py

Prompts

```
['create a Task instance with samples, loss function, source concepts, and dimensionality reduction method', 'compute mean and std statistics for training split data in a Task instance', 'get feature data tensor from a specific split of a Task instance', 'get label tensor for a specific property from a split of a Task instance', 'save a Task instance datasets and metadata to a specified directory path', 'create a TaskGenerator with a concept pool, transformation pool, samples per class, split names, strategy, seed, and augmentation settings', 'add a new task to the TaskGenerator task pool using the current strategy and optionally save it to a path', 'load a pre-saved task from disk by task name and load path into the TaskGenerator task pool', 'compute similarity between two tasks across components x for transformations, y for attributes, or z for source concepts', 'generate labeled samples from concepts, attributes, and transformations with optional test time augmentation applied']
```

Usage

```
{'create_Task_instance': 'create a Task instance with samples, loss function, source concepts, and dimensionality reduction method', 'compute_statistics_Task': 'compute mean and std statistics for training split data in a Task instance', 'get_data_Task': 'get feature data tensor from a specific split of a Task instance', 'get_labels_Task': 'get label tensor for a specific property from a split of a Task instance', 'save_Task': 'save a Task instance datasets and metadata to a specified directory path'}
```

## File: facebookresearch_ctrlbenchmark/ctrl/tasks/task_generator.py

Prompts

```
['create a Task instance with samples, loss function, source concepts, and dimensionality reduction method', 'compute mean and std statistics for training split data in a Task instance', 'get feature data tensor from a specific split of a Task instance', 'get label tensor for a specific property from a split of a Task instance', 'save a Task instance datasets and metadata to a specified directory path', 'create a TaskGenerator with a concept pool, transformation pool, samples per class, split names, strategy, seed, and augmentation settings', 'add a new task to the TaskGenerator task pool using the current strategy and optionally save it to a path', 'load a pre-saved task from disk by task name and load path into the TaskGenerator task pool', 'compute similarity between two tasks across components x for transformations, y for attributes, or z for source concepts', 'generate labeled samples from concepts, attributes, and transformations with optional test time augmentation applied']
```

Usage

```
{'create_TaskGenerator': 'create a TaskGenerator with a concept pool, transformation pool, samples per class, split names, strategy, seed, and augmentation settings', 'add_task_TaskGenerator': 'add a new task to the TaskGenerator task pool using the current strategy and optionally save it to a path', 'load_task_TaskGenerator': 'load a pre-saved task from disk by task name and load path into the TaskGenerator task pool', 'get_similarity_TaskGenerator': 'compute similarity between two tasks across components x for transformations, y for attributes, or z for source concepts', 'get_samples_TaskGenerator': 'generate labeled samples from concepts, attributes, and transformations with optional test time augmentation applied'}
```

