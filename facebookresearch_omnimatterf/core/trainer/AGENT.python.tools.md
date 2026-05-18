# Agent Python Tools

- repo: facebookresearch/omnimatterf
- repo_uri: https://github.com/facebookresearch/omnimatterf

## File: facebookresearch_omnimatterf/core/trainer/matting_trainer.py

Prompts

```
['build a MattingTrainer instance to train foreground and background matting models with configurable batch sizes', 'create prerendered background tensors for all dataset images and cache them as .pth files', 'train the background model by sampling rays from background-masked regions and computing RGB and depth losses', 'train the foreground matting model by rendering sparse foreground and background samples with optional BG gradient updates', 'render a full composite image by combining prerendered background with foreground alpha compositing']
```

Usage

```
{'build_matting_trainer': 'build a MattingTrainer instance to train foreground and background matting models with configurable batch sizes', 'create_prerendered_background': 'create prerendered background tensors for all dataset images and cache them as .pth files', 'train_background_model': 'train the background model by sampling rays from background-masked regions and computing RGB and depth losses', 'train_foreground_model': 'train the foreground matting model by rendering sparse foreground and background samples with optional BG gradient updates', 'render_composite_image': 'render a full composite image by combining prerendered background with foreground alpha compositing'}
```

