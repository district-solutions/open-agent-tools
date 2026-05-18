# Agent Python Tools

- repo: facebookresearch/mmf
- repo_uri: https://github.com/facebookresearch/mmf

## File: facebookresearch_mmf/mmf/trainers/base_trainer.py

Prompts

```
['review the BaseTrainer load method that orchestrates device config, datasets, model, optimizer, metrics, and callbacks', 'implement a subclass of BaseTrainer that configures the PyTorch device for GPU or CPU training', 'implement a BaseTrainer subclass method to load a multimodal model from a configuration file', 'implement a BaseTrainer subclass method that runs full training and optimization loops', 'implement a BaseTrainer subclass method that runs inference and generates predictions on validation data', 'build a LightningTrainer instance with a DictConfig to train a PyTorch Lightning model', 'load a model from a checkpoint path or zoo identifier using the load_model method', 'configure ModelCheckpoint callbacks to save training checkpoints at regular intervals', 'train a PyTorch Lightning model using the trainer fit method with a data module', 'get checkpoint file path and metadata from config or zoo identifier using get_checkpoint_data', 'train a multimodal model using MMFTrainer with a DictConfig specifying model, datasets, and training parameters', 'configure checkpoint, early stopping, logistics, and learning rate scheduler callbacks for MMFTrainer training events', 'load and build a multimodal model from config attributes and move it to the specified device', 'run inference on validation or test datasets using MMFTrainer evaluation or prediction loops', 'initialize FP16 gradient scaler for mixed precision training with PyTorch AMP or FairScale ShardedGradScaler']
```

Usage

```
{'review_BaseTrainer_load': 'review the BaseTrainer load method that orchestrates device config, datasets, model, optimizer, metrics, and callbacks', 'implement_BaseTrainer_configure_device': 'implement a subclass of BaseTrainer that configures the PyTorch device for GPU or CPU training', 'implement_BaseTrainer_load_model': 'implement a BaseTrainer subclass method to load a multimodal model from a configuration file', 'implement_BaseTrainer_train': 'implement a BaseTrainer subclass method that runs full training and optimization loops', 'implement_BaseTrainer_inference': 'implement a BaseTrainer subclass method that runs inference and generates predictions on validation data'}
```

## File: facebookresearch_mmf/mmf/trainers/lightning_trainer.py

Prompts

```
['review the BaseTrainer load method that orchestrates device config, datasets, model, optimizer, metrics, and callbacks', 'implement a subclass of BaseTrainer that configures the PyTorch device for GPU or CPU training', 'implement a BaseTrainer subclass method to load a multimodal model from a configuration file', 'implement a BaseTrainer subclass method that runs full training and optimization loops', 'implement a BaseTrainer subclass method that runs inference and generates predictions on validation data', 'build a LightningTrainer instance with a DictConfig to train a PyTorch Lightning model', 'load a model from a checkpoint path or zoo identifier using the load_model method', 'configure ModelCheckpoint callbacks to save training checkpoints at regular intervals', 'train a PyTorch Lightning model using the trainer fit method with a data module', 'get checkpoint file path and metadata from config or zoo identifier using get_checkpoint_data', 'train a multimodal model using MMFTrainer with a DictConfig specifying model, datasets, and training parameters', 'configure checkpoint, early stopping, logistics, and learning rate scheduler callbacks for MMFTrainer training events', 'load and build a multimodal model from config attributes and move it to the specified device', 'run inference on validation or test datasets using MMFTrainer evaluation or prediction loops', 'initialize FP16 gradient scaler for mixed precision training with PyTorch AMP or FairScale ShardedGradScaler']
```

Usage

```
{'build_lightning_trainer': 'build a LightningTrainer instance with a DictConfig to train a PyTorch Lightning model', 'load_model_from_checkpoint': 'load a model from a checkpoint path or zoo identifier using the load_model method', 'configure_checkpoint_callbacks': 'configure ModelCheckpoint callbacks to save training checkpoints at regular intervals', 'train_lightning_model': 'train a PyTorch Lightning model using the trainer fit method with a data module', 'get_checkpoint_data': 'get checkpoint file path and metadata from config or zoo identifier using get_checkpoint_data'}
```

## File: facebookresearch_mmf/mmf/trainers/mmf_trainer.py

Prompts

```
['review the BaseTrainer load method that orchestrates device config, datasets, model, optimizer, metrics, and callbacks', 'implement a subclass of BaseTrainer that configures the PyTorch device for GPU or CPU training', 'implement a BaseTrainer subclass method to load a multimodal model from a configuration file', 'implement a BaseTrainer subclass method that runs full training and optimization loops', 'implement a BaseTrainer subclass method that runs inference and generates predictions on validation data', 'build a LightningTrainer instance with a DictConfig to train a PyTorch Lightning model', 'load a model from a checkpoint path or zoo identifier using the load_model method', 'configure ModelCheckpoint callbacks to save training checkpoints at regular intervals', 'train a PyTorch Lightning model using the trainer fit method with a data module', 'get checkpoint file path and metadata from config or zoo identifier using get_checkpoint_data', 'train a multimodal model using MMFTrainer with a DictConfig specifying model, datasets, and training parameters', 'configure checkpoint, early stopping, logistics, and learning rate scheduler callbacks for MMFTrainer training events', 'load and build a multimodal model from config attributes and move it to the specified device', 'run inference on validation or test datasets using MMFTrainer evaluation or prediction loops', 'initialize FP16 gradient scaler for mixed precision training with PyTorch AMP or FairScale ShardedGradScaler']
```

Usage

```
{'train_MMFTrainer': 'train a multimodal model using MMFTrainer with a DictConfig specifying model, datasets, and training parameters', 'configure_callbacks_MMFTrainer': 'configure checkpoint, early stopping, logistics, and learning rate scheduler callbacks for MMFTrainer training events', 'load_model_MMFTrainer': 'load and build a multimodal model from config attributes and move it to the specified device', 'inference_MMFTrainer': 'run inference on validation or test datasets using MMFTrainer evaluation or prediction loops', 'load_fp16_scaler_MMFTrainer': 'initialize FP16 gradient scaler for mixed precision training with PyTorch AMP or FairScale ShardedGradScaler'}
```

