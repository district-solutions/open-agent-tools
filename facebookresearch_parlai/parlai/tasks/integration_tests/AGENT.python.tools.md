# Agent Python Tools

- repo: facebookresearch/parlai
- repo_uri: https://github.com/facebookresearch/parlai

## File: facebookresearch_parlai/parlai/tasks/integration_tests/agents.py

Prompts

```
['build a CandidateBaseTeacher subclass that overrides build_corpus to generate custom permutation-based training data', 'create a CandidateTeacher that yields dialog examples with label_candidates for ranking model evaluation', 'test the MultiturnCandidateTeacher to verify models correctly use dialog history across multiple turns', 'run a ClassifierTeacher that classifies inputs into one or zero based on the first word digit', 'review the ReverseTeacher to understand how reversed labels test complex generative model behavior']
```

Usage

```
{'build_CandidateBaseTeacher_corpus': 'build a CandidateBaseTeacher subclass that overrides build_corpus to generate custom permutation-based training data', 'create_CandidateTeacher_with_candidates': 'create a CandidateTeacher that yields dialog examples with label_candidates for ranking model evaluation', 'test_MultiturnCandidateTeacher_history': 'test the MultiturnCandidateTeacher to verify models correctly use dialog history across multiple turns', 'run_ClassifierTeacher_binary': 'run a ClassifierTeacher that classifies inputs into one or zero based on the first word digit', 'review_ReverseTeacher_generative': 'review the ReverseTeacher to understand how reversed labels test complex generative model behavior'}
```

