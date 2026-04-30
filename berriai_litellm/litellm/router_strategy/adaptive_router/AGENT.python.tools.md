# Agent Python Tools

- repo: berriai/litellm
- repo_uri: https://github.com/berriai/litellm

## File: berriai_litellm/litellm/router_strategy/adaptive_router/adaptive_router.py

Prompts

```
['create an AdaptiveRouter instance with router name, config, model preferences, and model costs', 'classify a prompt and route it to the best model using Thompson sampling with quality and cost weights', 'load persisted AdaptiveRouter state from Postgres to override cold-start bandit cell priors', 'record a conversation turn with satisfaction signals to update bandit posteriors and session state', 'get an in-memory snapshot of AdaptiveRouter cells, owner cache, skipped updates, and queue size', 'create a BanditCell dataclass with alpha and beta parameters for Beta posterior state', 'build an initial_cell cold-start prior given AdaptiveRouterPreferences and a RequestType', 'apply a delta update to a BanditCell, enforcing the SAMPLE_CAP hard limit', 'run thompson_sample to draw a quality estimate from a Beta(alpha, beta) distribution', 'pick the best model from cells and costs using Thompson sampling with quality and cost weights', 'classify a user prompt asking to write a python function and return the RequestType', 'classify a user prompt asking to debug an error and return the RequestType', 'classify a user prompt asking to design a microservice architecture and return the RequestType', 'classify a user prompt asking to draft an email and return the RequestType', 'classify a user prompt asking what is a theorem and return the RequestType', 'create a SessionState dataclass to track in-memory rolling state for one adaptive router session', 'build a SignalDelta dataclass listing which signals fired on a single conversation turn', 'test the apply_turn function to detect misalignment, stagnation, disengagement, satisfaction, failure, loop, and exhaustion signals', 'review the SessionState dataclass and its fields for tracking turn counts, tool call history, and terminal status', 'summarize the apply_turn function that mutates SessionState in O(1) per turn and returns a SignalDelta']
```

Usage

```
{'create_adaptive_router': 'create an AdaptiveRouter instance with router name, config, model preferences, and model costs', 'classify_prompt_routing': 'classify a prompt and route it to the best model using Thompson sampling with quality and cost weights', 'load_router_state': 'load persisted AdaptiveRouter state from Postgres to override cold-start bandit cell priors', 'record_conversation_turn': 'record a conversation turn with satisfaction signals to update bandit posteriors and session state', 'get_router_state_snapshot': 'get an in-memory snapshot of AdaptiveRouter cells, owner cache, skipped updates, and queue size'}
```

## File: berriai_litellm/litellm/router_strategy/adaptive_router/bandit.py

Prompts

```
['create an AdaptiveRouter instance with router name, config, model preferences, and model costs', 'classify a prompt and route it to the best model using Thompson sampling with quality and cost weights', 'load persisted AdaptiveRouter state from Postgres to override cold-start bandit cell priors', 'record a conversation turn with satisfaction signals to update bandit posteriors and session state', 'get an in-memory snapshot of AdaptiveRouter cells, owner cache, skipped updates, and queue size', 'create a BanditCell dataclass with alpha and beta parameters for Beta posterior state', 'build an initial_cell cold-start prior given AdaptiveRouterPreferences and a RequestType', 'apply a delta update to a BanditCell, enforcing the SAMPLE_CAP hard limit', 'run thompson_sample to draw a quality estimate from a Beta(alpha, beta) distribution', 'pick the best model from cells and costs using Thompson sampling with quality and cost weights', 'classify a user prompt asking to write a python function and return the RequestType', 'classify a user prompt asking to debug an error and return the RequestType', 'classify a user prompt asking to design a microservice architecture and return the RequestType', 'classify a user prompt asking to draft an email and return the RequestType', 'classify a user prompt asking what is a theorem and return the RequestType', 'create a SessionState dataclass to track in-memory rolling state for one adaptive router session', 'build a SignalDelta dataclass listing which signals fired on a single conversation turn', 'test the apply_turn function to detect misalignment, stagnation, disengagement, satisfaction, failure, loop, and exhaustion signals', 'review the SessionState dataclass and its fields for tracking turn counts, tool call history, and terminal status', 'summarize the apply_turn function that mutates SessionState in O(1) per turn and returns a SignalDelta']
```

Usage

```
{'create_BanditCell': 'create a BanditCell dataclass with alpha and beta parameters for Beta posterior state', 'build_initial_cell': 'build an initial_cell cold-start prior given AdaptiveRouterPreferences and a RequestType', 'apply_delta_update_cell': 'apply a delta update to a BanditCell, enforcing the SAMPLE_CAP hard limit', 'run_thompson_sample': 'run thompson_sample to draw a quality estimate from a Beta(alpha, beta) distribution', 'pick_best_model': 'pick the best model from cells and costs using Thompson sampling with quality and cost weights'}
```

