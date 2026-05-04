# Agent Python Tools

- repo: facebookresearch/elf
- repo_uri: https://github.com/facebookresearch/elf

## File: facebookresearch_elf/atari/benchmark-atari.py

Prompts

```
['run the benchmark function to measure FPS for parallel Atari games with configurable game count', 'create a GameContext object from initialized game configuration and options for Atari environments', 'test the benchmark function by running Niter iterations and measuring frames per second', 'review the initialize_game function to understand batch size and frame skip configuration', 'summarize the benchmark-atari module that measures parallel Atari game performance across multiple game counts', 'run a multi-threaded Atari Pong benchmark measuring FPS across N parallel game instances', 'run a multi-process Atari Pong benchmark using 8 worker processes to collect observations', 'test the bench_thread function by passing a number of parallel game instances to benchmark', 'review the bench_proc function that spawns 8 multiprocessing workers for Atari environment benchmarking', 'refactor the bench_thread function to support configurable environment names instead of hardcoded PongDeterministic-v3', 'run the Loader class to initialize an Atari game environment with configurable frame skip and ROM file', 'run the Atari game CLI with command line args like --num_games 64 --batchsize 16 --actor_only', 'create a Loader instance that defines Atari game options including frame skip, hist length, and ROM path', 'register an actor callback function that returns random actions for the Atari game batch', 'register a train callback function to process training batches from the Atari game environment', 'build an Atari actor-critic model with a CNN trunk and policy and value branches', 'create a Model_ActorCritic instance by passing args with params hist_len and num_action', 'run a forward pass on state dict x to get policy pi and value V outputs', 'review the CNN trunk with four conv layers and max pooling for Atari frame processing', 'summarize the Models dict mapping actor_critic key to Model_ActorCritic and ActorCritic classes']
```

Usage

```
{'run_benchmark_atari': 'run the benchmark function to measure FPS for parallel Atari games with configurable game count', 'create_game_context': 'create a GameContext object from initialized game configuration and options for Atari environments', 'test_benchmark_function': 'test the benchmark function by running Niter iterations and measuring frames per second', 'review_initialize_game': 'review the initialize_game function to understand batch size and frame skip configuration', 'summarize_benchmark_atari': 'summarize the benchmark-atari module that measures parallel Atari game performance across multiple game counts'}
```

## File: facebookresearch_elf/atari/benchmark-gym.py

Prompts

```
['run the benchmark function to measure FPS for parallel Atari games with configurable game count', 'create a GameContext object from initialized game configuration and options for Atari environments', 'test the benchmark function by running Niter iterations and measuring frames per second', 'review the initialize_game function to understand batch size and frame skip configuration', 'summarize the benchmark-atari module that measures parallel Atari game performance across multiple game counts', 'run a multi-threaded Atari Pong benchmark measuring FPS across N parallel game instances', 'run a multi-process Atari Pong benchmark using 8 worker processes to collect observations', 'test the bench_thread function by passing a number of parallel game instances to benchmark', 'review the bench_proc function that spawns 8 multiprocessing workers for Atari environment benchmarking', 'refactor the bench_thread function to support configurable environment names instead of hardcoded PongDeterministic-v3', 'run the Loader class to initialize an Atari game environment with configurable frame skip and ROM file', 'run the Atari game CLI with command line args like --num_games 64 --batchsize 16 --actor_only', 'create a Loader instance that defines Atari game options including frame skip, hist length, and ROM path', 'register an actor callback function that returns random actions for the Atari game batch', 'register a train callback function to process training batches from the Atari game environment', 'build an Atari actor-critic model with a CNN trunk and policy and value branches', 'create a Model_ActorCritic instance by passing args with params hist_len and num_action', 'run a forward pass on state dict x to get policy pi and value V outputs', 'review the CNN trunk with four conv layers and max pooling for Atari frame processing', 'summarize the Models dict mapping actor_critic key to Model_ActorCritic and ActorCritic classes']
```

Usage

```
{'run_benchmark_gym_threads': 'run a multi-threaded Atari Pong benchmark measuring FPS across N parallel game instances', 'run_benchmark_gym_processes': 'run a multi-process Atari Pong benchmark using 8 worker processes to collect observations', 'test_bench_thread': 'test the bench_thread function by passing a number of parallel game instances to benchmark', 'review_bench_proc': 'review the bench_proc function that spawns 8 multiprocessing workers for Atari environment benchmarking', 'refactor_bench_thread': 'refactor the bench_thread function to support configurable environment names instead of hardcoded PongDeterministic-v3'}
```

