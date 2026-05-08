# Agent Python Tools

- repo: facebookresearch/collaq
- repo_uri: https://github.com/facebookresearch/collaq

## File: facebookresearch_collaq/third_party/sacred/tests/test_stflow/test_internal.py

Prompts

```
['test the ContextMethodDecorator to ensure it can intercept method calls on a class', 'test the FooClass do_foo method with positional and keyword arguments', 'test the decorate_three_times decorator function that multiplies a method return value by three', 'test the decorate_three_times_with_exception decorator that raises a RuntimeError when called', 'test the ContextMethodDecorator context manager to verify decoration is scoped and removed after exit', 'test the LogFileWriter decorator that captures TensorFlow FileWriter logdirs into the Sacred run info dictionary', 'test the LogFileWriter context manager that scopes TensorFlow logdir capture to a specific code block', 'test the LogFileWriter context manager preserves captured logdirs even when an exception is raised inside', 'test the LogFileWriter decorator applied to a class method to capture TensorFlow logdirs', 'test that tf.summary.FileWriter calls are intercepted and logdirs are stored in the run info dict']
```

Usage

```
{'test_context_method_decorator': 'test the ContextMethodDecorator to ensure it can intercept method calls on a class', 'test_FooClass_do_foo': 'test the FooClass do_foo method with positional and keyword arguments', 'test_decorate_three_times': 'test the decorate_three_times decorator function that multiplies a method return value by three', 'test_decorate_three_times_with_exception': 'test the decorate_three_times_with_exception decorator that raises a RuntimeError when called', 'test_ContextMethodDecorator_context_manager': 'test the ContextMethodDecorator context manager to verify decoration is scoped and removed after exit'}
```

## File: facebookresearch_collaq/third_party/sacred/tests/test_stflow/test_method_interception.py

Prompts

```
['test the ContextMethodDecorator to ensure it can intercept method calls on a class', 'test the FooClass do_foo method with positional and keyword arguments', 'test the decorate_three_times decorator function that multiplies a method return value by three', 'test the decorate_three_times_with_exception decorator that raises a RuntimeError when called', 'test the ContextMethodDecorator context manager to verify decoration is scoped and removed after exit', 'test the LogFileWriter decorator that captures TensorFlow FileWriter logdirs into the Sacred run info dictionary', 'test the LogFileWriter context manager that scopes TensorFlow logdir capture to a specific code block', 'test the LogFileWriter context manager preserves captured logdirs even when an exception is raised inside', 'test the LogFileWriter decorator applied to a class method to capture TensorFlow logdirs', 'test that tf.summary.FileWriter calls are intercepted and logdirs are stored in the run info dict']
```

Usage

```
{'test_log_file_writer_decorator': 'test the LogFileWriter decorator that captures TensorFlow FileWriter logdirs into the Sacred run info dictionary', 'test_log_file_writer_context_manager': 'test the LogFileWriter context manager that scopes TensorFlow logdir capture to a specific code block', 'test_log_file_writer_exception_handling': 'test the LogFileWriter context manager preserves captured logdirs even when an exception is raised inside', 'test_log_file_writer_class_method': 'test the LogFileWriter decorator applied to a class method to capture TensorFlow logdirs', 'test_tensorflow_filewriter_interception': 'test that tf.summary.FileWriter calls are intercepted and logdirs are stored in the run info dict'}
```

