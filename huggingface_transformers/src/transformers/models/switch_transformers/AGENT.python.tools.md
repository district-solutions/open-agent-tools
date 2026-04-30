# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/switch_transformers/convert_big_switch.py

Prompts

```
['run the CLI to convert a BigSwitch T5X checkpoint to PyTorch sharded weights', 'build a sharded PyTorch checkpoint from a Google BigSwitch T5X checkpoint using shard_on_the_fly', 'rename Flax JAX keys and tensors to PyTorch-compatible weight names and layouts', 'test the sanity check that loads a converted Switch Transformers model and runs generation', 'save a renamed block of PyTorch weights to a sharded checkpoint file', 'convert a SwitchTransformers Flax/FLAX checkpoint to a PyTorch model using the t5x checkpoint loader', 'load Flax checkpoint weights into a PyTorch SwitchTransformers model with automatic key renaming and shape validation', 'rename Flax checkpoint keys to HuggingFace SwitchTransformers PyTorch naming conventions including expert and attention layers', 'convert a Google gin config file into a HuggingFace SwitchTransformersConfig object with expert and layer parameters', 'run the CLI tool to convert a SwitchTransformers t5x Flax checkpoint to a saved PyTorch model directory', 'create a SwitchTransformersModel with encoder-decoder architecture for sequence-to-sequence tasks', 'build a SwitchTransformersForConditionalGeneration model with language modeling head for text generation', 'run SwitchTransformersSparseMLP with top-1 router to route tokens to selected experts', 'test router z-loss computation to encourage small router logits for training stability', 'summarize the load balancing loss function that penalizes unbalanced expert routing', 'build a SwitchTransformersModel encoder-decoder MoE model with configurable sparse layers', 'run SwitchTransformersForConditionalGeneration with labels to compute cross-entropy and router auxiliary losses', 'create a SwitchTransformersEncoderModel to encode input sequences using sparse expert layers', 'test the SwitchTransformersTop1Router to assign tokens to top-1 experts with capacity constraints', 'summarize the SwitchTransformersSparseMLP module that combines a top-1 router with multiple dense expert feed-forward networks']
```

Usage

```
{'run_convert_big_switch_checkpoint': 'run the CLI to convert a BigSwitch T5X checkpoint to PyTorch sharded weights', 'build_sharded_checkpoint_conversion': 'build a sharded PyTorch checkpoint from a Google BigSwitch T5X checkpoint using shard_on_the_fly', 'rename_flax_keys_to_pytorch': 'rename Flax JAX keys and tensors to PyTorch-compatible weight names and layouts', 'test_sanity_check_conversion': 'test the sanity check that loads a converted Switch Transformers model and runs generation', 'save_renamed_block_weights': 'save a renamed block of PyTorch weights to a sharded checkpoint file'}
```

## File: huggingface_transformers/src/transformers/models/switch_transformers/convert_switch_transformers_original_flax_checkpoint_to_pytorch.py

Prompts

```
['run the CLI to convert a BigSwitch T5X checkpoint to PyTorch sharded weights', 'build a sharded PyTorch checkpoint from a Google BigSwitch T5X checkpoint using shard_on_the_fly', 'rename Flax JAX keys and tensors to PyTorch-compatible weight names and layouts', 'test the sanity check that loads a converted Switch Transformers model and runs generation', 'save a renamed block of PyTorch weights to a sharded checkpoint file', 'convert a SwitchTransformers Flax/FLAX checkpoint to a PyTorch model using the t5x checkpoint loader', 'load Flax checkpoint weights into a PyTorch SwitchTransformers model with automatic key renaming and shape validation', 'rename Flax checkpoint keys to HuggingFace SwitchTransformers PyTorch naming conventions including expert and attention layers', 'convert a Google gin config file into a HuggingFace SwitchTransformersConfig object with expert and layer parameters', 'run the CLI tool to convert a SwitchTransformers t5x Flax checkpoint to a saved PyTorch model directory', 'create a SwitchTransformersModel with encoder-decoder architecture for sequence-to-sequence tasks', 'build a SwitchTransformersForConditionalGeneration model with language modeling head for text generation', 'run SwitchTransformersSparseMLP with top-1 router to route tokens to selected experts', 'test router z-loss computation to encourage small router logits for training stability', 'summarize the load balancing loss function that penalizes unbalanced expert routing', 'build a SwitchTransformersModel encoder-decoder MoE model with configurable sparse layers', 'run SwitchTransformersForConditionalGeneration with labels to compute cross-entropy and router auxiliary losses', 'create a SwitchTransformersEncoderModel to encode input sequences using sparse expert layers', 'test the SwitchTransformersTop1Router to assign tokens to top-1 experts with capacity constraints', 'summarize the SwitchTransformersSparseMLP module that combines a top-1 router with multiple dense expert feed-forward networks']
```

Usage

```
{'convert_flax_checkpoint_to_pytorch': 'convert a SwitchTransformers Flax/FLAX checkpoint to a PyTorch model using the t5x checkpoint loader', 'load_flax_weights_in_pytorch_model': 'load Flax checkpoint weights into a PyTorch SwitchTransformers model with automatic key renaming and shape validation', 'rename_keys': 'rename Flax checkpoint keys to HuggingFace SwitchTransformers PyTorch naming conventions including expert and attention layers', 'convert_gin_to_config': 'convert a Google gin config file into a HuggingFace SwitchTransformersConfig object with expert and layer parameters', 'run_convert_cli': 'run the CLI tool to convert a SwitchTransformers t5x Flax checkpoint to a saved PyTorch model directory'}
```

