# Agent Python Tools

- repo: facebookresearch/cwm
- repo_uri: https://github.com/facebookresearch/cwm

## File: facebookresearch_cwm/cwm/exec/math/compare.py

Prompts

```
['compare two math expressions using regex patterns and exact bracket matching via a forked subprocess', 'compare two math expressions with configurable regex, bracket matching, and boxed answer expectations', 'verify two math expressions are equivalent using the math_verify_runner subprocess', 'create a CompareResult dataclass to hold comparison results with normalized expressions and duration', 'get the directory path containing the compare runner scripts', 'normalize a math answer by evaluating LaTeX and fraction expressions', 'run the compare runner as a subprocess via multiprocessing connections to compare expressions', 'invoke the compare function from CLI with two expression arguments and print results', 'review the compare function that normalizes and compares two math expressions with regex options', 'normalize a LaTeX math answer string by extracting boxed content and applying substitutions and cleanup', 'evaluate a LaTeX math expression like \\frac{5}{11} to a floating point number using sympy parse_latex', 'compare two complex math expressions including matrices and intervals by parsing and comparing parts individually', 'extract the result from a \\boxed{} LaTeX annotation in a math answer string', 'run the math_verify_runner module to compare two mathematical expressions via multiprocessing connections', 'verify if a target SymPy expression matches a gold expression using numeric and symbolic comparison strategies', 'compare two LaTeX math answer strings by extracting and normalizing boxed expressions before verification', 'review the verify function that compares gold and target expressions with configurable float rounding and strict mode', 'convert unicode math symbols in a string to their LaTeX equivalents using unicode_to_latex', 'convert greek letters like alpha beta gamma to LaTeX commands using unicode_to_latex', 'convert unicode arrows like leftarrow rightarrow to LaTeX using unicode_to_latex', 'convert set theory symbols like subset supset in to LaTeX using unicode_to_latex', 'convert integration symbols like int iint iiint to LaTeX using unicode_to_latex']
```

Usage

```
{'compare_math_expressions': 'compare two math expressions using regex patterns and exact bracket matching via a forked subprocess', 'compare_math_expressions_with_options': 'compare two math expressions with configurable regex, bracket matching, and boxed answer expectations', 'verify_math_expressions': 'verify two math expressions are equivalent using the math_verify_runner subprocess', 'get_compare_result_dataclass': 'create a CompareResult dataclass to hold comparison results with normalized expressions and duration', 'get_runners_directory': 'get the directory path containing the compare runner scripts'}
```

## File: facebookresearch_cwm/cwm/exec/math/compare_runner.py

Prompts

```
['compare two math expressions using regex patterns and exact bracket matching via a forked subprocess', 'compare two math expressions with configurable regex, bracket matching, and boxed answer expectations', 'verify two math expressions are equivalent using the math_verify_runner subprocess', 'create a CompareResult dataclass to hold comparison results with normalized expressions and duration', 'get the directory path containing the compare runner scripts', 'normalize a math answer by evaluating LaTeX and fraction expressions', 'run the compare runner as a subprocess via multiprocessing connections to compare expressions', 'invoke the compare function from CLI with two expression arguments and print results', 'review the compare function that normalizes and compares two math expressions with regex options', 'normalize a LaTeX math answer string by extracting boxed content and applying substitutions and cleanup', 'evaluate a LaTeX math expression like \\frac{5}{11} to a floating point number using sympy parse_latex', 'compare two complex math expressions including matrices and intervals by parsing and comparing parts individually', 'extract the result from a \\boxed{} LaTeX annotation in a math answer string', 'run the math_verify_runner module to compare two mathematical expressions via multiprocessing connections', 'verify if a target SymPy expression matches a gold expression using numeric and symbolic comparison strategies', 'compare two LaTeX math answer strings by extracting and normalizing boxed expressions before verification', 'review the verify function that compares gold and target expressions with configurable float rounding and strict mode', 'convert unicode math symbols in a string to their LaTeX equivalents using unicode_to_latex', 'convert greek letters like alpha beta gamma to LaTeX commands using unicode_to_latex', 'convert unicode arrows like leftarrow rightarrow to LaTeX using unicode_to_latex', 'convert set theory symbols like subset supset in to LaTeX using unicode_to_latex', 'convert integration symbols like int iint iiint to LaTeX using unicode_to_latex']
```

