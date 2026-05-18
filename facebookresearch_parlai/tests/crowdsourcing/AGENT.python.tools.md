# Agent Python Tools

- repo: facebookresearch/parlai
- repo_uri: https://github.com/facebookresearch/parlai

## File: facebookresearch_parlai/tests/crowdsourcing/test_acceptability.py

Prompts

```
['test the AcceptabilityChecker class by running sample inputs through check_messages to detect conversation violations', 'run check_messages on a list of conversation messages to detect violations like under_min_length or exact_match', 'review the ALL_VIOLATION_TYPES attribute of AcceptabilityChecker to see all supported violation categories', 'test that worker 0 messages starting with a greeting trigger the starts_with_greeting violation', 'test that messages with excessive all-caps text trigger the too_much_all_caps violation', 'test the MockResultsCompiler to compile all task data results into a dictionary', 'test the MockResultsCompilerWithFilter to compile results excluding rejected workers by worker id', 'create a MockResultsCompiler subclass of AbstractResultsCompiler that compiles task data keyed by unit id', 'create a MockResultsCompilerWithFilter that overrides is_unit_acceptable to filter out specific worker ids', 'run the TestResultsCompiler unittest suite to verify results compilation and worker filtering logic']
```

Usage

```
{'test_acceptability_checker': 'test the AcceptabilityChecker class by running sample inputs through check_messages to detect conversation violations', 'run_check_messages': 'run check_messages on a list of conversation messages to detect violations like under_min_length or exact_match', 'review_violation_types': 'review the ALL_VIOLATION_TYPES attribute of AcceptabilityChecker to see all supported violation categories', 'test_worker_0_greeting': 'test that worker 0 messages starting with a greeting trigger the starts_with_greeting violation', 'test_caps_violation': 'test that messages with excessive all-caps text trigger the too_much_all_caps violation'}
```

## File: facebookresearch_parlai/tests/crowdsourcing/test_analysis.py

Prompts

```
['test the AcceptabilityChecker class by running sample inputs through check_messages to detect conversation violations', 'run check_messages on a list of conversation messages to detect violations like under_min_length or exact_match', 'review the ALL_VIOLATION_TYPES attribute of AcceptabilityChecker to see all supported violation categories', 'test that worker 0 messages starting with a greeting trigger the starts_with_greeting violation', 'test that messages with excessive all-caps text trigger the too_much_all_caps violation', 'test the MockResultsCompiler to compile all task data results into a dictionary', 'test the MockResultsCompilerWithFilter to compile results excluding rejected workers by worker id', 'create a MockResultsCompiler subclass of AbstractResultsCompiler that compiles task data keyed by unit id', 'create a MockResultsCompilerWithFilter that overrides is_unit_acceptable to filter out specific worker ids', 'run the TestResultsCompiler unittest suite to verify results compilation and worker filtering logic']
```

Usage

```
{'test_compile_all_results': 'test the MockResultsCompiler to compile all task data results into a dictionary', 'test_compile_results_with_filter': 'test the MockResultsCompilerWithFilter to compile results excluding rejected workers by worker id', 'create_mock_results_compiler': 'create a MockResultsCompiler subclass of AbstractResultsCompiler that compiles task data keyed by unit id', 'create_mock_results_compiler_with_filter': 'create a MockResultsCompilerWithFilter that overrides is_unit_acceptable to filter out specific worker ids', 'run_test_results_compiler': 'run the TestResultsCompiler unittest suite to verify results compilation and worker filtering logic'}
```

