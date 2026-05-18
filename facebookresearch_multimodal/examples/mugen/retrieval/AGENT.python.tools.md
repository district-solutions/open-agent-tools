# Agent Python Tools

- repo: facebookresearch/multimodal
- repo_uri: https://github.com/facebookresearch/multimodal

## File: facebookresearch_multimodal/examples/mugen/retrieval/eval.py

Prompts

```
['run the VideoCLIP retrieval evaluation using a YAML config file and model checkpoint', 'run get_yaml_config to load and instantiate a YAML configuration from CLI arguments', 'test a VideoCLIPLightningModule checkpoint against the MUGEN test dataloader using PyTorch Lightning', 'review the evaluate function that sets up MUGENDataModule, loads a VideoCLIP checkpoint, and runs trainer.test', 'refactor get_yaml_config to support additional config sources beyond OmegaConf CLI arguments', 'build a VideoCLIP Lightning module with configurable logit scale, learning rate, and recall k values', 'run a training step that computes contrastive loss between text and video embeddings', 'run a validation step that computes contrastive loss and logs validation metrics', 'compute recall at k for video-to-text and text-to-video retrieval using similarity matrix', 'configure an AdamW optimizer with specified learning rate and weight decay parameters', 'run the VideoCLIP training loop using a YAML config file passed via CLI', 'review the train function that sets up MUGENDataModule, VideoCLIPLightningModule, and PyTorch Lightning Trainer', 'review the get_yaml_config function that parses CLI args and instantiates a YAML config with OmegaConf', 'refactor the train function to support additional callbacks or custom checkpoint strategies', 'create a MUGEN video-text CLIP model with pretrained DistilBERT text encoder and S3D video encoder', 'create a DistilBERT-based TextEncoder to encode tokenized text into CLS token hidden state representations', 'create an S3D-based VideoEncoder to encode video tensors into feature embeddings before the classifier layer', 'create a Projection MLP layer to project embeddings to a fixed 256-dimensional output space with dropout', 'build an attention mask tensor from input token IDs by comparing against the padding value']
```

Usage

```
{'run_evaluation': 'run the VideoCLIP retrieval evaluation using a YAML config file and model checkpoint', 'run_get_yaml_config': 'run get_yaml_config to load and instantiate a YAML configuration from CLI arguments', 'test_VideoCLIPLightningModule': 'test a VideoCLIPLightningModule checkpoint against the MUGEN test dataloader using PyTorch Lightning', 'review_evaluate': 'review the evaluate function that sets up MUGENDataModule, loads a VideoCLIP checkpoint, and runs trainer.test', 'refactor_get_yaml_config': 'refactor get_yaml_config to support additional config sources beyond OmegaConf CLI arguments'}
```

## File: facebookresearch_multimodal/examples/mugen/retrieval/model.py

Prompts

```
['run the VideoCLIP retrieval evaluation using a YAML config file and model checkpoint', 'run get_yaml_config to load and instantiate a YAML configuration from CLI arguments', 'test a VideoCLIPLightningModule checkpoint against the MUGEN test dataloader using PyTorch Lightning', 'review the evaluate function that sets up MUGENDataModule, loads a VideoCLIP checkpoint, and runs trainer.test', 'refactor get_yaml_config to support additional config sources beyond OmegaConf CLI arguments', 'build a VideoCLIP Lightning module with configurable logit scale, learning rate, and recall k values', 'run a training step that computes contrastive loss between text and video embeddings', 'run a validation step that computes contrastive loss and logs validation metrics', 'compute recall at k for video-to-text and text-to-video retrieval using similarity matrix', 'configure an AdamW optimizer with specified learning rate and weight decay parameters', 'run the VideoCLIP training loop using a YAML config file passed via CLI', 'review the train function that sets up MUGENDataModule, VideoCLIPLightningModule, and PyTorch Lightning Trainer', 'review the get_yaml_config function that parses CLI args and instantiates a YAML config with OmegaConf', 'refactor the train function to support additional callbacks or custom checkpoint strategies', 'create a MUGEN video-text CLIP model with pretrained DistilBERT text encoder and S3D video encoder', 'create a DistilBERT-based TextEncoder to encode tokenized text into CLS token hidden state representations', 'create an S3D-based VideoEncoder to encode video tensors into feature embeddings before the classifier layer', 'create a Projection MLP layer to project embeddings to a fixed 256-dimensional output space with dropout', 'build an attention mask tensor from input token IDs by comparing against the padding value']
```

Usage

```
{'build_VideoCLIPLightningModule': 'build a VideoCLIP Lightning module with configurable logit scale, learning rate, and recall k values', 'run_training_step': 'run a training step that computes contrastive loss between text and video embeddings', 'run_validation_step': 'run a validation step that computes contrastive loss and logs validation metrics', 'compute_recall': 'compute recall at k for video-to-text and text-to-video retrieval using similarity matrix', 'configure_optimizers': 'configure an AdamW optimizer with specified learning rate and weight decay parameters'}
```

