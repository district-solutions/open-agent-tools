# Agent Python Tools

- repo: docling-project/docling
- repo_uri: https://github.com/docling-project/docling

## File: docling-project_docling/docling/models/stages/picture_description/picture_description_api_model.py

Prompts

```
['create a PictureDescriptionApiModel instance with enabled flag and remote services allowed', 'get the options type class for PictureDescriptionApiModel returning PictureDescriptionApiOptions', 'run picture description on images via remote API using ThreadPoolExecutor with configurable concurrency', 'configure PictureDescriptionApiOptions with url, prompt, timeout, headers, and params for image annotation', 'test PictureDescriptionApiModel raises OperationNotAllowed when remote services are disabled but model is enabled', 'create a PictureDescriptionVlmEngineModel stage with VLM engine options and accelerator options for generating image descriptions', 'test the PictureDescriptionVlmEngineModel.get_options_type class method returns PictureDescriptionVlmEngineOptions', 'run _annotate_images on a batch of PIL images to generate description text using the VLM engine', 'build a VLM engine instance using create_vlm_engine with engine options, model spec, and accelerator options', 'review the __del__ method that cleans up VLM engine resources by calling engine.cleanup()', 'create a PictureDescriptionVlmModel instance to generate image descriptions using a Hugging Face vision-language model', 'configure AcceleratorOptions to control CUDA flash attention and device selection for the VLM model', 'download a Hugging Face vision-language model to a local artifacts directory for offline picture description', 'generate text descriptions for a batch of images using a configured PictureDescriptionVlmModel with a custom prompt', 'set generation configuration parameters such as max_new_tokens and temperature for the VLM image description model']
```

Usage

```
{'create_picture_description_api_model': 'create a PictureDescriptionApiModel instance with enabled flag and remote services allowed', 'get_options_type_api_model': 'get the options type class for PictureDescriptionApiModel returning PictureDescriptionApiOptions', 'run_picture_description_api': 'run picture description on images via remote API using ThreadPoolExecutor with configurable concurrency', 'configure_picture_description_options': 'configure PictureDescriptionApiOptions with url, prompt, timeout, headers, and params for image annotation', 'test_picture_description_api_model': 'test PictureDescriptionApiModel raises OperationNotAllowed when remote services are disabled but model is enabled'}
```

## File: docling-project_docling/docling/models/stages/picture_description/picture_description_vlm_engine_model.py

Prompts

```
['create a PictureDescriptionApiModel instance with enabled flag and remote services allowed', 'get the options type class for PictureDescriptionApiModel returning PictureDescriptionApiOptions', 'run picture description on images via remote API using ThreadPoolExecutor with configurable concurrency', 'configure PictureDescriptionApiOptions with url, prompt, timeout, headers, and params for image annotation', 'test PictureDescriptionApiModel raises OperationNotAllowed when remote services are disabled but model is enabled', 'create a PictureDescriptionVlmEngineModel stage with VLM engine options and accelerator options for generating image descriptions', 'test the PictureDescriptionVlmEngineModel.get_options_type class method returns PictureDescriptionVlmEngineOptions', 'run _annotate_images on a batch of PIL images to generate description text using the VLM engine', 'build a VLM engine instance using create_vlm_engine with engine options, model spec, and accelerator options', 'review the __del__ method that cleans up VLM engine resources by calling engine.cleanup()', 'create a PictureDescriptionVlmModel instance to generate image descriptions using a Hugging Face vision-language model', 'configure AcceleratorOptions to control CUDA flash attention and device selection for the VLM model', 'download a Hugging Face vision-language model to a local artifacts directory for offline picture description', 'generate text descriptions for a batch of images using a configured PictureDescriptionVlmModel with a custom prompt', 'set generation configuration parameters such as max_new_tokens and temperature for the VLM image description model']
```

Usage

```
{'create_stage_picture_description_vlm': 'create a PictureDescriptionVlmEngineModel stage with VLM engine options and accelerator options for generating image descriptions', 'test_get_options_type': 'test the PictureDescriptionVlmEngineModel.get_options_type class method returns PictureDescriptionVlmEngineOptions', 'run_annotate_images': 'run _annotate_images on a batch of PIL images to generate description text using the VLM engine', 'build_vlm_engine': 'build a VLM engine instance using create_vlm_engine with engine options, model spec, and accelerator options', 'review_cleanup_engine': 'review the __del__ method that cleans up VLM engine resources by calling engine.cleanup()'}
```

## File: docling-project_docling/docling/models/stages/picture_description/picture_description_vlm_model.py

Prompts

```
['create a PictureDescriptionApiModel instance with enabled flag and remote services allowed', 'get the options type class for PictureDescriptionApiModel returning PictureDescriptionApiOptions', 'run picture description on images via remote API using ThreadPoolExecutor with configurable concurrency', 'configure PictureDescriptionApiOptions with url, prompt, timeout, headers, and params for image annotation', 'test PictureDescriptionApiModel raises OperationNotAllowed when remote services are disabled but model is enabled', 'create a PictureDescriptionVlmEngineModel stage with VLM engine options and accelerator options for generating image descriptions', 'test the PictureDescriptionVlmEngineModel.get_options_type class method returns PictureDescriptionVlmEngineOptions', 'run _annotate_images on a batch of PIL images to generate description text using the VLM engine', 'build a VLM engine instance using create_vlm_engine with engine options, model spec, and accelerator options', 'review the __del__ method that cleans up VLM engine resources by calling engine.cleanup()', 'create a PictureDescriptionVlmModel instance to generate image descriptions using a Hugging Face vision-language model', 'configure AcceleratorOptions to control CUDA flash attention and device selection for the VLM model', 'download a Hugging Face vision-language model to a local artifacts directory for offline picture description', 'generate text descriptions for a batch of images using a configured PictureDescriptionVlmModel with a custom prompt', 'set generation configuration parameters such as max_new_tokens and temperature for the VLM image description model']
```

Usage

```
{'create_picture_description_model': 'create a PictureDescriptionVlmModel instance to generate image descriptions using a Hugging Face vision-language model', 'configure_vlm_accelerator': 'configure AcceleratorOptions to control CUDA flash attention and device selection for the VLM model', 'download_vlm_model': 'download a Hugging Face vision-language model to a local artifacts directory for offline picture description', 'generate_image_descriptions': 'generate text descriptions for a batch of images using a configured PictureDescriptionVlmModel with a custom prompt', 'set_vlm_generation_config': 'set generation configuration parameters such as max_new_tokens and temperature for the VLM image description model'}
```

