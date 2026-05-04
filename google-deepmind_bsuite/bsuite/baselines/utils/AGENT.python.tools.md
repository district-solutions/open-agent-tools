# Agent Python Tools

- repo: google-deepmind/bsuite
- repo_uri: https://github.com/google-deepmind/bsuite

## File: google-deepmind_bsuite/bsuite/baselines/utils/pool.py

Prompts

```
['run map_mpi to execute a function across multiple bsuite IDs in parallel with a progress bar', 'create a process pool that maps a callable over a sequence of experiment IDs', 'test map_mpi by passing a simple function and a list of bsuite IDs', 'refactor map_mpi to support custom progress bar formatting or different executor backends', 'review map_mpi to understand how it uses ProcessPoolExecutor and tqdm for parallel execution', 'create a Replay buffer with a specified capacity for storing experience tuples', 'add a sequence of items to the replay buffer using the add method', 'sample a random minibatch of specified size from the replay buffer', 'check the current size and fraction_filled properties of the replay buffer', 'reset the replay buffer to clear all stored data and preallocated memory', 'test the Replay buffer by adding samples and verifying sample shapes match expected dimensions', 'run the BasicReplayTest test case to validate replay buffer add and sample operations', 'review the test_end_to_end method that validates replay buffer sampling with varying buffer sizes', 'refactor the generate_sample helper to produce different random sample shapes for replay testing', 'summarize the BasicReplayTest class that tests Replay buffer capacity and sampling behavior', 'create a Buffer instance with observation and action specs to pre-allocate trajectory storage', 'append a timestep action and new timestep transition to the sequence buffer', 'drain the sequence buffer and return the accumulated trajectory as a Trajectory named tuple', 'check if the sequence buffer is empty before attempting to drain transitions', 'check if the sequence buffer is full before appending new transitions', 'test the Buffer class by appending transitions and verifying the buffer becomes full', 'test the Buffer drain method to retrieve a trajectory with observations and rewards', 'test the Buffer empty method after draining to confirm the buffer is empty', 'test the Buffer full method after appending max sequence length transitions', 'test the Buffer by appending a single transition and draining a partial trajectory']
```

Usage

```
{'run_map_mpi': 'run map_mpi to execute a function across multiple bsuite IDs in parallel with a progress bar', 'create_multiprocessing_pool': 'create a process pool that maps a callable over a sequence of experiment IDs', 'test_map_mpi': 'test map_mpi by passing a simple function and a list of bsuite IDs', 'refactor_map_mpi': 'refactor map_mpi to support custom progress bar formatting or different executor backends', 'review_map_mpi': 'review map_mpi to understand how it uses ProcessPoolExecutor and tqdm for parallel execution'}
```

## File: google-deepmind_bsuite/bsuite/baselines/utils/replay.py

Prompts

```
['run map_mpi to execute a function across multiple bsuite IDs in parallel with a progress bar', 'create a process pool that maps a callable over a sequence of experiment IDs', 'test map_mpi by passing a simple function and a list of bsuite IDs', 'refactor map_mpi to support custom progress bar formatting or different executor backends', 'review map_mpi to understand how it uses ProcessPoolExecutor and tqdm for parallel execution', 'create a Replay buffer with a specified capacity for storing experience tuples', 'add a sequence of items to the replay buffer using the add method', 'sample a random minibatch of specified size from the replay buffer', 'check the current size and fraction_filled properties of the replay buffer', 'reset the replay buffer to clear all stored data and preallocated memory', 'test the Replay buffer by adding samples and verifying sample shapes match expected dimensions', 'run the BasicReplayTest test case to validate replay buffer add and sample operations', 'review the test_end_to_end method that validates replay buffer sampling with varying buffer sizes', 'refactor the generate_sample helper to produce different random sample shapes for replay testing', 'summarize the BasicReplayTest class that tests Replay buffer capacity and sampling behavior', 'create a Buffer instance with observation and action specs to pre-allocate trajectory storage', 'append a timestep action and new timestep transition to the sequence buffer', 'drain the sequence buffer and return the accumulated trajectory as a Trajectory named tuple', 'check if the sequence buffer is empty before attempting to drain transitions', 'check if the sequence buffer is full before appending new transitions', 'test the Buffer class by appending transitions and verifying the buffer becomes full', 'test the Buffer drain method to retrieve a trajectory with observations and rewards', 'test the Buffer empty method after draining to confirm the buffer is empty', 'test the Buffer full method after appending max sequence length transitions', 'test the Buffer by appending a single transition and draining a partial trajectory']
```

