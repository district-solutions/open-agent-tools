# Agent Python Tools

- repo: vllm-project/llm-compressor
- repo_uri: https://github.com/vllm-project/llm-compressor

## File: vllm-project_llm-compressor/src/llmcompressor/pipelines/sequential/ast_utils/auto_wrapper.py

Prompts

```
['auto wrap untraceable code segments in an AST module by inserting wrapper function definitions', 'strip decorators from a forward function that prevent recompilation while preserving can_return_tuple', 'wrap an if statement whose condition cannot be statically evaluated into a torch.fx.wrap function', 'wrap a tuple node containing starred unpacking elements into a traceable wrapper function', 'wrap a function call with starred arguments or ignored function names into a torch.fx.wrap call', 'test the ControlFlowAnalyzer class to check if a code block can be safely wrapped into a function', 'build a check using ControlFlowAnalyzer.is_valid to determine if an AST node contains invalid control flow statements', 'refactor an AST node by using ControlFlowAnalyzer to validate it before extracting into a function', 'review code using ControlFlowAnalyzer to ensure break and continue statements are inside a For or While loop', 'summarize how ControlFlowAnalyzer validates await inside AsyncFunctionDef and yield inside FunctionDef contexts', 'analyze ast code to find unbound, assigned, and conditionally assigned variable names', 'create a NameAnalyzer instance with a set of names to omit from analysis', 'review the NameAnalyzer class that determines unbound and assigned names in Python AST nodes', 'test the visit_If method that splits assigned names across true and false branches', 'summarize how NameAnalyzer tracks unbound, assigned, and conditionally assigned names in Python code']
```

Usage

```
{'auto_wrap_untraceable_ast': 'auto wrap untraceable code segments in an AST module by inserting wrapper function definitions', 'strip_forward_decorators': 'strip decorators from a forward function that prevent recompilation while preserving can_return_tuple', 'wrap_if_with_dynamic_condition': 'wrap an if statement whose condition cannot be statically evaluated into a torch.fx.wrap function', 'wrap_starred_tuple_unpacking': 'wrap a tuple node containing starred unpacking elements into a traceable wrapper function', 'wrap_call_with_variadic_args': 'wrap a function call with starred arguments or ignored function names into a torch.fx.wrap call'}
```

## File: vllm-project_llm-compressor/src/llmcompressor/pipelines/sequential/ast_utils/control_flow_analyzer.py

Prompts

```
['auto wrap untraceable code segments in an AST module by inserting wrapper function definitions', 'strip decorators from a forward function that prevent recompilation while preserving can_return_tuple', 'wrap an if statement whose condition cannot be statically evaluated into a torch.fx.wrap function', 'wrap a tuple node containing starred unpacking elements into a traceable wrapper function', 'wrap a function call with starred arguments or ignored function names into a torch.fx.wrap call', 'test the ControlFlowAnalyzer class to check if a code block can be safely wrapped into a function', 'build a check using ControlFlowAnalyzer.is_valid to determine if an AST node contains invalid control flow statements', 'refactor an AST node by using ControlFlowAnalyzer to validate it before extracting into a function', 'review code using ControlFlowAnalyzer to ensure break and continue statements are inside a For or While loop', 'summarize how ControlFlowAnalyzer validates await inside AsyncFunctionDef and yield inside FunctionDef contexts', 'analyze ast code to find unbound, assigned, and conditionally assigned variable names', 'create a NameAnalyzer instance with a set of names to omit from analysis', 'review the NameAnalyzer class that determines unbound and assigned names in Python AST nodes', 'test the visit_If method that splits assigned names across true and false branches', 'summarize how NameAnalyzer tracks unbound, assigned, and conditionally assigned names in Python code']
```

Usage

```
{'test_control_flow_analyzer': 'test the ControlFlowAnalyzer class to check if a code block can be safely wrapped into a function', 'build_code_wrappability_check': 'build a check using ControlFlowAnalyzer.is_valid to determine if an AST node contains invalid control flow statements', 'refactor_ast_node': 'refactor an AST node by using ControlFlowAnalyzer to validate it before extracting into a function', 'review_break_continue': 'review code using ControlFlowAnalyzer to ensure break and continue statements are inside a For or While loop', 'summarize_await_yield': 'summarize how ControlFlowAnalyzer validates await inside AsyncFunctionDef and yield inside FunctionDef contexts'}
```

## File: vllm-project_llm-compressor/src/llmcompressor/pipelines/sequential/ast_utils/name_analyzer.py

Prompts

```
['auto wrap untraceable code segments in an AST module by inserting wrapper function definitions', 'strip decorators from a forward function that prevent recompilation while preserving can_return_tuple', 'wrap an if statement whose condition cannot be statically evaluated into a torch.fx.wrap function', 'wrap a tuple node containing starred unpacking elements into a traceable wrapper function', 'wrap a function call with starred arguments or ignored function names into a torch.fx.wrap call', 'test the ControlFlowAnalyzer class to check if a code block can be safely wrapped into a function', 'build a check using ControlFlowAnalyzer.is_valid to determine if an AST node contains invalid control flow statements', 'refactor an AST node by using ControlFlowAnalyzer to validate it before extracting into a function', 'review code using ControlFlowAnalyzer to ensure break and continue statements are inside a For or While loop', 'summarize how ControlFlowAnalyzer validates await inside AsyncFunctionDef and yield inside FunctionDef contexts', 'analyze ast code to find unbound, assigned, and conditionally assigned variable names', 'create a NameAnalyzer instance with a set of names to omit from analysis', 'review the NameAnalyzer class that determines unbound and assigned names in Python AST nodes', 'test the visit_If method that splits assigned names across true and false branches', 'summarize how NameAnalyzer tracks unbound, assigned, and conditionally assigned names in Python code']
```

Usage

```
{'analyze_code_unbound_assigned': 'analyze ast code to find unbound, assigned, and conditionally assigned variable names', 'create_name_analyzer': 'create a NameAnalyzer instance with a set of names to omit from analysis', 'review_NameAnalyzer': 'review the NameAnalyzer class that determines unbound and assigned names in Python AST nodes', 'test_visit_If_conditionals': 'test the visit_If method that splits assigned names across true and false branches', 'summarize_NameAnalyzer': 'summarize how NameAnalyzer tracks unbound, assigned, and conditionally assigned names in Python code'}
```

