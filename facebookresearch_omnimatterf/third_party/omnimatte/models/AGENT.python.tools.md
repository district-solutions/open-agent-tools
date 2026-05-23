# Agent Python Tools

- repo: facebookresearch/omnimatterf
- repo_uri: https://github.com/facebookresearch/omnimatterf

## File: facebookresearch_omnimatterf/third_party/omnimatte/models/networks.py

Prompts

```
['build an Omnimatte UNet model for video decomposition with configurable feature channels and normalization', 'run a forward pass through the Omnimatte layered neural renderer to composite RGBA and flow outputs', 'render a single layer through the Omnimatte UNet to get RGBA output and flow predictions', 'warp a tensor using optical flow in pixel space with grid sampling', 'define and initialize an Omnimatte network with optional multi-GPU support and batch normalization', 'run the OmnimatteModel forward pass to compute reconstruction, alpha composites, and layer flow outputs', 'train the OmnimatteModel by calling optimize_parameters which runs forward, backward, and optimizer step', 'get the final RGBA layers, masks, and flow results after detail transfer for each decomposed layer', 'configure commandline training options including loss weights, alpha regularization, and camera adjustment parameters']
```

Usage

```
{'build_omnimatte_model': 'build an Omnimatte UNet model for video decomposition with configurable feature channels and normalization', 'run_omnimatte_forward': 'run a forward pass through the Omnimatte layered neural renderer to composite RGBA and flow outputs', 'render_single_layer': 'render a single layer through the Omnimatte UNet to get RGBA output and flow predictions', 'warp_tensor_with_flow': 'warp a tensor using optical flow in pixel space with grid sampling', 'define_omnimatte_network': 'define and initialize an Omnimatte network with optional multi-GPU support and batch normalization'}
```

## File: facebookresearch_omnimatterf/third_party/omnimatte/models/omnimatte_model.py

Prompts

```
['build an Omnimatte UNet model for video decomposition with configurable feature channels and normalization', 'run a forward pass through the Omnimatte layered neural renderer to composite RGBA and flow outputs', 'render a single layer through the Omnimatte UNet to get RGBA output and flow predictions', 'warp a tensor using optical flow in pixel space with grid sampling', 'define and initialize an Omnimatte network with optional multi-GPU support and batch normalization', 'run the OmnimatteModel forward pass to compute reconstruction, alpha composites, and layer flow outputs', 'train the OmnimatteModel by calling optimize_parameters which runs forward, backward, and optimizer step', 'get the final RGBA layers, masks, and flow results after detail transfer for each decomposed layer', 'configure commandline training options including loss weights, alpha regularization, and camera adjustment parameters']
```

Usage

```
{'build_omnimatte_model': 'build a layered neural rendering model to decompose video into RGBA layers with alpha masks', 'run_forward_pass': 'run the OmnimatteModel forward pass to compute reconstruction, alpha composites, and layer flow outputs', 'train_omnimatte_model': 'train the OmnimatteModel by calling optimize_parameters which runs forward, backward, and optimizer step', 'get_layer_results': 'get the final RGBA layers, masks, and flow results after detail transfer for each decomposed layer', 'configure_training_options': 'configure commandline training options including loss weights, alpha regularization, and camera adjustment parameters'}
```

