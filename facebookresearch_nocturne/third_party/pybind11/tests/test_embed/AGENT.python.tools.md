# Agent Python Tools

- repo: facebookresearch/nocturne
- repo_uri: https://github.com/facebookresearch/nocturne

## File: facebookresearch_nocturne/third_party/pybind11/tests/test_embed/test_interpreter.py

Prompts

```
['create a DerivedWidget instance by passing a message string to the constructor', 'call the_answer on a DerivedWidget instance to return the integer 42', 'call argv0 on a DerivedWidget instance to return sys.argv[0]', 'review the DerivedWidget class that extends Widget and adds the_answer and argv0 methods', 'test that DerivedWidget correctly inherits from Widget and calls super init with a message', 'run func to create a Test subclass that overrides func to return 42', 'run func2 to create a Test subclass that inherits func without overriding it', 'test the pybind11 trampoline override cache by calling func and func2 repeatedly', 'review the test_override_cache_helper C++ class exposed via pybind11 trampoline module', 'summarize how trampoline_module exposes test_override_cache_helper for Python subclassing and override caching']
```

Usage

```
{'create_DerivedWidget': 'create a DerivedWidget instance by passing a message string to the constructor', 'call_the_answer': 'call the_answer on a DerivedWidget instance to return the integer 42', 'call_argv0': 'call argv0 on a DerivedWidget instance to return sys.argv[0]', 'review_DerivedWidget_class': 'review the DerivedWidget class that extends Widget and adds the_answer and argv0 methods', 'test_DerivedWidget_inheritance': 'test that DerivedWidget correctly inherits from Widget and calls super init with a message'}
```

## File: facebookresearch_nocturne/third_party/pybind11/tests/test_embed/test_trampoline.py

Prompts

```
['create a DerivedWidget instance by passing a message string to the constructor', 'call the_answer on a DerivedWidget instance to return the integer 42', 'call argv0 on a DerivedWidget instance to return sys.argv[0]', 'review the DerivedWidget class that extends Widget and adds the_answer and argv0 methods', 'test that DerivedWidget correctly inherits from Widget and calls super init with a message', 'run func to create a Test subclass that overrides func to return 42', 'run func2 to create a Test subclass that inherits func without overriding it', 'test the pybind11 trampoline override cache by calling func and func2 repeatedly', 'review the test_override_cache_helper C++ class exposed via pybind11 trampoline module', 'summarize how trampoline_module exposes test_override_cache_helper for Python subclassing and override caching']
```

Usage

```
{'run_func_trampoline_override': 'run func to create a Test subclass that overrides func to return 42', 'run_func2_trampoline_no_override': 'run func2 to create a Test subclass that inherits func without overriding it', 'test_trampoline_override_cache': 'test the pybind11 trampoline override cache by calling func and func2 repeatedly', 'review_test_override_cache_helper': 'review the test_override_cache_helper C++ class exposed via pybind11 trampoline module', 'summarize_trampoline_module': 'summarize how trampoline_module exposes test_override_cache_helper for Python subclassing and override caching'}
```

