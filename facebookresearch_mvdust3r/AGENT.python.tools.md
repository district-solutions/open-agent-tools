# Agent Python Tools

- repo: facebookresearch/mvdust3r
- repo_uri: https://github.com/facebookresearch/mvdust3r

## File: facebookresearch_mvdust3r/demo.py

Prompts

```
['run the MV-DUSt3R+ Gradio demo server with MVD or MVDp model weights on a specified port', 'run multi-view 3D scene reconstruction inference on a list of input images using the MVD model', 'extract a 3D GLB model from reconstructed scene output with configurable confidence threshold and camera size', 'convert 3D scene pointcloud or mesh data with camera poses into an exportable GLB file', 'configure the argparse CLI parser for server settings, model weights, device, and image size options', 'run DUSt3R inference with global optimization on a list of image tensors to get 3D point clouds and camera poses', 'run multi-view loss computation for a batch of views using global optimization inference and a criterion function', 'run DUSt3R reconstruction from a list of image files to produce a 3D scene with point clouds and camera poses', 'run 3D model extraction from a reconstructed scene to export a GLB file with optional point cloud or mesh output', 'run the DUSt3R gradio demo CLI with pretrained model weights to reconstruct 3D scenes from input images', 'run the DUST3R multi-view inference evaluation pipeline with global optimization on a test dataset', 'build a train or test data loader from a dataset config string with batch size and workers', 'save point cloud renderings, RGB images, and 3DGS videos from multi-view inference results', 'test one epoch of the model on a dataset and return averaged loss metrics and stats', 'add first-view and best-view aggregated metrics to a loss details dictionary for multi-reference evaluation', 'run the DUST3R training loop with a specified model, dataset, and learning rate via CLI arguments', 'run test evaluation on one or more datasets by passing --only_test 1 and --test_dataset', 'review the train_one_epoch function that handles forward pass, backward pass, gradient accumulation, and logging', 'review the test_one_epoch function that evaluates model loss and optionally saves point cloud renderings']
```

Usage

```
{'run_gradio_demo': 'run the MV-DUSt3R+ Gradio demo server with MVD or MVDp model weights on a specified port', 'run_multi_view_inference': 'run multi-view 3D scene reconstruction inference on a list of input images using the MVD model', 'extract_3d_glb_model': 'extract a 3D GLB model from reconstructed scene output with configurable confidence threshold and camera size', 'convert_scene_to_glb': 'convert 3D scene pointcloud or mesh data with camera poses into an exportable GLB file', 'configure_args_parser': 'configure the argparse CLI parser for server settings, model weights, device, and image size options'}
```

## File: facebookresearch_mvdust3r/inference_global_optimization.py

Prompts

```
['run the MV-DUSt3R+ Gradio demo server with MVD or MVDp model weights on a specified port', 'run multi-view 3D scene reconstruction inference on a list of input images using the MVD model', 'extract a 3D GLB model from reconstructed scene output with configurable confidence threshold and camera size', 'convert 3D scene pointcloud or mesh data with camera poses into an exportable GLB file', 'configure the argparse CLI parser for server settings, model weights, device, and image size options', 'run DUSt3R inference with global optimization on a list of image tensors to get 3D point clouds and camera poses', 'run multi-view loss computation for a batch of views using global optimization inference and a criterion function', 'run DUSt3R reconstruction from a list of image files to produce a 3D scene with point clouds and camera poses', 'run 3D model extraction from a reconstructed scene to export a GLB file with optional point cloud or mesh output', 'run the DUSt3R gradio demo CLI with pretrained model weights to reconstruct 3D scenes from input images', 'run the DUST3R multi-view inference evaluation pipeline with global optimization on a test dataset', 'build a train or test data loader from a dataset config string with batch size and workers', 'save point cloud renderings, RGB images, and 3DGS videos from multi-view inference results', 'test one epoch of the model on a dataset and return averaged loss metrics and stats', 'add first-view and best-view aggregated metrics to a loss details dictionary for multi-reference evaluation', 'run the DUST3R training loop with a specified model, dataset, and learning rate via CLI arguments', 'run test evaluation on one or more datasets by passing --only_test 1 and --test_dataset', 'review the train_one_epoch function that handles forward pass, backward pass, gradient accumulation, and logging', 'review the test_one_epoch function that evaluates model loss and optionally saves point cloud renderings']
```

Usage

```
{'run_inference_global_optimization': 'run DUSt3R inference with global optimization on a list of image tensors to get 3D point clouds and camera poses', 'run_loss_of_one_batch_go_mv': 'run multi-view loss computation for a batch of views using global optimization inference and a criterion function', 'run_get_reconstructed_scene': 'run DUSt3R reconstruction from a list of image files to produce a 3D scene with point clouds and camera poses', 'run_get_3D_model_from_scene': 'run 3D model extraction from a reconstructed scene to export a GLB file with optional point cloud or mesh output', 'run_main_cli': 'run the DUSt3R gradio demo CLI with pretrained model weights to reconstruct 3D scenes from input images'}
```

