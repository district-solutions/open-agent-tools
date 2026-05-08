# Agent Python Tools

- repo: facebookresearch/fairseq
- repo_uri: https://github.com/facebookresearch/fairseq

## File: facebookresearch_fairseq/examples/hubert/measure_teacher_quality.py

Prompts

```
['run the CLI tool to compute label quality metrics like purity and mutual information for HuBERT teacher labels', 'run main_phn_lab to compare hypothesis labels against phone alignments and print quality metrics', 'run main_lab_lab to compare hypothesis labels against reference labels and print quality metrics', 'compute the joint probability matrix between reference and hypothesis label sequences across utterances', 'compute normalized mutual information and entropy from a joint probability matrix', 'compute individual and aggregate purity scores from a joint probability distribution along an axis', 'compute the average segment duration in frames across a list of label sequences', 'read a TSV file of utterance IDs and phone sequences into a dictionary mapping UIDs to phones', 'read label files with optional padding and upsampling, returning a UID-to-labels dictionary', 'run the script to load a HuBERT checkpoint, update its state, and save it', 'summarize the update_state function that renames label_embs to label_embs_concat and updates task args', 'review the update_state function for renaming model keys and modifying checkpoint arguments', 'test the update_state function with a sample HuBERT checkpoint state dictionary', 'refactor the update_state function to accept configurable key names and task values']
```

Usage

```
{'run_measure_teacher_quality_cli': 'run the CLI tool to compute label quality metrics like purity and mutual information for HuBERT teacher labels', 'run_main_phn_lab': 'run main_phn_lab to compare hypothesis labels against phone alignments and print quality metrics', 'run_main_lab_lab': 'run main_lab_lab to compare hypothesis labels against reference labels and print quality metrics', 'comp_joint_prob': 'compute the joint probability matrix between reference and hypothesis label sequences across utterances', 'comp_norm_mutual_info': 'compute normalized mutual information and entropy from a joint probability matrix', 'comp_purity': 'compute individual and aggregate purity scores from a joint probability distribution along an axis', 'comp_avg_seg_dur': 'compute the average segment duration in frames across a list of label sequences', 'read_phn': 'read a TSV file of utterance IDs and phone sequences into a dictionary mapping UIDs to phones', 'read_lab': 'read label files with optional padding and upsampling, returning a UID-to-labels dictionary'}
```

## File: facebookresearch_fairseq/examples/hubert/update_ckpt.py

Prompts

```
['run the CLI tool to compute label quality metrics like purity and mutual information for HuBERT teacher labels', 'run main_phn_lab to compare hypothesis labels against phone alignments and print quality metrics', 'run main_lab_lab to compare hypothesis labels against reference labels and print quality metrics', 'compute the joint probability matrix between reference and hypothesis label sequences across utterances', 'compute normalized mutual information and entropy from a joint probability matrix', 'compute individual and aggregate purity scores from a joint probability distribution along an axis', 'compute the average segment duration in frames across a list of label sequences', 'read a TSV file of utterance IDs and phone sequences into a dictionary mapping UIDs to phones', 'read label files with optional padding and upsampling, returning a UID-to-labels dictionary', 'run the script to load a HuBERT checkpoint, update its state, and save it', 'summarize the update_state function that renames label_embs to label_embs_concat and updates task args', 'review the update_state function for renaming model keys and modifying checkpoint arguments', 'test the update_state function with a sample HuBERT checkpoint state dictionary', 'refactor the update_state function to accept configurable key names and task values']
```

Usage

```
{'run_update_hubert_checkpoint': 'run the script to load a HuBERT checkpoint, update its state, and save it', 'summarize_update_state': 'summarize the update_state function that renames label_embs to label_embs_concat and updates task args', 'review_update_state': 'review the update_state function for renaming model keys and modifying checkpoint arguments', 'test_update_state': 'test the update_state function with a sample HuBERT checkpoint state dictionary', 'refactor_update_state': 'refactor the update_state function to accept configurable key names and task values'}
```