Usage

```
{'create_replay_buffer': 'create a Replay buffer with a specified capacity for storing experience tuples', 'add_items_to_replay': 'add a sequence of items to the replay buffer using the add method', 'sample_from_replay': 'sample a random minibatch of specified size from the replay buffer', 'check_replay_size': 'check the current size and fraction_filled properties of the replay buffer', 'reset_replay_buffer': 'reset the replay buffer to clear all stored data and preallocated memory'}
```

## File: google-deepmind_bsuite/bsuite/baselines/utils/replay_test.py

Prompts

```
['run map_mpi to execute a function across multiple bsuite IDs in parallel with a progress bar', 'create a process pool that maps a callable over a sequence of experiment IDs', 'test map_mpi by passing a simple function and a list of bsuite IDs', 'refactor map_mpi to support custom progress bar formatting or different executor backends', 'review map_mpi to understand how it uses ProcessPoolExecutor and tqdm for parallel execution', 'create a Replay buffer with a specified capacity for storing experience tuples', 'add a sequence of items to the replay buffer using the add method', 'sample a random minibatch of specified size from the replay buffer', 'check the current size and fraction_filled properties of the replay buffer', 'reset the replay buffer to clear all stored data and preallocated memory', 'test the Replay buffer by adding samples and verifying sample shapes match expected dimensions', 'run the BasicReplayTest test case to validate replay buffer add and sample operations', 'review the test_end_to_end method that validates replay buffer sampling with varying buffer sizes', 'refactor the generate_sample helper to produce different random sample shapes for replay testing', 'summarize the BasicReplayTest class that tests Replay buffer capacity and sampling behavior', 'create a Buffer instance with observation and action specs to pre-allocate trajectory storage', 'append a timestep action and new timestep transition to the sequence buffer', 'drain the sequence buffer and return the accumulated trajectory as a Trajectory named tuple', 'check if the sequence buffer is empty before attempting to drain transitions', 'check if the sequence buffer is full before appending new transitions', 'test the Buffer class by appending transitions and verifying the buffer becomes full', 'test the Buffer drain method to retrieve a trajectory with observations and rewards', 'test the Buffer empty method after draining to confirm the buffer is empty', 'test the Buffer full method after appending max sequence length transitions', 'test the Buffer by appending a single transition and draining a partial trajectory']
```

Usage

```
{'test_Replay_buffer_end_to_end': 'test the Replay buffer by adding samples and verifying sample shapes match expected dimensions', 'run_BasicReplayTest': 'run the BasicReplayTest test case to validate replay buffer add and sample operations', 'review_BasicReplayTest_test_end_to_end': 'review the test_end_to_end method that validates replay buffer sampling with varying buffer sizes', 'refactor_generate_sample': 'refactor the generate_sample helper to produce different random sample shapes for replay testing', 'summarize_BasicReplayTest': 'summarize the BasicReplayTest class that tests Replay buffer capacity and sampling behavior'}
```

## File: google-deepmind_bsuite/bsuite/baselines/utils/sequence.py

Prompts

