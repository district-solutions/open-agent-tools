# Agent Python Tools

- repo: google-deepmind/actionengine
- repo_uri: https://github.com/google-deepmind/actionengine

## File: google-deepmind_actionengine/third_party/pybind11/tests/test_embed/test_interpreter.py

Prompts

```
['create a DerivedWidget instance by extending Widget with a custom message string', 'test the DerivedWidget the_answer method to confirm it returns the integer 42', 'test the DerivedWidget argv0 method to retrieve sys.argv[0] from the current process', 'review the DerivedWidget __init__ method that calls super to initialize the parent Widget class', 'summarize the DerivedWidget class that extends Widget with the_answer and argv0 methods', 'test the trampoline mechanism by creating a Python subclass that overrides a C++ virtual method to return a custom value', 'test the trampoline mechanism by creating a Python subclass that inherits from a C++ class without overriding any methods', 'create a Python subclass of trampoline_module.test_override_cache_helper that overrides func to return 42', 'create a Python subclass of trampoline_module.test_override_cache_helper that does not override any methods', 'review the trampoline_module.test_override_cache_helper class and how Python subclasses interact with its C++ virtual methods']
```

Usage

```
{'create_DerivedWidget': 'create a DerivedWidget instance by extending Widget with a custom message string', 'test_DerivedWidget_the_answer': 'test the DerivedWidget the_answer method to confirm it returns the integer 42', 'test_DerivedWidget_argv0': 'test the DerivedWidget argv0 method to retrieve sys.argv[0] from the current process', 'review_DerivedWidget_init': 'review the DerivedWidget __init__ method that calls super to initialize the parent Widget class', 'summarize_DerivedWidget': 'summarize the DerivedWidget class that extends Widget with the_answer and argv0 methods'}
```

## File: google-deepmind_actionengine/third_party/pybind11/tests/test_embed/test_trampoline.py

Prompts

```
['create a DerivedWidget instance by extending Widget with a custom message string', 'test the DerivedWidget the_answer method to confirm it returns the integer 42', 'test the DerivedWidget argv0 method to retrieve sys.argv[0] from the current process', 'review the DerivedWidget __init__ method that calls super to initialize the parent Widget class', 'summarize the DerivedWidget class that extends Widget with the_answer and argv0 methods', 'test the trampoline mechanism by creating a Python subclass that overrides a C++ virtual method to return a custom value', 'test the trampoline mechanism by creating a Python subclass that inherits from a C++ class without overriding any methods', 'create a Python subclass of trampoline_module.test_override_cache_helper that overrides func to return 42', 'create a Python subclass of trampoline_module.test_override_cache_helper that does not override any methods', 'review the trampoline_module.test_override_cache_helper class and how Python subclasses interact with its C++ virtual methods']
```

Usage

```
{'test_trampoline_override': 'test the trampoline mechanism by creating a Python subclass that overrides a C++ virtual method to return a custom value', 'test_trampoline_no_override': 'test the trampoline mechanism by creating a Python subclass that inherits from a C++ class without overriding any methods', 'create_trampoline_subclass_with_override': 'create a Python subclass of trampoline_module.test_override_cache_helper that overrides func to return 42', 'create_trampoline_subclass_without_override': 'create a Python subclass of trampoline_module.test_override_cache_helper that does not override any methods', 'review_trampoline_cache_helper': 'review the trampoline_module.test_override_cache_helper class and how Python subclasses interact with its C++ virtual methods'}
```

