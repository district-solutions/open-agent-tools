# Agent Python Tools

- repo: facebookresearch/meta-agents-research-environments
- repo_uri: https://github.com/facebookresearch/meta-agents-research-environments

## File: facebookresearch_meta-agents-research-environments/gaia2-cli/core/gaia2_core/judge/checkers.py

Prompts

```
['run hard checkers on agent and oracle arguments and return pass or fail with rationale', 'run soft LLM-based checkers on agent and oracle arguments for semantic validation', 'run combined hard and soft comparison on agent and oracle events with rationale', 'build all LLM checker instances for soft checking with configurable majority vote count', 'normalize an argument string by lowercasing removing accents and stripping punctuation for comparison', 'build expanded arg-checker and soft-checker registries for eval or RL mode', 'check if a CheckerType enum value is a hard checker using is_hard method', 'check if a CheckerType enum value is a scripted checker using is_scripted method', 'check if a SoftCheckerType requires a subtask using the need_subtask property', 'expand a registry dictionary with app-level aliases using _expand_app_aliases', 'build a Judge instance with oracle events, graph, tasks, and optional LLM engine for evaluation', 'run judge_turn to validate agent events against oracle events and return a JudgmentResult', 'test the preliminary checks that compare agent and oracle tool call counts for mismatches', 'refactor the oracle placeholder resolution to replace event ID references with matched agent return values', 'review the time checking logic that enforces agent event timing within tolerance windows of oracle expectations']
```

Usage

```
{'hard_compare': 'run hard checkers on agent and oracle arguments and return pass or fail with rationale', 'soft_compare': 'run soft LLM-based checkers on agent and oracle arguments for semantic validation', 'mild_compare': 'run combined hard and soft comparison on agent and oracle events with rationale', 'build_llm_checkers': 'build all LLM checker instances for soft checking with configurable majority vote count', 'normalize_arg': 'normalize an argument string by lowercasing removing accents and stripping punctuation for comparison'}
```

## File: facebookresearch_meta-agents-research-environments/gaia2-cli/core/gaia2_core/judge/config.py

Prompts

```
['run hard checkers on agent and oracle arguments and return pass or fail with rationale', 'run soft LLM-based checkers on agent and oracle arguments for semantic validation', 'run combined hard and soft comparison on agent and oracle events with rationale', 'build all LLM checker instances for soft checking with configurable majority vote count', 'normalize an argument string by lowercasing removing accents and stripping punctuation for comparison', 'build expanded arg-checker and soft-checker registries for eval or RL mode', 'check if a CheckerType enum value is a hard checker using is_hard method', 'check if a CheckerType enum value is a scripted checker using is_scripted method', 'check if a SoftCheckerType requires a subtask using the need_subtask property', 'expand a registry dictionary with app-level aliases using _expand_app_aliases', 'build a Judge instance with oracle events, graph, tasks, and optional LLM engine for evaluation', 'run judge_turn to validate agent events against oracle events and return a JudgmentResult', 'test the preliminary checks that compare agent and oracle tool call counts for mismatches', 'refactor the oracle placeholder resolution to replace event ID references with matched agent return values', 'review the time checking logic that enforces agent event timing within tolerance windows of oracle expectations']
```

Usage

```
{'build_checker_registries': 'build expanded arg-checker and soft-checker registries for eval or RL mode', 'check_checker_type_is_hard': 'check if a CheckerType enum value is a hard checker using is_hard method', 'check_checker_type_is_scripted': 'check if a CheckerType enum value is a scripted checker using is_scripted method', 'check_soft_checker_need_subtask': 'check if a SoftCheckerType requires a subtask using the need_subtask property', 'expand_app_aliases': 'expand a registry dictionary with app-level aliases using _expand_app_aliases'}
```

## File: facebookresearch_meta-agents-research-environments/gaia2-cli/core/gaia2_core/judge/judge.py

Prompts

```
['run hard checkers on agent and oracle arguments and return pass or fail with rationale', 'run soft LLM-based checkers on agent and oracle arguments for semantic validation', 'run combined hard and soft comparison on agent and oracle events with rationale', 'build all LLM checker instances for soft checking with configurable majority vote count', 'normalize an argument string by lowercasing removing accents and stripping punctuation for comparison', 'build expanded arg-checker and soft-checker registries for eval or RL mode', 'check if a CheckerType enum value is a hard checker using is_hard method', 'check if a CheckerType enum value is a scripted checker using is_scripted method', 'check if a SoftCheckerType requires a subtask using the need_subtask property', 'expand a registry dictionary with app-level aliases using _expand_app_aliases', 'build a Judge instance with oracle events, graph, tasks, and optional LLM engine for evaluation', 'run judge_turn to validate agent events against oracle events and return a JudgmentResult', 'test the preliminary checks that compare agent and oracle tool call counts for mismatches', 'refactor the oracle placeholder resolution to replace event ID references with matched agent return values', 'review the time checking logic that enforces agent event timing within tolerance windows of oracle expectations']
```

Usage

```
{'build_judge_instance': 'build a Judge instance with oracle events, graph, tasks, and optional LLM engine for evaluation', 'run_judge_turn': 'run judge_turn to validate agent events against oracle events and return a JudgmentResult', 'test_preliminary_checks': 'test the preliminary checks that compare agent and oracle tool call counts for mismatches', 'refactor_oracle_placeholder_resolution': 'refactor the oracle placeholder resolution to replace event ID references with matched agent return values', 'review_time_checking': 'review the time checking logic that enforces agent event timing within tolerance windows of oracle expectations'}
```

