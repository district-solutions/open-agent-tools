# Agent Python Tools

- repo: facebookresearch/sapiens
- repo_uri: https://github.com/facebookresearch/sapiens

## File: facebookresearch_sapiens/seg/mmseg/models/assigners/base_assigner.py

Prompts

```
['review the BaseAssigner abstract class and its assign method signature for mask assignment', 'review the abstract assign method that takes pred_instances and gt_instances as InstanceData', 'implement a subclass of BaseAssigner that overrides the abstract assign method', 'refactor the BaseAssigner assign method to add new keyword arguments for custom matching', 'summarize the BaseAssigner class which defines the interface for mask-to-ground-truth assignment', 'build a HungarianAssigner instance with match cost configs for bipartite matching between predictions and ground truth', 'assign predicted instance masks to ground truth masks using the Hungarian algorithm for minimum cost matching', 'compute weighted match costs between prediction masks and ground truth using configured cost functions', 'review the HungarianAssigner assign method to understand how it performs one-to-one matching with linear_sum_assignment', 'refactor the HungarianAssigner constructor to support additional match cost configuration formats']
```

Usage

```
{'review_BaseAssigner_class': 'review the BaseAssigner abstract class and its assign method signature for mask assignment', 'review_assign_abstract_method': 'review the abstract assign method that takes pred_instances and gt_instances as InstanceData', 'implement_BaseAssigner_subclass': 'implement a subclass of BaseAssigner that overrides the abstract assign method', 'refactor_BaseAssigner_assign': 'refactor the BaseAssigner assign method to add new keyword arguments for custom matching', 'summarize_BaseAssigner': 'summarize the BaseAssigner class which defines the interface for mask-to-ground-truth assignment'}
```

## File: facebookresearch_sapiens/seg/mmseg/models/assigners/hungarian_assigner.py

Prompts

```
['review the BaseAssigner abstract class and its assign method signature for mask assignment', 'review the abstract assign method that takes pred_instances and gt_instances as InstanceData', 'implement a subclass of BaseAssigner that overrides the abstract assign method', 'refactor the BaseAssigner assign method to add new keyword arguments for custom matching', 'summarize the BaseAssigner class which defines the interface for mask-to-ground-truth assignment', 'build a HungarianAssigner instance with match cost configs for bipartite matching between predictions and ground truth', 'assign predicted instance masks to ground truth masks using the Hungarian algorithm for minimum cost matching', 'compute weighted match costs between prediction masks and ground truth using configured cost functions', 'review the HungarianAssigner assign method to understand how it performs one-to-one matching with linear_sum_assignment', 'refactor the HungarianAssigner constructor to support additional match cost configuration formats']
```

Usage

```
{'build_HungarianAssigner': 'build a HungarianAssigner instance with match cost configs for bipartite matching between predictions and ground truth', 'assign_pred_to_gt': 'assign predicted instance masks to ground truth masks using the Hungarian algorithm for minimum cost matching', 'compute_match_costs': 'compute weighted match costs between prediction masks and ground truth using configured cost functions', 'review_HungarianAssigner_assign': 'review the HungarianAssigner assign method to understand how it performs one-to-one matching with linear_sum_assignment', 'refactor_HungarianAssigner_init': 'refactor the HungarianAssigner constructor to support additional match cost configuration formats'}
```