## File: huggingface_transformers/src/transformers/models/switch_transformers/modeling_switch_transformers.py

Prompts

```
['run the CLI to convert a BigSwitch T5X checkpoint to PyTorch sharded weights', 'build a sharded PyTorch checkpoint from a Google BigSwitch T5X checkpoint using shard_on_the_fly', 'rename Flax JAX keys and tensors to PyTorch-compatible weight names and layouts', 'test the sanity check that loads a converted Switch Transformers model and runs generation', 'save a renamed block of PyTorch weights to a sharded checkpoint file', 'convert a SwitchTransformers Flax/FLAX checkpoint to a PyTorch model using the t5x checkpoint loader', 'load Flax checkpoint weights into a PyTorch SwitchTransformers model with automatic key renaming and shape validation', 'rename Flax checkpoint keys to HuggingFace SwitchTransformers PyTorch naming conventions including expert and attention layers', 'convert a Google gin config file into a HuggingFace SwitchTransformersConfig object with expert and layer parameters', 'run the CLI tool to convert a SwitchTransformers t5x Flax checkpoint to a saved PyTorch model directory', 'create a SwitchTransformersModel with encoder-decoder architecture for sequence-to-sequence tasks', 'build a SwitchTransformersForConditionalGeneration model with language modeling head for text generation', 'run SwitchTransformersSparseMLP with top-1 router to route tokens to selected experts', 'test router z-loss computation to encourage small router logits for training stability', 'summarize the load balancing loss function that penalizes unbalanced expert routing', 'build a SwitchTransformersModel encoder-decoder MoE model with configurable sparse layers', 'run SwitchTransformersForConditionalGeneration with labels to compute cross-entropy and router auxiliary losses', 'create a SwitchTransformersEncoderModel to encode input sequences using sparse expert layers', 'test the SwitchTransformersTop1Router to assign tokens to top-1 experts with capacity constraints', 'summarize the SwitchTransformersSparseMLP module that combines a top-1 router with multiple dense expert feed-forward networks']
```

Usage

```
{'create_switch_transformers_model': 'create a SwitchTransformersModel with encoder-decoder architecture for sequence-to-sequence tasks', 'build_conditional_generation': 'build a SwitchTransformersForConditionalGeneration model with language modeling head for text generation', 'run_sparse_mlp_routing': 'run SwitchTransformersSparseMLP with top-1 router to route tokens to selected experts', 'test_router_z_loss': 'test router z-loss computation to encourage small router logits for training stability', 'summarize_load_balancing_loss': 'summarize the load balancing loss function that penalizes unbalanced expert routing'}
```

## File: huggingface_transformers/src/transformers/models/switch_transformers/modular_switch_transformers.py

Prompts

```
['run the CLI to convert a BigSwitch T5X checkpoint to PyTorch sharded weights', 'build a sharded PyTorch checkpoint from a Google BigSwitch T5X checkpoint using shard_on_the_fly', 'rename Flax JAX keys and tensors to PyTorch-compatible weight names and layouts', 'test the sanity check that loads a converted Switch Transformers model and runs generation', 'save a renamed block of PyTorch weights to a sharded checkpoint file', 'convert a SwitchTransformers Flax/FLAX checkpoint to a PyTorch model using the t5x checkpoint loader', 'load Flax checkpoint weights into a PyTorch SwitchTransformers model with automatic key renaming and shape validation', 'rename Flax checkpoint keys to HuggingFace SwitchTransformers PyTorch naming conventions including expert and attention layers', 'convert a Google gin config file into a HuggingFace SwitchTransformersConfig object with expert and layer parameters', 'run the CLI tool to convert a SwitchTransformers t5x Flax checkpoint to a saved PyTorch model directory', 'create a SwitchTransformersModel with encoder-decoder architecture for sequence-to-sequence tasks', 'build a SwitchTransformersForConditionalGeneration model with language modeling head for text generation', 'run SwitchTransformersSparseMLP with top-1 router to route tokens to selected experts', 'test router z-loss computation to encourage small router logits for training stability', 'summarize the load balancing loss function that penalizes unbalanced expert routing', 'build a SwitchTransformersModel encoder-decoder MoE model with configurable sparse layers', 'run SwitchTransformersForConditionalGeneration with labels to compute cross-entropy and router auxiliary losses', 'create a SwitchTransformersEncoderModel to encode input sequences using sparse expert layers', 'test the SwitchTransformersTop1Router to assign tokens to top-1 experts with capacity constraints', 'summarize the SwitchTransformersSparseMLP module that combines a top-1 router with multiple dense expert feed-forward networks']
```

Usage

```
{'build_switch_transformers_model': 'build a SwitchTransformersModel encoder-decoder MoE model with configurable sparse layers', 'run_switch_transformers_conditional_generation': 'run SwitchTransformersForConditionalGeneration with labels to compute cross-entropy and router auxiliary losses', 'create_switch_transformers_encoder': 'create a SwitchTransformersEncoderModel to encode input sequences using sparse expert layers', 'test_switch_transformers_top1_router': 'test the SwitchTransformersTop1Router to assign tokens to top-1 experts with capacity constraints', 'summarize_switch_transformers_sparse_mlp': 'summarize the SwitchTransformersSparseMLP module that combines a top-1 router with multiple dense expert feed-forward networks'}
```

