# Agent Python Tools

- repo: facebookresearch/parlai
- repo_uri: https://github.com/facebookresearch/parlai

## File: facebookresearch_parlai/parlai/tasks/bot_adversarial_dialogue/agents.py

Prompts

```
['run the BotAdversarialDialogueTeacher to load and serve bot adversarial dialogue data with configurable speaker and safety filters', 'run the HumanSafetyEvaluationTeacher to evaluate human safety labels on bot adversarial dialogues with optional dialogue flattening', 'run the HumanNonadvSafetyEvaluationTeacher to evaluate safety labels on non-adversarial dialogue data', 'run the FilterWantToTalkAboutLabelsMutator to filter out episodes ending with do you want to talk about utterances', 'review the BotAdversarialDialogueTeacher _setup_data method to understand how dialogue data is parsed, filtered by speaker and safety mix, and truncated', 'build the bot adversarial dialogue datasets by downloading and extracting them to the data path', 'build the human safety evaluation testset by downloading and extracting it to the data path', 'build the human non-adversarial safety evaluation testset by downloading and extracting it to the data path', 'build data from a given path by downloading files and marking the version as done', 'get the file path to the adversarial dialogue datasets folder under the given data path']
```

Usage

```
{'run_BotAdversarialDialogueTeacher': 'run the BotAdversarialDialogueTeacher to load and serve bot adversarial dialogue data with configurable speaker and safety filters', 'run_HumanSafetyEvaluationTeacher': 'run the HumanSafetyEvaluationTeacher to evaluate human safety labels on bot adversarial dialogues with optional dialogue flattening', 'run_HumanNonadvSafetyEvaluationTeacher': 'run the HumanNonadvSafetyEvaluationTeacher to evaluate safety labels on non-adversarial dialogue data', 'run_FilterWantToTalkAboutLabelsMutator': 'run the FilterWantToTalkAboutLabelsMutator to filter out episodes ending with do you want to talk about utterances', 'review_BotAdversarialDialogueTeacher_setup_data': 'review the BotAdversarialDialogueTeacher _setup_data method to understand how dialogue data is parsed, filtered by speaker and safety mix, and truncated'}
```

## File: facebookresearch_parlai/parlai/tasks/bot_adversarial_dialogue/build.py

Prompts

```
['run the BotAdversarialDialogueTeacher to load and serve bot adversarial dialogue data with configurable speaker and safety filters', 'run the HumanSafetyEvaluationTeacher to evaluate human safety labels on bot adversarial dialogues with optional dialogue flattening', 'run the HumanNonadvSafetyEvaluationTeacher to evaluate safety labels on non-adversarial dialogue data', 'run the FilterWantToTalkAboutLabelsMutator to filter out episodes ending with do you want to talk about utterances', 'review the BotAdversarialDialogueTeacher _setup_data method to understand how dialogue data is parsed, filtered by speaker and safety mix, and truncated', 'build the bot adversarial dialogue datasets by downloading and extracting them to the data path', 'build the human safety evaluation testset by downloading and extracting it to the data path', 'build the human non-adversarial safety evaluation testset by downloading and extracting it to the data path', 'build data from a given path by downloading files and marking the version as done', 'get the file path to the adversarial dialogue datasets folder under the given data path']
```

Usage

```
{'build_dialogue_datasets': 'build the bot adversarial dialogue datasets by downloading and extracting them to the data path', 'build_human_safety_eval_dataset': 'build the human safety evaluation testset by downloading and extracting it to the data path', 'build_human_nonadv_safety_eval_dataset': 'build the human non-adversarial safety evaluation testset by downloading and extracting it to the data path', 'build_data_from_path': 'build data from a given path by downloading files and marking the version as done', 'get_adversarial_dialogue_folder': 'get the file path to the adversarial dialogue datasets folder under the given data path'}
```

