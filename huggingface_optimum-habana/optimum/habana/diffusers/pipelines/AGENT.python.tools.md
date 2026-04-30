# Agent Python Tools

- repo: huggingface/optimum-habana
- repo_uri: https://github.com/huggingface/optimum-habana

## File: huggingface_optimum-habana/optimum/habana/diffusers/pipelines/auto_pipeline.py

Prompts

```
['load a Gaudi-optimized text-to-image diffusion pipeline from a pretrained model using AutoPipelineForText2Image.from_pretrained', 'load a Gaudi-optimized inpainting diffusion pipeline from a pretrained model using AutoPipelineForInpainting.from_pretrained', 'convert an existing diffusion pipeline to a Gaudi-optimized text-to-image pipeline using AutoPipelineForText2Image.from_pipe', 'convert an existing diffusion pipeline to a Gaudi-optimized inpainting pipeline using AutoPipelineForInpainting.from_pipe', 'review the _gaudi_get_task_class function that resolves Gaudi pipeline classes from model names using GAUDI_SUPPORTED_TASKS_MAPPINGS', 'create a GaudiDiffusionPipeline with use_habana and gaudi_config for HPU-accelerated diffusion', 'load a GaudiDiffusionPipeline from a pretrained model path using from_pretrained', 'save a GaudiDiffusionPipeline and its Gaudi config to a directory with save_pretrained', 'save LoRA weights from a GaudiDiffusionPipeline by moving layers from HPU to CPU', 'register modules on a GaudiDiffusionPipeline with library and class metadata']
```

Usage

```
{'load_gaudi_text2image_pipeline': 'load a Gaudi-optimized text-to-image diffusion pipeline from a pretrained model using AutoPipelineForText2Image.from_pretrained', 'load_gaudi_inpainting_pipeline': 'load a Gaudi-optimized inpainting diffusion pipeline from a pretrained model using AutoPipelineForInpainting.from_pretrained', 'convert_pipeline_to_gaudi_text2image': 'convert an existing diffusion pipeline to a Gaudi-optimized text-to-image pipeline using AutoPipelineForText2Image.from_pipe', 'convert_pipeline_to_gaudi_inpainting': 'convert an existing diffusion pipeline to a Gaudi-optimized inpainting pipeline using AutoPipelineForInpainting.from_pipe', 'review_gaudi_task_class_resolution': 'review the _gaudi_get_task_class function that resolves Gaudi pipeline classes from model names using GAUDI_SUPPORTED_TASKS_MAPPINGS'}
```

## File: huggingface_optimum-habana/optimum/habana/diffusers/pipelines/pipeline_utils.py

Prompts

```
['load a Gaudi-optimized text-to-image diffusion pipeline from a pretrained model using AutoPipelineForText2Image.from_pretrained', 'load a Gaudi-optimized inpainting diffusion pipeline from a pretrained model using AutoPipelineForInpainting.from_pretrained', 'convert an existing diffusion pipeline to a Gaudi-optimized text-to-image pipeline using AutoPipelineForText2Image.from_pipe', 'convert an existing diffusion pipeline to a Gaudi-optimized inpainting pipeline using AutoPipelineForInpainting.from_pipe', 'review the _gaudi_get_task_class function that resolves Gaudi pipeline classes from model names using GAUDI_SUPPORTED_TASKS_MAPPINGS', 'create a GaudiDiffusionPipeline with use_habana and gaudi_config for HPU-accelerated diffusion', 'load a GaudiDiffusionPipeline from a pretrained model path using from_pretrained', 'save a GaudiDiffusionPipeline and its Gaudi config to a directory with save_pretrained', 'save LoRA weights from a GaudiDiffusionPipeline by moving layers from HPU to CPU', 'register modules on a GaudiDiffusionPipeline with library and class metadata']
```

Usage

```
{'init_gaudi_diffusion_pipeline': 'create a GaudiDiffusionPipeline with use_habana and gaudi_config for HPU-accelerated diffusion', 'load_gaudi_pipeline_from_pretrained': 'load a GaudiDiffusionPipeline from a pretrained model path using from_pretrained', 'save_gaudi_pipeline_pretrained': 'save a GaudiDiffusionPipeline and its Gaudi config to a directory with save_pretrained', 'save_gaudi_lora_weights': 'save LoRA weights from a GaudiDiffusionPipeline by moving layers from HPU to CPU', 'register_gaudi_pipeline_modules': 'register modules on a GaudiDiffusionPipeline with library and class metadata'}
```

