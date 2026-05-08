# Agent Python Tools

- repo: facebookresearch/pytorch3d
- repo_uri: https://github.com/facebookresearch/pytorch3d.git

## File: facebookresearch_pytorch3d/pytorch3d/implicitron/models/view_pooler/feature_aggregator.py

Prompts

```
['build a ReductionFeatureAggregator to average and std-pool multi-view features across source cameras', 'create an AngleWeightedReductionFeatureAggregator that weights features by cosine similarity of target and source rays', 'test the IdentityFeatureAggregator to pass through sampled features with optional target view masking', 'refactor the ReductionFunction enum to add a new reduction operation like median pooling', 'review the AngleWeightedIdentityFeatureAggregator forward method to understand ray angle weighting without reduction', 'build a ViewPooler module to sample and aggregate image features at 3D point projections', 'run the ViewPooler forward pass to project 3D points and aggregate multi-view features', 'create a feature aggregator to reduce sampled features from multiple camera views per point', 'review the ViewPooler class and its integration of ViewSampler for 2D feature sampling', 'summarize the ViewPooler get_aggregated_feature_dim method to return output feature dimensionality', 'build a ViewSampler module to sample image features at 2D projections of 3D points', 'create a function to project 3D point clouds to cameras and sample features at 2D locations', 'test the handle_seq_id function to convert sequence ids to LongTensor on a device', 'refactor the cameras_points_cartesian_product function to generate all camera-point pairs for batched projection', 'review the ViewSampler forward method to understand feature sampling with masked and sequence-aware masking']
```

Usage

```
{'build_ReductionFeatureAggregator': 'build a ReductionFeatureAggregator to average and std-pool multi-view features across source cameras', 'create_AngleWeightedReductionFeatureAggregator': 'create an AngleWeightedReductionFeatureAggregator that weights features by cosine similarity of target and source rays', 'test_IdentityFeatureAggregator': 'test the IdentityFeatureAggregator to pass through sampled features with optional target view masking', 'refactor_ReductionFunction': 'refactor the ReductionFunction enum to add a new reduction operation like median pooling', 'review_AngleWeightedIdentityFeatureAggregator': 'review the AngleWeightedIdentityFeatureAggregator forward method to understand ray angle weighting without reduction'}
```

## File: facebookresearch_pytorch3d/pytorch3d/implicitron/models/view_pooler/view_pooler.py

Prompts

```
['build a ReductionFeatureAggregator to average and std-pool multi-view features across source cameras', 'create an AngleWeightedReductionFeatureAggregator that weights features by cosine similarity of target and source rays', 'test the IdentityFeatureAggregator to pass through sampled features with optional target view masking', 'refactor the ReductionFunction enum to add a new reduction operation like median pooling', 'review the AngleWeightedIdentityFeatureAggregator forward method to understand ray angle weighting without reduction', 'build a ViewPooler module to sample and aggregate image features at 3D point projections', 'run the ViewPooler forward pass to project 3D points and aggregate multi-view features', 'create a feature aggregator to reduce sampled features from multiple camera views per point', 'review the ViewPooler class and its integration of ViewSampler for 2D feature sampling', 'summarize the ViewPooler get_aggregated_feature_dim method to return output feature dimensionality', 'build a ViewSampler module to sample image features at 2D projections of 3D points', 'create a function to project 3D point clouds to cameras and sample features at 2D locations', 'test the handle_seq_id function to convert sequence ids to LongTensor on a device', 'refactor the cameras_points_cartesian_product function to generate all camera-point pairs for batched projection', 'review the ViewSampler forward method to understand feature sampling with masked and sequence-aware masking']
```

Usage

```
{'build_view_pooler': 'build a ViewPooler module to sample and aggregate image features at 3D point projections', 'run_view_pooler_forward': 'run the ViewPooler forward pass to project 3D points and aggregate multi-view features', 'create_feature_aggregator': 'create a feature aggregator to reduce sampled features from multiple camera views per point', 'review_view_sampler_integration': 'review the ViewPooler class and its integration of ViewSampler for 2D feature sampling', 'summarize_aggregated_feature_dim': 'summarize the ViewPooler get_aggregated_feature_dim method to return output feature dimensionality'}
```

## File: facebookresearch_pytorch3d/pytorch3d/implicitron/models/view_pooler/view_sampler.py

Prompts

```
['build a ReductionFeatureAggregator to average and std-pool multi-view features across source cameras', 'create an AngleWeightedReductionFeatureAggregator that weights features by cosine similarity of target and source rays', 'test the IdentityFeatureAggregator to pass through sampled features with optional target view masking', 'refactor the ReductionFunction enum to add a new reduction operation like median pooling', 'review the AngleWeightedIdentityFeatureAggregator forward method to understand ray angle weighting without reduction', 'build a ViewPooler module to sample and aggregate image features at 3D point projections', 'run the ViewPooler forward pass to project 3D points and aggregate multi-view features', 'create a feature aggregator to reduce sampled features from multiple camera views per point', 'review the ViewPooler class and its integration of ViewSampler for 2D feature sampling', 'summarize the ViewPooler get_aggregated_feature_dim method to return output feature dimensionality', 'build a ViewSampler module to sample image features at 2D projections of 3D points', 'create a function to project 3D point clouds to cameras and sample features at 2D locations', 'test the handle_seq_id function to convert sequence ids to LongTensor on a device', 'refactor the cameras_points_cartesian_product function to generate all camera-point pairs for batched projection', 'review the ViewSampler forward method to understand feature sampling with masked and sequence-aware masking']
```

Usage

```
{'build_view_sampler_module': 'build a ViewSampler module to sample image features at 2D projections of 3D points', 'create_project_points_and_sample': 'create a function to project 3D point clouds to cameras and sample features at 2D locations', 'test_handle_seq_id': 'test the handle_seq_id function to convert sequence ids to LongTensor on a device', 'refactor_cameras_points_cartesian_product': 'refactor the cameras_points_cartesian_product function to generate all camera-point pairs for batched projection', 'review_view_sampler_forward': 'review the ViewSampler forward method to understand feature sampling with masked and sequence-aware masking'}
```

