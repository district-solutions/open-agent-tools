# Agent Python Tools

- repo: facebookresearch/parlai
- repo_uri: https://github.com/facebookresearch/parlai

## File: facebookresearch_parlai/parlai/tasks/aqua/agents.py

Prompts

```
['run the DefaultTeacher dialog teacher to load and serve AQuA math word problem data', 'run the AQuAReasoningTeacher to get step-by-step reasoning data for AQuA multiple choice math problems', 'run the AQuAStepByStepReasoningTeacher to yield cleaned question, steps, and answer tuples from AQuA data', 'test the setup_data function to verify it yields question-answer pairs and rationale tuples from a JSONL file', 'review the AQuAStepByStepReasoningTeacher extrinsic_step mode that injects a random step from another problem', 'run the build function to download and set up the AQuA dataset from DeepMind', 'download the AQuA dataset zip file from the DeepMind GitHub repository', 'check if the AQuA dataset has already been built at the current version', 'remove an older version of the AQuA dataset directory before rebuilding', 'mark the AQuA dataset directory as built with the current version string']
```

Usage

```
{'run_DefaultTeacher': 'run the DefaultTeacher dialog teacher to load and serve AQuA math word problem data', 'run_AQuAReasoningTeacher': 'run the AQuAReasoningTeacher to get step-by-step reasoning data for AQuA multiple choice math problems', 'run_AQuAStepByStepReasoningTeacher': 'run the AQuAStepByStepReasoningTeacher to yield cleaned question, steps, and answer tuples from AQuA data', 'test_setup_data': 'test the setup_data function to verify it yields question-answer pairs and rationale tuples from a JSONL file', 'review_AQuAStepByStepReasoningTeacher_extrinsic_step': 'review the AQuAStepByStepReasoningTeacher extrinsic_step mode that injects a random step from another problem'}
```

## File: facebookresearch_parlai/parlai/tasks/aqua/build.py

Prompts

```
['run the DefaultTeacher dialog teacher to load and serve AQuA math word problem data', 'run the AQuAReasoningTeacher to get step-by-step reasoning data for AQuA multiple choice math problems', 'run the AQuAStepByStepReasoningTeacher to yield cleaned question, steps, and answer tuples from AQuA data', 'test the setup_data function to verify it yields question-answer pairs and rationale tuples from a JSONL file', 'review the AQuAStepByStepReasoningTeacher extrinsic_step mode that injects a random step from another problem', 'run the build function to download and set up the AQuA dataset from DeepMind', 'download the AQuA dataset zip file from the DeepMind GitHub repository', 'check if the AQuA dataset has already been built at the current version', 'remove an older version of the AQuA dataset directory before rebuilding', 'mark the AQuA dataset directory as built with the current version string']
```

Usage

```
{'build_aqua_dataset': 'run the build function to download and set up the AQuA dataset from DeepMind', 'download_aqua_resources': 'download the AQuA dataset zip file from the DeepMind GitHub repository', 'check_aqua_data_built': 'check if the AQuA dataset has already been built at the current version', 'remove_outdated_aqua_data': 'remove an older version of the AQuA dataset directory before rebuilding', 'mark_aqua_data_done': 'mark the AQuA dataset directory as built with the current version string'}
```

