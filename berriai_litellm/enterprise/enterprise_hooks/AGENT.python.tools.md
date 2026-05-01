# Agent Python Tools

- repo: berriai/litellm
- repo_uri: https://github.com/berriai/litellm

## File: berriai_litellm/enterprise/enterprise_hooks/aporia_ai.py

Prompts

```
['initialize an AporiaGuardrail instance with an API key and base URL for LLM guardrail validation', 'transform a list of message dicts to map unsupported roles to the default other role', 'prepare a request dict with messages and optional response string for Aporia AI validation', 'send an async POST request to the Aporia AI validate endpoint to check messages or responses', 'run the async post call success hook to validate LLM responses against Aporia AI guardrail policies', 'create a CustomLogger subclass that rejects calls containing banned keywords from a list or file', 'test a string against the banned keywords list and raise HTTPException on match', 'review the pre-call hook that checks completion messages for banned keywords before the LLM call', 'review the post-call hook that checks LLM response content for banned keywords', 'review the streaming hook that checks each streamed response chunk for banned keywords', 'build a LiteLLM enterprise hook that blocks users from making LLM API calls using a configurable list', 'create a blocked user list by loading user IDs from a newline-separated file path', 'test the async pre-call hook that rejects requests from blocked users via static list, cache, or database', 'review the _ENTERPRISE_BlockedUserList class that extends CustomLogger to enforce user blocking in LiteLLM proxy', 'refactor the print_verbose method to log at configurable INFO or DEBUG levels with optional verbose output', 'initialize the GoogleTextModeration class with configurable confidence thresholds for 16 safety categories', 'call the async moderation hook to check messages against Google Cloud text moderation API', 'set per-category confidence thresholds like toxic or profanity via litellm module attributes', 'review the 16 confidence categories including toxic, insult, profanity, and firearms_and_weapons', 'test the print_verbose method for debug logging with litellm verbose mode']
```

Usage

```
{'init_aporia_guardrail': 'initialize an AporiaGuardrail instance with an API key and base URL for LLM guardrail validation', 'transform_messages': 'transform a list of message dicts to map unsupported roles to the default other role', 'prepare_aporia_request': 'prepare a request dict with messages and optional response string for Aporia AI validation', 'make_aporia_api_request': 'send an async POST request to the Aporia AI validate endpoint to check messages or responses', 'run_post_call_hook': 'run the async post call success hook to validate LLM responses against Aporia AI guardrail policies'}
```

## File: berriai_litellm/enterprise/enterprise_hooks/banned_keywords.py

Prompts

```
['initialize an AporiaGuardrail instance with an API key and base URL for LLM guardrail validation', 'transform a list of message dicts to map unsupported roles to the default other role', 'prepare a request dict with messages and optional response string for Aporia AI validation', 'send an async POST request to the Aporia AI validate endpoint to check messages or responses', 'run the async post call success hook to validate LLM responses against Aporia AI guardrail policies', 'create a CustomLogger subclass that rejects calls containing banned keywords from a list or file', 'test a string against the banned keywords list and raise HTTPException on match', 'review the pre-call hook that checks completion messages for banned keywords before the LLM call', 'review the post-call hook that checks LLM response content for banned keywords', 'review the streaming hook that checks each streamed response chunk for banned keywords', 'build a LiteLLM enterprise hook that blocks users from making LLM API calls using a configurable list', 'create a blocked user list by loading user IDs from a newline-separated file path', 'test the async pre-call hook that rejects requests from blocked users via static list, cache, or database', 'review the _ENTERPRISE_BlockedUserList class that extends CustomLogger to enforce user blocking in LiteLLM proxy', 'refactor the print_verbose method to log at configurable INFO or DEBUG levels with optional verbose output', 'initialize the GoogleTextModeration class with configurable confidence thresholds for 16 safety categories', 'call the async moderation hook to check messages against Google Cloud text moderation API', 'set per-category confidence thresholds like toxic or profanity via litellm module attributes', 'review the 16 confidence categories including toxic, insult, profanity, and firearms_and_weapons', 'test the print_verbose method for debug logging with litellm verbose mode']
```

Usage

```
{'create_banned_keywords_class': 'create a CustomLogger subclass that rejects calls containing banned keywords from a list or file', 'test_violation_method': 'test a string against the banned keywords list and raise HTTPException on match', 'review_async_pre_call_hook': 'review the pre-call hook that checks completion messages for banned keywords before the LLM call', 'review_async_post_call_success_hook': 'review the post-call hook that checks LLM response content for banned keywords', 'review_async_post_call_streaming_hook': 'review the streaming hook that checks each streamed response chunk for banned keywords'}
```

