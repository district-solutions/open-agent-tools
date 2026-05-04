# Agent Python Tools

- repo: facebookresearch/avhubert
- repo_uri: https://github.com/facebookresearch/av_hubert

## File: facebookresearch_avhubert/fairseq/examples/hubert/measure_teacher_quality.py

Prompts

```
['run the CLI tool to measure teacher label quality against phone alignments or reference labels', 'run main_phn_lab to compare hypothesis labels against phone alignments and print quality metrics', 'run main_lab_lab to compare two sets of labels and compute purity and mutual information metrics', 'compute the joint probability distribution between reference and hypothesis label sequences across utterances', 'compute normalized mutual information and entropy from a joint probability matrix', 'update a HubERT checkpoint state dict by renaming label_embs to label_embs_concat and updating task args', 'load a HubERT checkpoint with torch.load, update its state, and save it with torch.save', 'rename the label_embs key in a HubERT model state dict to label_embs_concat', 'set the task argument in a HubERT checkpoint state to hubert_pretraining', 'wrap the labels argument in a HubERT checkpoint state with list bracket formatting']
```

Usage

```
{'run_measure_teacher_quality_cli': 'run the CLI tool to measure teacher label quality against phone alignments or reference labels', 'run_main_phn_lab': 'run main_phn_lab to compare hypothesis labels against phone alignments and print quality metrics', 'run_main_lab_lab': 'run main_lab_lab to compare two sets of labels and compute purity and mutual information metrics', 'comp_joint_prob': 'compute the joint probability distribution between reference and hypothesis label sequences across utterances', 'comp_norm_mutual_info': 'compute normalized mutual information and entropy from a joint probability matrix'}
```

## File: facebookresearch_avhubert/fairseq/examples/hubert/update_ckpt.py

Prompts

```
['run the CLI tool to measure teacher label quality against phone alignments or reference labels', 'run main_phn_lab to compare hypothesis labels against phone alignments and print quality metrics', 'run main_lab_lab to compare two sets of labels and compute purity and mutual information metrics', 'compute the joint probability distribution between reference and hypothesis label sequences across utterances', 'compute normalized mutual information and entropy from a joint probability matrix', 'update a HubERT checkpoint state dict by renaming label_embs to label_embs_concat and updating task args', 'load a HubERT checkpoint with torch.load, update its state, and save it with torch.save', 'rename the label_embs key in a HubERT model state dict to label_embs_concat', 'set the task argument in a HubERT checkpoint state to hubert_pretraining', 'wrap the labels argument in a HubERT checkpoint state with list bracket formatting']
```

Usage

```
{'update_state': 'update a HubERT checkpoint state dict by renaming label_embs to label_embs_concat and updating task args', 'load_and_update_checkpoint': 'load a HubERT checkpoint with torch.load, update its state, and save it with torch.save', 'rename_label_embs': 'rename the label_embs key in a HubERT model state dict to label_embs_concat', 'update_task_arg': 'set the task argument in a HubERT checkpoint state to hubert_pretraining', 'wrap_labels_arg': 'wrap the labels argument in a HubERT checkpoint state with list bracket formatting'}
```

