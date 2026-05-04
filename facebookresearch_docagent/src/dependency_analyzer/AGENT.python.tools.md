# Agent Python Tools

- repo: facebookresearch/docagent
- repo_uri: https://github.com/facebookresearch/docagent

## File: facebookresearch_docagent/src/dependency_analyzer/ast_parser.py

Prompts

```
['parse a Python repository to build a dependency graph between functions, classes, and methods', 'collect all import and from-import statements from a Python file using the ImportCollector visitor', 'analyze self.XXX references in class methods to find inter-method dependencies within a class', 'save the parsed dependency graph of code components to a JSON file for later use', 'load a previously saved dependency graph from a JSON file back into CodeComponent objects', "detect cycles in a dependency graph using Tarjan's algorithm to find strongly connected components", 'resolve cycles in a dependency graph by identifying strongly connected components and breaking edges', 'perform a topological sort on a dependency graph returning nodes with dependencies first', 'perform a depth-first traversal of a dependency graph starting from root nodes with no dependencies', 'build a dependency graph from a collection of code components with depends_on attributes']
```

Usage

```
{'parse_repository_dependencies': 'parse a Python repository to build a dependency graph between functions, classes, and methods', 'collect_imports_from_ast': 'collect all import and from-import statements from a Python file using the ImportCollector visitor', 'analyze_method_dependencies': 'analyze self.XXX references in class methods to find inter-method dependencies within a class', 'save_dependency_graph': 'save the parsed dependency graph of code components to a JSON file for later use', 'load_dependency_graph': 'load a previously saved dependency graph from a JSON file back into CodeComponent objects'}
```

## File: facebookresearch_docagent/src/dependency_analyzer/topo_sort.py

Prompts

```
['parse a Python repository to build a dependency graph between functions, classes, and methods', 'collect all import and from-import statements from a Python file using the ImportCollector visitor', 'analyze self.XXX references in class methods to find inter-method dependencies within a class', 'save the parsed dependency graph of code components to a JSON file for later use', 'load a previously saved dependency graph from a JSON file back into CodeComponent objects', "detect cycles in a dependency graph using Tarjan's algorithm to find strongly connected components", 'resolve cycles in a dependency graph by identifying strongly connected components and breaking edges', 'perform a topological sort on a dependency graph returning nodes with dependencies first', 'perform a depth-first traversal of a dependency graph starting from root nodes with no dependencies', 'build a dependency graph from a collection of code components with depends_on attributes']
```

Usage

```
{'detect_cycles_in_dependency_graph': "detect cycles in a dependency graph using Tarjan's algorithm to find strongly connected components", 'resolve_cycles_in_dependency_graph': 'resolve cycles in a dependency graph by identifying strongly connected components and breaking edges', 'topological_sort_dependency_graph': 'perform a topological sort on a dependency graph returning nodes with dependencies first', 'dependency_first_dfs_traversal': 'perform a depth-first traversal of a dependency graph starting from root nodes with no dependencies', 'build_graph_from_components': 'build a dependency graph from a collection of code components with depends_on attributes'}
```

