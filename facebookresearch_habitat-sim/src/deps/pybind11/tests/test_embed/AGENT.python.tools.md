# Agent Python Tools

- repo: facebookresearch/habitat-sim
- repo_uri: https://github.com/facebookresearch/habitat-sim

## File: facebookresearch_habitat-sim/src/deps/pybind11/tests/test_embed/test_interpreter.py

Prompts

```
['create a DerivedWidget instance by passing a message string to the constructor', 'call the_answer on a DerivedWidget instance to return the integer 42', 'call argv0 on a DerivedWidget instance to return sys.argv[0] as a string', 'review the DerivedWidget class that extends Widget and adds the_answer and argv0 methods', 'test that DerivedWidget properly inherits from Widget and calls super().__init__ with a message', 'test the trampoline override cache by creating a Python subclass that overrides the func method', 'test the trampoline override cache by creating a Python subclass that does not override any methods', 'run func to create a Test instance that overrides func and returns 42', 'run func2 to create a Test instance that inherits without overriding any methods', 'review the trampoline module override caching behavior for Python subclasses of test_override_cache_helper']
```

Usage

```
{'create_DerivedWidget_instance': 'create a DerivedWidget instance by passing a message string to the constructor', 'call_the_answer_method': 'call the_answer on a DerivedWidget instance to return the integer 42', 'call_argv0_method': 'call argv0 on a DerivedWidget instance to return sys.argv[0] as a string', 'review_DerivedWidget_class': 'review the DerivedWidget class that extends Widget and adds the_answer and argv0 methods', 'test_DerivedWidget_inheritance': 'test that DerivedWidget properly inherits from Widget and calls super().__init__ with a message'}
```

## File: facebookresearch_habitat-sim/src/deps/pybind11/tests/test_embed/test_trampoline.py

Prompts

```
['create a DerivedWidget instance by passing a message string to the constructor', 'call the_answer on a DerivedWidget instance to return the integer 42', 'call argv0 on a DerivedWidget instance to return sys.argv[0] as a string', 'review the DerivedWidget class that extends Widget and adds the_answer and argv0 methods', 'test that DerivedWidget properly inherits from Widget and calls super().__init__ with a message', 'test the trampoline override cache by creating a Python subclass that overrides the func method', 'test the trampoline override cache by creating a Python subclass that does not override any methods', 'run func to create a Test instance that overrides func and returns 42', 'run func2 to create a Test instance that inherits without overriding any methods', 'review the trampoline module override caching behavior for Python subclasses of test_override_cache_helper']
```

Usage

```
{'test_override_cache_with_override': 'test the trampoline override cache by creating a Python subclass that overrides the func method', 'test_override_cache_without_override': 'test the trampoline override cache by creating a Python subclass that does not override any methods', 'run_func_trampoline': 'run func to create a Test instance that overrides func and returns 42', 'run_func2_trampoline': 'run func2 to create a Test instance that inherits without overriding any methods', 'review_trampoline_override_caching': 'review the trampoline module override caching behavior for Python subclasses of test_override_cache_helper'}
```

