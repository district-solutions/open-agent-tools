# Agent Python Tools

- repo: facebookresearch/parlai
- repo_uri: https://github.com/facebookresearch/parlai

## File: facebookresearch_parlai/projects/cringe/cringe_loss.py

Prompts

```
['build a ContrastiveCrossEntropyLoss module that combines cross entropy and contrastive loss for training with positive and negative feedback labels', 'create a ContrastiveTorchGeneratorAgent subclass to train a generator model using contrastive loss on negative examples', 'review the ContrastiveTransformerGeneratorAgent class that merges contrastive loss with the transformer generator agent', 'refactor the ContrastiveFidAgent to adjust model output handling for BART generation models with encoder state', 'test the ContrastiveBB2Agent build_model method to construct a BlenderBot2 or T5 model with contrastive loss support', 'filter world logs JSONL files by classifier accuracy metric keeping balanced positive and negative examples', 'run the safety filter CLI to filter world logs by classifier accuracy and write balanced output', 'expand directory paths into individual world logs JSONL files for processing', 'deduplicate positive classifier accuracy labels allowing at most two identical generations', 'balance positive and negative filtered data counts and shuffle before writing output', 'build a Parlai IterativeTeacher agent that loads JSON data and filters unsafe tokens from labels', 'run the IterativeTeacher with prepend-classifier-label to inspect classifier labels prepended to generation labels', 'review the IterativeTeacher setup_data method that strips delete tokens and marks examples as LTR', 'refactor the _get_ep_from_turns method to extract classifier labels from turn metrics into episodes', 'test the IterativeTeacher add_cmdline_args method that registers the prepend-classifier-label argument']
```

Usage

```
{'build_contrastive_loss': 'build a ContrastiveCrossEntropyLoss module that combines cross entropy and contrastive loss for training with positive and negative feedback labels', 'create_contrastive_torch_agent': 'create a ContrastiveTorchGeneratorAgent subclass to train a generator model using contrastive loss on negative examples', 'review_contrastive_transformer_agent': 'review the ContrastiveTransformerGeneratorAgent class that merges contrastive loss with the transformer generator agent', 'refactor_contrastive_fid_agent': 'refactor the ContrastiveFidAgent to adjust model output handling for BART generation models with encoder state', 'test_contrastive_bb2_agent': 'test the ContrastiveBB2Agent build_model method to construct a BlenderBot2 or T5 model with contrastive loss support'}
```

## File: facebookresearch_parlai/projects/cringe/safety_filter_world_logs.py

Prompts

```
['build a ContrastiveCrossEntropyLoss module that combines cross entropy and contrastive loss for training with positive and negative feedback labels', 'create a ContrastiveTorchGeneratorAgent subclass to train a generator model using contrastive loss on negative examples', 'review the ContrastiveTransformerGeneratorAgent class that merges contrastive loss with the transformer generator agent', 'refactor the ContrastiveFidAgent to adjust model output handling for BART generation models with encoder state', 'test the ContrastiveBB2Agent build_model method to construct a BlenderBot2 or T5 model with contrastive loss support', 'filter world logs JSONL files by classifier accuracy metric keeping balanced positive and negative examples', 'run the safety filter CLI to filter world logs by classifier accuracy and write balanced output', 'expand directory paths into individual world logs JSONL files for processing', 'deduplicate positive classifier accuracy labels allowing at most two identical generations', 'balance positive and negative filtered data counts and shuffle before writing output', 'build a Parlai IterativeTeacher agent that loads JSON data and filters unsafe tokens from labels', 'run the IterativeTeacher with prepend-classifier-label to inspect classifier labels prepended to generation labels', 'review the IterativeTeacher setup_data method that strips delete tokens and marks examples as LTR', 'refactor the _get_ep_from_turns method to extract classifier labels from turn metrics into episodes', 'test the IterativeTeacher add_cmdline_args method that registers the prepend-classifier-label argument']
```

Usage

```
{'filter_world_logs_classifier_accuracy': 'filter world logs JSONL files by classifier accuracy metric keeping balanced positive and negative examples', 'run_safety_filter_world_logs_cli': 'run the safety filter CLI to filter world logs by classifier accuracy and write balanced output', 'expand_world_logs_directories': 'expand directory paths into individual world logs JSONL files for processing', 'deduplicate_positive_labels': 'deduplicate positive classifier accuracy labels allowing at most two identical generations', 'balance_and_shuffle_filtered_data': 'balance positive and negative filtered data counts and shuffle before writing output'}
```

## File: facebookresearch_parlai/projects/cringe/teachers.py

Prompts

```
['build a ContrastiveCrossEntropyLoss module that combines cross entropy and contrastive loss for training with positive and negative feedback labels', 'create a ContrastiveTorchGeneratorAgent subclass to train a generator model using contrastive loss on negative examples', 'review the ContrastiveTransformerGeneratorAgent class that merges contrastive loss with the transformer generator agent', 'refactor the ContrastiveFidAgent to adjust model output handling for BART generation models with encoder state', 'test the ContrastiveBB2Agent build_model method to construct a BlenderBot2 or T5 model with contrastive loss support', 'filter world logs JSONL files by classifier accuracy metric keeping balanced positive and negative examples', 'run the safety filter CLI to filter world logs by classifier accuracy and write balanced output', 'expand directory paths into individual world logs JSONL files for processing', 'deduplicate positive classifier accuracy labels allowing at most two identical generations', 'balance positive and negative filtered data counts and shuffle before writing output', 'build a Parlai IterativeTeacher agent that loads JSON data and filters unsafe tokens from labels', 'run the IterativeTeacher with prepend-classifier-label to inspect classifier labels prepended to generation labels', 'review the IterativeTeacher setup_data method that strips delete tokens and marks examples as LTR', 'refactor the _get_ep_from_turns method to extract classifier labels from turn metrics into episodes', 'test the IterativeTeacher add_cmdline_args method that registers the prepend-classifier-label argument']
```

Usage

```
{'build_iterative_teacher': 'build a Parlai IterativeTeacher agent that loads JSON data and filters unsafe tokens from labels', 'run_iterative_teacher_with_classifier': 'run the IterativeTeacher with prepend-classifier-label to inspect classifier labels prepended to generation labels', 'review_setup_data': 'review the IterativeTeacher setup_data method that strips delete tokens and marks examples as LTR', 'refactor_get_ep_from_turns': 'refactor the _get_ep_from_turns method to extract classifier labels from turn metrics into episodes', 'test_add_cmdline_args': 'test the IterativeTeacher add_cmdline_args method that registers the prepend-classifier-label argument'}
```