Usage

```
{'compare_math_expressions': 'compare two math expressions for equality using normalize and complex comparison logic', 'eval_answer_normalize': 'normalize a math answer by evaluating LaTeX and fraction expressions', 'run_compare_runner_main': 'run the compare runner as a subprocess via multiprocessing connections to compare expressions', 'invoke_main_cli': 'invoke the compare function from CLI with two expression arguments and print results', 'review_compare_function': 'review the compare function that normalizes and compares two math expressions with regex options'}
```

## File: facebookresearch_cwm/cwm/exec/math/math_process.py

Prompts

```
['compare two math expressions using regex patterns and exact bracket matching via a forked subprocess', 'compare two math expressions with configurable regex, bracket matching, and boxed answer expectations', 'verify two math expressions are equivalent using the math_verify_runner subprocess', 'create a CompareResult dataclass to hold comparison results with normalized expressions and duration', 'get the directory path containing the compare runner scripts', 'normalize a math answer by evaluating LaTeX and fraction expressions', 'run the compare runner as a subprocess via multiprocessing connections to compare expressions', 'invoke the compare function from CLI with two expression arguments and print results', 'review the compare function that normalizes and compares two math expressions with regex options', 'normalize a LaTeX math answer string by extracting boxed content and applying substitutions and cleanup', 'evaluate a LaTeX math expression like \\frac{5}{11} to a floating point number using sympy parse_latex', 'compare two complex math expressions including matrices and intervals by parsing and comparing parts individually', 'extract the result from a \\boxed{} LaTeX annotation in a math answer string', 'run the math_verify_runner module to compare two mathematical expressions via multiprocessing connections', 'verify if a target SymPy expression matches a gold expression using numeric and symbolic comparison strategies', 'compare two LaTeX math answer strings by extracting and normalizing boxed expressions before verification', 'review the verify function that compares gold and target expressions with configurable float rounding and strict mode', 'convert unicode math symbols in a string to their LaTeX equivalents using unicode_to_latex', 'convert greek letters like alpha beta gamma to LaTeX commands using unicode_to_latex', 'convert unicode arrows like leftarrow rightarrow to LaTeX using unicode_to_latex', 'convert set theory symbols like subset supset in to LaTeX using unicode_to_latex', 'convert integration symbols like int iint iiint to LaTeX using unicode_to_latex']
```

Usage

```
{'compare_math_expressions': 'compare two math expressions like 5/11 and 0.4545 for similarity using normalize_final_answer and evaluate_variants', 'normalize_final_answer': 'normalize a LaTeX math answer string by extracting boxed content and applying substitutions and cleanup', 'evaluate_latex_expression': 'evaluate a LaTeX math expression like \\frac{5}{11} to a floating point number using sympy parse_latex', 'compare_expressions_complex': 'compare two complex math expressions including matrices and intervals by parsing and comparing parts individually', 'extract_boxed_result': 'extract the result from a \\boxed{} LaTeX annotation in a math answer string'}
```

## File: facebookresearch_cwm/cwm/exec/math/math_verify_runner.py

Prompts

