# Agent Python Tools

- repo: huggingface/diffusers
- repo_uri: https://github.com/huggingface/diffusers

## File: huggingface_diffusers/tests/pipelines/controlnet_flux/test_controlnet_flux.py

Prompts

```
['run the FluxControlNetPipeline fast tests with dummy components and verify image output shape', 'test the FluxControlNetPipeline with a canny edge control image and precomputed prompt embeddings', 'create dummy FluxTransformer2DModel and FluxControlNetModel components with minimal configuration for testing', 'run the FluxControlNetPipeline and verify output image dimensions match expected height and width', 'test the FluxControlNetPipeline with control image and conditioning scale parameters for image generation', 'test FluxControlNetImg2ImgPipeline produces different outputs when given different prompts', 'test that fusing and unfusing QKV projections does not change pipeline outputs', 'test that FluxControlNetImg2ImgPipeline output image shape matches expected dimensions', 'create dummy transformer, text encoders, VAE, ControlNet, and scheduler components for testing', 'create dummy input tensors and parameters for FluxControlNetImg2ImgPipeline inference', 'test the FluxControlNetInpaintPipeline class for inpainting with controlnet guidance and mask images', 'create dummy transformer, text encoder, VAE, controlnet and scheduler components for pipeline testing', 'create dummy input tensors including image, mask, control image and prompt for pipeline inference', 'test the FluxControlNetInpaintPipeline generates multiple images per prompt with correct batch shape', 'test that changing controlnet_conditioning_scale parameter produces different inpainting output results']
```

Usage

```
{'run_FluxControlNetPipeline_fast_tests': 'run the FluxControlNetPipeline fast tests with dummy components and verify image output shape', 'test_FluxControlNetPipeline_canny': 'test the FluxControlNetPipeline with a canny edge control image and precomputed prompt embeddings', 'create_FluxTransformer2DModel_components': 'create dummy FluxTransformer2DModel and FluxControlNetModel components with minimal configuration for testing', 'run_FluxControlNetPipeline_image_output_shape': 'run the FluxControlNetPipeline and verify output image dimensions match expected height and width', 'test_FluxControlNetPipeline_conditioning': 'test the FluxControlNetPipeline with control image and conditioning scale parameters for image generation'}
```

## File: huggingface_diffusers/tests/pipelines/controlnet_flux/test_controlnet_flux_img2img.py

Prompts

```
['run the FluxControlNetPipeline fast tests with dummy components and verify image output shape', 'test the FluxControlNetPipeline with a canny edge control image and precomputed prompt embeddings', 'create dummy FluxTransformer2DModel and FluxControlNetModel components with minimal configuration for testing', 'run the FluxControlNetPipeline and verify output image dimensions match expected height and width', 'test the FluxControlNetPipeline with control image and conditioning scale parameters for image generation', 'test FluxControlNetImg2ImgPipeline produces different outputs when given different prompts', 'test that fusing and unfusing QKV projections does not change pipeline outputs', 'test that FluxControlNetImg2ImgPipeline output image shape matches expected dimensions', 'create dummy transformer, text encoders, VAE, ControlNet, and scheduler components for testing', 'create dummy input tensors and parameters for FluxControlNetImg2ImgPipeline inference', 'test the FluxControlNetInpaintPipeline class for inpainting with controlnet guidance and mask images', 'create dummy transformer, text encoder, VAE, controlnet and scheduler components for pipeline testing', 'create dummy input tensors including image, mask, control image and prompt for pipeline inference', 'test the FluxControlNetInpaintPipeline generates multiple images per prompt with correct batch shape', 'test that changing controlnet_conditioning_scale parameter produces different inpainting output results']
```

Usage

```
{'test_FluxControlNetImg2ImgPipeline_different_prompts': 'test FluxControlNetImg2ImgPipeline produces different outputs when given different prompts', 'test_FluxControlNetImg2ImgPipeline_fused_qkv_projections': 'test that fusing and unfusing QKV projections does not change pipeline outputs', 'test_FluxControlNetImg2ImgPipeline_image_output_shape': 'test that FluxControlNetImg2ImgPipeline output image shape matches expected dimensions', 'create_dummy_components_FluxControlNetImg2ImgPipeline': 'create dummy transformer, text encoders, VAE, ControlNet, and scheduler components for testing', 'create_dummy_inputs_FluxControlNetImg2ImgPipeline': 'create dummy input tensors and parameters for FluxControlNetImg2ImgPipeline inference'}
```

## File: huggingface_diffusers/tests/pipelines/controlnet_flux/test_controlnet_flux_inpaint.py

Prompts

```
['run the FluxControlNetPipeline fast tests with dummy components and verify image output shape', 'test the FluxControlNetPipeline with a canny edge control image and precomputed prompt embeddings', 'create dummy FluxTransformer2DModel and FluxControlNetModel components with minimal configuration for testing', 'run the FluxControlNetPipeline and verify output image dimensions match expected height and width', 'test the FluxControlNetPipeline with control image and conditioning scale parameters for image generation', 'test FluxControlNetImg2ImgPipeline produces different outputs when given different prompts', 'test that fusing and unfusing QKV projections does not change pipeline outputs', 'test that FluxControlNetImg2ImgPipeline output image shape matches expected dimensions', 'create dummy transformer, text encoders, VAE, ControlNet, and scheduler components for testing', 'create dummy input tensors and parameters for FluxControlNetImg2ImgPipeline inference', 'test the FluxControlNetInpaintPipeline class for inpainting with controlnet guidance and mask images', 'create dummy transformer, text encoder, VAE, controlnet and scheduler components for pipeline testing', 'create dummy input tensors including image, mask, control image and prompt for pipeline inference', 'test the FluxControlNetInpaintPipeline generates multiple images per prompt with correct batch shape', 'test that changing controlnet_conditioning_scale parameter produces different inpainting output results']
```

Usage

```
{'test_FluxControlNetInpaintPipeline': 'test the FluxControlNetInpaintPipeline class for inpainting with controlnet guidance and mask images', 'run_get_dummy_components': 'create dummy transformer, text encoder, VAE, controlnet and scheduler components for pipeline testing', 'run_get_dummy_inputs': 'create dummy input tensors including image, mask, control image and prompt for pipeline inference', 'test_num_images_per_prompt': 'test the FluxControlNetInpaintPipeline generates multiple images per prompt with correct batch shape', 'test_controlnet_conditioning_scale': 'test that changing controlnet_conditioning_scale parameter produces different inpainting output results'}
```

