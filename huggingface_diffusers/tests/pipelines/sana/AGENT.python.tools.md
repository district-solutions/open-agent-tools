# Agent Python Tools

- repo: huggingface/diffusers
- repo_uri: https://github.com/huggingface/diffusers

## File: huggingface_diffusers/tests/pipelines/sana/test_sana.py

Prompts

```
['run the SanaPipelineFastTests unittest class to test SanaPipeline with dummy transformer, VAE, and scheduler components', 'run the SanaPipelineIntegrationTests to validate Sana 1024px and 512px pretrained models against expected output slices', 'test the SanaPipeline callback_on_step_end functionality to verify tensor inputs passed during each inference step', 'test the SanaPipeline attention slicing forward pass to verify slicing does not affect inference results', 'test the SanaPipeline VAE tiling feature to verify tiled decoding produces results close to non-tiled decoding', 'run the SanaControlNetPipeline inference test with dummy components and a control image', 'test the SanaControlNetPipeline callback on step end tensor inputs functionality', 'test the SanaControlNetPipeline attention slicing forward pass with different slice sizes', 'test the SanaControlNetPipeline VAE tiling with tile sample height and width parameters', 'test the SanaControlNetPipeline float16 inference with higher tolerance for dtype sensitivity', 'test the SanaSprintPipeline inference by running the pipeline with dummy components and verifying generated image shape', 'test the SanaSprintPipeline callback on step end functionality by passing tensor inputs and validating callback behavior', 'test the SanaSprintPipeline attention slicing forward pass by comparing outputs with and without slicing enabled', 'test the SanaSprintPipeline VAE tiling by enabling tiling and comparing outputs with and without tiling', 'test the SanaSprintPipeline float16 inference by running the pipeline in half precision and checking output differences', 'test the SanaSprintImg2ImgPipeline inference by running dummy components and validating output image shape', 'test float16 inference with higher tolerance for dtype sensitivity in the pipeline']
```

Usage

```
{'run_SanaPipeline_fast_tests': 'run the SanaPipelineFastTests unittest class to test SanaPipeline with dummy transformer, VAE, and scheduler components', 'run_SanaPipeline_integration_tests': 'run the SanaPipelineIntegrationTests to validate Sana 1024px and 512px pretrained models against expected output slices', 'test_callback_inputs': 'test the SanaPipeline callback_on_step_end functionality to verify tensor inputs passed during each inference step', 'test_attention_slicing': 'test the SanaPipeline attention slicing forward pass to verify slicing does not affect inference results', 'test_vae_tiling': 'test the SanaPipeline VAE tiling feature to verify tiled decoding produces results close to non-tiled decoding'}
```

## File: huggingface_diffusers/tests/pipelines/sana/test_sana_controlnet.py

Prompts

```
['run the SanaPipelineFastTests unittest class to test SanaPipeline with dummy transformer, VAE, and scheduler components', 'run the SanaPipelineIntegrationTests to validate Sana 1024px and 512px pretrained models against expected output slices', 'test the SanaPipeline callback_on_step_end functionality to verify tensor inputs passed during each inference step', 'test the SanaPipeline attention slicing forward pass to verify slicing does not affect inference results', 'test the SanaPipeline VAE tiling feature to verify tiled decoding produces results close to non-tiled decoding', 'run the SanaControlNetPipeline inference test with dummy components and a control image', 'test the SanaControlNetPipeline callback on step end tensor inputs functionality', 'test the SanaControlNetPipeline attention slicing forward pass with different slice sizes', 'test the SanaControlNetPipeline VAE tiling with tile sample height and width parameters', 'test the SanaControlNetPipeline float16 inference with higher tolerance for dtype sensitivity', 'test the SanaSprintPipeline inference by running the pipeline with dummy components and verifying generated image shape', 'test the SanaSprintPipeline callback on step end functionality by passing tensor inputs and validating callback behavior', 'test the SanaSprintPipeline attention slicing forward pass by comparing outputs with and without slicing enabled', 'test the SanaSprintPipeline VAE tiling by enabling tiling and comparing outputs with and without tiling', 'test the SanaSprintPipeline float16 inference by running the pipeline in half precision and checking output differences', 'test the SanaSprintImg2ImgPipeline inference by running dummy components and validating output image shape', 'test float16 inference with higher tolerance for dtype sensitivity in the pipeline']
```

Usage

```
{'run_sana_controlnet_inference': 'run the SanaControlNetPipeline inference test with dummy components and a control image', 'test_sana_controlnet_callback_inputs': 'test the SanaControlNetPipeline callback on step end tensor inputs functionality', 'test_sana_controlnet_attention_slicing': 'test the SanaControlNetPipeline attention slicing forward pass with different slice sizes', 'test_sana_controlnet_vae_tiling': 'test the SanaControlNetPipeline VAE tiling with tile sample height and width parameters', 'test_sana_controlnet_float16': 'test the SanaControlNetPipeline float16 inference with higher tolerance for dtype sensitivity'}
```

