# Agent Python Tools

- repo: huggingface/diffusers
- repo_uri: https://github.com/huggingface/diffusers

## File: huggingface_diffusers/tests/pipelines/z_image/test_z_image.py

Prompts

```
['run the ZImagePipelineFastTests unittest suite for Z-Image pipeline inference', 'create dummy ZImageTransformer2DModel, AutoencoderKL, scheduler, and Qwen3 text encoder components', 'create dummy inference inputs with prompt, guidance scale, and image dimensions', 'test ZImagePipeline inference and verify generated image shape and pixel values', 'test VAE tiling by comparing output with and without tiling enabled', 'test the ZImageImg2ImgPipeline inference by running the pipeline with dummy components and a prompt on CPU', 'test the ZImageImg2ImgPipeline batch inference with identical inputs to verify consistent output across batch sizes', 'test the ZImageImg2ImgPipeline strength parameter by comparing outputs with low and high strength values', 'test the ZImageImg2ImgPipeline VAE tiling by comparing outputs with and without tiling enabled', 'test the ZImageImg2ImgPipeline attention slicing by comparing outputs with different slice sizes', 'test the ZImageInpaintPipeline by running inference with dummy components and verifying output image shape', 'test the ZImageInpaintPipeline batch processing by generating multiple identical images and comparing results', 'test the ZImageInpaintPipeline strength parameter by comparing outputs with low and high strength values', 'test the ZImageInpaintPipeline mask inpainting by comparing full mask and no mask outputs', 'test the ZImageInpaintPipeline VAE tiling by comparing outputs with and without tiling enabled']
```

Usage

```
{'run_ZImagePipelineFastTests': 'run the ZImagePipelineFastTests unittest suite for Z-Image pipeline inference', 'create_get_dummy_components': 'create dummy ZImageTransformer2DModel, AutoencoderKL, scheduler, and Qwen3 text encoder components', 'create_get_dummy_inputs': 'create dummy inference inputs with prompt, guidance scale, and image dimensions', 'test_inference': 'test ZImagePipeline inference and verify generated image shape and pixel values', 'test_vae_tiling': 'test VAE tiling by comparing output with and without tiling enabled'}
```

## File: huggingface_diffusers/tests/pipelines/z_image/test_z_image_img2img.py

Prompts

```
['run the ZImagePipelineFastTests unittest suite for Z-Image pipeline inference', 'create dummy ZImageTransformer2DModel, AutoencoderKL, scheduler, and Qwen3 text encoder components', 'create dummy inference inputs with prompt, guidance scale, and image dimensions', 'test ZImagePipeline inference and verify generated image shape and pixel values', 'test VAE tiling by comparing output with and without tiling enabled', 'test the ZImageImg2ImgPipeline inference by running the pipeline with dummy components and a prompt on CPU', 'test the ZImageImg2ImgPipeline batch inference with identical inputs to verify consistent output across batch sizes', 'test the ZImageImg2ImgPipeline strength parameter by comparing outputs with low and high strength values', 'test the ZImageImg2ImgPipeline VAE tiling by comparing outputs with and without tiling enabled', 'test the ZImageImg2ImgPipeline attention slicing by comparing outputs with different slice sizes', 'test the ZImageInpaintPipeline by running inference with dummy components and verifying output image shape', 'test the ZImageInpaintPipeline batch processing by generating multiple identical images and comparing results', 'test the ZImageInpaintPipeline strength parameter by comparing outputs with low and high strength values', 'test the ZImageInpaintPipeline mask inpainting by comparing full mask and no mask outputs', 'test the ZImageInpaintPipeline VAE tiling by comparing outputs with and without tiling enabled']
```

Usage

```
{'test_ZImageImg2ImgPipeline_inference': 'test the ZImageImg2ImgPipeline inference by running the pipeline with dummy components and a prompt on CPU', 'test_ZImageImg2ImgPipeline_batch': 'test the ZImageImg2ImgPipeline batch inference with identical inputs to verify consistent output across batch sizes', 'test_ZImageImg2ImgPipeline_strength': 'test the ZImageImg2ImgPipeline strength parameter by comparing outputs with low and high strength values', 'test_ZImageImg2ImgPipeline_vae_tiling': 'test the ZImageImg2ImgPipeline VAE tiling by comparing outputs with and without tiling enabled', 'test_ZImageImg2ImgPipeline_attention_slicing': 'test the ZImageImg2ImgPipeline attention slicing by comparing outputs with different slice sizes'}
```

## File: huggingface_diffusers/tests/pipelines/z_image/test_z_image_inpaint.py

Prompts

```
['run the ZImagePipelineFastTests unittest suite for Z-Image pipeline inference', 'create dummy ZImageTransformer2DModel, AutoencoderKL, scheduler, and Qwen3 text encoder components', 'create dummy inference inputs with prompt, guidance scale, and image dimensions', 'test ZImagePipeline inference and verify generated image shape and pixel values', 'test VAE tiling by comparing output with and without tiling enabled', 'test the ZImageImg2ImgPipeline inference by running the pipeline with dummy components and a prompt on CPU', 'test the ZImageImg2ImgPipeline batch inference with identical inputs to verify consistent output across batch sizes', 'test the ZImageImg2ImgPipeline strength parameter by comparing outputs with low and high strength values', 'test the ZImageImg2ImgPipeline VAE tiling by comparing outputs with and without tiling enabled', 'test the ZImageImg2ImgPipeline attention slicing by comparing outputs with different slice sizes', 'test the ZImageInpaintPipeline by running inference with dummy components and verifying output image shape', 'test the ZImageInpaintPipeline batch processing by generating multiple identical images and comparing results', 'test the ZImageInpaintPipeline strength parameter by comparing outputs with low and high strength values', 'test the ZImageInpaintPipeline mask inpainting by comparing full mask and no mask outputs', 'test the ZImageInpaintPipeline VAE tiling by comparing outputs with and without tiling enabled']
```

Usage

```
{'test_zimage_inpaint_pipeline_inference': 'test the ZImageInpaintPipeline by running inference with dummy components and verifying output image shape', 'test_zimage_inpaint_batch_processing': 'test the ZImageInpaintPipeline batch processing by generating multiple identical images and comparing results', 'test_zimage_inpaint_strength_parameter': 'test the ZImageInpaintPipeline strength parameter by comparing outputs with low and high strength values', 'test_zimage_inpaint_mask_control': 'test the ZImageInpaintPipeline mask inpainting by comparing full mask and no mask outputs', 'test_zimage_inpaint_vae_tiling': 'test the ZImageInpaintPipeline VAE tiling by comparing outputs with and without tiling enabled'}
```

