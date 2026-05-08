# Agent Python Tools

- repo: facebookresearch/largeconceptmodel
- repo_uri: https://github.com/facebookresearch/large_concept_model

## File: facebookresearch_largeconceptmodel/lcm/train/two_tower_diffusion_lcm/criterion.py

Prompts

```
['build a TwoTowerDiffusionCriterion with config and model to compute diffusion-based LCM training loss', 'create a TowerDiffusionLCMCriterionConfig with cf_guidance_probability and step_sampling settings for diffusion training', 'review the sample_noisy_input_and_targets method to understand noise scheduling and target preparation for diffusion', 'refactor the compute_loss method to support alternative loss functions beyond MSE for diffusion training', 'test the DiffusionNextSentFinetuningCriterion for supervised next-sentence prediction with diffusion-based denoising', 'create a TwoTowerDiffusionLCM training config and call prepare_two_tower_diffusion_lcm_trainer to build an LCMTrainer', 'instantiate DiffusionLCMTrainerBuilder with a TwoTowerDiffusionLCMTrainingConfig and call build_trainer to get an LCMTrainer', 'create a TwoTowerDiffusionLCMTrainingConfig with a model config or name and optional criterion settings', 'access the model_loader property on DiffusionLCMTrainerBuilder to get the two tower diffusion LCM model loader', 'configure the TowerDiffusionLCMCriterionConfig on a TwoTowerDiffusionLCMTrainingConfig to customize the training loss']
```

Usage

```
{'build_TwoTowerDiffusionCriterion': 'build a TwoTowerDiffusionCriterion with config and model to compute diffusion-based LCM training loss', 'create_TowerDiffusionLCMCriterionConfig': 'create a TowerDiffusionLCMCriterionConfig with cf_guidance_probability and step_sampling settings for diffusion training', 'review_TwoTowerDiffusionCriterion_sample_noisy_input': 'review the sample_noisy_input_and_targets method to understand noise scheduling and target preparation for diffusion', 'refactor_TwoTowerDiffusionCriterion_compute_loss': 'refactor the compute_loss method to support alternative loss functions beyond MSE for diffusion training', 'test_DiffusionNextSentFinetuningCriterion': 'test the DiffusionNextSentFinetuningCriterion for supervised next-sentence prediction with diffusion-based denoising'}
```

## File: facebookresearch_largeconceptmodel/lcm/train/two_tower_diffusion_lcm/trainer.py

Prompts

```
['build a TwoTowerDiffusionCriterion with config and model to compute diffusion-based LCM training loss', 'create a TowerDiffusionLCMCriterionConfig with cf_guidance_probability and step_sampling settings for diffusion training', 'review the sample_noisy_input_and_targets method to understand noise scheduling and target preparation for diffusion', 'refactor the compute_loss method to support alternative loss functions beyond MSE for diffusion training', 'test the DiffusionNextSentFinetuningCriterion for supervised next-sentence prediction with diffusion-based denoising', 'create a TwoTowerDiffusionLCM training config and call prepare_two_tower_diffusion_lcm_trainer to build an LCMTrainer', 'instantiate DiffusionLCMTrainerBuilder with a TwoTowerDiffusionLCMTrainingConfig and call build_trainer to get an LCMTrainer', 'create a TwoTowerDiffusionLCMTrainingConfig with a model config or name and optional criterion settings', 'access the model_loader property on DiffusionLCMTrainerBuilder to get the two tower diffusion LCM model loader', 'configure the TowerDiffusionLCMCriterionConfig on a TwoTowerDiffusionLCMTrainingConfig to customize the training loss']
```

Usage

```
{'prepare_two_tower_diffusion_lcm_trainer': 'create a TwoTowerDiffusionLCM training config and call prepare_two_tower_diffusion_lcm_trainer to build an LCMTrainer', 'DiffusionLCMTrainerBuilder': 'instantiate DiffusionLCMTrainerBuilder with a TwoTowerDiffusionLCMTrainingConfig and call build_trainer to get an LCMTrainer', 'TwoTowerDiffusionLCMTrainingConfig': 'create a TwoTowerDiffusionLCMTrainingConfig with a model config or name and optional criterion settings', 'DiffusionLCMTrainerBuilder_model_loader': 'access the model_loader property on DiffusionLCMTrainerBuilder to get the two tower diffusion LCM model loader', 'TwoTowerDiffusionLCMTrainingConfig_criterion': 'configure the TowerDiffusionLCMCriterionConfig on a TwoTowerDiffusionLCMTrainingConfig to customize the training loss'}
```