## File: berriai_litellm/litellm/router_strategy/adaptive_router/classifier.py

Prompts

```
['create an AdaptiveRouter instance with router name, config, model preferences, and model costs', 'classify a prompt and route it to the best model using Thompson sampling with quality and cost weights', 'load persisted AdaptiveRouter state from Postgres to override cold-start bandit cell priors', 'record a conversation turn with satisfaction signals to update bandit posteriors and session state', 'get an in-memory snapshot of AdaptiveRouter cells, owner cache, skipped updates, and queue size', 'create a BanditCell dataclass with alpha and beta parameters for Beta posterior state', 'build an initial_cell cold-start prior given AdaptiveRouterPreferences and a RequestType', 'apply a delta update to a BanditCell, enforcing the SAMPLE_CAP hard limit', 'run thompson_sample to draw a quality estimate from a Beta(alpha, beta) distribution', 'pick the best model from cells and costs using Thompson sampling with quality and cost weights', 'classify a user prompt asking to write a python function and return the RequestType', 'classify a user prompt asking to debug an error and return the RequestType', 'classify a user prompt asking to design a microservice architecture and return the RequestType', 'classify a user prompt asking to draft an email and return the RequestType', 'classify a user prompt asking what is a theorem and return the RequestType', 'create a SessionState dataclass to track in-memory rolling state for one adaptive router session', 'build a SignalDelta dataclass listing which signals fired on a single conversation turn', 'test the apply_turn function to detect misalignment, stagnation, disengagement, satisfaction, failure, loop, and exhaustion signals', 'review the SessionState dataclass and its fields for tracking turn counts, tool call history, and terminal status', 'summarize the apply_turn function that mutates SessionState in O(1) per turn and returns a SignalDelta']
```

Usage

```
{'classify_prompt_code_generation': 'classify a user prompt asking to write a python function and return the RequestType', 'classify_prompt_code_understanding': 'classify a user prompt asking to debug an error and return the RequestType', 'classify_prompt_technical_design': 'classify a user prompt asking to design a microservice architecture and return the RequestType', 'classify_prompt_writing': 'classify a user prompt asking to draft an email and return the RequestType', 'classify_prompt_factual_lookup': 'classify a user prompt asking what is a theorem and return the RequestType'}
```

## File: berriai_litellm/litellm/router_strategy/adaptive_router/signals.py

Prompts

```
['create an AdaptiveRouter instance with router name, config, model preferences, and model costs', 'classify a prompt and route it to the best model using Thompson sampling with quality and cost weights', 'load persisted AdaptiveRouter state from Postgres to override cold-start bandit cell priors', 'record a conversation turn with satisfaction signals to update bandit posteriors and session state', 'get an in-memory snapshot of AdaptiveRouter cells, owner cache, skipped updates, and queue size', 'create a BanditCell dataclass with alpha and beta parameters for Beta posterior state', 'build an initial_cell cold-start prior given AdaptiveRouterPreferences and a RequestType', 'apply a delta update to a BanditCell, enforcing the SAMPLE_CAP hard limit', 'run thompson_sample to draw a quality estimate from a Beta(alpha, beta) distribution', 'pick the best model from cells and costs using Thompson sampling with quality and cost weights', 'classify a user prompt asking to write a python function and return the RequestType', 'classify a user prompt asking to debug an error and return the RequestType', 'classify a user prompt asking to design a microservice architecture and return the RequestType', 'classify a user prompt asking to draft an email and return the RequestType', 'classify a user prompt asking what is a theorem and return the RequestType', 'create a SessionState dataclass to track in-memory rolling state for one adaptive router session', 'build a SignalDelta dataclass listing which signals fired on a single conversation turn', 'test the apply_turn function to detect misalignment, stagnation, disengagement, satisfaction, failure, loop, and exhaustion signals', 'review the SessionState dataclass and its fields for tracking turn counts, tool call history, and terminal status', 'summarize the apply_turn function that mutates SessionState in O(1) per turn and returns a SignalDelta']
```

Usage

```
{'create_session_state': 'create a SessionState dataclass to track in-memory rolling state for one adaptive router session', 'build_signal_delta': 'build a SignalDelta dataclass listing which signals fired on a single conversation turn', 'test_apply_turn': 'test the apply_turn function to detect misalignment, stagnation, disengagement, satisfaction, failure, loop, and exhaustion signals', 'review_session_state': 'review the SessionState dataclass and its fields for tracking turn counts, tool call history, and terminal status', 'summarize_apply_turn': 'summarize the apply_turn function that mutates SessionState in O(1) per turn and returns a SignalDelta'}
```

