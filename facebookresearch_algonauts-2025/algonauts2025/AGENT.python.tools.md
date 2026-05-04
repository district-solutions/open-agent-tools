# Agent Python Tools

- repo: facebookresearch/algonauts-2025
- repo_uri: https://github.com/facebookresearch/algonauts-2025

## File: facebookresearch_algonauts-2025/algonauts2025/callbacks.py

Prompts

```
['create a JitterWindows callback to add random jitter to training segment start times and durations', 'use the JitterWindows on_train_epoch_start method to regenerate strided window segments with jitter applied', 'create a Benchmark callback to collect and save model predictions during test evaluation', 'use the Benchmark on_test_batch_end method to aggregate predictions by subject and chunk', 'use the Benchmark on_test_epoch_end method to save predictions as a zipped submission file', 'run the Experiment to train an fMRI brain encoding model with text, audio, and video features', 'build train, val, and test DataLoaders from a Data config with multimodal fMRI study events', 'compute per-region Pearson correlation between predicted and true fMRI activations across a DataLoader', 'fit the BrainModule on training and validation DataLoaders using the Lightning trainer with SWA and early stopping', 'test the trained BrainModule on a test DataLoader and log results to the experiment folder', 'build an FmriEncoder model from FmriEncoderConfig with feature dimensions and output timesteps', 'create an FmriEncoderConfig with feature aggregation, layer aggregation, and modality dropout settings', 'run the FmriEncoder forward pass on a SegmentData batch to get predicted outputs', 'review the FmriEncoder aggregate_features method that projects and combines multi-modal fMRI features', 'refactor the FmriEncoder transformer_forward method to add time and subject embeddings before encoding', 'build a PyTorch Lightning BrainModule with a model, loss function, optimizer config, and metrics dictionary', 'run a training step on fMRI segment data batches using the BrainModule training_step method', 'run a validation step on fMRI segment data batches using the BrainModule validation_step method', 'run a test step on fMRI segment data batches using the BrainModule test_step method', 'review the BrainModule configure_optimizers method that builds an optimizer from unfrozen model parameters']
```

Usage

```
{'create_JitterWindows_callback': 'create a JitterWindows callback to add random jitter to training segment start times and durations', 'use_JitterWindows_on_train_epoch_start': 'use the JitterWindows on_train_epoch_start method to regenerate strided window segments with jitter applied', 'create_Benchmark_callback': 'create a Benchmark callback to collect and save model predictions during test evaluation', 'use_Benchmark_on_test_batch_end': 'use the Benchmark on_test_batch_end method to aggregate predictions by subject and chunk', 'use_Benchmark_on_test_epoch_end': 'use the Benchmark on_test_epoch_end method to save predictions as a zipped submission file'}
```

## File: facebookresearch_algonauts-2025/algonauts2025/main.py

Prompts

```
['create a JitterWindows callback to add random jitter to training segment start times and durations', 'use the JitterWindows on_train_epoch_start method to regenerate strided window segments with jitter applied', 'create a Benchmark callback to collect and save model predictions during test evaluation', 'use the Benchmark on_test_batch_end method to aggregate predictions by subject and chunk', 'use the Benchmark on_test_epoch_end method to save predictions as a zipped submission file', 'run the Experiment to train an fMRI brain encoding model with text, audio, and video features', 'build train, val, and test DataLoaders from a Data config with multimodal fMRI study events', 'compute per-region Pearson correlation between predicted and true fMRI activations across a DataLoader', 'fit the BrainModule on training and validation DataLoaders using the Lightning trainer with SWA and early stopping', 'test the trained BrainModule on a test DataLoader and log results to the experiment folder', 'build an FmriEncoder model from FmriEncoderConfig with feature dimensions and output timesteps', 'create an FmriEncoderConfig with feature aggregation, layer aggregation, and modality dropout settings', 'run the FmriEncoder forward pass on a SegmentData batch to get predicted outputs', 'review the FmriEncoder aggregate_features method that projects and combines multi-modal fMRI features', 'refactor the FmriEncoder transformer_forward method to add time and subject embeddings before encoding', 'build a PyTorch Lightning BrainModule with a model, loss function, optimizer config, and metrics dictionary', 'run a training step on fMRI segment data batches using the BrainModule training_step method', 'run a validation step on fMRI segment data batches using the BrainModule validation_step method', 'run a test step on fMRI segment data batches using the BrainModule test_step method', 'review the BrainModule configure_optimizers method that builds an optimizer from unfrozen model parameters']
```

Usage

```
{'run_experiment': 'run the Experiment to train an fMRI brain encoding model with text, audio, and video features', 'build_dataloaders': 'build train, val, and test DataLoaders from a Data config with multimodal fMRI study events', 'compute_multidim_pearson': 'compute per-region Pearson correlation between predicted and true fMRI activations across a DataLoader', 'fit_brain_model': 'fit the BrainModule on training and validation DataLoaders using the Lightning trainer with SWA and early stopping', 'test_brain_model': 'test the trained BrainModule on a test DataLoader and log results to the experiment folder'}
```

