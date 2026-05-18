# Agent Python Tools

- repo: facebookresearch/minihack
- repo_uri: https://github.com/facebookresearch/minihack

## File: facebookresearch_minihack/minihack/agent/polybeast/evaluate.py

Prompts

```
['run the evaluate CLI tool to evaluate a pretrained MiniHack model on a Gymnasium environment', 'run get_action to infer the next action from a PolyBeast model given observations and hidden state', 'run load_model to load a pretrained PolyBeast model and its hidden state from a checkpoint directory', 'run eval to evaluate a model over multiple episodes with optional GIF recording and rendering', 'run main to parse CLI arguments and start model evaluation with configurable episodes, seeds, and render mode', 'run the polybeast remote environment server with 4 NetHack environment processes', 'run the polybeast server using a mock environment instead of NetHack', 'create the archive directory under the savedir for experiment data storage', 'serve a single NetHack environment process via a libtorchbeast server', 'run the polybeast server with custom reward and penalty settings for training', 'train a NetHack reinforcement learning agent using PPO with configurable actors and environment steps', 'run inference threads that process actor observations and return policy actions and baselines', 'test a trained PolyBeast checkpoint by copying it with zero learning rate and running evaluation', 'clip environment rewards using tanh scaling, soft asymmetric, or no clipping strategy', 'compute intrinsic exploration rewards using RND or RIDE models with forward and inverse dynamics', 'run the polyhydra main entry point with hydra config flags to start a polybeast training run', 'run the polybeast learner process with the provided OmegaConf flags dictionary', 'run the polybeast environment process with flags after seeding numpy random in the forked process', 'get learner-specific flags by setting the checkpoint path and converting entropy_cost to float', 'get environment-specific flags by setting num_servers from num_actors and clearing the seedspath']
```

Usage

```
{'run_evaluation_cli': 'run the evaluate CLI tool to evaluate a pretrained MiniHack model on a Gymnasium environment', 'run_get_action': 'run get_action to infer the next action from a PolyBeast model given observations and hidden state', 'run_load_model': 'run load_model to load a pretrained PolyBeast model and its hidden state from a checkpoint directory', 'run_eval_episodes': 'run eval to evaluate a model over multiple episodes with optional GIF recording and rendering', 'run_main_parser': 'run main to parse CLI arguments and start model evaluation with configurable episodes, seeds, and render mode'}
```

## File: facebookresearch_minihack/minihack/agent/polybeast/polybeast_env.py

Prompts

```
['run the evaluate CLI tool to evaluate a pretrained MiniHack model on a Gymnasium environment', 'run get_action to infer the next action from a PolyBeast model given observations and hidden state', 'run load_model to load a pretrained PolyBeast model and its hidden state from a checkpoint directory', 'run eval to evaluate a model over multiple episodes with optional GIF recording and rendering', 'run main to parse CLI arguments and start model evaluation with configurable episodes, seeds, and render mode', 'run the polybeast remote environment server with 4 NetHack environment processes', 'run the polybeast server using a mock environment instead of NetHack', 'create the archive directory under the savedir for experiment data storage', 'serve a single NetHack environment process via a libtorchbeast server', 'run the polybeast server with custom reward and penalty settings for training', 'train a NetHack reinforcement learning agent using PPO with configurable actors and environment steps', 'run inference threads that process actor observations and return policy actions and baselines', 'test a trained PolyBeast checkpoint by copying it with zero learning rate and running evaluation', 'clip environment rewards using tanh scaling, soft asymmetric, or no clipping strategy', 'compute intrinsic exploration rewards using RND or RIDE models with forward and inverse dynamics', 'run the polyhydra main entry point with hydra config flags to start a polybeast training run', 'run the polybeast learner process with the provided OmegaConf flags dictionary', 'run the polybeast environment process with flags after seeding numpy random in the forked process', 'get learner-specific flags by setting the checkpoint path and converting entropy_cost to float', 'get environment-specific flags by setting num_servers from num_actors and clearing the seedspath']
```

Usage

```
{'run_polybeast_server': 'run the polybeast remote environment server with 4 NetHack environment processes', 'run_mock_environment': 'run the polybeast server using a mock environment instead of NetHack', 'create_archive_folders': 'create the archive directory under the savedir for experiment data storage', 'serve_environment_process': 'serve a single NetHack environment process via a libtorchbeast server', 'run_custom_reward': 'run the polybeast server with custom reward and penalty settings for training'}
```

