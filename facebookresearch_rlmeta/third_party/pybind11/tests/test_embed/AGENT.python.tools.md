# Agent Python Tools

- repo: facebookresearch/rlmeta
- repo_uri: https://github.com/facebookresearch/rlmeta

## File: facebookresearch_rlmeta/third_party/pybind11/tests/test_embed/test_interpreter.py

Prompts

```
['create a DerivedWidget instance by passing a message string to its constructor', 'call the the_answer method on a DerivedWidget instance to get the integer 42', 'call the argv0 method on a DerivedWidget instance to retrieve sys.argv[0]', 'review the DerivedWidget class that extends Widget from widget_module with custom methods', 'test that DerivedWidget properly inherits from Widget and calls super init with a message', 'test the pybind11 trampoline override cache by creating a Python subclass that overrides func to return 42', 'test the pybind11 trampoline override cache by creating a Python subclass that does not override func', 'run func to create a Test subclass of test_override_cache_helper that overrides func returning 42', 'run func2 to create a Test subclass of test_override_cache_helper without overriding any methods', 'review how trampoline_module.test_override_cache_helper is subclassed in Python to test pybind11 trampoline caching behavior']
```

Usage

```
{'create_DerivedWidget_instance': 'create a DerivedWidget instance by passing a message string to its constructor', 'call_the_answer_method': 'call the the_answer method on a DerivedWidget instance to get the integer 42', 'call_argv0_method': 'call the argv0 method on a DerivedWidget instance to retrieve sys.argv[0]', 'review_DerivedWidget_class': 'review the DerivedWidget class that extends Widget from widget_module with custom methods', 'test_DerivedWidget_inheritance': 'test that DerivedWidget properly inherits from Widget and calls super init with a message'}
```

## File: facebookresearch_rlmeta/third_party/pybind11/tests/test_embed/test_trampoline.py

Prompts

```
['create a DerivedWidget instance by passing a message string to its constructor', 'call the the_answer method on a DerivedWidget instance to get the integer 42', 'call the argv0 method on a DerivedWidget instance to retrieve sys.argv[0]', 'review the DerivedWidget class that extends Widget from widget_module with custom methods', 'test that DerivedWidget properly inherits from Widget and calls super init with a message', 'test the pybind11 trampoline override cache by creating a Python subclass that overrides func to return 42', 'test the pybind11 trampoline override cache by creating a Python subclass that does not override func', 'run func to create a Test subclass of test_override_cache_helper that overrides func returning 42', 'run func2 to create a Test subclass of test_override_cache_helper without overriding any methods', 'review how trampoline_module.test_override_cache_helper is subclassed in Python to test pybind11 trampoline caching behavior']
```

Usage

```
{'test_trampoline_override_cache_with_override': 'test the pybind11 trampoline override cache by creating a Python subclass that overrides func to return 42', 'test_trampoline_override_cache_without_override': 'test the pybind11 trampoline override cache by creating a Python subclass that does not override func', 'run_func_trampoline_test': 'run func to create a Test subclass of test_override_cache_helper that overrides func returning 42', 'run_func2_trampoline_test': 'run func2 to create a Test subclass of test_override_cache_helper without overriding any methods', 'review_trampoline_module_usage': 'review how trampoline_module.test_override_cache_helper is subclassed in Python to test pybind11 trampoline caching behavior'}
```

