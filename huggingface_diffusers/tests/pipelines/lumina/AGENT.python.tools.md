# Agent Python Tools

- repo: huggingface/diffusers
- repo_uri: https://github.com/huggingface/diffusers

## File: huggingface_diffusers/tests/pipelines/lumina/test_lumina_nextdit.py

Prompts

```
['run the LuminaPipelineFastTests to test LuminaPipeline with dummy transformer, VAE, scheduler, and text encoder components', 'run the LuminaPipelineSlowTests to perform end-to-end inference with the pretrained Lumina-Next-SFT-diffusers model', 'create dummy LuminaNextDiT2DModel, AutoencoderKL, FlowMatchEulerDiscreteScheduler, and GemmaForCausalLM components for fast testing', 'create dummy input dictionary with prompt, generator, num_inference_steps, guidance_scale, and output_type for Lumina pipeline tests', 'run the skipped xformers attention forward generator test for Lumina pipeline since no attention processor exists']
```

Usage

```
{'test_lumina_pipeline_fast': 'run the LuminaPipelineFastTests to test LuminaPipeline with dummy transformer, VAE, scheduler, and text encoder components', 'test_lumina_inference': 'run the LuminaPipelineSlowTests to perform end-to-end inference with the pretrained Lumina-Next-SFT-diffusers model', 'get_dummy_components_lumina': 'create dummy LuminaNextDiT2DModel, AutoencoderKL, FlowMatchEulerDiscreteScheduler, and GemmaForCausalLM components for fast testing', 'get_dummy_inputs_lumina': 'create dummy input dictionary with prompt, generator, num_inference_steps, guidance_scale, and output_type for Lumina pipeline tests', 'test_lumina_xformers_attention': 'run the skipped xformers attention forward generator test for Lumina pipeline since no attention processor exists'}
```