```
['run map_mpi to execute a function across multiple bsuite IDs in parallel with a progress bar', 'create a process pool that maps a callable over a sequence of experiment IDs', 'test map_mpi by passing a simple function and a list of bsuite IDs', 'refactor map_mpi to support custom progress bar formatting or different executor backends', 'review map_mpi to understand how it uses ProcessPoolExecutor and tqdm for parallel execution', 'create a Replay buffer with a specified capacity for storing experience tuples', 'add a sequence of items to the replay buffer using the add method', 'sample a random minibatch of specified size from the replay buffer', 'check the current size and fraction_filled properties of the replay buffer', 'reset the replay buffer to clear all stored data and preallocated memory', 'test the Replay buffer by adding samples and verifying sample shapes match expected dimensions', 'run the BasicReplayTest test case to validate replay buffer add and sample operations', 'review the test_end_to_end method that validates replay buffer sampling with varying buffer sizes', 'refactor the generate_sample helper to produce different random sample shapes for replay testing', 'summarize the BasicReplayTest class that tests Replay buffer capacity and sampling behavior', 'create a Buffer instance with observation and action specs to pre-allocate trajectory storage', 'append a timestep action and new timestep transition to the sequence buffer', 'drain the sequence buffer and return the accumulated trajectory as a Trajectory named tuple', 'check if the sequence buffer is empty before attempting to drain transitions', 'check if the sequence buffer is full before appending new transitions', 'test the Buffer class by appending transitions and verifying the buffer becomes full', 'test the Buffer drain method to retrieve a trajectory with observations and rewards', 'test the Buffer empty method after draining to confirm the buffer is empty', 'test the Buffer full method after appending max sequence length transitions', 'test the Buffer by appending a single transition and draining a partial trajectory']
```

Usage

```
{'create_buffer_trajectory': 'create a Buffer instance with observation and action specs to pre-allocate trajectory storage', 'append_transition_buffer': 'append a timestep action and new timestep transition to the sequence buffer', 'drain_buffer_trajectory': 'drain the sequence buffer and return the accumulated trajectory as a Trajectory named tuple', 'check_buffer_empty': 'check if the sequence buffer is empty before attempting to drain transitions', 'check_buffer_full': 'check if the sequence buffer is full before appending new transitions'}
```

## File: google-deepmind_bsuite/bsuite/baselines/utils/sequence_test.py

Prompts

```
['run map_mpi to execute a function across multiple bsuite IDs in parallel with a progress bar', 'create a process pool that maps a callable over a sequence of experiment IDs', 'test map_mpi by passing a simple function and a list of bsuite IDs', 'refactor map_mpi to support custom progress bar formatting or different executor backends', 'review map_mpi to understand how it uses ProcessPoolExecutor and tqdm for parallel execution', 'create a Replay buffer with a specified capacity for storing experience tuples', 'add a sequence of items to the replay buffer using the add method', 'sample a random minibatch of specified size from the replay buffer', 'check the current size and fraction_filled properties of the replay buffer', 'reset the replay buffer to clear all stored data and preallocated memory', 'test the Replay buffer by adding samples and verifying sample shapes match expected dimensions', 'run the BasicReplayTest test case to validate replay buffer add and sample operations', 'review the test_end_to_end method that validates replay buffer sampling with varying buffer sizes', 'refactor the generate_sample helper to produce different random sample shapes for replay testing', 'summarize the BasicReplayTest class that tests Replay buffer capacity and sampling behavior', 'create a Buffer instance with observation and action specs to pre-allocate trajectory storage', 'append a timestep action and new timestep transition to the sequence buffer', 'drain the sequence buffer and return the accumulated trajectory as a Trajectory named tuple', 'check if the sequence buffer is empty before attempting to drain transitions', 'check if the sequence buffer is full before appending new transitions', 'test the Buffer class by appending transitions and verifying the buffer becomes full', 'test the Buffer drain method to retrieve a trajectory with observations and rewards', 'test the Buffer empty method after draining to confirm the buffer is empty', 'test the Buffer full method after appending max sequence length transitions', 'test the Buffer by appending a single transition and draining a partial trajectory']
```

Usage

```
{'test_Buffer_append': 'test the Buffer class by appending transitions and verifying the buffer becomes full', 'test_Buffer_drain': 'test the Buffer drain method to retrieve a trajectory with observations and rewards', 'test_Buffer_empty': 'test the Buffer empty method after draining to confirm the buffer is empty', 'test_Buffer_full': 'test the Buffer full method after appending max sequence length transitions', 'test_Buffer_partial_trajectory': 'test the Buffer by appending a single transition and draining a partial trajectory'}
```

