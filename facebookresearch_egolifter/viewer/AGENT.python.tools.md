# Agent Python Tools

- repo: facebookresearch/egolifter
- repo_uri: https://github.com/facebookresearch/egolifter

## File: facebookresearch_egolifter/viewer/client.py

Prompts

```
['calculate canvas and image dimensions from max resolution, aspect ratio, and lock aspect settings', 'create a ClientThread to handle rendering and sending images for a viser viewer client', 'render a 3D Gaussian Splatting scene from the current camera pose and send to client', 'get the current render resolution and JPEG quality based on low or high state', 'stop a running ClientThread by setting the stop_client flag to true', 'create a ViewerRenderer instance with a VanillaGaussian model for 3D Gaussian Splatting rendering', 'run get_outputs on a ViewerRenderer to render a camera view with an optional scaling modifier', 'review the ViewerRenderer class init method to understand how it stores the VanillaGaussian model', 'summarize the ViewerRenderer class which wraps a VanillaGaussian model and provides camera-based rendering outputs', 'refactor the get_outputs method to fix missing self.renderer and self.gaussian_model attribute references']
```

Usage

```
{'get_sizes': 'calculate canvas and image dimensions from max resolution, aspect ratio, and lock aspect settings', 'create_ClientThread': 'create a ClientThread to handle rendering and sending images for a viser viewer client', 'render_and_send': 'render a 3D Gaussian Splatting scene from the current camera pose and send to client', 'get_render_options': 'get the current render resolution and JPEG quality based on low or high state', 'stop_ClientThread': 'stop a running ClientThread by setting the stop_client flag to true'}
```

## File: facebookresearch_egolifter/viewer/renderer.py

Prompts

```
['calculate canvas and image dimensions from max resolution, aspect ratio, and lock aspect settings', 'create a ClientThread to handle rendering and sending images for a viser viewer client', 'render a 3D Gaussian Splatting scene from the current camera pose and send to client', 'get the current render resolution and JPEG quality based on low or high state', 'stop a running ClientThread by setting the stop_client flag to true', 'create a ViewerRenderer instance with a VanillaGaussian model for 3D Gaussian Splatting rendering', 'run get_outputs on a ViewerRenderer to render a camera view with an optional scaling modifier', 'review the ViewerRenderer class init method to understand how it stores the VanillaGaussian model', 'summarize the ViewerRenderer class which wraps a VanillaGaussian model and provides camera-based rendering outputs', 'refactor the get_outputs method to fix missing self.renderer and self.gaussian_model attribute references']
```

Usage

```
{'create_ViewerRenderer': 'create a ViewerRenderer instance with a VanillaGaussian model for 3D Gaussian Splatting rendering', 'run_get_outputs': 'run get_outputs on a ViewerRenderer to render a camera view with an optional scaling modifier', 'review_ViewerRenderer_init': 'review the ViewerRenderer class init method to understand how it stores the VanillaGaussian model', 'summarize_ViewerRenderer': 'summarize the ViewerRenderer class which wraps a VanillaGaussian model and provides camera-based rendering outputs', 'refactor_get_outputs': 'refactor the get_outputs method to fix missing self.renderer and self.gaussian_model attribute references'}
```

