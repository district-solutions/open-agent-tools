# Agent Python Tools

- repo: huggingface/diffusers
- repo_uri: https://github.com/huggingface/diffusers

## File: huggingface_diffusers/src/diffusers/schedulers/deprecated/scheduling_karras_ve.py

Prompts

```
['create a KarrasVeScheduler instance with custom sigma_min sigma_max s_noise s_churn s_min and s_max parameters', 'set the discrete timesteps and sigma schedule for a KarrasVeScheduler given a number of inference steps', 'add explicit Langevin-like churn noise to a sample tensor to reach a higher noise level sigma_hat', 'predict the previous timestep sample by reversing the SDE using model output sigma_hat sigma_prev and sample_hat', 'correct the predicted sample using a second model output evaluation and average the two derivative estimates', 'create a ScoreSdeVpScheduler instance with custom num_train_timesteps beta_min beta_max and sampling_eps parameters', 'set continuous timesteps for the diffusion chain by calling set_timesteps with num_inference_steps and device', 'predict the sample from the previous timestep by reversing the SDE using step_pred with score x and t', 'review the ScoreSdeVpScheduler step_pred method to understand how it propagates the diffusion process from model outputs', 'summarize the ScoreSdeVpScheduler class which implements a variance preserving stochastic differential equation scheduler for diffusion models']
```

Usage

```
{'create_karras_ve_scheduler': 'create a KarrasVeScheduler instance with custom sigma_min sigma_max s_noise s_churn s_min and s_max parameters', 'set_timesteps_karras_ve': 'set the discrete timesteps and sigma schedule for a KarrasVeScheduler given a number of inference steps', 'add_noise_to_input_karras_ve': 'add explicit Langevin-like churn noise to a sample tensor to reach a higher noise level sigma_hat', 'step_karras_ve': 'predict the previous timestep sample by reversing the SDE using model output sigma_hat sigma_prev and sample_hat', 'step_correct_karras_ve': 'correct the predicted sample using a second model output evaluation and average the two derivative estimates'}
```

## File: huggingface_diffusers/src/diffusers/schedulers/deprecated/scheduling_sde_vp.py

Prompts

```
['create a KarrasVeScheduler instance with custom sigma_min sigma_max s_noise s_churn s_min and s_max parameters', 'set the discrete timesteps and sigma schedule for a KarrasVeScheduler given a number of inference steps', 'add explicit Langevin-like churn noise to a sample tensor to reach a higher noise level sigma_hat', 'predict the previous timestep sample by reversing the SDE using model output sigma_hat sigma_prev and sample_hat', 'correct the predicted sample using a second model output evaluation and average the two derivative estimates', 'create a ScoreSdeVpScheduler instance with custom num_train_timesteps beta_min beta_max and sampling_eps parameters', 'set continuous timesteps for the diffusion chain by calling set_timesteps with num_inference_steps and device', 'predict the sample from the previous timestep by reversing the SDE using step_pred with score x and t', 'review the ScoreSdeVpScheduler step_pred method to understand how it propagates the diffusion process from model outputs', 'summarize the ScoreSdeVpScheduler class which implements a variance preserving stochastic differential equation scheduler for diffusion models']
```

Usage

```
{'create_ScoreSdeVpScheduler': 'create a ScoreSdeVpScheduler instance with custom num_train_timesteps beta_min beta_max and sampling_eps parameters', 'set_timesteps_ScoreSdeVpScheduler': 'set continuous timesteps for the diffusion chain by calling set_timesteps with num_inference_steps and device', 'step_pred_ScoreSdeVpScheduler': 'predict the sample from the previous timestep by reversing the SDE using step_pred with score x and t', 'review_ScoreSdeVpScheduler_step_pred': 'review the ScoreSdeVpScheduler step_pred method to understand how it propagates the diffusion process from model outputs', 'summarize_ScoreSdeVpScheduler': 'summarize the ScoreSdeVpScheduler class which implements a variance preserving stochastic differential equation scheduler for diffusion models'}
```

