# Agent Python Tools

- repo: facebookresearch/symbolicmathematics
- repo_uri: https://github.com/facebookresearch/symbolicmathematics

## File: facebookresearch_symbolicmathematics/src/envs/char_sp.py

Prompts

```
['generate random function primitive pairs using CharSPEnvironment gen_prim_fwd for symbolic integration training', 'generate function derivative pairs using CharSPEnvironment gen_prim_bwd for symbolic differentiation training', 'generate first order differential equation pairs using CharSPEnvironment gen_ode1 for ODE solving training', 'convert a prefix expression list to infix string using CharSPEnvironment prefix_to_infix method', 'convert a SymPy expression to prefix notation using CharSPEnvironment sympy_to_prefix method', 'simplify a SymPy mathematical expression with a configurable timeout to prevent hanging', 'count atom occurrences in a SymPy expression using recursive or preorder traversal', 'remove root constant terms from a SymPy expression in add, mul, or pow mode', 'extract a non-constant sub-tree from a SymPy equation given a list of variables', 'reduce coefficients in a SymPy expression by replacing subexpressions with coefficient symbols']
```

Usage

```
{'generate_primitive_forward': 'generate random function primitive pairs using CharSPEnvironment gen_prim_fwd for symbolic integration training', 'generate_primitive_backward': 'generate function derivative pairs using CharSPEnvironment gen_prim_bwd for symbolic differentiation training', 'generate_ode_first_order': 'generate first order differential equation pairs using CharSPEnvironment gen_ode1 for ODE solving training', 'convert_prefix_to_infix': 'convert a prefix expression list to infix string using CharSPEnvironment prefix_to_infix method', 'convert_sympy_to_prefix': 'convert a SymPy expression to prefix notation using CharSPEnvironment sympy_to_prefix method'}
```

## File: facebookresearch_symbolicmathematics/src/envs/sympy_utils.py

Prompts

```
['generate random function primitive pairs using CharSPEnvironment gen_prim_fwd for symbolic integration training', 'generate function derivative pairs using CharSPEnvironment gen_prim_bwd for symbolic differentiation training', 'generate first order differential equation pairs using CharSPEnvironment gen_ode1 for ODE solving training', 'convert a prefix expression list to infix string using CharSPEnvironment prefix_to_infix method', 'convert a SymPy expression to prefix notation using CharSPEnvironment sympy_to_prefix method', 'simplify a SymPy mathematical expression with a configurable timeout to prevent hanging', 'count atom occurrences in a SymPy expression using recursive or preorder traversal', 'remove root constant terms from a SymPy expression in add, mul, or pow mode', 'extract a non-constant sub-tree from a SymPy equation given a list of variables', 'reduce coefficients in a SymPy expression by replacing subexpressions with coefficient symbols']
```

Usage

```
{'simplify_symPy_expression': 'simplify a SymPy mathematical expression with a configurable timeout to prevent hanging', 'count_atom_occurrences': 'count atom occurrences in a SymPy expression using recursive or preorder traversal', 'remove_constant_terms': 'remove root constant terms from a SymPy expression in add, mul, or pow mode', 'extract_non_constant_subtree': 'extract a non-constant sub-tree from a SymPy equation given a list of variables', 'reduce_coefficients': 'reduce coefficients in a SymPy expression by replacing subexpressions with coefficient symbols'}
```

