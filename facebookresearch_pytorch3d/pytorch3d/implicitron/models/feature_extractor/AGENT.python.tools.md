# Agent Python Tools

- repo: facebookresearch/pytorch3d
- repo_uri: https://github.com/facebookresearch/pytorch3d.git

## File: facebookresearch_pytorch3d/pytorch3d/implicitron/models/feature_extractor/feature_extractor.py

Prompts

```
['review the FeatureExtractorBase class and its abstract methods for image feature extraction', 'summarize the FeatureExtractorBase class which extracts features from images and masks', 'build a subclass of FeatureExtractorBase that implements get_feat_dims and forward methods', 'test the FeatureExtractorBase forward method with a batch of images and optional masks', 'refactor the FeatureExtractorBase class to add support for additional input types', 'build a ResNetFeatureExtractor with pretrained resnet34 to extract multi-stage image features', 'run a forward pass through ResNetFeatureExtractor with images and masks to get feature dict', 'create a ResNetFeatureExtractor extracting features only from stages 2 and 4', 'review the ResNetFeatureExtractor l2_norm setting which normalizes features across stages', 'summarize the get_feat_dims method which returns total feature dimension count']
```

Usage

```
{'review_FeatureExtractorBase': 'review the FeatureExtractorBase class and its abstract methods for image feature extraction', 'summarize_FeatureExtractorBase': 'summarize the FeatureExtractorBase class which extracts features from images and masks', 'build_FeatureExtractorBase_subclass': 'build a subclass of FeatureExtractorBase that implements get_feat_dims and forward methods', 'test_FeatureExtractorBase_forward': 'test the FeatureExtractorBase forward method with a batch of images and optional masks', 'refactor_FeatureExtractorBase': 'refactor the FeatureExtractorBase class to add support for additional input types'}
```

## File: facebookresearch_pytorch3d/pytorch3d/implicitron/models/feature_extractor/resnet_feature_extractor.py

Prompts

```
['review the FeatureExtractorBase class and its abstract methods for image feature extraction', 'summarize the FeatureExtractorBase class which extracts features from images and masks', 'build a subclass of FeatureExtractorBase that implements get_feat_dims and forward methods', 'test the FeatureExtractorBase forward method with a batch of images and optional masks', 'refactor the FeatureExtractorBase class to add support for additional input types', 'build a ResNetFeatureExtractor with pretrained resnet34 to extract multi-stage image features', 'run a forward pass through ResNetFeatureExtractor with images and masks to get feature dict', 'create a ResNetFeatureExtractor extracting features only from stages 2 and 4', 'review the ResNetFeatureExtractor l2_norm setting which normalizes features across stages', 'summarize the get_feat_dims method which returns total feature dimension count']
```

Usage

```
{'build_resnet_feature_extractor': 'build a ResNetFeatureExtractor with pretrained resnet34 to extract multi-stage image features', 'run_forward_pass': 'run a forward pass through ResNetFeatureExtractor with images and masks to get feature dict', 'create_feature_extractor_with_custom_stages': 'create a ResNetFeatureExtractor extracting features only from stages 2 and 4', 'review_l2_normalization': 'review the ResNetFeatureExtractor l2_norm setting which normalizes features across stages', 'summarize_get_feat_dims': 'summarize the get_feat_dims method which returns total feature dimension count'}
```

