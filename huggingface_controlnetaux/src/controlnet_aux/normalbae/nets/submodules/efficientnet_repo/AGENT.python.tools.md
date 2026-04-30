# Agent Python Tools

- repo: huggingface/controlnetaux
- repo_uri: https://github.com/huggingface/controlnet_aux

## File: huggingface_controlnetaux/src/controlnet_aux/normalbae/nets/submodules/efficientnet_repo/caffe2_validate.py

Prompts

```
['run the caffe2 validation script to verify exported ONNX models against a dataset', 'run the main function to validate a caffe2 model using init and predict protobuf files', 'test the accuracy_np function to compute top1 and top5 accuracy from numpy output and target arrays', 'review the main function that loads caffe2 protobuf nets and runs inference over a data loader', 'summarize the accuracy_np function that calculates top1 and top5 classification accuracy using numpy argsort', 'run the ONNX optimizer script to prune nodes and fuse batchnorm layers into convolutions for a model file', 'run traverse_graph to recursively print all nodes and subgraphs in an ONNX model graph with node counts', 'optimize an ONNX model by applying passes like fuse_bn_into_conv, eliminate_identity, and fuse_consecutive_transposes', 'review the traverse_graph function that recursively walks an ONNX graph and returns node count and printable node strings', 'summarize the ONNX optimization script that loads a model, applies optimizer passes, and saves the optimized model', 'run ONNX model validation on a dataset to measure top-1 and top-5 accuracy', 'run ONNX model inference with profiling enabled to capture performance metrics', 'run ONNX validation and export the optimized graph to a file', 'run ONNX model validation using TensorFlow MNASNet preprocessing pipeline', 'create an AverageMeter instance to track running average of training loss values', 'update an AverageMeter with new batch values and count to compute running average', 'reset an AverageMeter to clear all accumulated values and start fresh tracking', 'compute top-k classification accuracy from model output tensor and target labels', 'create an output directory with optional incremental naming if directory already exists']
```

Usage

```
{'run_caffe2_validation': 'run the caffe2 validation script to verify exported ONNX models against a dataset', 'run_main': 'run the main function to validate a caffe2 model using init and predict protobuf files', 'test_accuracy_np': 'test the accuracy_np function to compute top1 and top5 accuracy from numpy output and target arrays', 'review_main': 'review the main function that loads caffe2 protobuf nets and runs inference over a data loader', 'summarize_accuracy_np': 'summarize the accuracy_np function that calculates top1 and top5 classification accuracy using numpy argsort'}
```

## File: huggingface_controlnetaux/src/controlnet_aux/normalbae/nets/submodules/efficientnet_repo/onnx_optimize.py

Prompts

```
['run the caffe2 validation script to verify exported ONNX models against a dataset', 'run the main function to validate a caffe2 model using init and predict protobuf files', 'test the accuracy_np function to compute top1 and top5 accuracy from numpy output and target arrays', 'review the main function that loads caffe2 protobuf nets and runs inference over a data loader', 'summarize the accuracy_np function that calculates top1 and top5 classification accuracy using numpy argsort', 'run the ONNX optimizer script to prune nodes and fuse batchnorm layers into convolutions for a model file', 'run traverse_graph to recursively print all nodes and subgraphs in an ONNX model graph with node counts', 'optimize an ONNX model by applying passes like fuse_bn_into_conv, eliminate_identity, and fuse_consecutive_transposes', 'review the traverse_graph function that recursively walks an ONNX graph and returns node count and printable node strings', 'summarize the ONNX optimization script that loads a model, applies optimizer passes, and saves the optimized model', 'run ONNX model validation on a dataset to measure top-1 and top-5 accuracy', 'run ONNX model inference with profiling enabled to capture performance metrics', 'run ONNX validation and export the optimized graph to a file', 'run ONNX model validation using TensorFlow MNASNet preprocessing pipeline', 'create an AverageMeter instance to track running average of training loss values', 'update an AverageMeter with new batch values and count to compute running average', 'reset an AverageMeter to clear all accumulated values and start fresh tracking', 'compute top-k classification accuracy from model output tensor and target labels', 'create an output directory with optional incremental naming if directory already exists']
```

Usage

```
{'run_onnx_optimize': 'run the ONNX optimizer script to prune nodes and fuse batchnorm layers into convolutions for a model file', 'run_traverse_graph': 'run traverse_graph to recursively print all nodes and subgraphs in an ONNX model graph with node counts', 'optimize_onnx_model': 'optimize an ONNX model by applying passes like fuse_bn_into_conv, eliminate_identity, and fuse_consecutive_transposes', 'review_traverse_graph': 'review the traverse_graph function that recursively walks an ONNX graph and returns node count and printable node strings', 'summarize_onnx_optimize': 'summarize the ONNX optimization script that loads a model, applies optimizer passes, and saves the optimized model'}
```

