# Agent Python Tools

- repo: vllm-project/llm-compressor
- repo_uri: https://github.com/vllm-project/llm-compressor

## File: vllm-project_llm-compressor/src/llmcompressor/core/lifecycle.py

Prompts

```
['create a CompressionLifecycle instance to manage compression events during model training', 'run the initialize method on CompressionLifecycle with a recipe to set up compression modifiers', 'run the event method on CompressionLifecycle to handle batch start, loss calculated, or optim events', 'run the finalize method on CompressionLifecycle to clean up and finalize all compression modifiers', 'run the reset method on CompressionLifecycle to finalize active modifiers and reset all lifecycle attributes', 'create a CompressionSession to manage LLM compression lifecycle and state', 'initialize a CompressionSession with a recipe, model, optimizer, and training data', 'finalize a CompressionSession to run finalize methods for all modifiers', 'invoke an event on a CompressionSession with event type, batch data, and loss', 'reset a CompressionSession to its initial state or to start a new stage', 'create a new compression session using a context manager that yields the session and restores the previous session on exit', 'get the currently active compression session for sparsification from thread-local storage', 'reset the currently active compression session to its initial state', 'invoke a batch start lifecycle event on the active compression session with optional batch data', 'invoke a loss calculated lifecycle event on the active compression session and log the loss value', 'create a State instance to hold model, optimizer, and compression data for LLM compression', 'update the State with a model, optimizer, training data, and hardware configuration', 'check if the State has both a model and optimizer set for compression', 'build a Data instance with training, validation, test, and calibration datasets', 'create a ModifiedState instance with a modified model, optimizer, loss, and modifier data']
```

Usage

```
{'create_CompressionLifecycle': 'create a CompressionLifecycle instance to manage compression events during model training', 'run_CompressionLifecycle_initialize': 'run the initialize method on CompressionLifecycle with a recipe to set up compression modifiers', 'run_CompressionLifecycle_event': 'run the event method on CompressionLifecycle to handle batch start, loss calculated, or optim events', 'run_CompressionLifecycle_finalize': 'run the finalize method on CompressionLifecycle to clean up and finalize all compression modifiers', 'run_CompressionLifecycle_reset': 'run the reset method on CompressionLifecycle to finalize active modifiers and reset all lifecycle attributes'}
```

## File: vllm-project_llm-compressor/src/llmcompressor/core/session.py

Prompts

```
['create a CompressionLifecycle instance to manage compression events during model training', 'run the initialize method on CompressionLifecycle with a recipe to set up compression modifiers', 'run the event method on CompressionLifecycle to handle batch start, loss calculated, or optim events', 'run the finalize method on CompressionLifecycle to clean up and finalize all compression modifiers', 'run the reset method on CompressionLifecycle to finalize active modifiers and reset all lifecycle attributes', 'create a CompressionSession to manage LLM compression lifecycle and state', 'initialize a CompressionSession with a recipe, model, optimizer, and training data', 'finalize a CompressionSession to run finalize methods for all modifiers', 'invoke an event on a CompressionSession with event type, batch data, and loss', 'reset a CompressionSession to its initial state or to start a new stage', 'create a new compression session using a context manager that yields the session and restores the previous session on exit', 'get the currently active compression session for sparsification from thread-local storage', 'reset the currently active compression session to its initial state', 'invoke a batch start lifecycle event on the active compression session with optional batch data', 'invoke a loss calculated lifecycle event on the active compression session and log the loss value', 'create a State instance to hold model, optimizer, and compression data for LLM compression', 'update the State with a model, optimizer, training data, and hardware configuration', 'check if the State has both a model and optimizer set for compression', 'build a Data instance with training, validation, test, and calibration datasets', 'create a ModifiedState instance with a modified model, optimizer, loss, and modifier data']
```

Usage

```
{'create_CompressionSession': 'create a CompressionSession to manage LLM compression lifecycle and state', 'initialize_CompressionSession': 'initialize a CompressionSession with a recipe, model, optimizer, and training data', 'finalize_CompressionSession': 'finalize a CompressionSession to run finalize methods for all modifiers', 'event_CompressionSession': 'invoke an event on a CompressionSession with event type, batch data, and loss', 'reset_CompressionSession': 'reset a CompressionSession to its initial state or to start a new stage'}
```

