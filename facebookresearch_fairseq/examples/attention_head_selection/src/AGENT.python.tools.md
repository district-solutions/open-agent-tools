# Agent Python Tools

- repo: facebookresearch/fairseq
- repo_uri: https://github.com/facebookresearch/fairseq

## File: facebookresearch_fairseq/examples/attention_head_selection/src/speech_to_text_head_selection.py

Prompts

```
['build a fairseq task that performs speech-to-text with attention head selection for language or domain tasks', 'create a mapping from source language, target language, and domain names to integer IDs for training subsets', 'run a training step that computes criterion loss plus KL divergence loss for encoder and decoder attention head selection', 'load a speech-to-text dataset with domain metadata from TSV files using language and domain mappings', 'run inference on speech-to-text samples by setting task IDs on encoder and decoder before generating output']
```

Usage

```
{'build_speech_to_text_head_selection_task': 'build a fairseq task that performs speech-to-text with attention head selection for language or domain tasks', 'create_map_task_to_id': 'create a mapping from source language, target language, and domain names to integer IDs for training subsets', 'run_train_step_with_kl_loss': 'run a training step that computes criterion loss plus KL divergence loss for encoder and decoder attention head selection', 'load_dataset_with_domain': 'load a speech-to-text dataset with domain metadata from TSV files using language and domain mappings', 'run_inference_step': 'run inference on speech-to-text samples by setting task IDs on encoder and decoder before generating output'}
```

