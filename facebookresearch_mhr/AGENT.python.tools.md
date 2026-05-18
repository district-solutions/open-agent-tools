# Agent Python Tools

- repo: facebookresearch/mhr
- repo_uri: https://github.com/facebookresearch/mhr

## File: facebookresearch_mhr/demo.py

Prompts

```
['run the MHR demo to generate and export a 3D character mesh as a PLY file', 'create random identity, model parameter, and face expression coefficient tensors for a given batch size', 'load an MHR model from files using MHR.from_files with a specified device and level of detail', 'call the MHR model with identity, model, and expression coefficients to get vertices and skeletal state', 'compare native MHR model output against a TorchScript-serialized model and print per-vertex offset statistics']
```

Usage

```
{'run_MHR_demo': 'run the MHR demo to generate and export a 3D character mesh as a PLY file', 'prepare_input_data': 'create random identity, model parameter, and face expression coefficient tensors for a given batch size', 'load_MHR_from_files': 'load an MHR model from files using MHR.from_files with a specified device and level of detail', 'forward_MHR_model': 'call the MHR model with identity, model, and expression coefficients to get vertices and skeletal state', 'compare_torchscript_model': 'compare native MHR model output against a TorchScript-serialized model and print per-vertex offset statistics'}
```

