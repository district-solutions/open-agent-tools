# Agent Python Tools

- repo: huggingface/diffusers
- repo_uri: https://github.com/huggingface/diffusers

## File: huggingface_diffusers/tests/modular_pipelines/stable_diffusion_xl/test_modular_pipeline_stable_diffusion_xl.py

Prompts

```
['test the SDXL modular pipeline by running Euler denoising and validating output image shape and slice values', 'test IP Adapter integration by verifying single and multi adapter scaling produces expected output differences', 'test ControlNet integration by verifying conditioning scale zero matches baseline and non-zero scale changes output', 'test the SDXL text-to-image modular pipeline fast tests with dummy inputs and expected Euler output slices', 'test the SDXL image-to-image modular pipeline fast tests with strength parameter and expected output slices']
```

Usage

```
{'test_SDXLModularTesterMixin': 'test the SDXL modular pipeline by running Euler denoising and validating output image shape and slice values', 'test_SDXLModularIPAdapterTesterMixin': 'test IP Adapter integration by verifying single and multi adapter scaling produces expected output differences', 'test_SDXLModularControlNetTesterMixin': 'test ControlNet integration by verifying conditioning scale zero matches baseline and non-zero scale changes output', 'test_TestSDXLModularPipelineFast': 'test the SDXL text-to-image modular pipeline fast tests with dummy inputs and expected Euler output slices', 'test_TestSDXLImg2ImgModularPipelineFast': 'test the SDXL image-to-image modular pipeline fast tests with strength parameter and expected output slices'}
```

