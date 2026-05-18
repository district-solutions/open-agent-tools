# Agent Python Tools

- repo: facebookresearch/nle
- repo_uri: https://github.com/facebookresearch/nle

## File: facebookresearch_nle/third_party/pybind11/tests/test_embed/test_interpreter.py

Prompts

```
['create a DerivedWidget instance by passing a message string to the constructor', 'call the_answer on a DerivedWidget instance to return the integer 42', 'call argv0 on a DerivedWidget instance to return sys.argv[0]', 'access the the_message read-only property on a DerivedWidget instance to get the stored message string', 'test that DerivedWidget properly inherits from the pybind11 Widget base class and overrides pure virtual methods', 'test the pybind11 trampoline override cache by calling func and func2 in a tight loop', 'run func to create a Python subclass that overrides the C++ virtual func method to return 42', 'run func2 to create a Python subclass without overriding the C++ virtual func method', 'review the test_override_cache_helper C++ class exposed via trampoline_module for Python subclassing', 'summarize the trampoline_module embedded module that exposes test_override_cache_helper with a trampoline class']
```

Usage

```
{'create_DerivedWidget_instance': 'create a DerivedWidget instance by passing a message string to the constructor', 'call_the_answer_method': 'call the_answer on a DerivedWidget instance to return the integer 42', 'call_argv0_method': 'call argv0 on a DerivedWidget instance to return sys.argv[0]', 'access_the_message_property': 'access the the_message read-only property on a DerivedWidget instance to get the stored message string', 'test_DerivedWidget_inheritance': 'test that DerivedWidget properly inherits from the pybind11 Widget base class and overrides pure virtual methods'}
```

## File: facebookresearch_nle/third_party/pybind11/tests/test_embed/test_trampoline.py

Prompts

```
['create a DerivedWidget instance by passing a message string to the constructor', 'call the_answer on a DerivedWidget instance to return the integer 42', 'call argv0 on a DerivedWidget instance to return sys.argv[0]', 'access the the_message read-only property on a DerivedWidget instance to get the stored message string', 'test that DerivedWidget properly inherits from the pybind11 Widget base class and overrides pure virtual methods', 'test the pybind11 trampoline override cache by calling func and func2 in a tight loop', 'run func to create a Python subclass that overrides the C++ virtual func method to return 42', 'run func2 to create a Python subclass without overriding the C++ virtual func method', 'review the test_override_cache_helper C++ class exposed via trampoline_module for Python subclassing', 'summarize the trampoline_module embedded module that exposes test_override_cache_helper with a trampoline class']
```

Usage

```
{'test_trampoline_override_cache': 'test the pybind11 trampoline override cache by calling func and func2 in a tight loop', 'run_func_trampoline_override': 'run func to create a Python subclass that overrides the C++ virtual func method to return 42', 'run_func2_trampoline_no_override': 'run func2 to create a Python subclass without overriding the C++ virtual func method', 'review_test_override_cache_helper': 'review the test_override_cache_helper C++ class exposed via trampoline_module for Python subclassing', 'summarize_trampoline_module': 'summarize the trampoline_module embedded module that exposes test_override_cache_helper with a trampoline class'}
```

