# Agent Python Tools

- repo: facebookresearch/lightplane
- repo_uri: https://github.com/facebookresearch/lightplane

## File: facebookresearch_lightplane/lightplane/triton_src/templates/cog_util.py

Prompts

```
['generate a named Triton template file string from template name and layer counts for trunk, opacity, and color', 'generate a named splatter MLP file string from a template name and number of layers', 'build a comma-separated enumerated string with a given prefix and postfix for N items', 'generate a comma-separated string of weight and bias variable names for an MLP with N layers', 'generate a comma-separated string of gradient weight and bias variable names for an MLP with N layers', 'review the bw_kernel Triton JIT function for backward volumetric rendering gradient computation', 'summarize the bw_kernel backward pass logic including transmittance, opacity, and color gradient propagation', 'refactor the bw_kernel to support additional depth sampling strategies beyond inverse sphere and linear', 'review the load_mlp_params stub function that is overridden by cog-generated MLP parameter loading code', 'summarize the cog code generation template that auto-generates MLP forward and backward functions for trunk, opacity, and color heads', 'run the triton JIT forward rendering kernel to perform volumetric ray marching over feature grids', 'review the fw_kernel triton JIT function for volumetric ray marching and expected depth computation', 'summarize the fw_kernel forward pass logic including grid sampling, MLP evaluation, and color compositing', 'refactor the load_mlp_params placeholder function to load MLP weights from a custom tensor layout', 'test the mlp_trunk placeholder function after cog codegen generates the actual trunk MLP forward pass', 'review the bw_kernel_wMLP Triton JIT kernel for backward-pass gradient splatting with MLP layers', 'summarize how fwbw_splatter_init initializes ray sampling buffers for backward splatting kernels', 'review the cog template directives that auto-generate MLP parameter loading and gradient accumulation code', 'summarize how sample_grid_rep and splat_grid_rep sample and scatter gradients across 3D feature grids', 'run the Triton fw_kernel_wMLP to splat features through an MLP into a 3D grid', 'review the fw_kernel_wMLP Triton JIT function for MLP-augmented feature splatting']
```

Usage

```
{'generate_triton_template_file_name': 'generate a named Triton template file string from template name and layer counts for trunk, opacity, and color', 'generate_splatter_mlp_file_name': 'generate a named splatter MLP file string from a template name and number of layers', 'build_enumerated_variable_string': 'build a comma-separated enumerated string with a given prefix and postfix for N items', 'generate_mlp_weight_bias_string': 'generate a comma-separated string of weight and bias variable names for an MLP with N layers', 'generate_mlp_gradient_string': 'generate a comma-separated string of gradient weight and bias variable names for an MLP with N layers'}
```

## File: facebookresearch_lightplane/lightplane/triton_src/templates/renderer_bw.py

Prompts

```
['generate a named Triton template file string from template name and layer counts for trunk, opacity, and color', 'generate a named splatter MLP file string from a template name and number of layers', 'build a comma-separated enumerated string with a given prefix and postfix for N items', 'generate a comma-separated string of weight and bias variable names for an MLP with N layers', 'generate a comma-separated string of gradient weight and bias variable names for an MLP with N layers', 'review the bw_kernel Triton JIT function for backward volumetric rendering gradient computation', 'summarize the bw_kernel backward pass logic including transmittance, opacity, and color gradient propagation', 'refactor the bw_kernel to support additional depth sampling strategies beyond inverse sphere and linear', 'review the load_mlp_params stub function that is overridden by cog-generated MLP parameter loading code', 'summarize the cog code generation template that auto-generates MLP forward and backward functions for trunk, opacity, and color heads', 'run the triton JIT forward rendering kernel to perform volumetric ray marching over feature grids', 'review the fw_kernel triton JIT function for volumetric ray marching and expected depth computation', 'summarize the fw_kernel forward pass logic including grid sampling, MLP evaluation, and color compositing', 'refactor the load_mlp_params placeholder function to load MLP weights from a custom tensor layout', 'test the mlp_trunk placeholder function after cog codegen generates the actual trunk MLP forward pass', 'review the bw_kernel_wMLP Triton JIT kernel for backward-pass gradient splatting with MLP layers', 'summarize how fwbw_splatter_init initializes ray sampling buffers for backward splatting kernels', 'review the cog template directives that auto-generate MLP parameter loading and gradient accumulation code', 'summarize how sample_grid_rep and splat_grid_rep sample and scatter gradients across 3D feature grids', 'run the Triton fw_kernel_wMLP to splat features through an MLP into a 3D grid', 'review the fw_kernel_wMLP Triton JIT function for MLP-augmented feature splatting']
```

