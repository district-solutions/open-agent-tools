# Agent Python Tools

- repo: facebookresearch/metamotivo
- repo_uri: https://github.com/facebookresearch/metamotivo

## File: facebookresearch_metamotivo/metamotivo/fb_cpr/agent.py

Prompts

```
['create an FBcprAgent instance by passing model and train config kwargs to initialize the agent', 'review the FBcprAgent update method that trains the discriminator, critic, and actor networks in one step', 'test the FBcprAgent update_discriminator method that computes WGAN loss with gradient penalty on expert and train observations', 'refactor the FBcprAgent update_critic method to modify how target Q values are computed with pessimism penalty', 'summarize the FBcprAgent update_actor method that optimizes the actor using discriminator reward and forward map loss', 'build a python module to instantiate FBcprModel with kwargs for obs_dim, action_dim, and device', 'create a CriticArchiConfig dataclass with hidden_dim, model type, hidden_layers, and ensemble_mode settings', 'create a DiscriminatorArchiConfig dataclass with hidden_dim and hidden_layers for discriminator architecture', 'run the FBcprModel critic method with observation, latent z, and action tensors to get Q-value', 'run the FBcprModel discriminator method with observation and latent z tensors to get discriminator output']
```

Usage

```
{'create_FBcprAgent': 'create an FBcprAgent instance by passing model and train config kwargs to initialize the agent', 'review_FBcprAgent_update': 'review the FBcprAgent update method that trains the discriminator, critic, and actor networks in one step', 'test_FBcprAgent_update_discriminator': 'test the FBcprAgent update_discriminator method that computes WGAN loss with gradient penalty on expert and train observations', 'refactor_FBcprAgent_update_critic': 'refactor the FBcprAgent update_critic method to modify how target Q values are computed with pessimism penalty', 'summarize_FBcprAgent_update_actor': 'summarize the FBcprAgent update_actor method that optimizes the actor using discriminator reward and forward map loss'}
```

## File: facebookresearch_metamotivo/metamotivo/fb_cpr/model.py

Prompts

```
['create an FBcprAgent instance by passing model and train config kwargs to initialize the agent', 'review the FBcprAgent update method that trains the discriminator, critic, and actor networks in one step', 'test the FBcprAgent update_discriminator method that computes WGAN loss with gradient penalty on expert and train observations', 'refactor the FBcprAgent update_critic method to modify how target Q values are computed with pessimism penalty', 'summarize the FBcprAgent update_actor method that optimizes the actor using discriminator reward and forward map loss', 'build a python module to instantiate FBcprModel with kwargs for obs_dim, action_dim, and device', 'create a CriticArchiConfig dataclass with hidden_dim, model type, hidden_layers, and ensemble_mode settings', 'create a DiscriminatorArchiConfig dataclass with hidden_dim and hidden_layers for discriminator architecture', 'run the FBcprModel critic method with observation, latent z, and action tensors to get Q-value', 'run the FBcprModel discriminator method with observation and latent z tensors to get discriminator output']
```

Usage

```
{'build_FBcprModel': 'build a python module to instantiate FBcprModel with kwargs for obs_dim, action_dim, and device', 'create_CriticArchiConfig': 'create a CriticArchiConfig dataclass with hidden_dim, model type, hidden_layers, and ensemble_mode settings', 'create_DiscriminatorArchiConfig': 'create a DiscriminatorArchiConfig dataclass with hidden_dim and hidden_layers for discriminator architecture', 'run_FBcprModel_critic': 'run the FBcprModel critic method with observation, latent z, and action tensors to get Q-value', 'run_FBcprModel_discriminator': 'run the FBcprModel discriminator method with observation and latent z tensors to get discriminator output'}
```

