# Agent Python Tools

- repo: facebookresearch/diplomacycicero
- repo_uri: https://github.com/facebookresearch/diplomacy_cicero

## File: facebookresearch_diplomacycicero/fairdiplomacy/annotate/lie_detection.py

Prompts

```
['read lie detector annotation JSON files from a directory and return normalized scores per game and phase', 'read lie detector annotations from a directory using a pickle cache for faster subsequent loads', 'read lie detector annotations from a directory without normalizing the log-sum-exp scores', 'create a fake nested defaultdict of lie detector annotations for debugging purposes', 'review the read_lie_detector_annotations function to understand how it parses JSON annotations and normalizes scores']
```

Usage

```
{'read_lie_detector_annotations': 'read lie detector annotation JSON files from a directory and return normalized scores per game and phase', 'read_lie_detector_annotations_with_cache': 'read lie detector annotations from a directory using a pickle cache for faster subsequent loads', 'read_lie_detector_annotations_unnormalized': 'read lie detector annotations from a directory without normalizing the log-sum-exp scores', 'make_fake_lie_detector_annotations': 'create a fake nested defaultdict of lie detector annotations for debugging purposes', 'review_read_lie_detector_annotations': 'review the read_lie_detector_annotations function to understand how it parses JSON annotations and normalizes scores'}
```

