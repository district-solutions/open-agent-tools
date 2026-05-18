# Agent Python Tools

- repo: facebookresearch/omnimatterf
- repo_uri: https://github.com/facebookresearch/omnimatterf

## File: facebookresearch_omnimatterf/core/utils/omnimatte_utils.py

Prompts

```
['render foreground layers with Omnimatte using a matting dataset, batch data, and foreground inference function', 'review the render_omnimatte_fg function to understand how it composites RGBA layers with background flow', 'summarize the render_omnimatte_fg function that renders foreground and background layers with alpha compositing', 'test the render_omnimatte_fg function with a MattingDataset batch and foreground inference callback', 'refactor the render_omnimatte_fg function to support additional background rendering modes beyond homography', 'create an MLPRender_Fea_Switchable instance with configurable viewpe skip steps for gradual view direction training', 'run the forward pass of MLPRender_Fea_Switchable to compute RGB from points, viewdirs, and features', 'create a MyTensorVMSplit tensor volume model with viewpe skip steps for deferred view direction encoding', 'run the forward pass of MyTensorVMSplit to render rays with automatic global step tracking', 'query rendered RGB values from MyTensorVMSplit given 3D points and view directions', 'convert a single frame dictionary of tensors to a batch by prepending a dimension', 'extract a single frame from a batch dictionary of tensors by index', 'summarize the frame_to_batch function that adds a batch dimension to tensor dictionaries', 'summarize the batch_to_frame function that extracts a frame from a batch by index', 'review the trainer_utils module containing frame and batch conversion helper functions']
```

Usage

```
{'render_omnimatte_fg': 'render foreground layers with Omnimatte using a matting dataset, batch data, and foreground inference function', 'review_render_omnimatte_fg': 'review the render_omnimatte_fg function to understand how it composites RGBA layers with background flow', 'summarize_render_omnimatte_fg': 'summarize the render_omnimatte_fg function that renders foreground and background layers with alpha compositing', 'test_render_omnimatte_fg': 'test the render_omnimatte_fg function with a MattingDataset batch and foreground inference callback', 'refactor_render_omnimatte_fg': 'refactor the render_omnimatte_fg function to support additional background rendering modes beyond homography'}
```

## File: facebookresearch_omnimatterf/core/utils/tensorf_utils.py

Prompts

```
['render foreground layers with Omnimatte using a matting dataset, batch data, and foreground inference function', 'review the render_omnimatte_fg function to understand how it composites RGBA layers with background flow', 'summarize the render_omnimatte_fg function that renders foreground and background layers with alpha compositing', 'test the render_omnimatte_fg function with a MattingDataset batch and foreground inference callback', 'refactor the render_omnimatte_fg function to support additional background rendering modes beyond homography', 'create an MLPRender_Fea_Switchable instance with configurable viewpe skip steps for gradual view direction training', 'run the forward pass of MLPRender_Fea_Switchable to compute RGB from points, viewdirs, and features', 'create a MyTensorVMSplit tensor volume model with viewpe skip steps for deferred view direction encoding', 'run the forward pass of MyTensorVMSplit to render rays with automatic global step tracking', 'query rendered RGB values from MyTensorVMSplit given 3D points and view directions', 'convert a single frame dictionary of tensors to a batch by prepending a dimension', 'extract a single frame from a batch dictionary of tensors by index', 'summarize the frame_to_batch function that adds a batch dimension to tensor dictionaries', 'summarize the batch_to_frame function that extracts a frame from a batch by index', 'review the trainer_utils module containing frame and batch conversion helper functions']
```

Usage

```
{'create_MLPRender_Fea_Switchable': 'create an MLPRender_Fea_Switchable instance with configurable viewpe skip steps for gradual view direction training', 'forward_MLPRender_Fea_Switchable': 'run the forward pass of MLPRender_Fea_Switchable to compute RGB from points, viewdirs, and features', 'create_MyTensorVMSplit': 'create a MyTensorVMSplit tensor volume model with viewpe skip steps for deferred view direction encoding', 'forward_MyTensorVMSplit': 'run the forward pass of MyTensorVMSplit to render rays with automatic global step tracking', 'query_render_rgb_MyTensorVMSplit': 'query rendered RGB values from MyTensorVMSplit given 3D points and view directions'}
```

## File: facebookresearch_omnimatterf/core/utils/trainer_utils.py

Prompts

```
['render foreground layers with Omnimatte using a matting dataset, batch data, and foreground inference function', 'review the render_omnimatte_fg function to understand how it composites RGBA layers with background flow', 'summarize the render_omnimatte_fg function that renders foreground and background layers with alpha compositing', 'test the render_omnimatte_fg function with a MattingDataset batch and foreground inference callback', 'refactor the render_omnimatte_fg function to support additional background rendering modes beyond homography', 'create an MLPRender_Fea_Switchable instance with configurable viewpe skip steps for gradual view direction training', 'run the forward pass of MLPRender_Fea_Switchable to compute RGB from points, viewdirs, and features', 'create a MyTensorVMSplit tensor volume model with viewpe skip steps for deferred view direction encoding', 'run the forward pass of MyTensorVMSplit to render rays with automatic global step tracking', 'query rendered RGB values from MyTensorVMSplit given 3D points and view directions', 'convert a single frame dictionary of tensors to a batch by prepending a dimension', 'extract a single frame from a batch dictionary of tensors by index', 'summarize the frame_to_batch function that adds a batch dimension to tensor dictionaries', 'summarize the batch_to_frame function that extracts a frame from a batch by index', 'review the trainer_utils module containing frame and batch conversion helper functions']
```

Usage

```
{'convert_frame_to_batch': 'convert a single frame dictionary of tensors to a batch by prepending a dimension', 'convert_batch_to_frame': 'extract a single frame from a batch dictionary of tensors by index', 'summarize_frame_to_batch': 'summarize the frame_to_batch function that adds a batch dimension to tensor dictionaries', 'summarize_batch_to_frame': 'summarize the batch_to_frame function that extracts a frame from a batch by index', 'review_trainer_utils': 'review the trainer_utils module containing frame and batch conversion helper functions'}
```

