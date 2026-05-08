# Agent Python Tools

- repo: facebookresearch/fairo
- repo_uri: https://github.com/facebookresearch/fairo

## File: facebookresearch_fairo/tools/annotation_tools/text_to_tree_tool/qual_task/evaluate_qualification.py

Prompts

```
['run the qualification evaluation tool with a gold set and worker file to compute accuracy stats', 'read a gold answer set file and compile allowed answers per command into a defaultdict', 'compare an action dictionary against an allowed dictionary to check if the answer matches', 'get statistics on which keys differ between a worker answer and the gold answer', 'evaluate worker answers from a tab-separated file against the gold set and compute accuracy percentages']
```

Usage

```
{'run_evaluate_qualification': 'run the qualification evaluation tool with a gold set and worker file to compute accuracy stats', 'read_gold_set': 'read a gold answer set file and compile allowed answers per command into a defaultdict', 'compare_dicts': 'compare an action dictionary against an allowed dictionary to check if the answer matches', 'get_wrong_stats': 'get statistics on which keys differ between a worker answer and the gold answer', 'evaluate_workers': 'evaluate worker answers from a tab-separated file against the gold set and compute accuracy percentages'}
```