## File: facebookresearch_elf/atari/game.py

Prompts

```
['run the benchmark function to measure FPS for parallel Atari games with configurable game count', 'create a GameContext object from initialized game configuration and options for Atari environments', 'test the benchmark function by running Niter iterations and measuring frames per second', 'review the initialize_game function to understand batch size and frame skip configuration', 'summarize the benchmark-atari module that measures parallel Atari game performance across multiple game counts', 'run a multi-threaded Atari Pong benchmark measuring FPS across N parallel game instances', 'run a multi-process Atari Pong benchmark using 8 worker processes to collect observations', 'test the bench_thread function by passing a number of parallel game instances to benchmark', 'review the bench_proc function that spawns 8 multiprocessing workers for Atari environment benchmarking', 'refactor the bench_thread function to support configurable environment names instead of hardcoded PongDeterministic-v3', 'run the Loader class to initialize an Atari game environment with configurable frame skip and ROM file', 'run the Atari game CLI with command line args like --num_games 64 --batchsize 16 --actor_only', 'create a Loader instance that defines Atari game options including frame skip, hist length, and ROM path', 'register an actor callback function that returns random actions for the Atari game batch', 'register a train callback function to process training batches from the Atari game environment', 'build an Atari actor-critic model with a CNN trunk and policy and value branches', 'create a Model_ActorCritic instance by passing args with params hist_len and num_action', 'run a forward pass on state dict x to get policy pi and value V outputs', 'review the CNN trunk with four conv layers and max pooling for Atari frame processing', 'summarize the Models dict mapping actor_critic key to Model_ActorCritic and ActorCritic classes']
```

Usage

```
{'run_atari_game_loader': 'run the Loader class to initialize an Atari game environment with configurable frame skip and ROM file', 'run_atari_game_cli': 'run the Atari game CLI with command line args like --num_games 64 --batchsize 16 --actor_only', 'create_loader_with_args': 'create a Loader instance that defines Atari game options including frame skip, hist length, and ROM path', 'register_actor_callback': 'register an actor callback function that returns random actions for the Atari game batch', 'register_train_callback': 'register a train callback function to process training batches from the Atari game environment'}
```

## File: facebookresearch_elf/atari/model.py

Prompts

```
['run the benchmark function to measure FPS for parallel Atari games with configurable game count', 'create a GameContext object from initialized game configuration and options for Atari environments', 'test the benchmark function by running Niter iterations and measuring frames per second', 'review the initialize_game function to understand batch size and frame skip configuration', 'summarize the benchmark-atari module that measures parallel Atari game performance across multiple game counts', 'run a multi-threaded Atari Pong benchmark measuring FPS across N parallel game instances', 'run a multi-process Atari Pong benchmark using 8 worker processes to collect observations', 'test the bench_thread function by passing a number of parallel game instances to benchmark', 'review the bench_proc function that spawns 8 multiprocessing workers for Atari environment benchmarking', 'refactor the bench_thread function to support configurable environment names instead of hardcoded PongDeterministic-v3', 'run the Loader class to initialize an Atari game environment with configurable frame skip and ROM file', 'run the Atari game CLI with command line args like --num_games 64 --batchsize 16 --actor_only', 'create a Loader instance that defines Atari game options including frame skip, hist length, and ROM path', 'register an actor callback function that returns random actions for the Atari game batch', 'register a train callback function to process training batches from the Atari game environment', 'build an Atari actor-critic model with a CNN trunk and policy and value branches', 'create a Model_ActorCritic instance by passing args with params hist_len and num_action', 'run a forward pass on state dict x to get policy pi and value V outputs', 'review the CNN trunk with four conv layers and max pooling for Atari frame processing', 'summarize the Models dict mapping actor_critic key to Model_ActorCritic and ActorCritic classes']
```

Usage

```
{'build_actor_critic_model': 'build an Atari actor-critic model with a CNN trunk and policy and value branches', 'create_model_init': 'create a Model_ActorCritic instance by passing args with params hist_len and num_action', 'run_forward_pass': 'run a forward pass on state dict x to get policy pi and value V outputs', 'review_cnn_trunk': 'review the CNN trunk with four conv layers and max pooling for Atari frame processing', 'summarize_models_dict': 'summarize the Models dict mapping actor_critic key to Model_ActorCritic and ActorCritic classes'}
```

