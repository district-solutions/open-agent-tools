# Agent Python Tools

- repo: facebookresearch/collaq
- repo_uri: https://github.com/facebookresearch/collaq

## File: facebookresearch_collaq/third_party/sacred/sacred/stflow/internal.py

Prompts

```
['create a ContextMethodDecorator instance with a class, method name, and decorator function', 'use ContextMethodDecorator as a context manager to temporarily patch a class method', 'exit the ContextMethodDecorator context to automatically restore the original unpatched method', 'review the ContextMethodDecorator sacred_patched guard that prevents re-patching the same method', 'summarize the decorator function signature requiring instance, original_method, args, and kwargs parameters', 'create a LogFileWriter decorator on a function to intercept TensorFlow FileWriter logdir arguments', 'create a LogFileWriter context manager to capture TensorFlow FileWriter logdir paths in scoped blocks', 'review the LogFileWriter class that intercepts tf.summary.FileWriter init to log directory paths', 'refactor the LogFileWriter init method to customize how logdir arguments are extracted and stored', 'summarize the LogFileWriter class usage as both a decorator and context manager for TensorFlow experiments']
```

Usage

```
{'create_context_method_decorator': 'create a ContextMethodDecorator instance with a class, method name, and decorator function', 'patch_method_with_context': 'use ContextMethodDecorator as a context manager to temporarily patch a class method', 'restore_original_method': 'exit the ContextMethodDecorator context to automatically restore the original unpatched method', 'review_double_patch_protection': 'review the ContextMethodDecorator sacred_patched guard that prevents re-patching the same method', 'summarize_decorator_func_signature': 'summarize the decorator function signature requiring instance, original_method, args, and kwargs parameters'}
```

## File: facebookresearch_collaq/third_party/sacred/sacred/stflow/method_interception.py

Prompts

```
['create a ContextMethodDecorator instance with a class, method name, and decorator function', 'use ContextMethodDecorator as a context manager to temporarily patch a class method', 'exit the ContextMethodDecorator context to automatically restore the original unpatched method', 'review the ContextMethodDecorator sacred_patched guard that prevents re-patching the same method', 'summarize the decorator function signature requiring instance, original_method, args, and kwargs parameters', 'create a LogFileWriter decorator on a function to intercept TensorFlow FileWriter logdir arguments', 'create a LogFileWriter context manager to capture TensorFlow FileWriter logdir paths in scoped blocks', 'review the LogFileWriter class that intercepts tf.summary.FileWriter init to log directory paths', 'refactor the LogFileWriter init method to customize how logdir arguments are extracted and stored', 'summarize the LogFileWriter class usage as both a decorator and context manager for TensorFlow experiments']
```

Usage

```
{'create_logfilewriter_decorator': 'create a LogFileWriter decorator on a function to intercept TensorFlow FileWriter logdir arguments', 'create_logfilewriter_context_manager': 'create a LogFileWriter context manager to capture TensorFlow FileWriter logdir paths in scoped blocks', 'review_logfilewriter_class': 'review the LogFileWriter class that intercepts tf.summary.FileWriter init to log directory paths', 'refactor_logfilewriter_init': 'refactor the LogFileWriter init method to customize how logdir arguments are extracted and stored', 'summarize_logfilewriter_usage': 'summarize the LogFileWriter class usage as both a decorator and context manager for TensorFlow experiments'}
```

