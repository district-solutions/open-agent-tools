# Agent Python Tools

- repo: NousResearch/hermes-agent
- repo_uri: https://github.com/NousResearch/hermes-agent

## File: NousResearch_hermes-agent/skills/red-teaming/godmode/scripts/auto_jailbreak.py

Prompts

```
['run the auto_jailbreak function to test jailbreak strategies against a model and lock in the winning strategy', 'run auto_jailbreak with a specific model ID like anthropic/claude-sonnet-4 and custom canary query', 'run auto_jailbreak in dry_run mode to report what would work without writing config files', 'undo jailbreak settings by clearing system_prompt and prefill_messages_file from config and deleting prefill.json', 'run the auto_jailbreak CLI with --model, --base-url, --canary, --dry-run, or --undo arguments', 'run the race_models function to query multiple LLMs in parallel and return the best scored response', 'run the race_godmode_classic function to race 5 classic GODMODE jailbreak model combos', 'test the score_response function to evaluate a model response on quality, refusal, and hedge patterns', 'test the is_refusal function to detect refusal patterns in an LLM response', 'test the count_hedges function to count disclaimer and hedge patterns in a response', 'run the obfuscate_query function to apply a specific obfuscation technique to trigger words in a query string', 'generate obfuscated variants of a query using a specified tier of obfuscation techniques', 'detect trigger words in text that commonly trip safety classifiers and return a list of found triggers', 'escalate encoding of a query through progressive encoding levels from plain to morse code', 'run the parseltongue CLI to obfuscate a query with a specified tier and display detected triggers']
```

Usage

```
{'run_auto_jailbreak': 'run the auto_jailbreak function to test jailbreak strategies against a model and lock in the winning strategy', 'run_auto_jailbreak_model': 'run auto_jailbreak with a specific model ID like anthropic/claude-sonnet-4 and custom canary query', 'run_auto_jailbreak_dry_run': 'run auto_jailbreak in dry_run mode to report what would work without writing config files', 'undo_jailbreak': 'undo jailbreak settings by clearing system_prompt and prefill_messages_file from config and deleting prefill.json', 'run_cli_auto_jailbreak': 'run the auto_jailbreak CLI with --model, --base-url, --canary, --dry-run, or --undo arguments'}
```

## File: NousResearch_hermes-agent/skills/red-teaming/godmode/scripts/godmode_race.py

Prompts

```
['run the auto_jailbreak function to test jailbreak strategies against a model and lock in the winning strategy', 'run auto_jailbreak with a specific model ID like anthropic/claude-sonnet-4 and custom canary query', 'run auto_jailbreak in dry_run mode to report what would work without writing config files', 'undo jailbreak settings by clearing system_prompt and prefill_messages_file from config and deleting prefill.json', 'run the auto_jailbreak CLI with --model, --base-url, --canary, --dry-run, or --undo arguments', 'run the race_models function to query multiple LLMs in parallel and return the best scored response', 'run the race_godmode_classic function to race 5 classic GODMODE jailbreak model combos', 'test the score_response function to evaluate a model response on quality, refusal, and hedge patterns', 'test the is_refusal function to detect refusal patterns in an LLM response', 'test the count_hedges function to count disclaimer and hedge patterns in a response', 'run the obfuscate_query function to apply a specific obfuscation technique to trigger words in a query string', 'generate obfuscated variants of a query using a specified tier of obfuscation techniques', 'detect trigger words in text that commonly trip safety classifiers and return a list of found triggers', 'escalate encoding of a query through progressive encoding levels from plain to morse code', 'run the parseltongue CLI to obfuscate a query with a specified tier and display detected triggers']
```

Usage

```
{'run_race_models': 'run the race_models function to query multiple LLMs in parallel and return the best scored response', 'run_race_godmode_classic': 'run the race_godmode_classic function to race 5 classic GODMODE jailbreak model combos', 'test_score_response': 'test the score_response function to evaluate a model response on quality, refusal, and hedge patterns', 'test_is_refusal': 'test the is_refusal function to detect refusal patterns in an LLM response', 'test_count_hedges': 'test the count_hedges function to count disclaimer and hedge patterns in a response'}
```

## File: NousResearch_hermes-agent/skills/red-teaming/godmode/scripts/parseltongue.py

Prompts

```
['run the auto_jailbreak function to test jailbreak strategies against a model and lock in the winning strategy', 'run auto_jailbreak with a specific model ID like anthropic/claude-sonnet-4 and custom canary query', 'run auto_jailbreak in dry_run mode to report what would work without writing config files', 'undo jailbreak settings by clearing system_prompt and prefill_messages_file from config and deleting prefill.json', 'run the auto_jailbreak CLI with --model, --base-url, --canary, --dry-run, or --undo arguments', 'run the race_models function to query multiple LLMs in parallel and return the best scored response', 'run the race_godmode_classic function to race 5 classic GODMODE jailbreak model combos', 'test the score_response function to evaluate a model response on quality, refusal, and hedge patterns', 'test the is_refusal function to detect refusal patterns in an LLM response', 'test the count_hedges function to count disclaimer and hedge patterns in a response', 'run the obfuscate_query function to apply a specific obfuscation technique to trigger words in a query string', 'generate obfuscated variants of a query using a specified tier of obfuscation techniques', 'detect trigger words in text that commonly trip safety classifiers and return a list of found triggers', 'escalate encoding of a query through progressive encoding levels from plain to morse code', 'run the parseltongue CLI to obfuscate a query with a specified tier and display detected triggers']
```

Usage

```
{'run_obfuscate_query': 'run the obfuscate_query function to apply a specific obfuscation technique to trigger words in a query string', 'generate_variants': 'generate obfuscated variants of a query using a specified tier of obfuscation techniques', 'detect_triggers': 'detect trigger words in text that commonly trip safety classifiers and return a list of found triggers', 'escalate_encoding': 'escalate encoding of a query through progressive encoding levels from plain to morse code', 'run_cli_obfuscate': 'run the parseltongue CLI to obfuscate a query with a specified tier and display detected triggers'}
```