## File: huggingface_controlnetaux/src/controlnet_aux/normalbae/nets/submodules/efficientnet_repo/onnx_validate.py

Prompts

```
['run the caffe2 validation script to verify exported ONNX models against a dataset', 'run the main function to validate a caffe2 model using init and predict protobuf files', 'test the accuracy_np function to compute top1 and top5 accuracy from numpy output and target arrays', 'review the main function that loads caffe2 protobuf nets and runs inference over a data loader', 'summarize the accuracy_np function that calculates top1 and top5 classification accuracy using numpy argsort', 'run the ONNX optimizer script to prune nodes and fuse batchnorm layers into convolutions for a model file', 'run traverse_graph to recursively print all nodes and subgraphs in an ONNX model graph with node counts', 'optimize an ONNX model by applying passes like fuse_bn_into_conv, eliminate_identity, and fuse_consecutive_transposes', 'review the traverse_graph function that recursively walks an ONNX graph and returns node count and printable node strings', 'summarize the ONNX optimization script that loads a model, applies optimizer passes, and saves the optimized model', 'run ONNX model validation on a dataset to measure top-1 and top-5 accuracy', 'run ONNX model inference with profiling enabled to capture performance metrics', 'run ONNX validation and export the optimized graph to a file', 'run ONNX model validation using TensorFlow MNASNet preprocessing pipeline', 'create an AverageMeter instance to track running average of training loss values', 'update an AverageMeter with new batch values and count to compute running average', 'reset an AverageMeter to clear all accumulated values and start fresh tracking', 'compute top-k classification accuracy from model output tensor and target labels', 'create an output directory with optional incremental naming if directory already exists']
```

Usage

```
{'run_onnx_validation': 'run ONNX model validation on a dataset to measure top-1 and top-5 accuracy', 'run_onnx_with_profiling': 'run ONNX model inference with profiling enabled to capture performance metrics', 'run_onnx_optimized_export': 'run ONNX validation and export the optimized graph to a file', 'run_onnx_with_tf_preprocessing': 'run ONNX model validation using TensorFlow MNASNet preprocessing pipeline', 'summarize_accuracy_np': 'summarize the accuracy_np function that computes top-1 and top-5 accuracy from numpy output arrays'}
```

## File: huggingface_controlnetaux/src/controlnet_aux/normalbae/nets/submodules/efficientnet_repo/utils.py

Prompts

```
['run the caffe2 validation script to verify exported ONNX models against a dataset', 'run the main function to validate a caffe2 model using init and predict protobuf files', 'test the accuracy_np function to compute top1 and top5 accuracy from numpy output and target arrays', 'review the main function that loads caffe2 protobuf nets and runs inference over a data loader', 'summarize the accuracy_np function that calculates top1 and top5 classification accuracy using numpy argsort', 'run the ONNX optimizer script to prune nodes and fuse batchnorm layers into convolutions for a model file', 'run traverse_graph to recursively print all nodes and subgraphs in an ONNX model graph with node counts', 'optimize an ONNX model by applying passes like fuse_bn_into_conv, eliminate_identity, and fuse_consecutive_transposes', 'review the traverse_graph function that recursively walks an ONNX graph and returns node count and printable node strings', 'summarize the ONNX optimization script that loads a model, applies optimizer passes, and saves the optimized model', 'run ONNX model validation on a dataset to measure top-1 and top-5 accuracy', 'run ONNX model inference with profiling enabled to capture performance metrics', 'run ONNX validation and export the optimized graph to a file', 'run ONNX model validation using TensorFlow MNASNet preprocessing pipeline', 'create an AverageMeter instance to track running average of training loss values', 'update an AverageMeter with new batch values and count to compute running average', 'reset an AverageMeter to clear all accumulated values and start fresh tracking', 'compute top-k classification accuracy from model output tensor and target labels', 'create an output directory with optional incremental naming if directory already exists']
```

Usage

```
{'create_AverageMeter': 'create an AverageMeter instance to track running average of training loss values', 'update_AverageMeter': 'update an AverageMeter with new batch values and count to compute running average', 'reset_AverageMeter': 'reset an AverageMeter to clear all accumulated values and start fresh tracking', 'compute_accuracy_topk': 'compute top-k classification accuracy from model output tensor and target labels', 'create_output_directory': 'create an output directory with optional incremental naming if directory already exists'}
```