Usage

```
{'review_bw_kernel': 'review the bw_kernel Triton JIT function for backward volumetric rendering gradient computation', 'summarize_bw_kernel': 'summarize the bw_kernel backward pass logic including transmittance, opacity, and color gradient propagation', 'refactor_bw_kernel': 'refactor the bw_kernel to support additional depth sampling strategies beyond inverse sphere and linear', 'review_load_mlp_params': 'review the load_mlp_params stub function that is overridden by cog-generated MLP parameter loading code', 'summarize_cog_template': 'summarize the cog code generation template that auto-generates MLP forward and backward functions for trunk, opacity, and color heads'}
```

## File: facebookresearch_lightplane/lightplane/triton_src/templates/renderer_fw.py

Prompts

```
['generate a named Triton template file string from template name and layer counts for trunk, opacity, and color', 'generate a named splatter MLP file string from a template name and number of layers', 'build a comma-separated enumerated string with a given prefix and postfix for N items', 'generate a comma-separated string of weight and bias variable names for an MLP with N layers', 'generate a comma-separated string of gradient weight and bias variable names for an MLP with N layers', 'review the bw_kernel Triton JIT function for backward volumetric rendering gradient computation', 'summarize the bw_kernel backward pass logic including transmittance, opacity, and color gradient propagation', 'refactor the bw_kernel to support additional depth sampling strategies beyond inverse sphere and linear', 'review the load_mlp_params stub function that is overridden by cog-generated MLP parameter loading code', 'summarize the cog code generation template that auto-generates MLP forward and backward functions for trunk, opacity, and color heads', 'run the triton JIT forward rendering kernel to perform volumetric ray marching over feature grids', 'review the fw_kernel triton JIT function for volumetric ray marching and expected depth computation', 'summarize the fw_kernel forward pass logic including grid sampling, MLP evaluation, and color compositing', 'refactor the load_mlp_params placeholder function to load MLP weights from a custom tensor layout', 'test the mlp_trunk placeholder function after cog codegen generates the actual trunk MLP forward pass', 'review the bw_kernel_wMLP Triton JIT kernel for backward-pass gradient splatting with MLP layers', 'summarize how fwbw_splatter_init initializes ray sampling buffers for backward splatting kernels', 'review the cog template directives that auto-generate MLP parameter loading and gradient accumulation code', 'summarize how sample_grid_rep and splat_grid_rep sample and scatter gradients across 3D feature grids', 'run the Triton fw_kernel_wMLP to splat features through an MLP into a 3D grid', 'review the fw_kernel_wMLP Triton JIT function for MLP-augmented feature splatting']
```

Usage

```
{'run_fw_kernel': 'run the triton JIT forward rendering kernel to perform volumetric ray marching over feature grids', 'review_fw_kernel': 'review the fw_kernel triton JIT function for volumetric ray marching and expected depth computation', 'summarize_fw_kernel': 'summarize the fw_kernel forward pass logic including grid sampling, MLP evaluation, and color compositing', 'refactor_load_mlp_params': 'refactor the load_mlp_params placeholder function to load MLP weights from a custom tensor layout', 'test_mlp_trunk': 'test the mlp_trunk placeholder function after cog codegen generates the actual trunk MLP forward pass'}
```

## File: facebookresearch_lightplane/lightplane/triton_src/templates/splatter_bw.py

Prompts

