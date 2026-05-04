# Agent Python Tools

- repo: facebookresearch/docagent
- repo_uri: https://github.com/facebookresearch/docagent

## File: facebookresearch_docagent/src/evaluator/helper/context_finder.py

Prompts

```
['find all usages of a function or method across a Python repository using ContextSearcher', 'prepare context code and ground truth for all usages of a function using ContextPreparer', 'parse a Python function or class signature to extract its name and type', 'search for function calls, method calls, and class instantiations in a file using AST parsing', 'cache and retrieve search results for function usages to avoid repeated repository scans']
```

Usage

```
{'find_usages_of_function': 'find all usages of a function or method across a Python repository using ContextSearcher', 'prepare_contexts_for_evaluation': 'prepare context code and ground truth for all usages of a function using ContextPreparer', 'parse_python_signature': 'parse a Python function or class signature to extract its name and type', 'search_usages_with_ast': 'search for function calls, method calls, and class instantiations in a file using AST parsing', 'cache_search_results': 'cache and retrieve search results for function usages to avoid repeated repository scans'}
```