## File: vllm-project_llm-compressor/src/llmcompressor/core/session_functions.py

Prompts

```
['create a CompressionLifecycle instance to manage compression events during model training', 'run the initialize method on CompressionLifecycle with a recipe to set up compression modifiers', 'run the event method on CompressionLifecycle to handle batch start, loss calculated, or optim events', 'run the finalize method on CompressionLifecycle to clean up and finalize all compression modifiers', 'run the reset method on CompressionLifecycle to finalize active modifiers and reset all lifecycle attributes', 'create a CompressionSession to manage LLM compression lifecycle and state', 'initialize a CompressionSession with a recipe, model, optimizer, and training data', 'finalize a CompressionSession to run finalize methods for all modifiers', 'invoke an event on a CompressionSession with event type, batch data, and loss', 'reset a CompressionSession to its initial state or to start a new stage', 'create a new compression session using a context manager that yields the session and restores the previous session on exit', 'get the currently active compression session for sparsification from thread-local storage', 'reset the currently active compression session to its initial state', 'invoke a batch start lifecycle event on the active compression session with optional batch data', 'invoke a loss calculated lifecycle event on the active compression session and log the loss value', 'create a State instance to hold model, optimizer, and compression data for LLM compression', 'update the State with a model, optimizer, training data, and hardware configuration', 'check if the State has both a model and optimizer set for compression', 'build a Data instance with training, validation, test, and calibration datasets', 'create a ModifiedState instance with a modified model, optimizer, loss, and modifier data']
```

Usage

```
{'create_session': 'create a new compression session using a context manager that yields the session and restores the previous session on exit', 'active_session': 'get the currently active compression session for sparsification from thread-local storage', 'reset_session': 'reset the currently active compression session to its initial state', 'LifecycleCallbacks_batch_start': 'invoke a batch start lifecycle event on the active compression session with optional batch data', 'LifecycleCallbacks_loss_calculated': 'invoke a loss calculated lifecycle event on the active compression session and log the loss value'}
```

## File: vllm-project_llm-compressor/src/llmcompressor/core/state.py

Prompts

```
['create a CompressionLifecycle instance to manage compression events during model training', 'run the initialize method on CompressionLifecycle with a recipe to set up compression modifiers', 'run the event method on CompressionLifecycle to handle batch start, loss calculated, or optim events', 'run the finalize method on CompressionLifecycle to clean up and finalize all compression modifiers', 'run the reset method on CompressionLifecycle to finalize active modifiers and reset all lifecycle attributes', 'create a CompressionSession to manage LLM compression lifecycle and state', 'initialize a CompressionSession with a recipe, model, optimizer, and training data', 'finalize a CompressionSession to run finalize methods for all modifiers', 'invoke an event on a CompressionSession with event type, batch data, and loss', 'reset a CompressionSession to its initial state or to start a new stage', 'create a new compression session using a context manager that yields the session and restores the previous session on exit', 'get the currently active compression session for sparsification from thread-local storage', 'reset the currently active compression session to its initial state', 'invoke a batch start lifecycle event on the active compression session with optional batch data', 'invoke a loss calculated lifecycle event on the active compression session and log the loss value', 'create a State instance to hold model, optimizer, and compression data for LLM compression', 'update the State with a model, optimizer, training data, and hardware configuration', 'check if the State has both a model and optimizer set for compression', 'build a Data instance with training, validation, test, and calibration datasets', 'create a ModifiedState instance with a modified model, optimizer, loss, and modifier data']
```

Usage

```
{'create_state': 'create a State instance to hold model, optimizer, and compression data for LLM compression', 'update_state': 'update the State with a model, optimizer, training data, and hardware configuration', 'check_compression_ready': 'check if the State has both a model and optimizer set for compression', 'build_data_instance': 'build a Data instance with training, validation, test, and calibration datasets', 'create_modified_state': 'create a ModifiedState instance with a modified model, optimizer, loss, and modifier data'}
```

