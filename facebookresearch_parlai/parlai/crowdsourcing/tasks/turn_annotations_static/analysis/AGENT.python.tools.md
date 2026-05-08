# Agent Python Tools

- repo: facebookresearch/parlai
- repo_uri: https://github.com/facebookresearch/parlai

## File: facebookresearch_parlai/parlai/crowdsourcing/tasks/turn_annotations_static/analysis/compile_results.py

Prompts

```
['run TurnAnnotationsStaticResultsCompiler to compile crowdsource turn annotation results from Mephisto data folders into a pandas DataFrame', 'calculate basic inter-annotator agreement statistics across problem buckets for bot utterances annotated by multiple workers', 'compute Fleiss kappa inter-rater reliability statistics for each problem bucket across multiple annotators', 'calculate agreement between crowdsource worker annotations and gold standard annotations for turn-level problem buckets', 'validate HIT data and conversation subtasks to filter out incomplete or malformed crowdsource annotation data']
```

Usage

```
{'compile_turn_annotations_results': 'run TurnAnnotationsStaticResultsCompiler to compile crowdsource turn annotation results from Mephisto data folders into a pandas DataFrame', 'calculate_interannotator_agreement': 'calculate basic inter-annotator agreement statistics across problem buckets for bot utterances annotated by multiple workers', 'calculate_fleiss_kappa': 'compute Fleiss kappa inter-rater reliability statistics for each problem bucket across multiple annotators', 'calculate_agreement_with_gold': 'calculate agreement between crowdsource worker annotations and gold standard annotations for turn-level problem buckets', 'validate_hit_and_subtask': 'validate HIT data and conversation subtasks to filter out incomplete or malformed crowdsource annotation data'}
```