## File: berriai_litellm/enterprise/enterprise_hooks/blocked_user_list.py

Prompts

```
['initialize an AporiaGuardrail instance with an API key and base URL for LLM guardrail validation', 'transform a list of message dicts to map unsupported roles to the default other role', 'prepare a request dict with messages and optional response string for Aporia AI validation', 'send an async POST request to the Aporia AI validate endpoint to check messages or responses', 'run the async post call success hook to validate LLM responses against Aporia AI guardrail policies', 'create a CustomLogger subclass that rejects calls containing banned keywords from a list or file', 'test a string against the banned keywords list and raise HTTPException on match', 'review the pre-call hook that checks completion messages for banned keywords before the LLM call', 'review the post-call hook that checks LLM response content for banned keywords', 'review the streaming hook that checks each streamed response chunk for banned keywords', 'build a LiteLLM enterprise hook that blocks users from making LLM API calls using a configurable list', 'create a blocked user list by loading user IDs from a newline-separated file path', 'test the async pre-call hook that rejects requests from blocked users via static list, cache, or database', 'review the _ENTERPRISE_BlockedUserList class that extends CustomLogger to enforce user blocking in LiteLLM proxy', 'refactor the print_verbose method to log at configurable INFO or DEBUG levels with optional verbose output', 'initialize the GoogleTextModeration class with configurable confidence thresholds for 16 safety categories', 'call the async moderation hook to check messages against Google Cloud text moderation API', 'set per-category confidence thresholds like toxic or profanity via litellm module attributes', 'review the 16 confidence categories including toxic, insult, profanity, and firearms_and_weapons', 'test the print_verbose method for debug logging with litellm verbose mode']
```

Usage

```
{'build_blocked_user_list_hook': 'build a LiteLLM enterprise hook that blocks users from making LLM API calls using a configurable list', 'create_blocked_user_list_from_file': 'create a blocked user list by loading user IDs from a newline-separated file path', 'test_async_pre_call_hook': 'test the async pre-call hook that rejects requests from blocked users via static list, cache, or database', 'review_blocked_user_list_class': 'review the _ENTERPRISE_BlockedUserList class that extends CustomLogger to enforce user blocking in LiteLLM proxy', 'refactor_print_verbose_logging': 'refactor the print_verbose method to log at configurable INFO or DEBUG levels with optional verbose output'}
```

## File: berriai_litellm/enterprise/enterprise_hooks/google_text_moderation.py

Prompts

```
['initialize an AporiaGuardrail instance with an API key and base URL for LLM guardrail validation', 'transform a list of message dicts to map unsupported roles to the default other role', 'prepare a request dict with messages and optional response string for Aporia AI validation', 'send an async POST request to the Aporia AI validate endpoint to check messages or responses', 'run the async post call success hook to validate LLM responses against Aporia AI guardrail policies', 'create a CustomLogger subclass that rejects calls containing banned keywords from a list or file', 'test a string against the banned keywords list and raise HTTPException on match', 'review the pre-call hook that checks completion messages for banned keywords before the LLM call', 'review the post-call hook that checks LLM response content for banned keywords', 'review the streaming hook that checks each streamed response chunk for banned keywords', 'build a LiteLLM enterprise hook that blocks users from making LLM API calls using a configurable list', 'create a blocked user list by loading user IDs from a newline-separated file path', 'test the async pre-call hook that rejects requests from blocked users via static list, cache, or database', 'review the _ENTERPRISE_BlockedUserList class that extends CustomLogger to enforce user blocking in LiteLLM proxy', 'refactor the print_verbose method to log at configurable INFO or DEBUG levels with optional verbose output', 'initialize the GoogleTextModeration class with configurable confidence thresholds for 16 safety categories', 'call the async moderation hook to check messages against Google Cloud text moderation API', 'set per-category confidence thresholds like toxic or profanity via litellm module attributes', 'review the 16 confidence categories including toxic, insult, profanity, and firearms_and_weapons', 'test the print_verbose method for debug logging with litellm verbose mode']
```

Usage

```
{'init_google_text_moderation': 'initialize the GoogleTextModeration class with configurable confidence thresholds for 16 safety categories', 'run_async_moderation_hook': 'call the async moderation hook to check messages against Google Cloud text moderation API', 'configure_confidence_thresholds': 'set per-category confidence thresholds like toxic or profanity via litellm module attributes', 'review_moderation_categories': 'review the 16 confidence categories including toxic, insult, profanity, and firearms_and_weapons', 'test_verbose_logging': 'test the print_verbose method for debug logging with litellm verbose mode'}
```

