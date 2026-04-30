# Agent Python Tools

- repo: berriai/litellm
- repo_uri: https://github.com/berriai/litellm

## File: berriai_litellm/litellm/proxy/guardrails/guardrail_hooks/litellm_content_filter/content_filter.py

Prompts

```
['create a ContentFilterGuardrail instance with regex patterns and blocked words to detect sensitive content', 'build a category-based keyword filter that loads YAML/JSON category files with severity thresholds and exceptions', 'test regex pattern matching with prebuilt patterns like SSN, credit cards, and custom regex for sensitive data detection', 'run content filtering on streaming LLM responses with buffering to detect patterns split across chunks and apply masking', 'review competitor intent detection that blocks or reframes requests comparing products to configured competitors', 'test the get_compiled_pattern function to return a compiled regex for a sensitive data pattern', 'get all available prebuilt regex pattern names for content filtering', 'get pattern metadata including display names and categories for UI display', 'get available content categories from YAML and JSON files in the categories directory', 'test the PrebuiltPatternName enum with dynamically generated pattern names from patterns.json']
```

Usage

```
{'create_content_filter_guardrail': 'create a ContentFilterGuardrail instance with regex patterns and blocked words to detect sensitive content', 'build_category_keyword_filter': 'build a category-based keyword filter that loads YAML/JSON category files with severity thresholds and exceptions', 'test_pattern_matching': 'test regex pattern matching with prebuilt patterns like SSN, credit cards, and custom regex for sensitive data detection', 'run_streaming_response_filter': 'run content filtering on streaming LLM responses with buffering to detect patterns split across chunks and apply masking', 'review_competitor_intent_check': 'review competitor intent detection that blocks or reframes requests comparing products to configured competitors'}
```

## File: berriai_litellm/litellm/proxy/guardrails/guardrail_hooks/litellm_content_filter/patterns.py

Prompts

```
['create a ContentFilterGuardrail instance with regex patterns and blocked words to detect sensitive content', 'build a category-based keyword filter that loads YAML/JSON category files with severity thresholds and exceptions', 'test regex pattern matching with prebuilt patterns like SSN, credit cards, and custom regex for sensitive data detection', 'run content filtering on streaming LLM responses with buffering to detect patterns split across chunks and apply masking', 'review competitor intent detection that blocks or reframes requests comparing products to configured competitors', 'test the get_compiled_pattern function to return a compiled regex for a sensitive data pattern', 'get all available prebuilt regex pattern names for content filtering', 'get pattern metadata including display names and categories for UI display', 'get available content categories from YAML and JSON files in the categories directory', 'test the PrebuiltPatternName enum with dynamically generated pattern names from patterns.json']
```

Usage

```
{'test_get_compiled_pattern': 'test the get_compiled_pattern function to return a compiled regex for a sensitive data pattern', 'get_get_all_pattern_names': 'get all available prebuilt regex pattern names for content filtering', 'get_get_pattern_metadata': 'get pattern metadata including display names and categories for UI display', 'get_get_available_content_categories': 'get available content categories from YAML and JSON files in the categories directory', 'test_PrebuiltPatternName': 'test the PrebuiltPatternName enum with dynamically generated pattern names from patterns.json'}
```

