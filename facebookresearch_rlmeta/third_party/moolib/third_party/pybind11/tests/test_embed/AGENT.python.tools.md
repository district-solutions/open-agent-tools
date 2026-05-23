# Agent Python Tools

- repo: facebookresearch/rlmeta
- repo_uri: https://github.com/facebookresearch/rlmeta

## File: facebookresearch_rlmeta/third_party/moolib/third_party/pybind11/tests/test_embed/test_interpreter.py

Prompts

```
['create a DerivedWidget instance by passing a message string to its constructor', 'call the the_answer method on a DerivedWidget instance to get the integer 42', 'call the argv0 method on a DerivedWidget instance to retrieve sys.argv[0]', 'test that DerivedWidget properly inherits from Widget by calling super().__init__ with a message', 'review the DerivedWidget class and its the_answer and argv0 methods', 'test pybind11 trampoline override caching by subclassing test_override_cache_helper and overriding func to return 42', 'test pybind11 trampoline override caching by subclassing test_override_cache_helper without overriding any methods', 'review the trampoline_module test_override_cache_helper class and how Python subclasses override its virtual methods', 'summarize the func test which creates a Python subclass that overrides func to return 42', 'summarize the func2 test which creates a Python subclass with no method overrides']
```

Usage

```
{'create_DerivedWidget_instance': 'create a DerivedWidget instance by passing a message string to its constructor', 'call_the_answer_method': 'call the the_answer method on a DerivedWidget instance to get the integer 42', 'call_argv0_method': 'call the argv0 method on a DerivedWidget instance to retrieve sys.argv[0]', 'test_DerivedWidget_inheritance': 'test that DerivedWidget properly inherits from Widget by calling super().__init__ with a message', 'review_DerivedWidget_class': 'review the DerivedWidget class and its the_answer and argv0 methods'}
```

## File: facebookresearch_rlmeta/third_party/moolib/third_party/pybind11/tests/test_embed/test_trampoline.py

Prompts

```
['create a DerivedWidget instance by passing a message string to its constructor', 'call the the_answer method on a DerivedWidget instance to get the integer 42', 'call the argv0 method on a DerivedWidget instance to retrieve sys.argv[0]', 'test that DerivedWidget properly inherits from Widget by calling super().__init__ with a message', 'review the DerivedWidget class and its the_answer and argv0 methods', 'test pybind11 trampoline override caching by subclassing test_override_cache_helper and overriding func to return 42', 'test pybind11 trampoline override caching by subclassing test_override_cache_helper without overriding any methods', 'review the trampoline_module test_override_cache_helper class and how Python subclasses override its virtual methods', 'summarize the func test which creates a Python subclass that overrides func to return 42', 'summarize the func2 test which creates a Python subclass with no method overrides']
```

Usage

```
{'test_trampoline_override_with_method': 'test pybind11 trampoline override caching by subclassing test_override_cache_helper and overriding func to return 42', 'test_trampoline_override_without_method': 'test pybind11 trampoline override caching by subclassing test_override_cache_helper without overriding any methods', 'review_test_override_cache_helper_subclass': 'review the trampoline_module test_override_cache_helper class and how Python subclasses override its virtual methods', 'summarize_func_trampoline_test': 'summarize the func test which creates a Python subclass that overrides func to return 42', 'summarize_func2_trampoline_test': 'summarize the func2 test which creates a Python subclass with no method overrides'}
```

