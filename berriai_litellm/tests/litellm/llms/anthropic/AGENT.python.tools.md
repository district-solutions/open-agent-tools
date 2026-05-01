# Agent Python Tools

- repo: berriai/litellm
- repo_uri: https://github.com/berriai/litellm

## File: berriai_litellm/tests/litellm/llms/anthropic/test_anthropic_reasoning_effort.py

Prompts

```
['test _map_reasoning_effort returns None for claude-opus-4-6 when reasoning_effort is None', 'test _map_reasoning_effort returns None for non-Opus models when reasoning_effort is None', 'test _map_reasoning_effort returns adaptive type for claude-opus-4-6 with low or high effort', 'test _map_reasoning_effort returns enabled type with budget_tokens for non-Opus models', "test _map_reasoning_effort returns None when reasoning_effort is the string 'none'", 'test filter_anthropic_output_schema removes minimum and maximum from integer and number schema properties', 'test filter_anthropic_output_schema removes minLength and maxLength from string schema properties', 'test filter_anthropic_output_schema removes minItems and maxItems from array schema properties', 'test filter_anthropic_output_schema recursively removes constraints from nested object and array schemas', 'test filter_anthropic_output_schema recursively removes constraints from anyOf oneOf and allOf schemas']
```

Usage

```
{'test_map_reasoning_effort_opus_4_6': 'test _map_reasoning_effort returns None for claude-opus-4-6 when reasoning_effort is None', 'test_map_reasoning_effort_other_models': 'test _map_reasoning_effort returns None for non-Opus models when reasoning_effort is None', 'test_map_reasoning_effort_adaptive': 'test _map_reasoning_effort returns adaptive type for claude-opus-4-6 with low or high effort', 'test_map_reasoning_effort_enabled_budget': 'test _map_reasoning_effort returns enabled type with budget_tokens for non-Opus models', 'test_map_reasoning_effort_none_string': "test _map_reasoning_effort returns None when reasoning_effort is the string 'none'"}
```

## File: berriai_litellm/tests/litellm/llms/anthropic/test_anthropic_schema_filter.py

Prompts

```
['test _map_reasoning_effort returns None for claude-opus-4-6 when reasoning_effort is None', 'test _map_reasoning_effort returns None for non-Opus models when reasoning_effort is None', 'test _map_reasoning_effort returns adaptive type for claude-opus-4-6 with low or high effort', 'test _map_reasoning_effort returns enabled type with budget_tokens for non-Opus models', "test _map_reasoning_effort returns None when reasoning_effort is the string 'none'", 'test filter_anthropic_output_schema removes minimum and maximum from integer and number schema properties', 'test filter_anthropic_output_schema removes minLength and maxLength from string schema properties', 'test filter_anthropic_output_schema removes minItems and maxItems from array schema properties', 'test filter_anthropic_output_schema recursively removes constraints from nested object and array schemas', 'test filter_anthropic_output_schema recursively removes constraints from anyOf oneOf and allOf schemas']
```

Usage

```
{'test_filter_numeric_constraints': 'test filter_anthropic_output_schema removes minimum and maximum from integer and number schema properties', 'test_filter_string_constraints': 'test filter_anthropic_output_schema removes minLength and maxLength from string schema properties', 'test_filter_array_constraints': 'test filter_anthropic_output_schema removes minItems and maxItems from array schema properties', 'test_filter_nested_schemas': 'test filter_anthropic_output_schema recursively removes constraints from nested object and array schemas', 'test_filter_anyof_oneof_allof': 'test filter_anthropic_output_schema recursively removes constraints from anyOf oneOf and allOf schemas'}
```