```
['compare two math expressions using regex patterns and exact bracket matching via a forked subprocess', 'compare two math expressions with configurable regex, bracket matching, and boxed answer expectations', 'verify two math expressions are equivalent using the math_verify_runner subprocess', 'create a CompareResult dataclass to hold comparison results with normalized expressions and duration', 'get the directory path containing the compare runner scripts', 'normalize a math answer by evaluating LaTeX and fraction expressions', 'run the compare runner as a subprocess via multiprocessing connections to compare expressions', 'invoke the compare function from CLI with two expression arguments and print results', 'review the compare function that normalizes and compares two math expressions with regex options', 'normalize a LaTeX math answer string by extracting boxed content and applying substitutions and cleanup', 'evaluate a LaTeX math expression like \\frac{5}{11} to a floating point number using sympy parse_latex', 'compare two complex math expressions including matrices and intervals by parsing and comparing parts individually', 'extract the result from a \\boxed{} LaTeX annotation in a math answer string', 'run the math_verify_runner module to compare two mathematical expressions via multiprocessing connections', 'verify if a target SymPy expression matches a gold expression using numeric and symbolic comparison strategies', 'compare two LaTeX math answer strings by extracting and normalizing boxed expressions before verification', 'review the verify function that compares gold and target expressions with configurable float rounding and strict mode', 'convert unicode math symbols in a string to their LaTeX equivalents using unicode_to_latex', 'convert greek letters like alpha beta gamma to LaTeX commands using unicode_to_latex', 'convert unicode arrows like leftarrow rightarrow to LaTeX using unicode_to_latex', 'convert set theory symbols like subset supset in to LaTeX using unicode_to_latex', 'convert integration symbols like int iint iiint to LaTeX using unicode_to_latex']
```

Usage

```
{'run_math_expression_comparison': 'run the math_verify_runner module to compare two mathematical expressions via multiprocessing connections', 'verify_sympy_expressions': 'verify if a target SymPy expression matches a gold expression using numeric and symbolic comparison strategies', 'compare_latex_math_answers': 'compare two LaTeX math answer strings by extracting and normalizing boxed expressions before verification', 'invoke_main_cli': 'invoke the math_verify_runner CLI to compare two math expressions passed as command line arguments', 'review_verify_function': 'review the verify function that compares gold and target expressions with configurable float rounding and strict mode'}
```

## File: facebookresearch_cwm/cwm/exec/math/unicode_to_latex.py

Prompts

```
['compare two math expressions using regex patterns and exact bracket matching via a forked subprocess', 'compare two math expressions with configurable regex, bracket matching, and boxed answer expectations', 'verify two math expressions are equivalent using the math_verify_runner subprocess', 'create a CompareResult dataclass to hold comparison results with normalized expressions and duration', 'get the directory path containing the compare runner scripts', 'normalize a math answer by evaluating LaTeX and fraction expressions', 'run the compare runner as a subprocess via multiprocessing connections to compare expressions', 'invoke the compare function from CLI with two expression arguments and print results', 'review the compare function that normalizes and compares two math expressions with regex options', 'normalize a LaTeX math answer string by extracting boxed content and applying substitutions and cleanup', 'evaluate a LaTeX math expression like \\frac{5}{11} to a floating point number using sympy parse_latex', 'compare two complex math expressions including matrices and intervals by parsing and comparing parts individually', 'extract the result from a \\boxed{} LaTeX annotation in a math answer string', 'run the math_verify_runner module to compare two mathematical expressions via multiprocessing connections', 'verify if a target SymPy expression matches a gold expression using numeric and symbolic comparison strategies', 'compare two LaTeX math answer strings by extracting and normalizing boxed expressions before verification', 'review the verify function that compares gold and target expressions with configurable float rounding and strict mode', 'convert unicode math symbols in a string to their LaTeX equivalents using unicode_to_latex', 'convert greek letters like alpha beta gamma to LaTeX commands using unicode_to_latex', 'convert unicode arrows like leftarrow rightarrow to LaTeX using unicode_to_latex', 'convert set theory symbols like subset supset in to LaTeX using unicode_to_latex', 'convert integration symbols like int iint iiint to LaTeX using unicode_to_latex']
```

Usage

```
{'convert_unicode_math_to_latex': 'convert unicode math symbols in a string to their LaTeX equivalents using unicode_to_latex', 'convert_greek_letters_to_latex': 'convert greek letters like alpha beta gamma to LaTeX commands using unicode_to_latex', 'convert_arrows_to_latex': 'convert unicode arrows like leftarrow rightarrow to LaTeX using unicode_to_latex', 'convert_set_theory_symbols_to_latex': 'convert set theory symbols like subset supset in to LaTeX using unicode_to_latex', 'convert_integration_symbols_to_latex': 'convert integration symbols like int iint iiint to LaTeX using unicode_to_latex'}
```

