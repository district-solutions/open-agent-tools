# Agent Python Tools

- repo: facebookresearch/pytorchganzoo
- repo_uri: https://github.com/facebookresearch/pytorch_gan_zoo

## File: facebookresearch_pytorchganzoo/models/metrics/inception_score.py

Prompts

```
['create an InceptionScore instance with a pretrained classifier model for evaluating generated images', 'update the InceptionScore accumulator with a mini-batch of reference image tensors', 'get the final inception score after processing all mini-batches of generated images', 'review the InceptionScore class to understand how entropy and softmax are accumulated across batches', 'refactor the InceptionScore getScore method to support batched or streaming score computation', 'build a LaplacianSWDMetric instance with patchSize, nDescriptorLevel, and depthPyramid parameters', 'run updateWithMiniBatch on a LaplacianSWDMetric to extract and store descriptors from reference and target minibatches', 'run getScore on a LaplacianSWDMetric to compute SWD distance between stored reference and target descriptor distributions', "test the sliced_wasserstein function to compute NVIDIA's approximation of the SWD distance between two descriptor arrays", 'test getDescriptorsForMinibatch to extract randomly chosen patches of a given size from each image in a minibatch', 'build a stratified train/val/test split from an attributes JSON file with configurable ratios', 'compute frequency statistics for each attribute category and label across a dataset', 'train a ResNet-18 feature extractor model on attributed image data with optional visualization', 'extract features from a dataset using a loaded model and save a KDTree with image names', 'load a pretrained feature extractor model from a saved checkpoint with configurable gradient settings']
```

Usage

```
{'create_InceptionScore': 'create an InceptionScore instance with a pretrained classifier model for evaluating generated images', 'updateWithMiniBatch': 'update the InceptionScore accumulator with a mini-batch of reference image tensors', 'getScore': 'get the final inception score after processing all mini-batches of generated images', 'review_InceptionScore_class': 'review the InceptionScore class to understand how entropy and softmax are accumulated across batches', 'refactor_InceptionScore_getScore': 'refactor the InceptionScore getScore method to support batched or streaming score computation'}
```

## File: facebookresearch_pytorchganzoo/models/metrics/laplacian_swd.py

Prompts

```
['create an InceptionScore instance with a pretrained classifier model for evaluating generated images', 'update the InceptionScore accumulator with a mini-batch of reference image tensors', 'get the final inception score after processing all mini-batches of generated images', 'review the InceptionScore class to understand how entropy and softmax are accumulated across batches', 'refactor the InceptionScore getScore method to support batched or streaming score computation', 'build a LaplacianSWDMetric instance with patchSize, nDescriptorLevel, and depthPyramid parameters', 'run updateWithMiniBatch on a LaplacianSWDMetric to extract and store descriptors from reference and target minibatches', 'run getScore on a LaplacianSWDMetric to compute SWD distance between stored reference and target descriptor distributions', "test the sliced_wasserstein function to compute NVIDIA's approximation of the SWD distance between two descriptor arrays", 'test getDescriptorsForMinibatch to extract randomly chosen patches of a given size from each image in a minibatch', 'build a stratified train/val/test split from an attributes JSON file with configurable ratios', 'compute frequency statistics for each attribute category and label across a dataset', 'train a ResNet-18 feature extractor model on attributed image data with optional visualization', 'extract features from a dataset using a loaded model and save a KDTree with image names', 'load a pretrained feature extractor model from a saved checkpoint with configurable gradient settings']
```

Usage

```
{'build_LaplacianSWDMetric': 'build a LaplacianSWDMetric instance with patchSize, nDescriptorLevel, and depthPyramid parameters', 'run_updateWithMiniBatch': 'run updateWithMiniBatch on a LaplacianSWDMetric to extract and store descriptors from reference and target minibatches', 'run_getScore': 'run getScore on a LaplacianSWDMetric to compute SWD distance between stored reference and target descriptor distributions', 'test_sliced_wasserstein': "test the sliced_wasserstein function to compute NVIDIA's approximation of the SWD distance between two descriptor arrays", 'test_getDescriptorsForMinibatch': 'test getDescriptorsForMinibatch to extract randomly chosen patches of a given size from each image in a minibatch'}
```

## File: facebookresearch_pytorchganzoo/models/metrics/nn_score.py

Prompts

```
['create an InceptionScore instance with a pretrained classifier model for evaluating generated images', 'update the InceptionScore accumulator with a mini-batch of reference image tensors', 'get the final inception score after processing all mini-batches of generated images', 'review the InceptionScore class to understand how entropy and softmax are accumulated across batches', 'refactor the InceptionScore getScore method to support batched or streaming score computation', 'build a LaplacianSWDMetric instance with patchSize, nDescriptorLevel, and depthPyramid parameters', 'run updateWithMiniBatch on a LaplacianSWDMetric to extract and store descriptors from reference and target minibatches', 'run getScore on a LaplacianSWDMetric to compute SWD distance between stored reference and target descriptor distributions', "test the sliced_wasserstein function to compute NVIDIA's approximation of the SWD distance between two descriptor arrays", 'test getDescriptorsForMinibatch to extract randomly chosen patches of a given size from each image in a minibatch', 'build a stratified train/val/test split from an attributes JSON file with configurable ratios', 'compute frequency statistics for each attribute category and label across a dataset', 'train a ResNet-18 feature extractor model on attributed image data with optional visualization', 'extract features from a dataset using a loaded model and save a KDTree with image names', 'load a pretrained feature extractor model from a saved checkpoint with configurable gradient settings']
```

Usage

```
{'build_train_val_test_split': 'build a stratified train/val/test split from an attributes JSON file with configurable ratios', 'compute_dataset_attribute_stats': 'compute frequency statistics for each attribute category and label across a dataset', 'train_feature_maker_resnet': 'train a ResNet-18 feature extractor model on attributed image data with optional visualization', 'extract_features_and_build_kdtree': 'extract features from a dataset using a loaded model and save a KDTree with image names', 'load_feature_extractor_model': 'load a pretrained feature extractor model from a saved checkpoint with configurable gradient settings'}
```