```
['generate a named Triton template file string from template name and layer counts for trunk, opacity, and color', 'generate a named splatter MLP file string from a template name and number of layers', 'build a comma-separated enumerated string with a given prefix and postfix for N items', 'generate a comma-separated string of weight and bias variable names for an MLP with N layers', 'generate a comma-separated string of gradient weight and bias variable names for an MLP with N layers', 'review the bw_kernel Triton JIT function for backward volumetric rendering gradient computation', 'summarize the bw_kernel backward pass logic including transmittance, opacity, and color gradient propagation', 'refactor the bw_kernel to support additional depth sampling strategies beyond inverse sphere and linear', 'review the load_mlp_params stub function that is overridden by cog-generated MLP parameter loading code', 'summarize the cog code generation template that auto-generates MLP forward and backward functions for trunk, opacity, and color heads', 'run the triton JIT forward rendering kernel to perform volumetric ray marching over feature grids', 'review the fw_kernel triton JIT function for volumetric ray marching and expected depth computation', 'summarize the fw_kernel forward pass logic including grid sampling, MLP evaluation, and color compositing', 'refactor the load_mlp_params placeholder function to load MLP weights from a custom tensor layout', 'test the mlp_trunk placeholder function after cog codegen generates the actual trunk MLP forward pass', 'review the bw_kernel_wMLP Triton JIT kernel for backward-pass gradient splatting with MLP layers', 'summarize how fwbw_splatter_init initializes ray sampling buffers for backward splatting kernels', 'review the cog template directives that auto-generate MLP parameter loading and gradient accumulation code', 'summarize how sample_grid_rep and splat_grid_rep sample and scatter gradients across 3D feature grids', 'run the Triton fw_kernel_wMLP to splat features through an MLP into a 3D grid', 'review the fw_kernel_wMLP Triton JIT function for MLP-augmented feature splatting']
```

Usage

```
{'review_bw_kernel': 'review the bw_kernel Triton JIT kernel for backward-pass gradient splatting on feature grids', 'review_bw_kernel_wMLP': 'review the bw_kernel_wMLP Triton JIT kernel for backward-pass gradient splatting with MLP layers', 'summarize_fwbw_splatter_init': 'summarize how fwbw_splatter_init initializes ray sampling buffers for backward splatting kernels', 'review_cog_template': 'review the cog template directives that auto-generate MLP parameter loading and gradient accumulation code', 'summarize_sample_grid_rep': 'summarize how sample_grid_rep and splat_grid_rep sample and scatter gradients across 3D feature grids'}
```

## File: facebookresearch_lightplane/lightplane/triton_src/templates/splatter_fw.py

Prompts

```
['generate a named Triton template file string from template name and layer counts for trunk, opacity, and color', 'generate a named splatter MLP file string from a template name and number of layers', 'build a comma-separated enumerated string with a given prefix and postfix for N items', 'generate a comma-separated string of weight and bias variable names for an MLP with N layers', 'generate a comma-separated string of gradient weight and bias variable names for an MLP with N layers', 'review the bw_kernel Triton JIT function for backward volumetric rendering gradient computation', 'summarize the bw_kernel backward pass logic including transmittance, opacity, and color gradient propagation', 'refactor the bw_kernel to support additional depth sampling strategies beyond inverse sphere and linear', 'review the load_mlp_params stub function that is overridden by cog-generated MLP parameter loading code', 'summarize the cog code generation template that auto-generates MLP forward and backward functions for trunk, opacity, and color heads', 'run the triton JIT forward rendering kernel to perform volumetric ray marching over feature grids', 'review the fw_kernel triton JIT function for volumetric ray marching and expected depth computation', 'summarize the fw_kernel forward pass logic including grid sampling, MLP evaluation, and color compositing', 'refactor the load_mlp_params placeholder function to load MLP weights from a custom tensor layout', 'test the mlp_trunk placeholder function after cog codegen generates the actual trunk MLP forward pass', 'review the bw_kernel_wMLP Triton JIT kernel for backward-pass gradient splatting with MLP layers', 'summarize how fwbw_splatter_init initializes ray sampling buffers for backward splatting kernels', 'review the cog template directives that auto-generate MLP parameter loading and gradient accumulation code', 'summarize how sample_grid_rep and splat_grid_rep sample and scatter gradients across 3D feature grids', 'run the Triton fw_kernel_wMLP to splat features through an MLP into a 3D grid', 'review the fw_kernel_wMLP Triton JIT function for MLP-augmented feature splatting']
```

Usage

```
{'run_fw_kernel': 'run the Triton fw_kernel to splat features into a 3D grid along camera rays', 'run_fw_kernel_wMLP': 'run the Triton fw_kernel_wMLP to splat features through an MLP into a 3D grid', 'review_fw_kernel': 'review the fw_kernel Triton JIT function for ray marching and grid splatting logic', 'review_fw_kernel_wMLP': 'review the fw_kernel_wMLP Triton JIT function for MLP-augmented feature splatting', 'summarize_cog_template': 'summarize the cog code generation template that auto-generates MLP parameter loading and splatting code'}
```