## File: facebookresearch_algonauts-2025/algonauts2025/model.py

Prompts

```
['create a JitterWindows callback to add random jitter to training segment start times and durations', 'use the JitterWindows on_train_epoch_start method to regenerate strided window segments with jitter applied', 'create a Benchmark callback to collect and save model predictions during test evaluation', 'use the Benchmark on_test_batch_end method to aggregate predictions by subject and chunk', 'use the Benchmark on_test_epoch_end method to save predictions as a zipped submission file', 'run the Experiment to train an fMRI brain encoding model with text, audio, and video features', 'build train, val, and test DataLoaders from a Data config with multimodal fMRI study events', 'compute per-region Pearson correlation between predicted and true fMRI activations across a DataLoader', 'fit the BrainModule on training and validation DataLoaders using the Lightning trainer with SWA and early stopping', 'test the trained BrainModule on a test DataLoader and log results to the experiment folder', 'build an FmriEncoder model from FmriEncoderConfig with feature dimensions and output timesteps', 'create an FmriEncoderConfig with feature aggregation, layer aggregation, and modality dropout settings', 'run the FmriEncoder forward pass on a SegmentData batch to get predicted outputs', 'review the FmriEncoder aggregate_features method that projects and combines multi-modal fMRI features', 'refactor the FmriEncoder transformer_forward method to add time and subject embeddings before encoding', 'build a PyTorch Lightning BrainModule with a model, loss function, optimizer config, and metrics dictionary', 'run a training step on fMRI segment data batches using the BrainModule training_step method', 'run a validation step on fMRI segment data batches using the BrainModule validation_step method', 'run a test step on fMRI segment data batches using the BrainModule test_step method', 'review the BrainModule configure_optimizers method that builds an optimizer from unfrozen model parameters']
```

Usage

```
{'build_fmri_encoder': 'build an FmriEncoder model from FmriEncoderConfig with feature dimensions and output timesteps', 'create_fmri_encoder_config': 'create an FmriEncoderConfig with feature aggregation, layer aggregation, and modality dropout settings', 'run_fmri_encoder_forward': 'run the FmriEncoder forward pass on a SegmentData batch to get predicted outputs', 'review_aggregate_features': 'review the FmriEncoder aggregate_features method that projects and combines multi-modal fMRI features', 'refactor_transformer_forward': 'refactor the FmriEncoder transformer_forward method to add time and subject embeddings before encoding'}
```

## File: facebookresearch_algonauts-2025/algonauts2025/pl_module.py

Prompts

```
['create a JitterWindows callback to add random jitter to training segment start times and durations', 'use the JitterWindows on_train_epoch_start method to regenerate strided window segments with jitter applied', 'create a Benchmark callback to collect and save model predictions during test evaluation', 'use the Benchmark on_test_batch_end method to aggregate predictions by subject and chunk', 'use the Benchmark on_test_epoch_end method to save predictions as a zipped submission file', 'run the Experiment to train an fMRI brain encoding model with text, audio, and video features', 'build train, val, and test DataLoaders from a Data config with multimodal fMRI study events', 'compute per-region Pearson correlation between predicted and true fMRI activations across a DataLoader', 'fit the BrainModule on training and validation DataLoaders using the Lightning trainer with SWA and early stopping', 'test the trained BrainModule on a test DataLoader and log results to the experiment folder', 'build an FmriEncoder model from FmriEncoderConfig with feature dimensions and output timesteps', 'create an FmriEncoderConfig with feature aggregation, layer aggregation, and modality dropout settings', 'run the FmriEncoder forward pass on a SegmentData batch to get predicted outputs', 'review the FmriEncoder aggregate_features method that projects and combines multi-modal fMRI features', 'refactor the FmriEncoder transformer_forward method to add time and subject embeddings before encoding', 'build a PyTorch Lightning BrainModule with a model, loss function, optimizer config, and metrics dictionary', 'run a training step on fMRI segment data batches using the BrainModule training_step method', 'run a validation step on fMRI segment data batches using the BrainModule validation_step method', 'run a test step on fMRI segment data batches using the BrainModule test_step method', 'review the BrainModule configure_optimizers method that builds an optimizer from unfrozen model parameters']
```

Usage

```
{'build_BrainModule': 'build a PyTorch Lightning BrainModule with a model, loss function, optimizer config, and metrics dictionary', 'run_BrainModule_training_step': 'run a training step on fMRI segment data batches using the BrainModule training_step method', 'run_BrainModule_validation_step': 'run a validation step on fMRI segment data batches using the BrainModule validation_step method', 'run_BrainModule_test_step': 'run a test step on fMRI segment data batches using the BrainModule test_step method', 'review_BrainModule_configure_optimizers': 'review the BrainModule configure_optimizers method that builds an optimizer from unfrozen model parameters'}
```

