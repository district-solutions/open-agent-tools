# Agent Python Tools

- repo: sgl-project/sglang
- repo_uri: https://github.com/sgl-project/sglang

## File: sgl-project_sglang/python/sglang/test/longbench_v2/test_longbench_v2_eval.py

Prompts

```
['format a LongBench-v2 question row into the official template with context, choices, and answer prompt', 'extract the answer letter from a model response using regex patterns for official and fallback formats', 'test LongBenchV2Eval class initialization with a JSON data source file and optional category filter', 'run LongBenchV2Eval evaluation with a sampler callable to compute accuracy and difficulty-specific metrics', 'filter LongBenchV2Eval examples by requested domain categories from the data source JSON file', 'test the format_longbench_v2_question function with official and alternative data formats', 'test the extract_longbench_v2_answer function with various response patterns', 'run the LongBenchV2Eval class to evaluate model responses against benchmark questions', 'test LongBenchV2Eval category filtering to select specific data categories', 'run an accuracy benchmark using LongBenchV2Eval with a mock sampler', 'run the complete LongBench-v2 validation suite including format, extraction, and accuracy tests']
```

Usage

```
{'format_longbench_v2_question': 'format a LongBench-v2 question row into the official template with context, choices, and answer prompt', 'extract_longbench_v2_answer': 'extract the answer letter from a model response using regex patterns for official and fallback formats', 'test_LongBenchV2Eval_initialization': 'test LongBenchV2Eval class initialization with a JSON data source file and optional category filter', 'run_LongBenchV2Eval_evaluation': 'run LongBenchV2Eval evaluation with a sampler callable to compute accuracy and difficulty-specific metrics', 'filter_LongBenchV2Eval_categories': 'filter LongBenchV2Eval examples by requested domain categories from the data source JSON file'}
```

## File: sgl-project_sglang/python/sglang/test/longbench_v2/validate_longbench_v2.py

Prompts

```
['format a LongBench-v2 question row into the official template with context, choices, and answer prompt', 'extract the answer letter from a model response using regex patterns for official and fallback formats', 'test LongBenchV2Eval class initialization with a JSON data source file and optional category filter', 'run LongBenchV2Eval evaluation with a sampler callable to compute accuracy and difficulty-specific metrics', 'filter LongBenchV2Eval examples by requested domain categories from the data source JSON file', 'test the format_longbench_v2_question function with official and alternative data formats', 'test the extract_longbench_v2_answer function with various response patterns', 'run the LongBenchV2Eval class to evaluate model responses against benchmark questions', 'test LongBenchV2Eval category filtering to select specific data categories', 'run an accuracy benchmark using LongBenchV2Eval with a mock sampler', 'run the complete LongBench-v2 validation suite including format, extraction, and accuracy tests']
```

Usage

```
{'test_format_compatibility': 'test the format_longbench_v2_question function with official and alternative data formats', 'test_answer_extraction': 'test the extract_longbench_v2_answer function with various response patterns', 'run_evaluation_pipeline': 'run the LongBenchV2Eval class to evaluate model responses against benchmark questions', 'test_category_filtering': 'test LongBenchV2Eval category filtering to select specific data categories', 'run_accuracy_benchmark': 'run an accuracy benchmark using LongBenchV2Eval with a mock sampler'}
```

## File: sgl-project_sglang/python/sglang/test/longbench_v2/validate_longbench_v2_standalone.py

Prompts

```
['format a LongBench-v2 question row into the official template with context, choices, and answer prompt', 'extract the answer letter from a model response using regex patterns for official and fallback formats', 'test LongBenchV2Eval class initialization with a JSON data source file and optional category filter', 'run LongBenchV2Eval evaluation with a sampler callable to compute accuracy and difficulty-specific metrics', 'filter LongBenchV2Eval examples by requested domain categories from the data source JSON file', 'test the format_longbench_v2_question function with official and alternative data formats', 'test the extract_longbench_v2_answer function with various response patterns', 'run the LongBenchV2Eval class to evaluate model responses against benchmark questions', 'test LongBenchV2Eval category filtering to select specific data categories', 'run an accuracy benchmark using LongBenchV2Eval with a mock sampler', 'run the complete LongBench-v2 validation suite including format, extraction, and accuracy tests']
```

Usage

```
{'format_longbench_v2_question': 'format a LongBench-v2 question row into the official template prompt with choices A through D', 'extract_longbench_v2_answer': 'extract the multiple-choice answer letter from a model response string using regex patterns', 'test_format_compatibility': 'test that both official and alternative question formats produce valid formatted prompts', 'test_answer_extraction': 'test answer extraction against multiple response formats including parentheses, asterisks, and freeform text', 'main': 'run the complete LongBench-v2 validation suite including format, extraction, and accuracy tests'}
```

