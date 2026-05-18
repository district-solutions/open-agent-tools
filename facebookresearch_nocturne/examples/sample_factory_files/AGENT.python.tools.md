# Agent Python Tools

- repo: facebookresearch/nocturne
- repo_uri: https://github.com/facebookresearch/nocturne

## File: facebookresearch_nocturne/examples/sample_factory_files/run_sample_factory.py

Prompts

```
['run the sample factory RL training script with APPO algorithm and hydra config', 'create a SampleFactoryEnv wrapper to convert nocturne environment dicts to sample factory list format', 'register the custom multi-agent environment and custom encoder with sample factory', 'build a CustomEncoder MLP network for encoding observations in the sample factory algorithm', 'review the SampleFactoryEnv step method that converts actions and tracks per-agent rewards and collisions', 'run evaluation of a trained sample factory policy and save rendered episode frames to video', 'run the sample factory visualization script with a config path to generate policy evaluation videos', 'create an actor-critic model from sample factory config and environment observation and action spaces', 'load a trained policy checkpoint using LearnerWorker and apply it to an actor-critic model', 'render environment frames during policy evaluation and save them as MP4 animation files']
```

Usage

```
{'run_sample_factory_training': 'run the sample factory RL training script with APPO algorithm and hydra config', 'create_SampleFactoryEnv_wrapper': 'create a SampleFactoryEnv wrapper to convert nocturne environment dicts to sample factory list format', 'register_custom_components': 'register the custom multi-agent environment and custom encoder with sample factory', 'build_CustomEncoder': 'build a CustomEncoder MLP network for encoding observations in the sample factory algorithm', 'review_SampleFactoryEnv_step': 'review the SampleFactoryEnv step method that converts actions and tracks per-agent rewards and collisions'}
```

## File: facebookresearch_nocturne/examples/sample_factory_files/visualize_sample_factory.py

Prompts

```
['run the sample factory RL training script with APPO algorithm and hydra config', 'create a SampleFactoryEnv wrapper to convert nocturne environment dicts to sample factory list format', 'register the custom multi-agent environment and custom encoder with sample factory', 'build a CustomEncoder MLP network for encoding observations in the sample factory algorithm', 'review the SampleFactoryEnv step method that converts actions and tracks per-agent rewards and collisions', 'run evaluation of a trained sample factory policy and save rendered episode frames to video', 'run the sample factory visualization script with a config path to generate policy evaluation videos', 'create an actor-critic model from sample factory config and environment observation and action spaces', 'load a trained policy checkpoint using LearnerWorker and apply it to an actor-critic model', 'render environment frames during policy evaluation and save them as MP4 animation files']
```

Usage

```
{'run_eval_policy': 'run evaluation of a trained sample factory policy and save rendered episode frames to video', 'run_visualize_cli': 'run the sample factory visualization script with a config path to generate policy evaluation videos', 'create_actor_critic_model': 'create an actor-critic model from sample factory config and environment observation and action spaces', 'load_checkpoint_policy': 'load a trained policy checkpoint using LearnerWorker and apply it to an actor-critic model', 'render_episode_frames': 'render environment frames during policy evaluation and save them as MP4 animation files'}
```

