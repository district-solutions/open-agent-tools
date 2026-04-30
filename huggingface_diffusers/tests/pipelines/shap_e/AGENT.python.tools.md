# Agent Python Tools

- repo: huggingface/diffusers
- repo_uri: https://github.com/huggingface/diffusers

## File: huggingface_diffusers/tests/pipelines/shap_e/test_shap_e.py

Prompts

```
['test the ShapEPipeline with dummy components and verify output image shape and pixel values', 'test the ShapEPipeline integration with the pretrained openai/shap-e model and compare against expected output', 'test the ShapEPipeline num_images_per_prompt parameter to verify batch image generation output count', 'test the ShapEPipeline inference batch consistency across batch sizes 1 and 2', 'test the ShapEPipeline float16 inference and verify output matches expected maximum difference threshold', 'run the ShapEImg2ImgPipeline fast test with dummy components and verify output shape and pixel values', 'create a PriorTransformer dummy model with configurable attention heads and embedding dimensions for testing', 'create a ShapERenderer dummy model with param shapes and latent dimensions for testing', 'create a CLIPVisionModel dummy image encoder with configurable hidden size and attention heads', 'run the ShapEImg2ImgPipeline integration test using pretrained openai/shap-e-img2img model with guidance scale and inference steps']
```

Usage

```
{'test_shap_e_pipeline': 'test the ShapEPipeline with dummy components and verify output image shape and pixel values', 'test_shap_e_integration': 'test the ShapEPipeline integration with the pretrained openai/shap-e model and compare against expected output', 'test_num_images_per_prompt': 'test the ShapEPipeline num_images_per_prompt parameter to verify batch image generation output count', 'test_inference_batch_consistent': 'test the ShapEPipeline inference batch consistency across batch sizes 1 and 2', 'test_float16_inference': 'test the ShapEPipeline float16 inference and verify output matches expected maximum difference threshold'}
```

## File: huggingface_diffusers/tests/pipelines/shap_e/test_shap_e_img2img.py

Prompts

```
['test the ShapEPipeline with dummy components and verify output image shape and pixel values', 'test the ShapEPipeline integration with the pretrained openai/shap-e model and compare against expected output', 'test the ShapEPipeline num_images_per_prompt parameter to verify batch image generation output count', 'test the ShapEPipeline inference batch consistency across batch sizes 1 and 2', 'test the ShapEPipeline float16 inference and verify output matches expected maximum difference threshold', 'run the ShapEImg2ImgPipeline fast test with dummy components and verify output shape and pixel values', 'create a PriorTransformer dummy model with configurable attention heads and embedding dimensions for testing', 'create a ShapERenderer dummy model with param shapes and latent dimensions for testing', 'create a CLIPVisionModel dummy image encoder with configurable hidden size and attention heads', 'run the ShapEImg2ImgPipeline integration test using pretrained openai/shap-e-img2img model with guidance scale and inference steps']
```

Usage

```
{'test_shap_e_img2img_pipeline': 'run the ShapEImg2ImgPipeline fast test with dummy components and verify output shape and pixel values', 'test_dummy_prior_components': 'create a PriorTransformer dummy model with configurable attention heads and embedding dimensions for testing', 'test_dummy_renderer_components': 'create a ShapERenderer dummy model with param shapes and latent dimensions for testing', 'test_dummy_image_encoder': 'create a CLIPVisionModel dummy image encoder with configurable hidden size and attention heads', 'test_integration_shap_e_img2img': 'run the ShapEImg2ImgPipeline integration test using pretrained openai/shap-e-img2img model with guidance scale and inference steps'}
```

