# Agent Python Tools

- repo: facebookresearch/collaborative-reasoner
- repo_uri: https://github.com/facebookresearch/collaborative-reasoner

## File: facebookresearch_collaborative-reasoner/lightning_modules/models/tree_sampling_utils.py

Prompts

```
['run a tree-search conversation between teacher and student agents with beam expansion and diversity sampling', 'run a single-path conversation simulation between teacher and student agents with rater evaluation', 'create a beam selection that picks conversations by extracted belief diversity across candidates', 'create a random conversation picker with optional stratified sampling by turn correctness', 'create a beam shrinking function that reduces expanded candidates back to the target beam size', 'run a PyTorch Lightning module that orchestrates teacher-student interactive reasoning conversations with async batching', 'run an async tree search interaction between teacher and student models with configurable expansion size', 'run batched async teacher-student interactions with progress tracking and JSONL output saving', 'run a thread-safe function to save a list of dictionaries to a JSONL file in write or append mode', 'run a validation step that processes batches of init prompts through the teacher-student interactive model']
```

Usage

```
{'run_ts_interaction_with_expansion': 'run a tree-search conversation between teacher and student agents with beam expansion and diversity sampling', 'run_ts_interaction_single': 'run a single-path conversation simulation between teacher and student agents with rater evaluation', 'create_pick_by_diversity': 'create a beam selection that picks conversations by extracted belief diversity across candidates', 'create_rand_pick_one': 'create a random conversation picker with optional stratified sampling by turn correctness', 'create_shrink_beam': 'create a beam shrinking function that reduces expanded candidates back to the target beam size'}
```

## File: facebookresearch_collaborative-reasoner/lightning_modules/models/ts_interactive_model.py

Prompts

```
['run a tree-search conversation between teacher and student agents with beam expansion and diversity sampling', 'run a single-path conversation simulation between teacher and student agents with rater evaluation', 'create a beam selection that picks conversations by extracted belief diversity across candidates', 'create a random conversation picker with optional stratified sampling by turn correctness', 'create a beam shrinking function that reduces expanded candidates back to the target beam size', 'run a PyTorch Lightning module that orchestrates teacher-student interactive reasoning conversations with async batching', 'run an async tree search interaction between teacher and student models with configurable expansion size', 'run batched async teacher-student interactions with progress tracking and JSONL output saving', 'run a thread-safe function to save a list of dictionaries to a JSONL file in write or append mode', 'run a validation step that processes batches of init prompts through the teacher-student interactive model']
```

Usage

```
{'run_TSInteractiveModel': 'run a PyTorch Lightning module that orchestrates teacher-student interactive reasoning conversations with async batching', 'run_ts_interaction': 'run an async tree search interaction between teacher and student models with configurable expansion size', 'run_batch_ts_interaction': 'run batched async teacher-student interactions with progress tracking and JSONL output saving', 'run_save_to_jsonl': 'run a thread-safe function to save a list of dictionaries to a JSONL file in write or append mode', 'run_validation_step': 'run a validation step that processes batches of init prompts through the teacher-student interactive model'}
```

