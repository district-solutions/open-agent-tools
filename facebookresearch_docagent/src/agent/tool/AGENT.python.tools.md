# Agent Python Tools

- repo: facebookresearch/docagent
- repo_uri: https://github.com/facebookresearch/docagent

## File: facebookresearch_docagent/src/agent/tool/ast.py

Prompts

```
['build a call graph for a Python repository using CallGraphBuilder to analyze function calls and class relationships', 'get the source code of a child function called by a given component using CallGraphBuilder.get_child_function', 'get the source code of a child method called by a component using CallGraphBuilder.get_child_method with optional prefix', 'get the class signature and init method of a child class used by a component using CallGraphBuilder.get_child_class_init', 'find all parent components that call or use a given function or method using CallGraphBuilder.get_parent', 'get the source code of a class, function, or method by its dot-separated dependency path', 'find all components that call or depend on the focal component using a dependency graph', 'initialize a PerplexityAPI wrapper with an API key or config file path', 'send a single question to the Perplexity API and get a structured response', 'send multiple questions to the Perplexity API and get a list of responses', 'load Perplexity API configuration settings from a YAML config file', 'review the PerplexityResponse dataclass that holds response content and raw API data']
```

Usage

```
{'build_call_graph': 'build a call graph for a Python repository using CallGraphBuilder to analyze function calls and class relationships', 'get_child_function': 'get the source code of a child function called by a given component using CallGraphBuilder.get_child_function', 'get_child_method': 'get the source code of a child method called by a component using CallGraphBuilder.get_child_method with optional prefix', 'get_child_class_init': 'get the class signature and init method of a child class used by a component using CallGraphBuilder.get_child_class_init', 'find_parent_components': 'find all parent components that call or use a given function or method using CallGraphBuilder.get_parent'}
```

## File: facebookresearch_docagent/src/agent/tool/internal_traverse.py

Prompts

```
['build a call graph for a Python repository using CallGraphBuilder to analyze function calls and class relationships', 'get the source code of a child function called by a given component using CallGraphBuilder.get_child_function', 'get the source code of a child method called by a component using CallGraphBuilder.get_child_method with optional prefix', 'get the class signature and init method of a child class used by a component using CallGraphBuilder.get_child_class_init', 'find all parent components that call or use a given function or method using CallGraphBuilder.get_parent', 'get the source code of a class, function, or method by its dot-separated dependency path', 'find all components that call or depend on the focal component using a dependency graph', 'initialize a PerplexityAPI wrapper with an API key or config file path', 'send a single question to the Perplexity API and get a structured response', 'send multiple questions to the Perplexity API and get a list of responses', 'load Perplexity API configuration settings from a YAML config file', 'review the PerplexityResponse dataclass that holds response content and raw API data']
```

Usage

```
{'get_component_by_path': 'get the source code of a class, function, or method by its dot-separated dependency path', 'get_child_class_init': 'get a child class signature and init method used by the current component to save tokens', 'get_child_function': 'find and retrieve the source code of a function called by the focal component', 'get_child_method': 'find and retrieve the source code of a method called by the focal component', 'get_parent_components': 'find all components that call or depend on the focal component using a dependency graph'}
```

## File: facebookresearch_docagent/src/agent/tool/perplexity_api.py

Prompts

```
['build a call graph for a Python repository using CallGraphBuilder to analyze function calls and class relationships', 'get the source code of a child function called by a given component using CallGraphBuilder.get_child_function', 'get the source code of a child method called by a component using CallGraphBuilder.get_child_method with optional prefix', 'get the class signature and init method of a child class used by a component using CallGraphBuilder.get_child_class_init', 'find all parent components that call or use a given function or method using CallGraphBuilder.get_parent', 'get the source code of a class, function, or method by its dot-separated dependency path', 'find all components that call or depend on the focal component using a dependency graph', 'initialize a PerplexityAPI wrapper with an API key or config file path', 'send a single question to the Perplexity API and get a structured response', 'send multiple questions to the Perplexity API and get a list of responses', 'load Perplexity API configuration settings from a YAML config file', 'review the PerplexityResponse dataclass that holds response content and raw API data']
```

Usage

```
{'init_perplexity_api': 'initialize a PerplexityAPI wrapper with an API key or config file path', 'query_perplexity_api': 'send a single question to the Perplexity API and get a structured response', 'batch_query_perplexity_api': 'send multiple questions to the Perplexity API and get a list of responses', 'load_config_perplexity_api': 'load Perplexity API configuration settings from a YAML config file', 'review_perplexity_response': 'review the PerplexityResponse dataclass that holds response content and raw API data'}
```

