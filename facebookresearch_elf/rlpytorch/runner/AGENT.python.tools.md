# Agent Python Tools

- repo: facebookresearch/elf
- repo_uri: https://github.com/facebookresearch/elf

## File: facebookresearch_elf/rlpytorch/runner/eval_iters.py

Prompts

```
['create an EvalIters instance to set up evaluation with num_eval games and optional tqdm progress bar', 'run the EvalIters iters generator to loop through evaluation games until num_eval is reached', 'test EvalIters with the tqdm flag enabled to visualize a progress bar during evaluation', 'review the EvalIters class initialization to understand num_eval and tqdm argument configuration', 'summarize how EvalIters uses Stats to track completed games and print a summary at the end', 'run a multi-process reinforcement learning training loop with configurable episodes and minibatches', 'setup a MultiProcessRun instance with GameContext, ModelInterface, and remote initialization callbacks', 'configure multi-process training arguments including num_minibatch, num_episode, num_process, and tqdm progress', 'review the MultiProcessRun _train method that sends batches to SharedData for remote processing', 'summarize the MultiProcessRun main loop that iterates episodes with episode_start and episode_summary hooks', 'run the SingleProcessRun main training loop with episode start and summary callbacks', 'setup a SingleProcessRun instance with a GameContext and optional episode start and summary functions', 'run the SingleProcessRun multithreaded training loop with separate train and actor threads', 'review the SingleProcessRun class and its training loop configuration with num_minibatch and num_episode args', 'refactor the run_multithread method to fix the missing threading import and add proper thread cleanup']
```

Usage

```
{'create_eval_iters': 'create an EvalIters instance to set up evaluation with num_eval games and optional tqdm progress bar', 'run_eval_iters_iters': 'run the EvalIters iters generator to loop through evaluation games until num_eval is reached', 'test_eval_iters_tqdm': 'test EvalIters with the tqdm flag enabled to visualize a progress bar during evaluation', 'review_eval_iters_init': 'review the EvalIters class initialization to understand num_eval and tqdm argument configuration', 'summarize_eval_iters_stats': 'summarize how EvalIters uses Stats to track completed games and print a summary at the end'}
```

## File: facebookresearch_elf/rlpytorch/runner/multi_process.py

Prompts

```
['create an EvalIters instance to set up evaluation with num_eval games and optional tqdm progress bar', 'run the EvalIters iters generator to loop through evaluation games until num_eval is reached', 'test EvalIters with the tqdm flag enabled to visualize a progress bar during evaluation', 'review the EvalIters class initialization to understand num_eval and tqdm argument configuration', 'summarize how EvalIters uses Stats to track completed games and print a summary at the end', 'run a multi-process reinforcement learning training loop with configurable episodes and minibatches', 'setup a MultiProcessRun instance with GameContext, ModelInterface, and remote initialization callbacks', 'configure multi-process training arguments including num_minibatch, num_episode, num_process, and tqdm progress', 'review the MultiProcessRun _train method that sends batches to SharedData for remote processing', 'summarize the MultiProcessRun main loop that iterates episodes with episode_start and episode_summary hooks', 'run the SingleProcessRun main training loop with episode start and summary callbacks', 'setup a SingleProcessRun instance with a GameContext and optional episode start and summary functions', 'run the SingleProcessRun multithreaded training loop with separate train and actor threads', 'review the SingleProcessRun class and its training loop configuration with num_minibatch and num_episode args', 'refactor the run_multithread method to fix the missing threading import and add proper thread cleanup']
```

Usage

```
{'run_multiprocess_rl_training': 'run a multi-process reinforcement learning training loop with configurable episodes and minibatches', 'setup_multiprocess_run': 'setup a MultiProcessRun instance with GameContext, ModelInterface, and remote initialization callbacks', 'configure_multiprocess_args': 'configure multi-process training arguments including num_minibatch, num_episode, num_process, and tqdm progress', 'review_multiprocess_train_callback': 'review the MultiProcessRun _train method that sends batches to SharedData for remote processing', 'summarize_multiprocess_run_loop': 'summarize the MultiProcessRun main loop that iterates episodes with episode_start and episode_summary hooks'}
```

## File: facebookresearch_elf/rlpytorch/runner/single_process.py

Prompts

```
['create an EvalIters instance to set up evaluation with num_eval games and optional tqdm progress bar', 'run the EvalIters iters generator to loop through evaluation games until num_eval is reached', 'test EvalIters with the tqdm flag enabled to visualize a progress bar during evaluation', 'review the EvalIters class initialization to understand num_eval and tqdm argument configuration', 'summarize how EvalIters uses Stats to track completed games and print a summary at the end', 'run a multi-process reinforcement learning training loop with configurable episodes and minibatches', 'setup a MultiProcessRun instance with GameContext, ModelInterface, and remote initialization callbacks', 'configure multi-process training arguments including num_minibatch, num_episode, num_process, and tqdm progress', 'review the MultiProcessRun _train method that sends batches to SharedData for remote processing', 'summarize the MultiProcessRun main loop that iterates episodes with episode_start and episode_summary hooks', 'run the SingleProcessRun main training loop with episode start and summary callbacks', 'setup a SingleProcessRun instance with a GameContext and optional episode start and summary functions', 'run the SingleProcessRun multithreaded training loop with separate train and actor threads', 'review the SingleProcessRun class and its training loop configuration with num_minibatch and num_episode args', 'refactor the run_multithread method to fix the missing threading import and add proper thread cleanup']
```

Usage

```
{'run_single_process_training': 'run the SingleProcessRun main training loop with episode start and summary callbacks', 'setup_game_context': 'setup a SingleProcessRun instance with a GameContext and optional episode start and summary functions', 'run_multithread_training': 'run the SingleProcessRun multithreaded training loop with separate train and actor threads', 'review_SingleProcessRun_class': 'review the SingleProcessRun class and its training loop configuration with num_minibatch and num_episode args', 'refactor_run_multithread': 'refactor the run_multithread method to fix the missing threading import and add proper thread cleanup'}
```

