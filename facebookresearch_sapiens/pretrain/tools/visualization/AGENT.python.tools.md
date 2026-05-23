# Agent Python Tools

- repo: facebookresearch/sapiens
- repo_uri: https://github.com/facebookresearch/sapiens

## File: facebookresearch_sapiens/pretrain/tools/visualization/browse_dataset.py

Prompts

```
['browse a dataset by visualizing train test or val phase images with configurable display mode', 'concatenate multiple images into a single grid figure with labels and shape annotations', 'inspect dataset pipeline transforms by recording intermediate images after each transformation step', 'visualize dataset samples using UniversalVisualizer with classification labels and optional mask overlay', 'parse command line arguments for dataset browsing including config output dir phase and display mode', 'run the vis_cam CLI tool to visualize class activation maps on an image using a pretrained model', 'run GradCAM visualization on an image with a config file and checkpoint to generate heatmaps', 'run CAM visualization on ViT-like networks by specifying the --vit-like flag and extra tokens', 'run CAM visualization targeting specific model layers using the --target-layers argument', 'run CAM visualization and save the output heatmap image to a specified path with --save-path', 'run the vis_scheduler CLI tool to visualize learning rate curves from an mmengine config file', 'run plot_curve to generate a matplotlib graph of learning rate or momentum over training iterations', 'run simulate_train to simulate a training loop and record optimizer parameter changes over time', 'review the ParamRecordHook class that records learning rate, momentum, and weight decay during training', 'review the SimpleModel class used as a no-op placeholder model for scheduler visualization', 'run t-SNE visualization on model features from a config file and checkpoint', 'run t-SNE visualization for specific class indices with custom perplexity and learning rate', 'run t-SNE visualization on backbone features extracted from a pretrained model', 'run t-SNE visualization and display a legend of all categories in the plot', 'run t-SNE visualization on neck stage features with custom max samples per class']
```

Usage

```
{'browse_dataset_visualize': 'browse a dataset by visualizing train test or val phase images with configurable display mode', 'make_grid_concat_images': 'concatenate multiple images into a single grid figure with labels and shape annotations', 'InspectCompose_record_transforms': 'inspect dataset pipeline transforms by recording intermediate images after each transformation step', 'visualize_dataset_with_visualizer': 'visualize dataset samples using UniversalVisualizer with classification labels and optional mask overlay', 'parse_args_dataset_browse': 'parse command line arguments for dataset browsing including config output dir phase and display mode'}
```

## File: facebookresearch_sapiens/pretrain/tools/visualization/vis_cam.py

Prompts

```
['browse a dataset by visualizing train test or val phase images with configurable display mode', 'concatenate multiple images into a single grid figure with labels and shape annotations', 'inspect dataset pipeline transforms by recording intermediate images after each transformation step', 'visualize dataset samples using UniversalVisualizer with classification labels and optional mask overlay', 'parse command line arguments for dataset browsing including config output dir phase and display mode', 'run the vis_cam CLI tool to visualize class activation maps on an image using a pretrained model', 'run GradCAM visualization on an image with a config file and checkpoint to generate heatmaps', 'run CAM visualization on ViT-like networks by specifying the --vit-like flag and extra tokens', 'run CAM visualization targeting specific model layers using the --target-layers argument', 'run CAM visualization and save the output heatmap image to a specified path with --save-path', 'run the vis_scheduler CLI tool to visualize learning rate curves from an mmengine config file', 'run plot_curve to generate a matplotlib graph of learning rate or momentum over training iterations', 'run simulate_train to simulate a training loop and record optimizer parameter changes over time', 'review the ParamRecordHook class that records learning rate, momentum, and weight decay during training', 'review the SimpleModel class used as a no-op placeholder model for scheduler visualization', 'run t-SNE visualization on model features from a config file and checkpoint', 'run t-SNE visualization for specific class indices with custom perplexity and learning rate', 'run t-SNE visualization on backbone features extracted from a pretrained model', 'run t-SNE visualization and display a legend of all categories in the plot', 'run t-SNE visualization on neck stage features with custom max samples per class']
```

Usage

```
{'run_vis_cam_cli': 'run the vis_cam CLI tool to visualize class activation maps on an image using a pretrained model', 'run_gradcam_visualization': 'run GradCAM visualization on an image with a config file and checkpoint to generate heatmaps', 'run_vit_cam_visualization': 'run CAM visualization on ViT-like networks by specifying the --vit-like flag and extra tokens', 'run_cam_with_target_layers': 'run CAM visualization targeting specific model layers using the --target-layers argument', 'run_cam_save_output': 'run CAM visualization and save the output heatmap image to a specified path with --save-path'}
```

