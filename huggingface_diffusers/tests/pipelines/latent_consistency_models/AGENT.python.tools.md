# Agent Python Tools

- repo: huggingface/diffusers
- repo_uri: https://github.com/huggingface/diffusers

## File: huggingface_diffusers/tests/pipelines/latent_consistency_models/test_latent_consistency_models.py

Prompts

```
['run the LatentConsistencyModelPipeline with one inference step and verify the output image shape and pixel values', 'run the LatentConsistencyModelPipeline with multiple inference steps and verify the output image matches expected values', 'run the LatentConsistencyModelPipeline with custom timesteps instead of num_inference_steps and verify output correctness', 'test the callback_on_step_end functionality by modifying the denoised tensor on the final step', 'test the IP adapter integration with the LatentConsistencyModelPipeline and verify expected output slice values', 'test the LatentConsistencyModelImg2ImgPipeline with one inference step using dummy components', 'test the LatentConsistencyModelImg2ImgPipeline with multiple inference steps using dummy components', 'test the callback_on_step_end functionality with tensor inputs for the LCM img2img pipeline', 'test the LatentConsistencyModelImg2ImgPipeline with the pretrained SimianLuo/LCM_Dreamshaper_v7 model']
```

Usage

```
{'test_lcm_onestep': 'run the LatentConsistencyModelPipeline with one inference step and verify the output image shape and pixel values', 'test_lcm_multistep': 'run the LatentConsistencyModelPipeline with multiple inference steps and verify the output image matches expected values', 'test_lcm_custom_timesteps': 'run the LatentConsistencyModelPipeline with custom timesteps instead of num_inference_steps and verify output correctness', 'test_callback_inputs': 'test the callback_on_step_end functionality by modifying the denoised tensor on the final step', 'test_ip_adapter': 'test the IP adapter integration with the LatentConsistencyModelPipeline and verify expected output slice values'}
```

## File: huggingface_diffusers/tests/pipelines/latent_consistency_models/test_latent_consistency_models_img2img.py

Prompts

```
['run the LatentConsistencyModelPipeline with one inference step and verify the output image shape and pixel values', 'run the LatentConsistencyModelPipeline with multiple inference steps and verify the output image matches expected values', 'run the LatentConsistencyModelPipeline with custom timesteps instead of num_inference_steps and verify output correctness', 'test the callback_on_step_end functionality by modifying the denoised tensor on the final step', 'test the IP adapter integration with the LatentConsistencyModelPipeline and verify expected output slice values', 'test the LatentConsistencyModelImg2ImgPipeline with one inference step using dummy components', 'test the LatentConsistencyModelImg2ImgPipeline with multiple inference steps using dummy components', 'test the callback_on_step_end functionality with tensor inputs for the LCM img2img pipeline', 'test the LatentConsistencyModelImg2ImgPipeline with the pretrained SimianLuo/LCM_Dreamshaper_v7 model']
```

Usage

```
{'test_lcm_img2img_onestep': 'test the LatentConsistencyModelImg2ImgPipeline with one inference step using dummy components', 'test_lcm_img2img_multistep': 'test the LatentConsistencyModelImg2ImgPipeline with multiple inference steps using dummy components', 'test_lcm_custom_timesteps': 'test the LatentConsistencyModelImg2ImgPipeline with custom timestep values instead of num_inference_steps', 'test_lcm_callback_inputs': 'test the callback_on_step_end functionality with tensor inputs for the LCM img2img pipeline', 'test_lcm_slow_full_model': 'test the LatentConsistencyModelImg2ImgPipeline with the pretrained SimianLuo/LCM_Dreamshaper_v7 model'}
```