## File: facebookresearch_mvdust3r/inference_global_optimization_batch.py

Prompts

```
['run the MV-DUSt3R+ Gradio demo server with MVD or MVDp model weights on a specified port', 'run multi-view 3D scene reconstruction inference on a list of input images using the MVD model', 'extract a 3D GLB model from reconstructed scene output with configurable confidence threshold and camera size', 'convert 3D scene pointcloud or mesh data with camera poses into an exportable GLB file', 'configure the argparse CLI parser for server settings, model weights, device, and image size options', 'run DUSt3R inference with global optimization on a list of image tensors to get 3D point clouds and camera poses', 'run multi-view loss computation for a batch of views using global optimization inference and a criterion function', 'run DUSt3R reconstruction from a list of image files to produce a 3D scene with point clouds and camera poses', 'run 3D model extraction from a reconstructed scene to export a GLB file with optional point cloud or mesh output', 'run the DUSt3R gradio demo CLI with pretrained model weights to reconstruct 3D scenes from input images', 'run the DUST3R multi-view inference evaluation pipeline with global optimization on a test dataset', 'build a train or test data loader from a dataset config string with batch size and workers', 'save point cloud renderings, RGB images, and 3DGS videos from multi-view inference results', 'test one epoch of the model on a dataset and return averaged loss metrics and stats', 'add first-view and best-view aggregated metrics to a loss details dictionary for multi-reference evaluation', 'run the DUST3R training loop with a specified model, dataset, and learning rate via CLI arguments', 'run test evaluation on one or more datasets by passing --only_test 1 and --test_dataset', 'review the train_one_epoch function that handles forward pass, backward pass, gradient accumulation, and logging', 'review the test_one_epoch function that evaluates model loss and optionally saves point cloud renderings']
```

Usage

```
{'run_inference_evaluation': 'run the DUST3R multi-view inference evaluation pipeline with global optimization on a test dataset', 'build_dataset_loader': 'build a train or test data loader from a dataset config string with batch size and workers', 'save_results_visualization': 'save point cloud renderings, RGB images, and 3DGS videos from multi-view inference results', 'test_one_epoch': 'test one epoch of the model on a dataset and return averaged loss metrics and stats', 'add_first_best': 'add first-view and best-view aggregated metrics to a loss details dictionary for multi-reference evaluation'}
```

## File: facebookresearch_mvdust3r/train.py

Prompts

```
['run the MV-DUSt3R+ Gradio demo server with MVD or MVDp model weights on a specified port', 'run multi-view 3D scene reconstruction inference on a list of input images using the MVD model', 'extract a 3D GLB model from reconstructed scene output with configurable confidence threshold and camera size', 'convert 3D scene pointcloud or mesh data with camera poses into an exportable GLB file', 'configure the argparse CLI parser for server settings, model weights, device, and image size options', 'run DUSt3R inference with global optimization on a list of image tensors to get 3D point clouds and camera poses', 'run multi-view loss computation for a batch of views using global optimization inference and a criterion function', 'run DUSt3R reconstruction from a list of image files to produce a 3D scene with point clouds and camera poses', 'run 3D model extraction from a reconstructed scene to export a GLB file with optional point cloud or mesh output', 'run the DUSt3R gradio demo CLI with pretrained model weights to reconstruct 3D scenes from input images', 'run the DUST3R multi-view inference evaluation pipeline with global optimization on a test dataset', 'build a train or test data loader from a dataset config string with batch size and workers', 'save point cloud renderings, RGB images, and 3DGS videos from multi-view inference results', 'test one epoch of the model on a dataset and return averaged loss metrics and stats', 'add first-view and best-view aggregated metrics to a loss details dictionary for multi-reference evaluation', 'run the DUST3R training loop with a specified model, dataset, and learning rate via CLI arguments', 'run test evaluation on one or more datasets by passing --only_test 1 and --test_dataset', 'review the train_one_epoch function that handles forward pass, backward pass, gradient accumulation, and logging', 'review the test_one_epoch function that evaluates model loss and optionally saves point cloud renderings']
```

Usage

```
{'run_training': 'run the DUST3R training loop with a specified model, dataset, and learning rate via CLI arguments', 'run_testing': 'run test evaluation on one or more datasets by passing --only_test 1 and --test_dataset', 'build_dataset_loader': 'build a train or test data loader from a dataset config string with batch size and workers', 'review_train_one_epoch': 'review the train_one_epoch function that handles forward pass, backward pass, gradient accumulation, and logging', 'review_test_one_epoch': 'review the test_one_epoch function that evaluates model loss and optionally saves point cloud renderings'}
```