## File: facebookresearch_sapiens/pretrain/tools/visualization/vis_scheduler.py

Prompts

```
['browse a dataset by visualizing train test or val phase images with configurable display mode', 'concatenate multiple images into a single grid figure with labels and shape annotations', 'inspect dataset pipeline transforms by recording intermediate images after each transformation step', 'visualize dataset samples using UniversalVisualizer with classification labels and optional mask overlay', 'parse command line arguments for dataset browsing including config output dir phase and display mode', 'run the vis_cam CLI tool to visualize class activation maps on an image using a pretrained model', 'run GradCAM visualization on an image with a config file and checkpoint to generate heatmaps', 'run CAM visualization on ViT-like networks by specifying the --vit-like flag and extra tokens', 'run CAM visualization targeting specific model layers using the --target-layers argument', 'run CAM visualization and save the output heatmap image to a specified path with --save-path', 'run the vis_scheduler CLI tool to visualize learning rate curves from an mmengine config file', 'run plot_curve to generate a matplotlib graph of learning rate or momentum over training iterations', 'run simulate_train to simulate a training loop and record optimizer parameter changes over time', 'review the ParamRecordHook class that records learning rate, momentum, and weight decay during training', 'review the SimpleModel class used as a no-op placeholder model for scheduler visualization', 'run t-SNE visualization on model features from a config file and checkpoint', 'run t-SNE visualization for specific class indices with custom perplexity and learning rate', 'run t-SNE visualization on backbone features extracted from a pretrained model', 'run t-SNE visualization and display a legend of all categories in the plot', 'run t-SNE visualization on neck stage features with custom max samples per class']
```

Usage

```
{'run_vis_scheduler_cli': 'run the vis_scheduler CLI tool to visualize learning rate curves from an mmengine config file', 'run_plot_curve': 'run plot_curve to generate a matplotlib graph of learning rate or momentum over training iterations', 'run_simulate_train': 'run simulate_train to simulate a training loop and record optimizer parameter changes over time', 'review_ParamRecordHook': 'review the ParamRecordHook class that records learning rate, momentum, and weight decay during training', 'review_SimpleModel': 'review the SimpleModel class used as a no-op placeholder model for scheduler visualization'}
```

## File: facebookresearch_sapiens/pretrain/tools/visualization/vis_tsne.py

Prompts

```
['browse a dataset by visualizing train test or val phase images with configurable display mode', 'concatenate multiple images into a single grid figure with labels and shape annotations', 'inspect dataset pipeline transforms by recording intermediate images after each transformation step', 'visualize dataset samples using UniversalVisualizer with classification labels and optional mask overlay', 'parse command line arguments for dataset browsing including config output dir phase and display mode', 'run the vis_cam CLI tool to visualize class activation maps on an image using a pretrained model', 'run GradCAM visualization on an image with a config file and checkpoint to generate heatmaps', 'run CAM visualization on ViT-like networks by specifying the --vit-like flag and extra tokens', 'run CAM visualization targeting specific model layers using the --target-layers argument', 'run CAM visualization and save the output heatmap image to a specified path with --save-path', 'run the vis_scheduler CLI tool to visualize learning rate curves from an mmengine config file', 'run plot_curve to generate a matplotlib graph of learning rate or momentum over training iterations', 'run simulate_train to simulate a training loop and record optimizer parameter changes over time', 'review the ParamRecordHook class that records learning rate, momentum, and weight decay during training', 'review the SimpleModel class used as a no-op placeholder model for scheduler visualization', 'run t-SNE visualization on model features from a config file and checkpoint', 'run t-SNE visualization for specific class indices with custom perplexity and learning rate', 'run t-SNE visualization on backbone features extracted from a pretrained model', 'run t-SNE visualization and display a legend of all categories in the plot', 'run t-SNE visualization on neck stage features with custom max samples per class']
```

Usage

```
{'run_tsne_visualization': 'run t-SNE visualization on model features from a config file and checkpoint', 'run_tsne_with_custom_classes': 'run t-SNE visualization for specific class indices with custom perplexity and learning rate', 'run_tsne_backbone_features': 'run t-SNE visualization on backbone features extracted from a pretrained model', 'run_tsne_with_legend': 'run t-SNE visualization and display a legend of all categories in the plot', 'run_tsne_neck_features': 'run t-SNE visualization on neck stage features with custom max samples per class'}
```

