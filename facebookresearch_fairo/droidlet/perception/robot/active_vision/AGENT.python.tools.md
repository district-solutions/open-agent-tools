# Agent Python Tools

- repo: facebookresearch/fairo
- repo_uri: https://github.com/facebookresearch/fairo

## File: facebookresearch_fairo/droidlet/perception/robot/active_vision/candidate_selection.py

Prompts

```
['create a SampleGoodCandidates instance to filter and sample good image candidates from a data directory', 'run the is_good_candidate method to check if a segmentation mask meets boundary and area thresholds', 'run get_n_candidates to uniformly sample n good or bad candidate image IDs from filtered lists', 'run visualize to display candidate images with overlaid segmentation masks using matplotlib and OpenCV', 'create a JSON-backed caching decorator to memoize expensive candidate evaluation results across runs']
```

Usage

```
{'create_SampleGoodCandidates': 'create a SampleGoodCandidates instance to filter and sample good image candidates from a data directory', 'run_is_good_candidate': 'run the is_good_candidate method to check if a segmentation mask meets boundary and area thresholds', 'run_get_n_candidates': 'run get_n_candidates to uniformly sample n good or bad candidate image IDs from filtered lists', 'run_visualize': 'run visualize to display candidate images with overlaid segmentation masks using matplotlib and OpenCV', 'create_cached_decorator': 'create a JSON-backed caching decorator to memoize expensive candidate evaluation results across runs'}
```