## File: facebookresearch_multimodal/examples/mugen/retrieval/train.py

Prompts

```
['run the VideoCLIP retrieval evaluation using a YAML config file and model checkpoint', 'run get_yaml_config to load and instantiate a YAML configuration from CLI arguments', 'test a VideoCLIPLightningModule checkpoint against the MUGEN test dataloader using PyTorch Lightning', 'review the evaluate function that sets up MUGENDataModule, loads a VideoCLIP checkpoint, and runs trainer.test', 'refactor get_yaml_config to support additional config sources beyond OmegaConf CLI arguments', 'build a VideoCLIP Lightning module with configurable logit scale, learning rate, and recall k values', 'run a training step that computes contrastive loss between text and video embeddings', 'run a validation step that computes contrastive loss and logs validation metrics', 'compute recall at k for video-to-text and text-to-video retrieval using similarity matrix', 'configure an AdamW optimizer with specified learning rate and weight decay parameters', 'run the VideoCLIP training loop using a YAML config file passed via CLI', 'review the train function that sets up MUGENDataModule, VideoCLIPLightningModule, and PyTorch Lightning Trainer', 'review the get_yaml_config function that parses CLI args and instantiates a YAML config with OmegaConf', 'refactor the train function to support additional callbacks or custom checkpoint strategies', 'create a MUGEN video-text CLIP model with pretrained DistilBERT text encoder and S3D video encoder', 'create a DistilBERT-based TextEncoder to encode tokenized text into CLS token hidden state representations', 'create an S3D-based VideoEncoder to encode video tensors into feature embeddings before the classifier layer', 'create a Projection MLP layer to project embeddings to a fixed 256-dimensional output space with dropout', 'build an attention mask tensor from input token IDs by comparing against the padding value']
```

Usage

```
{'run_train': 'run the VideoCLIP training loop using a YAML config file passed via CLI', 'run_get_yaml_config': 'load and instantiate a YAML configuration file for VideoCLIP training from CLI arguments', 'review_train': 'review the train function that sets up MUGENDataModule, VideoCLIPLightningModule, and PyTorch Lightning Trainer', 'review_get_yaml_config': 'review the get_yaml_config function that parses CLI args and instantiates a YAML config with OmegaConf', 'refactor_train': 'refactor the train function to support additional callbacks or custom checkpoint strategies'}
```

## File: facebookresearch_multimodal/examples/mugen/retrieval/video_clip.py

Prompts

```
['run the VideoCLIP retrieval evaluation using a YAML config file and model checkpoint', 'run get_yaml_config to load and instantiate a YAML configuration from CLI arguments', 'test a VideoCLIPLightningModule checkpoint against the MUGEN test dataloader using PyTorch Lightning', 'review the evaluate function that sets up MUGENDataModule, loads a VideoCLIP checkpoint, and runs trainer.test', 'refactor get_yaml_config to support additional config sources beyond OmegaConf CLI arguments', 'build a VideoCLIP Lightning module with configurable logit scale, learning rate, and recall k values', 'run a training step that computes contrastive loss between text and video embeddings', 'run a validation step that computes contrastive loss and logs validation metrics', 'compute recall at k for video-to-text and text-to-video retrieval using similarity matrix', 'configure an AdamW optimizer with specified learning rate and weight decay parameters', 'run the VideoCLIP training loop using a YAML config file passed via CLI', 'review the train function that sets up MUGENDataModule, VideoCLIPLightningModule, and PyTorch Lightning Trainer', 'review the get_yaml_config function that parses CLI args and instantiates a YAML config with OmegaConf', 'refactor the train function to support additional callbacks or custom checkpoint strategies', 'create a MUGEN video-text CLIP model with pretrained DistilBERT text encoder and S3D video encoder', 'create a DistilBERT-based TextEncoder to encode tokenized text into CLS token hidden state representations', 'create an S3D-based VideoEncoder to encode video tensors into feature embeddings before the classifier layer', 'create a Projection MLP layer to project embeddings to a fixed 256-dimensional output space with dropout', 'build an attention mask tensor from input token IDs by comparing against the padding value']
```

Usage

```
{'create_videoclip_model': 'create a MUGEN video-text CLIP model with pretrained DistilBERT text encoder and S3D video encoder', 'create_text_encoder': 'create a DistilBERT-based TextEncoder to encode tokenized text into CLS token hidden state representations', 'create_video_encoder': 'create an S3D-based VideoEncoder to encode video tensors into feature embeddings before the classifier layer', 'create_projection_layer': 'create a Projection MLP layer to project embeddings to a fixed 256-dimensional output space with dropout', 'build_attention_mask': 'build an attention mask tensor from input token IDs by comparing against the padding value'}
```

