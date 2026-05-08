# Agent Python Tools

- repo: facebookresearch/pytorchvideo
- repo_uri: https://github.com/facebookresearch/pytorchvideo

## File: facebookresearch_pytorchvideo/pytorchvideo/accelerator/deployment/mobile_cpu/transmuter/transmuter_mobile_cpu.py

Prompts

```
['transmute a 1x1x1 pointwise nn.Conv3d module into an equivalent Conv3dPwBnAct for mobile CPU optimization', 'transmute a 3x3x3 depthwise nn.Conv3d module into an equivalent Conv3d3x3x3DwBnAct for mobile CPU optimization', 'transmute a temporal kernel 1 nn.Conv3d module into an equivalent Conv3dTemporalKernel1BnAct for mobile CPU optimization', 'transmute a 3x1x1 temporal nn.Conv3d module into an equivalent Conv3d3x1x1BnAct for mobile CPU optimization', 'transmute a 5x1x1 temporal nn.Conv3d module into an equivalent Conv3d5x1x1BnAct for mobile CPU optimization']
```

Usage

```
{'transmute_Conv3dPwBnAct': 'transmute a 1x1x1 pointwise nn.Conv3d module into an equivalent Conv3dPwBnAct for mobile CPU optimization', 'transmute_Conv3d3x3x3DwBnAct': 'transmute a 3x3x3 depthwise nn.Conv3d module into an equivalent Conv3d3x3x3DwBnAct for mobile CPU optimization', 'transmute_Conv3dTemporalKernel1BnAct': 'transmute a temporal kernel 1 nn.Conv3d module into an equivalent Conv3dTemporalKernel1BnAct for mobile CPU optimization', 'transmute_Conv3d3x1x1BnAct': 'transmute a 3x1x1 temporal nn.Conv3d module into an equivalent Conv3d3x1x1BnAct for mobile CPU optimization', 'transmute_Conv3d5x1x1BnAct': 'transmute a 5x1x1 temporal nn.Conv3d module into an equivalent Conv3d5x1x1BnAct for mobile CPU optimization'}
```

