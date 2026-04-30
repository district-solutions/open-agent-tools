# Agent Python Tools

- repo: berriai/litellm
- repo_uri: https://github.com/berriai/litellm

## File: berriai_litellm/litellm/proxy/guardrails/guardrail_hooks/custom_code/custom_code_guardrail.py

Prompts

```
['create a CustomCodeGuardrail instance with user-defined Python code for content moderation', 'test the CustomCodeGuardrail apply_guardrail method with request inputs and input_type', 'update the CustomCodeGuardrail custom_code and recompile without restarting the server', 'review the CustomCodeGuardrailConfigModel configuration class with custom_code field', 'build a custom code guardrail that blocks requests containing sensitive data patterns', 'build a guardrail that blocks requests containing SQL injection patterns using regex_match', 'create an async HTTP request to call an external content moderation API and return the response', 'test that a user-provided JSON object validates against a required schema using json_schema_valid', 'refactor detect_code_languages to return language names sorted by confidence score', 'summarize how extract_urls finds all URLs in text and validates each with is_valid_url', 'build a globals dict for executing restricted guardrail code with curated builtins and RestrictedPython guards', 'compile user-supplied guardrail source with RestrictedPython AST transformer to block dangerous constructs', 'create an AST transformer that extends RestrictingNodeTransformer to allow async def and await while keeping all other restrictions', 'test the build_sandbox_globals function returns a dict with primitives, builtins, and RestrictedPython guard functions', 'review the compile_sandboxed function that raises SyntaxError on restricted constructs like import, exec, or dunder names']
```

Usage

```
{'create_CustomCodeGuardrail': 'create a CustomCodeGuardrail instance with user-defined Python code for content moderation', 'test_CustomCodeGuardrail_apply_guardrail': 'test the CustomCodeGuardrail apply_guardrail method with request inputs and input_type', 'update_CustomCodeGuardrail_custom_code': 'update the CustomCodeGuardrail custom_code and recompile without restarting the server', 'review_CustomCodeGuardrailConfigModel': 'review the CustomCodeGuardrailConfigModel configuration class with custom_code field', 'build_CustomCodeGuardrail_block': 'build a custom code guardrail that blocks requests containing sensitive data patterns'}
```

## File: berriai_litellm/litellm/proxy/guardrails/guardrail_hooks/custom_code/primitives.py

Prompts

```
['create a CustomCodeGuardrail instance with user-defined Python code for content moderation', 'test the CustomCodeGuardrail apply_guardrail method with request inputs and input_type', 'update the CustomCodeGuardrail custom_code and recompile without restarting the server', 'review the CustomCodeGuardrailConfigModel configuration class with custom_code field', 'build a custom code guardrail that blocks requests containing sensitive data patterns', 'build a guardrail that blocks requests containing SQL injection patterns using regex_match', 'create an async HTTP request to call an external content moderation API and return the response', 'test that a user-provided JSON object validates against a required schema using json_schema_valid', 'refactor detect_code_languages to return language names sorted by confidence score', 'summarize how extract_urls finds all URLs in text and validates each with is_valid_url', 'build a globals dict for executing restricted guardrail code with curated builtins and RestrictedPython guards', 'compile user-supplied guardrail source with RestrictedPython AST transformer to block dangerous constructs', 'create an AST transformer that extends RestrictingNodeTransformer to allow async def and await while keeping all other restrictions', 'test the build_sandbox_globals function returns a dict with primitives, builtins, and RestrictedPython guard functions', 'review the compile_sandboxed function that raises SyntaxError on restricted constructs like import, exec, or dunder names']
```

Usage

```
{'build_guardrail_block_injection': 'build a guardrail that blocks requests containing SQL injection patterns using regex_match', 'create_http_request_moderation': 'create an async HTTP request to call an external content moderation API and return the response', 'test_json_schema_validation': 'test that a user-provided JSON object validates against a required schema using json_schema_valid', 'refactor_code_language_detection': 'refactor detect_code_languages to return language names sorted by confidence score', 'summarize_url_extraction': 'summarize how extract_urls finds all URLs in text and validates each with is_valid_url'}
```

## File: berriai_litellm/litellm/proxy/guardrails/guardrail_hooks/custom_code/sandbox.py

Prompts

```
['create a CustomCodeGuardrail instance with user-defined Python code for content moderation', 'test the CustomCodeGuardrail apply_guardrail method with request inputs and input_type', 'update the CustomCodeGuardrail custom_code and recompile without restarting the server', 'review the CustomCodeGuardrailConfigModel configuration class with custom_code field', 'build a custom code guardrail that blocks requests containing sensitive data patterns', 'build a guardrail that blocks requests containing SQL injection patterns using regex_match', 'create an async HTTP request to call an external content moderation API and return the response', 'test that a user-provided JSON object validates against a required schema using json_schema_valid', 'refactor detect_code_languages to return language names sorted by confidence score', 'summarize how extract_urls finds all URLs in text and validates each with is_valid_url', 'build a globals dict for executing restricted guardrail code with curated builtins and RestrictedPython guards', 'compile user-supplied guardrail source with RestrictedPython AST transformer to block dangerous constructs', 'create an AST transformer that extends RestrictingNodeTransformer to allow async def and await while keeping all other restrictions', 'test the build_sandbox_globals function returns a dict with primitives, builtins, and RestrictedPython guard functions', 'review the compile_sandboxed function that raises SyntaxError on restricted constructs like import, exec, or dunder names']
```

Usage

```
{'build_sandbox_globals': 'build a globals dict for executing restricted guardrail code with curated builtins and RestrictedPython guards', 'compile_sandboxed': 'compile user-supplied guardrail source with RestrictedPython AST transformer to block dangerous constructs', 'create_AsyncAwareTransformer': 'create an AST transformer that extends RestrictingNodeTransformer to allow async def and await while keeping all other restrictions', 'test_build_sandbox_globals': 'test the build_sandbox_globals function returns a dict with primitives, builtins, and RestrictedPython guard functions', 'review_compile_sandboxed': 'review the compile_sandboxed function that raises SyntaxError on restricted constructs like import, exec, or dunder names'}
```

