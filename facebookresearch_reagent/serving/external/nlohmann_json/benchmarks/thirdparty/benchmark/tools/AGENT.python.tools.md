# Agent Python Tools

- repo: facebookresearch/reagent
- repo_uri: https://github.com/facebookresearch/reagent

## File: facebookresearch_reagent/serving/external/nlohmann_json/benchmarks/thirdparty/benchmark/tools/compare.py

Prompts

```
['run compare.py benchmarks mode to compare two benchmark JSON output files side by side', 'run compare.py filters mode to compare two filters from the same benchmark file', 'run compare.py benchmarksfiltered mode to compare different filters across two benchmark files', 'review the check_inputs function that validates user inputs and diagnoses abnormalities in benchmark files', 'test the create_parser function that builds the argparse subparsers for all three compare modes', 'check_inputs validates two benchmark inputs and flags for potential issues like file overwrites', 'run_or_load_benchmark executes a benchmark executable or loads a JSON output file', 'generate_difference_report produces a comparison report between two benchmark JSON results', 'classify_input_file determines whether an input is a benchmark executable or JSON file', 'run strip_asm.py to strip an input assembly file and write cleaned output to a file', 'process raw assembly text to strip unwanted directives, comments, and normalize labels', 'transform assembly labels by normalizing them and removing unused label declarations', 'process identifiers in an assembly line to normalize ELF and MachO naming differences', 'find all used local labels referenced by jump instructions in assembly text']
```

Usage

```
{'run_compare_benchmarks': 'run compare.py benchmarks mode to compare two benchmark JSON output files side by side', 'run_compare_filters': 'run compare.py filters mode to compare two filters from the same benchmark file', 'run_compare_benchmarksfiltered': 'run compare.py benchmarksfiltered mode to compare different filters across two benchmark files', 'review_check_inputs': 'review the check_inputs function that validates user inputs and diagnoses abnormalities in benchmark files', 'test_create_parser': 'test the create_parser function that builds the argparse subparsers for all three compare modes'}
```

## File: facebookresearch_reagent/serving/external/nlohmann_json/benchmarks/thirdparty/benchmark/tools/compare_bench.py

Prompts

```
['run compare.py benchmarks mode to compare two benchmark JSON output files side by side', 'run compare.py filters mode to compare two filters from the same benchmark file', 'run compare.py benchmarksfiltered mode to compare different filters across two benchmark files', 'review the check_inputs function that validates user inputs and diagnoses abnormalities in benchmark files', 'test the create_parser function that builds the argparse subparsers for all three compare modes', 'check_inputs validates two benchmark inputs and flags for potential issues like file overwrites', 'run_or_load_benchmark executes a benchmark executable or loads a JSON output file', 'generate_difference_report produces a comparison report between two benchmark JSON results', 'classify_input_file determines whether an input is a benchmark executable or JSON file', 'run strip_asm.py to strip an input assembly file and write cleaned output to a file', 'process raw assembly text to strip unwanted directives, comments, and normalize labels', 'transform assembly labels by normalizing them and removing unused label declarations', 'process identifiers in an assembly line to normalize ELF and MachO naming differences', 'find all used local labels referenced by jump instructions in assembly text']
```

Usage

```
{'run_compare_benchmarks': 'run compare_bench.py with two benchmark executables or JSON files to compare their results', 'check_inputs_validate': 'check_inputs validates two benchmark inputs and flags for potential issues like file overwrites', 'run_or_load_benchmark': 'run_or_load_benchmark executes a benchmark executable or loads a JSON output file', 'generate_difference_report': 'generate_difference_report produces a comparison report between two benchmark JSON results', 'classify_input_file': 'classify_input_file determines whether an input is a benchmark executable or JSON file'}
```

## File: facebookresearch_reagent/serving/external/nlohmann_json/benchmarks/thirdparty/benchmark/tools/strip_asm.py

Prompts

```
['run compare.py benchmarks mode to compare two benchmark JSON output files side by side', 'run compare.py filters mode to compare two filters from the same benchmark file', 'run compare.py benchmarksfiltered mode to compare different filters across two benchmark files', 'review the check_inputs function that validates user inputs and diagnoses abnormalities in benchmark files', 'test the create_parser function that builds the argparse subparsers for all three compare modes', 'check_inputs validates two benchmark inputs and flags for potential issues like file overwrites', 'run_or_load_benchmark executes a benchmark executable or loads a JSON output file', 'generate_difference_report produces a comparison report between two benchmark JSON results', 'classify_input_file determines whether an input is a benchmark executable or JSON file', 'run strip_asm.py to strip an input assembly file and write cleaned output to a file', 'process raw assembly text to strip unwanted directives, comments, and normalize labels', 'transform assembly labels by normalizing them and removing unused label declarations', 'process identifiers in an assembly line to normalize ELF and MachO naming differences', 'find all used local labels referenced by jump instructions in assembly text']
```

Usage

```
{'strip_asm_file': 'run strip_asm.py to strip an input assembly file and write cleaned output to a file', 'process_asm': 'process raw assembly text to strip unwanted directives, comments, and normalize labels', 'transform_labels': 'transform assembly labels by normalizing them and removing unused label declarations', 'process_identifiers': 'process identifiers in an assembly line to normalize ELF and MachO naming differences', 'find_used_labels': 'find all used local labels referenced by jump instructions in assembly text'}
```

