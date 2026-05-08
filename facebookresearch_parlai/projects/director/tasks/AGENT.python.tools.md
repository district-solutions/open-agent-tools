# Agent Python Tools

- repo: facebookresearch/parlai
- repo_uri: https://github.com/facebookresearch/parlai

## File: facebookresearch_parlai/projects/director/tasks/safety.py

Prompts

```
['create a LeftToRightMutator that breaks episodes into all partial word sequences for LTR training', 'create an EDCLeftToRightMutator that splits utterances into encoder context and decoder labels for EDC models', 'create a SafetyLTRMutator that converts safety labels to pos/neg and generates partial sequences', 'create a ClassifierMetricTeacher that evaluates model responses with an external classifier for safety accuracy', 'create a SafetyRelabelClassesMutator that relabels __ok__ and __notok__ labels to pos and neg']
```

Usage

```
{'create_LTR_mutator': 'create a LeftToRightMutator that breaks episodes into all partial word sequences for LTR training', 'create_EDC_LTR_mutator': 'create an EDCLeftToRightMutator that splits utterances into encoder context and decoder labels for EDC models', 'create_safety_LTR_mutator': 'create a SafetyLTRMutator that converts safety labels to pos/neg and generates partial sequences', 'create_ClassifierMetricTeacher': 'create a ClassifierMetricTeacher that evaluates model responses with an external classifier for safety accuracy', 'create_safety_relabel_mutator': 'create a SafetyRelabelClassesMutator that relabels __ok__ and __notok__ labels to pos and neg'}
```