## File: facebookresearch_minihack/minihack/agent/polybeast/polybeast_learner.py

Prompts

```
['run the evaluate CLI tool to evaluate a pretrained MiniHack model on a Gymnasium environment', 'run get_action to infer the next action from a PolyBeast model given observations and hidden state', 'run load_model to load a pretrained PolyBeast model and its hidden state from a checkpoint directory', 'run eval to evaluate a model over multiple episodes with optional GIF recording and rendering', 'run main to parse CLI arguments and start model evaluation with configurable episodes, seeds, and render mode', 'run the polybeast remote environment server with 4 NetHack environment processes', 'run the polybeast server using a mock environment instead of NetHack', 'create the archive directory under the savedir for experiment data storage', 'serve a single NetHack environment process via a libtorchbeast server', 'run the polybeast server with custom reward and penalty settings for training', 'train a NetHack reinforcement learning agent using PPO with configurable actors and environment steps', 'run inference threads that process actor observations and return policy actions and baselines', 'test a trained PolyBeast checkpoint by copying it with zero learning rate and running evaluation', 'clip environment rewards using tanh scaling, soft asymmetric, or no clipping strategy', 'compute intrinsic exploration rewards using RND or RIDE models with forward and inverse dynamics', 'run the polyhydra main entry point with hydra config flags to start a polybeast training run', 'run the polybeast learner process with the provided OmegaConf flags dictionary', 'run the polybeast environment process with flags after seeding numpy random in the forked process', 'get learner-specific flags by setting the checkpoint path and converting entropy_cost to float', 'get environment-specific flags by setting num_servers from num_actors and clearing the seedspath']
```

Usage

```
{'train_polybeast_agent': 'train a NetHack reinforcement learning agent using PPO with configurable actors and environment steps', 'run_inference_thread': 'run inference threads that process actor observations and return policy actions and baselines', 'test_trained_model': 'test a trained PolyBeast checkpoint by copying it with zero learning rate and running evaluation', 'clip_rewards': 'clip environment rewards using tanh scaling, soft asymmetric, or no clipping strategy', 'compute_intrinsic_rewards': 'compute intrinsic exploration rewards using RND or RIDE models with forward and inverse dynamics'}
```

## File: facebookresearch_minihack/minihack/agent/polybeast/polyhydra.py

Prompts

```
['run the evaluate CLI tool to evaluate a pretrained MiniHack model on a Gymnasium environment', 'run get_action to infer the next action from a PolyBeast model given observations and hidden state', 'run load_model to load a pretrained PolyBeast model and its hidden state from a checkpoint directory', 'run eval to evaluate a model over multiple episodes with optional GIF recording and rendering', 'run main to parse CLI arguments and start model evaluation with configurable episodes, seeds, and render mode', 'run the polybeast remote environment server with 4 NetHack environment processes', 'run the polybeast server using a mock environment instead of NetHack', 'create the archive directory under the savedir for experiment data storage', 'serve a single NetHack environment process via a libtorchbeast server', 'run the polybeast server with custom reward and penalty settings for training', 'train a NetHack reinforcement learning agent using PPO with configurable actors and environment steps', 'run inference threads that process actor observations and return policy actions and baselines', 'test a trained PolyBeast checkpoint by copying it with zero learning rate and running evaluation', 'clip environment rewards using tanh scaling, soft asymmetric, or no clipping strategy', 'compute intrinsic exploration rewards using RND or RIDE models with forward and inverse dynamics', 'run the polyhydra main entry point with hydra config flags to start a polybeast training run', 'run the polybeast learner process with the provided OmegaConf flags dictionary', 'run the polybeast environment process with flags after seeding numpy random in the forked process', 'get learner-specific flags by setting the checkpoint path and converting entropy_cost to float', 'get environment-specific flags by setting num_servers from num_actors and clearing the seedspath']
```

Usage

```
{'run_polyhydra_main': 'run the polyhydra main entry point with hydra config flags to start a polybeast training run', 'run_learner': 'run the polybeast learner process with the provided OmegaConf flags dictionary', 'run_env': 'run the polybeast environment process with flags after seeding numpy random in the forked process', 'get_learner_flags': 'get learner-specific flags by setting the checkpoint path and converting entropy_cost to float', 'get_environment_flags': 'get environment-specific flags by setting num_servers from num_actors and clearing the seedspath'}
```

