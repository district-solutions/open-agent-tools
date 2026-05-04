# Agent Python Tools

- repo: facebookresearch/flowmm
- repo_uri: https://github.com/facebookresearch/flowmm

## File: facebookresearch_flowmm/scripts_model/evaluate.py

Prompts

```
['run reconstruction of crystal structures from a model checkpoint using the reconstruct CLI command', 'run generation of new crystal structures from a trained model checkpoint using the generate CLI command', 'run prediction of crystal structures given atom types using the predict CLI command', 'run consolidation of prediction outputs across multiple eval runs into a single consolidated file', 'run reconstruction and generation evaluation metrics computation and log results to wandb', 'run the MaterialsRFM model training loop with Hydra config and PyTorch Lightning trainer', 'build a list of PyTorch Lightning callbacks including EarlyStopping, ModelCheckpoint, and LearningRateMonitor from config', 'run the Hydra main entry point to start training with the default config from conf directory', 'test the trained MaterialsRFM model using the best or last checkpoint via trainer.test', 'review the run function that instantiates datamodule, model, callbacks, WandbLogger, and trainer for training']
```

Usage

```
{'run_reconstruct_crystal_structures': 'run reconstruction of crystal structures from a model checkpoint using the reconstruct CLI command', 'run_generate_crystal_structures': 'run generation of new crystal structures from a trained model checkpoint using the generate CLI command', 'run_predict_crystal_structures': 'run prediction of crystal structures given atom types using the predict CLI command', 'run_consolidate_predictions': 'run consolidation of prediction outputs across multiple eval runs into a single consolidated file', 'run_old_eval_metrics': 'run reconstruction and generation evaluation metrics computation and log results to wandb'}
```

## File: facebookresearch_flowmm/scripts_model/run.py

Prompts

```
['run reconstruction of crystal structures from a model checkpoint using the reconstruct CLI command', 'run generation of new crystal structures from a trained model checkpoint using the generate CLI command', 'run prediction of crystal structures given atom types using the predict CLI command', 'run consolidation of prediction outputs across multiple eval runs into a single consolidated file', 'run reconstruction and generation evaluation metrics computation and log results to wandb', 'run the MaterialsRFM model training loop with Hydra config and PyTorch Lightning trainer', 'build a list of PyTorch Lightning callbacks including EarlyStopping, ModelCheckpoint, and LearningRateMonitor from config', 'run the Hydra main entry point to start training with the default config from conf directory', 'test the trained MaterialsRFM model using the best or last checkpoint via trainer.test', 'review the run function that instantiates datamodule, model, callbacks, WandbLogger, and trainer for training']
```

Usage

```
{'run_materials_rfm_training': 'run the MaterialsRFM model training loop with Hydra config and PyTorch Lightning trainer', 'build_callbacks_for_training': 'build a list of PyTorch Lightning callbacks including EarlyStopping, ModelCheckpoint, and LearningRateMonitor from config', 'run_hydra_main_entry': 'run the Hydra main entry point to start training with the default config from conf directory', 'test_model_with_checkpoint': 'test the trained MaterialsRFM model using the best or last checkpoint via trainer.test', 'review_run_function': 'review the run function that instantiates datamodule, model, callbacks, WandbLogger, and trainer for training'}
```

