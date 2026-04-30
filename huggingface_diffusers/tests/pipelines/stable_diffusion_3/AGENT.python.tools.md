# Agent Python Tools

- repo: huggingface/diffusers
- repo_uri: https://github.com/huggingface/diffusers

## File: huggingface_diffusers/tests/pipelines/stable_diffusion_3/test_pipeline_stable_diffusion_3.py

Prompts

```
['test the StableDiffusion3PipelineFastTests class to run inference with dummy components and verify output matches expected slice', "test the fused QKV projections in StableDiffusion3PipelineFastTests to verify fusion doesn't affect outputs", 'test the skip guidance layers feature in StableDiffusion3PipelineFastTests to verify outputs differ when layers are skipped', 'test the StableDiffusion3PipelineSlowTests class to run full model inference with pretrained SD3 medium model', 'run the StableDiffusion3Pipeline with a prompt to generate images using the flow match Euler discrete scheduler', 'run the StableDiffusion3Img2ImgPipelineFastTests to test inference with dummy components and expected output slices', 'run the StableDiffusion3Img2ImgPipelineSlowTests to test real SD3 img2img inference with pretrained models', 'test the StableDiffusion3Img2ImgPipeline inference by comparing generated image slices against expected values', 'create dummy SD3 components including transformer, text encoders, tokenizers, VAE, and scheduler for testing', 'review the StableDiffusion3Img2ImgPipeline test suite covering fast unit tests and slow integration tests', 'test the StableDiffusion3InpaintPipeline inference output matches expected values using dummy components', 'run the StableDiffusion3InpaintPipelineFastTests suite to validate inpainting pipeline behavior', 'create dummy SD3 transformer, CLIP encoders, T5 encoder, VAE, and scheduler for testing', 'create dummy image, mask, prompt, and generator inputs for SD3 inpainting pipeline tests', 'review the StableDiffusion3InpaintPipelineFastTests class and its test methods for coverage']
```

Usage

```
{'test_StableDiffusion3PipelineFastTests_inference': 'test the StableDiffusion3PipelineFastTests class to run inference with dummy components and verify output matches expected slice', 'test_StableDiffusion3PipelineFastTests_fused_qkv': "test the fused QKV projections in StableDiffusion3PipelineFastTests to verify fusion doesn't affect outputs", 'test_StableDiffusion3PipelineFastTests_skip_guidance': 'test the skip guidance layers feature in StableDiffusion3PipelineFastTests to verify outputs differ when layers are skipped', 'test_StableDiffusion3PipelineSlowTests_inference': 'test the StableDiffusion3PipelineSlowTests class to run full model inference with pretrained SD3 medium model', 'run_StableDiffusion3Pipeline_inference': 'run the StableDiffusion3Pipeline with a prompt to generate images using the flow match Euler discrete scheduler'}
```

## File: huggingface_diffusers/tests/pipelines/stable_diffusion_3/test_pipeline_stable_diffusion_3_img2img.py

Prompts

```
['test the StableDiffusion3PipelineFastTests class to run inference with dummy components and verify output matches expected slice', "test the fused QKV projections in StableDiffusion3PipelineFastTests to verify fusion doesn't affect outputs", 'test the skip guidance layers feature in StableDiffusion3PipelineFastTests to verify outputs differ when layers are skipped', 'test the StableDiffusion3PipelineSlowTests class to run full model inference with pretrained SD3 medium model', 'run the StableDiffusion3Pipeline with a prompt to generate images using the flow match Euler discrete scheduler', 'run the StableDiffusion3Img2ImgPipelineFastTests to test inference with dummy components and expected output slices', 'run the StableDiffusion3Img2ImgPipelineSlowTests to test real SD3 img2img inference with pretrained models', 'test the StableDiffusion3Img2ImgPipeline inference by comparing generated image slices against expected values', 'create dummy SD3 components including transformer, text encoders, tokenizers, VAE, and scheduler for testing', 'review the StableDiffusion3Img2ImgPipeline test suite covering fast unit tests and slow integration tests', 'test the StableDiffusion3InpaintPipeline inference output matches expected values using dummy components', 'run the StableDiffusion3InpaintPipelineFastTests suite to validate inpainting pipeline behavior', 'create dummy SD3 transformer, CLIP encoders, T5 encoder, VAE, and scheduler for testing', 'create dummy image, mask, prompt, and generator inputs for SD3 inpainting pipeline tests', 'review the StableDiffusion3InpaintPipelineFastTests class and its test methods for coverage']
```

Usage

```
{'run_sd3_img2img_fast_tests': 'run the StableDiffusion3Img2ImgPipelineFastTests to test inference with dummy components and expected output slices', 'run_sd3_img2img_slow_tests': 'run the StableDiffusion3Img2ImgPipelineSlowTests to test real SD3 img2img inference with pretrained models', 'test_sd3_img2img_inference': 'test the StableDiffusion3Img2ImgPipeline inference by comparing generated image slices against expected values', 'create_dummy_sd3_components': 'create dummy SD3 components including transformer, text encoders, tokenizers, VAE, and scheduler for testing', 'review_sd3_img2img_pipeline_tests': 'review the StableDiffusion3Img2ImgPipeline test suite covering fast unit tests and slow integration tests'}
```

## File: huggingface_diffusers/tests/pipelines/stable_diffusion_3/test_pipeline_stable_diffusion_3_inpaint.py

Prompts

```
['test the StableDiffusion3PipelineFastTests class to run inference with dummy components and verify output matches expected slice', "test the fused QKV projections in StableDiffusion3PipelineFastTests to verify fusion doesn't affect outputs", 'test the skip guidance layers feature in StableDiffusion3PipelineFastTests to verify outputs differ when layers are skipped', 'test the StableDiffusion3PipelineSlowTests class to run full model inference with pretrained SD3 medium model', 'run the StableDiffusion3Pipeline with a prompt to generate images using the flow match Euler discrete scheduler', 'run the StableDiffusion3Img2ImgPipelineFastTests to test inference with dummy components and expected output slices', 'run the StableDiffusion3Img2ImgPipelineSlowTests to test real SD3 img2img inference with pretrained models', 'test the StableDiffusion3Img2ImgPipeline inference by comparing generated image slices against expected values', 'create dummy SD3 components including transformer, text encoders, tokenizers, VAE, and scheduler for testing', 'review the StableDiffusion3Img2ImgPipeline test suite covering fast unit tests and slow integration tests', 'test the StableDiffusion3InpaintPipeline inference output matches expected values using dummy components', 'run the StableDiffusion3InpaintPipelineFastTests suite to validate inpainting pipeline behavior', 'create dummy SD3 transformer, CLIP encoders, T5 encoder, VAE, and scheduler for testing', 'create dummy image, mask, prompt, and generator inputs for SD3 inpainting pipeline tests', 'review the StableDiffusion3InpaintPipelineFastTests class and its test methods for coverage']
```

Usage

```
{'test_SD3_inpaint_pipeline_inference': 'test the StableDiffusion3InpaintPipeline inference output matches expected values using dummy components', 'run_SD3_inpaint_fast_tests': 'run the StableDiffusion3InpaintPipelineFastTests suite to validate inpainting pipeline behavior', 'create_dummy_components_for_SD3_inpaint': 'create dummy SD3 transformer, CLIP encoders, T5 encoder, VAE, and scheduler for testing', 'create_dummy_inputs_for_SD3_inpaint': 'create dummy image, mask, prompt, and generator inputs for SD3 inpainting pipeline tests', 'review_SD3_inpaint_test_class': 'review the StableDiffusion3InpaintPipelineFastTests class and its test methods for coverage'}
```

