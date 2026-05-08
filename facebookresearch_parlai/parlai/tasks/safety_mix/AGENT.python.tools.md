# Agent Python Tools

- repo: facebookresearch/parlai
- repo_uri: https://github.com/facebookresearch/parlai

## File: facebookresearch_parlai/parlai/tasks/safety_mix/agents.py

Prompts

```
['run the SafetyMixTeacher to load and serve safety mix dialogue data for a given troll type', 'run the PosSafetyMixTeacher to load positive safety mix data with pos_ prefixed files', 'run the NegSafetyMixTeacher to load negative safety mix data with neg_ prefixed files', 'review the SafetyMixTeacher init method to understand data loading and troll type validation', 'review the SafetyMixTeacher _load_data_dump method to understand JSONL file parsing and data loading', 'build the safety_mix dataset by downloading single_turn_safety.json and generating troll-type splits for train, valid, and test folds', 'generate a user-based dataset with configurable troll type ratios and noise levels from standard and adversarial safety samples', 'flip labels on a percentage of samples using deterministic MD5 hashing to simulate noisy annotations', 'analyze a dataset to count standard vs adversarial samples, flipped labels, and duplicated text entries', 'save a dataset as JSONL files split into positive and negative classes for balanced two-class training']
```

Usage

```
{'run_safety_mix_teacher': 'run the SafetyMixTeacher to load and serve safety mix dialogue data for a given troll type', 'run_pos_safety_mix_teacher': 'run the PosSafetyMixTeacher to load positive safety mix data with pos_ prefixed files', 'run_neg_safety_mix_teacher': 'run the NegSafetyMixTeacher to load negative safety mix data with neg_ prefixed files', 'review_safety_mix_teacher_init': 'review the SafetyMixTeacher init method to understand data loading and troll type validation', 'review_safety_mix_teacher_load_data': 'review the SafetyMixTeacher _load_data_dump method to understand JSONL file parsing and data loading'}
```

## File: facebookresearch_parlai/parlai/tasks/safety_mix/build.py

Prompts

```
['run the SafetyMixTeacher to load and serve safety mix dialogue data for a given troll type', 'run the PosSafetyMixTeacher to load positive safety mix data with pos_ prefixed files', 'run the NegSafetyMixTeacher to load negative safety mix data with neg_ prefixed files', 'review the SafetyMixTeacher init method to understand data loading and troll type validation', 'review the SafetyMixTeacher _load_data_dump method to understand JSONL file parsing and data loading', 'build the safety_mix dataset by downloading single_turn_safety.json and generating troll-type splits for train, valid, and test folds', 'generate a user-based dataset with configurable troll type ratios and noise levels from standard and adversarial safety samples', 'flip labels on a percentage of samples using deterministic MD5 hashing to simulate noisy annotations', 'analyze a dataset to count standard vs adversarial samples, flipped labels, and duplicated text entries', 'save a dataset as JSONL files split into positive and negative classes for balanced two-class training']
```

Usage

```
{'build_safety_mix_dataset': 'build the safety_mix dataset by downloading single_turn_safety.json and generating troll-type splits for train, valid, and test folds', 'generate_user_based_dataset': 'generate a user-based dataset with configurable troll type ratios and noise levels from standard and adversarial safety samples', 'flip_labels': 'flip labels on a percentage of samples using deterministic MD5 hashing to simulate noisy annotations', 'analysis_dataset': 'analyze a dataset to count standard vs adversarial samples, flipped labels, and duplicated text entries', 'save_dataset_for_two_class': 'save a dataset as JSONL files split into positive and negative classes for balanced two-class training'}
```