## File: huggingface_diffusers/tests/pipelines/sana/test_sana_sprint.py

Prompts

```
['run the SanaPipelineFastTests unittest class to test SanaPipeline with dummy transformer, VAE, and scheduler components', 'run the SanaPipelineIntegrationTests to validate Sana 1024px and 512px pretrained models against expected output slices', 'test the SanaPipeline callback_on_step_end functionality to verify tensor inputs passed during each inference step', 'test the SanaPipeline attention slicing forward pass to verify slicing does not affect inference results', 'test the SanaPipeline VAE tiling feature to verify tiled decoding produces results close to non-tiled decoding', 'run the SanaControlNetPipeline inference test with dummy components and a control image', 'test the SanaControlNetPipeline callback on step end tensor inputs functionality', 'test the SanaControlNetPipeline attention slicing forward pass with different slice sizes', 'test the SanaControlNetPipeline VAE tiling with tile sample height and width parameters', 'test the SanaControlNetPipeline float16 inference with higher tolerance for dtype sensitivity', 'test the SanaSprintPipeline inference by running the pipeline with dummy components and verifying generated image shape', 'test the SanaSprintPipeline callback on step end functionality by passing tensor inputs and validating callback behavior', 'test the SanaSprintPipeline attention slicing forward pass by comparing outputs with and without slicing enabled', 'test the SanaSprintPipeline VAE tiling by enabling tiling and comparing outputs with and without tiling', 'test the SanaSprintPipeline float16 inference by running the pipeline in half precision and checking output differences', 'test the SanaSprintImg2ImgPipeline inference by running dummy components and validating output image shape', 'test float16 inference with higher tolerance for dtype sensitivity in the pipeline']
```

Usage

```
{'test_sana_sprint_pipeline_inference': 'test the SanaSprintPipeline inference by running the pipeline with dummy components and verifying generated image shape', 'test_sana_sprint_callback_inputs': 'test the SanaSprintPipeline callback on step end functionality by passing tensor inputs and validating callback behavior', 'test_sana_sprint_attention_slicing': 'test the SanaSprintPipeline attention slicing forward pass by comparing outputs with and without slicing enabled', 'test_sana_sprint_vae_tiling': 'test the SanaSprintPipeline VAE tiling by enabling tiling and comparing outputs with and without tiling', 'test_sana_sprint_float16_inference': 'test the SanaSprintPipeline float16 inference by running the pipeline in half precision and checking output differences'}
```

## File: huggingface_diffusers/tests/pipelines/sana/test_sana_sprint_img2img.py

Prompts

```
['run the SanaPipelineFastTests unittest class to test SanaPipeline with dummy transformer, VAE, and scheduler components', 'run the SanaPipelineIntegrationTests to validate Sana 1024px and 512px pretrained models against expected output slices', 'test the SanaPipeline callback_on_step_end functionality to verify tensor inputs passed during each inference step', 'test the SanaPipeline attention slicing forward pass to verify slicing does not affect inference results', 'test the SanaPipeline VAE tiling feature to verify tiled decoding produces results close to non-tiled decoding', 'run the SanaControlNetPipeline inference test with dummy components and a control image', 'test the SanaControlNetPipeline callback on step end tensor inputs functionality', 'test the SanaControlNetPipeline attention slicing forward pass with different slice sizes', 'test the SanaControlNetPipeline VAE tiling with tile sample height and width parameters', 'test the SanaControlNetPipeline float16 inference with higher tolerance for dtype sensitivity', 'test the SanaSprintPipeline inference by running the pipeline with dummy components and verifying generated image shape', 'test the SanaSprintPipeline callback on step end functionality by passing tensor inputs and validating callback behavior', 'test the SanaSprintPipeline attention slicing forward pass by comparing outputs with and without slicing enabled', 'test the SanaSprintPipeline VAE tiling by enabling tiling and comparing outputs with and without tiling', 'test the SanaSprintPipeline float16 inference by running the pipeline in half precision and checking output differences', 'test the SanaSprintImg2ImgPipeline inference by running dummy components and validating output image shape', 'test float16 inference with higher tolerance for dtype sensitivity in the pipeline']
```

Usage

```
{'test_SanaSprintImg2ImgPipeline_inference': 'test the SanaSprintImg2ImgPipeline inference by running dummy components and validating output image shape', 'test_callback_inputs': 'test callback on step end functionality by passing tensor inputs to the pipeline callback', 'test_attention_slicing': 'test attention slicing forward pass with different slice sizes and compare output differences', 'test_vae_tiling': 'test VAE tiling by enabling tile encoding and decoding and comparing results without tiling', 'test_float16_inference': 'test float16 inference with higher tolerance for dtype sensitivity in the pipeline'}
```

