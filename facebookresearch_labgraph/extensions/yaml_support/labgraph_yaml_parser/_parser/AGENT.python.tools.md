# Agent Python Tools

- repo: facebookresearch/labgraph
- repo_uri: https://github.com/facebookresearch/labgraph

## File: facebookresearch_labgraph/extensions/yaml_support/labgraph_yaml_parser/_parser/base_parser.py

Prompts

```
['review the python BaseParser abstract class and its parse method signature', 'refactor the python BaseParser to add additional abstract methods or type hints', 'summarize the python BaseParser abstract base class and its intended usage pattern', 'parse a Python source string containing LabGraph unit classes and extract their structure into LabGraphUnitsModel objects', 'visit AST ClassDef nodes to detect and extract LabGraph builtin unit subclasses like Node, Group, Graph, Message, Config, and State', 'recursively construct a dot-separated type string from a typed_ast AST node representing a class member or method annotation', 'extract publisher and subscriber decorator arguments from LabGraph unit methods to map data flow inputs and outputs', 'parse the connections method body in LabGraph Group or Graph classes to build a key-value dictionary of unit connections']
```

Usage

```
{'review_BaseParser': 'review the python BaseParser abstract class and its parse method signature', 'refactor_BaseParser': 'refactor the python BaseParser to add additional abstract methods or type hints', 'summarize_BaseParser': 'summarize the python BaseParser abstract base class and its intended usage pattern'}
```

## File: facebookresearch_labgraph/extensions/yaml_support/labgraph_yaml_parser/_parser/lg_units_parser.py

Prompts

```
['review the python BaseParser abstract class and its parse method signature', 'refactor the python BaseParser to add additional abstract methods or type hints', 'summarize the python BaseParser abstract base class and its intended usage pattern', 'parse a Python source string containing LabGraph unit classes and extract their structure into LabGraphUnitsModel objects', 'visit AST ClassDef nodes to detect and extract LabGraph builtin unit subclasses like Node, Group, Graph, Message, Config, and State', 'recursively construct a dot-separated type string from a typed_ast AST node representing a class member or method annotation', 'extract publisher and subscriber decorator arguments from LabGraph unit methods to map data flow inputs and outputs', 'parse the connections method body in LabGraph Group or Graph classes to build a key-value dictionary of unit connections']
```

Usage

```
{'parse_labgraph_units_from_python_code': 'parse a Python source string containing LabGraph unit classes and extract their structure into LabGraphUnitsModel objects', 'visit_classdef_for_labgraph_builtin_units': 'visit AST ClassDef nodes to detect and extract LabGraph builtin unit subclasses like Node, Group, Graph, Message, Config, and State', 'construct_complex_type_from_ast_node': 'recursively construct a dot-separated type string from a typed_ast AST node representing a class member or method annotation', 'extract_publishers_and_subscribers_from_decorators': 'extract publisher and subscriber decorator arguments from LabGraph unit methods to map data flow inputs and outputs', 'parse_connections_method_for_groups_and_graphs': 'parse the connections method body in LabGraph Group or Graph classes to build a key-value dictionary of unit connections'}
```

