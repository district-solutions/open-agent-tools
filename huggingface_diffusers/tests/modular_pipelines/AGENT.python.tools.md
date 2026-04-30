# Agent Python Tools

- repo: huggingface/diffusers
- repo_uri: https://github.com/huggingface/diffusers

## File: huggingface_diffusers/tests/modular_pipelines/test_conditional_pipeline_blocks.py

Prompts

```
['create a ModularPipelineBlocks subclass for text-to-image workflow with prompt input', 'create a ModularPipelineBlocks subclass for image-to-image workflow with prompt and image inputs', 'create a ModularPipelineBlocks subclass for inpaint workflow with prompt, image, and mask inputs', 'build a ConditionalPipelineBlocks class that selects inpaint, img2img, or text2img based on mask and image triggers', 'test the select_block method to verify conditional block selection by mask and image inputs', 'test that a modular pipeline __call__ method has all required input parameters', 'test that a modular pipeline produces consistent outputs across different batch sizes', 'test that a modular pipeline produces similar outputs in float16 versus float32 precision', 'test that a modular pipeline moves all components correctly between CPU and accelerator devices', 'test the generation of modular model card content including pipeline name, tags, and component descriptions', 'create a tiny model directory with modeling code, config, and PyTorch weights for testing', 'build a custom modular pipeline block that takes a prompt input and returns a modified output prompt', 'test saving and loading a custom modular pipeline block with pretrained config and code file', 'test that sequential pipeline blocks correctly save and load their dependency requirements', 'test loading and running the Krea realtime video modular pipeline with frame generation']
```

Usage

```
{'create_TextToImageBlock': 'create a ModularPipelineBlocks subclass for text-to-image workflow with prompt input', 'create_ImageToImageBlock': 'create a ModularPipelineBlocks subclass for image-to-image workflow with prompt and image inputs', 'create_InpaintBlock': 'create a ModularPipelineBlocks subclass for inpaint workflow with prompt, image, and mask inputs', 'build_ConditionalImageBlocks': 'build a ConditionalPipelineBlocks class that selects inpaint, img2img, or text2img based on mask and image triggers', 'test_select_block': 'test the select_block method to verify conditional block selection by mask and image inputs'}
```

## File: huggingface_diffusers/tests/modular_pipelines/test_modular_pipelines_common.py

Prompts

```
['create a ModularPipelineBlocks subclass for text-to-image workflow with prompt input', 'create a ModularPipelineBlocks subclass for image-to-image workflow with prompt and image inputs', 'create a ModularPipelineBlocks subclass for inpaint workflow with prompt, image, and mask inputs', 'build a ConditionalPipelineBlocks class that selects inpaint, img2img, or text2img based on mask and image triggers', 'test the select_block method to verify conditional block selection by mask and image inputs', 'test that a modular pipeline __call__ method has all required input parameters', 'test that a modular pipeline produces consistent outputs across different batch sizes', 'test that a modular pipeline produces similar outputs in float16 versus float32 precision', 'test that a modular pipeline moves all components correctly between CPU and accelerator devices', 'test the generation of modular model card content including pipeline name, tags, and component descriptions', 'create a tiny model directory with modeling code, config, and PyTorch weights for testing', 'build a custom modular pipeline block that takes a prompt input and returns a modified output prompt', 'test saving and loading a custom modular pipeline block with pretrained config and code file', 'test that sequential pipeline blocks correctly save and load their dependency requirements', 'test loading and running the Krea realtime video modular pipeline with frame generation']
```

Usage

```
{'test_modular_pipeline_call_signature': 'test that a modular pipeline __call__ method has all required input parameters', 'test_modular_pipeline_batch_inference': 'test that a modular pipeline produces consistent outputs across different batch sizes', 'test_modular_pipeline_fp16_inference': 'test that a modular pipeline produces similar outputs in float16 versus float32 precision', 'test_modular_pipeline_device_transfer': 'test that a modular pipeline moves all components correctly between CPU and accelerator devices', 'test_modular_model_card_content': 'test the generation of modular model card content including pipeline name, tags, and component descriptions'}
```

## File: huggingface_diffusers/tests/modular_pipelines/test_modular_pipelines_custom_blocks.py

Prompts

```
['create a ModularPipelineBlocks subclass for text-to-image workflow with prompt input', 'create a ModularPipelineBlocks subclass for image-to-image workflow with prompt and image inputs', 'create a ModularPipelineBlocks subclass for inpaint workflow with prompt, image, and mask inputs', 'build a ConditionalPipelineBlocks class that selects inpaint, img2img, or text2img based on mask and image triggers', 'test the select_block method to verify conditional block selection by mask and image inputs', 'test that a modular pipeline __call__ method has all required input parameters', 'test that a modular pipeline produces consistent outputs across different batch sizes', 'test that a modular pipeline produces similar outputs in float16 versus float32 precision', 'test that a modular pipeline moves all components correctly between CPU and accelerator devices', 'test the generation of modular model card content including pipeline name, tags, and component descriptions', 'create a tiny model directory with modeling code, config, and PyTorch weights for testing', 'build a custom modular pipeline block that takes a prompt input and returns a modified output prompt', 'test saving and loading a custom modular pipeline block with pretrained config and code file', 'test that sequential pipeline blocks correctly save and load their dependency requirements', 'test loading and running the Krea realtime video modular pipeline with frame generation']
```

Usage

```
{'create_tiny_model_dir': 'create a tiny model directory with modeling code, config, and PyTorch weights for testing', 'build_custom_block': 'build a custom modular pipeline block that takes a prompt input and returns a modified output prompt', 'test_custom_block_save_load': 'test saving and loading a custom modular pipeline block with pretrained config and code file', 'test_sequential_block_requirements': 'test that sequential pipeline blocks correctly save and load their dependency requirements', 'test_krea_video_pipeline': 'test loading and running the Krea realtime video modular pipeline with frame generation'}
```

