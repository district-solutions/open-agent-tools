# Agent Python Tools

- repo: docling-project/docling
- repo_uri: https://github.com/docling-project/docling

## File: docling-project_docling/docling/models/vlm_pipeline_models/api_vlm_model.py

Prompts

```
['create an ApiVlmModel instance with enabled flag, remote services flag, and ApiVlmOptions for remote VLM inference', 'run ApiVlmModel on a ConversionResult and page batch to extract VLM predictions from document pages', 'run ApiVlmModel.process_images with a batch of images and prompts to return VlmPrediction results via threaded concurrency', 'review ApiVlmModel.__init__ to verify it raises OperationNotAllowed when remote services are disabled but model is enabled', 'summarize ApiVlmModel.process_images which converts numpy arrays to PIL images and calls remote VLM API with streaming or non-streaming fallback', 'create a HuggingFaceTransformersVlmModel instance with enabled flag, artifacts path, accelerator options, and VLM options', 'run VLM inference on a batch of pages by calling the model with a conversion result and page iterable', 'run batched VLM inference on a list of images and prompts yielding VlmPrediction objects', "build a formatted prompt for a document page using the model's prompt formulation method", 'load a HuggingFace transformers VLM model with device selection, quantization, and flash attention support', 'create an instance of HuggingFaceMlxModel to run MLX-based vision-language model inference on document pages', 'run the HuggingFaceMlxModel __call__ method to process a batch of document pages and attach VLM predictions', 'run the process_images method to generate VLM predictions from raw images and prompts using the MLX model', 'test HuggingFaceMlxModel __init__ to validate mlx-vlm import and model artifact path resolution', "review the process_images method's custom stopping criteria support for GenerationStopper and stop string handling", 'create a vllm vlm model instance to process document pages with vision-language inference', 'run vllm vlm inference on a batch of document pages to generate text predictions', 'process a batch of images with prompts through vllm and yield vlm predictions', 'build vllm sampling parameters with temperature, max tokens, and stop strings for generation', 'configure vllm engine with model path, device, quantization, and parallelism settings']
```

Usage

```
{'create_api_vlm_model': 'create an ApiVlmModel instance with enabled flag, remote services flag, and ApiVlmOptions for remote VLM inference', 'run_api_vlm_model': 'run ApiVlmModel on a ConversionResult and page batch to extract VLM predictions from document pages', 'run_process_images': 'run ApiVlmModel.process_images with a batch of images and prompts to return VlmPrediction results via threaded concurrency', 'review_api_vlm_model': 'review ApiVlmModel.__init__ to verify it raises OperationNotAllowed when remote services are disabled but model is enabled', 'summarize_process_images': 'summarize ApiVlmModel.process_images which converts numpy arrays to PIL images and calls remote VLM API with streaming or non-streaming fallback'}
```

## File: docling-project_docling/docling/models/vlm_pipeline_models/hf_transformers_model.py

Prompts

```
['create an ApiVlmModel instance with enabled flag, remote services flag, and ApiVlmOptions for remote VLM inference', 'run ApiVlmModel on a ConversionResult and page batch to extract VLM predictions from document pages', 'run ApiVlmModel.process_images with a batch of images and prompts to return VlmPrediction results via threaded concurrency', 'review ApiVlmModel.__init__ to verify it raises OperationNotAllowed when remote services are disabled but model is enabled', 'summarize ApiVlmModel.process_images which converts numpy arrays to PIL images and calls remote VLM API with streaming or non-streaming fallback', 'create a HuggingFaceTransformersVlmModel instance with enabled flag, artifacts path, accelerator options, and VLM options', 'run VLM inference on a batch of pages by calling the model with a conversion result and page iterable', 'run batched VLM inference on a list of images and prompts yielding VlmPrediction objects', "build a formatted prompt for a document page using the model's prompt formulation method", 'load a HuggingFace transformers VLM model with device selection, quantization, and flash attention support', 'create an instance of HuggingFaceMlxModel to run MLX-based vision-language model inference on document pages', 'run the HuggingFaceMlxModel __call__ method to process a batch of document pages and attach VLM predictions', 'run the process_images method to generate VLM predictions from raw images and prompts using the MLX model', 'test HuggingFaceMlxModel __init__ to validate mlx-vlm import and model artifact path resolution', "review the process_images method's custom stopping criteria support for GenerationStopper and stop string handling", 'create a vllm vlm model instance to process document pages with vision-language inference', 'run vllm vlm inference on a batch of document pages to generate text predictions', 'process a batch of images with prompts through vllm and yield vlm predictions', 'build vllm sampling parameters with temperature, max tokens, and stop strings for generation', 'configure vllm engine with model path, device, quantization, and parallelism settings']
```

Usage

```
{'create_hf_transformers_vlm_model': 'create a HuggingFaceTransformersVlmModel instance with enabled flag, artifacts path, accelerator options, and VLM options', 'run_vlm_page_inference': 'run VLM inference on a batch of pages by calling the model with a conversion result and page iterable', 'run_vlm_batch_inference': 'run batched VLM inference on a list of images and prompts yielding VlmPrediction objects', 'build_vlm_prompt': "build a formatted prompt for a document page using the model's prompt formulation method", 'load_hf_vlm_model': 'load a HuggingFace transformers VLM model with device selection, quantization, and flash attention support'}
```

## File: docling-project_docling/docling/models/vlm_pipeline_models/mlx_model.py

Prompts

```
['create an ApiVlmModel instance with enabled flag, remote services flag, and ApiVlmOptions for remote VLM inference', 'run ApiVlmModel on a ConversionResult and page batch to extract VLM predictions from document pages', 'run ApiVlmModel.process_images with a batch of images and prompts to return VlmPrediction results via threaded concurrency', 'review ApiVlmModel.__init__ to verify it raises OperationNotAllowed when remote services are disabled but model is enabled', 'summarize ApiVlmModel.process_images which converts numpy arrays to PIL images and calls remote VLM API with streaming or non-streaming fallback', 'create a HuggingFaceTransformersVlmModel instance with enabled flag, artifacts path, accelerator options, and VLM options', 'run VLM inference on a batch of pages by calling the model with a conversion result and page iterable', 'run batched VLM inference on a list of images and prompts yielding VlmPrediction objects', "build a formatted prompt for a document page using the model's prompt formulation method", 'load a HuggingFace transformers VLM model with device selection, quantization, and flash attention support', 'create an instance of HuggingFaceMlxModel to run MLX-based vision-language model inference on document pages', 'run the HuggingFaceMlxModel __call__ method to process a batch of document pages and attach VLM predictions', 'run the process_images method to generate VLM predictions from raw images and prompts using the MLX model', 'test HuggingFaceMlxModel __init__ to validate mlx-vlm import and model artifact path resolution', "review the process_images method's custom stopping criteria support for GenerationStopper and stop string handling", 'create a vllm vlm model instance to process document pages with vision-language inference', 'run vllm vlm inference on a batch of document pages to generate text predictions', 'process a batch of images with prompts through vllm and yield vlm predictions', 'build vllm sampling parameters with temperature, max tokens, and stop strings for generation', 'configure vllm engine with model path, device, quantization, and parallelism settings']
```

Usage

```
{'create_class_huggingfacemlxmodel': 'create an instance of HuggingFaceMlxModel to run MLX-based vision-language model inference on document pages', 'run_method_call': 'run the HuggingFaceMlxModel __call__ method to process a batch of document pages and attach VLM predictions', 'run_method_process_images': 'run the process_images method to generate VLM predictions from raw images and prompts using the MLX model', 'test_method_init_validation': 'test HuggingFaceMlxModel __init__ to validate mlx-vlm import and model artifact path resolution', 'review_method_stopping_criteria': "review the process_images method's custom stopping criteria support for GenerationStopper and stop string handling"}
```

## File: docling-project_docling/docling/models/vlm_pipeline_models/vllm_model.py

Prompts

```
['create an ApiVlmModel instance with enabled flag, remote services flag, and ApiVlmOptions for remote VLM inference', 'run ApiVlmModel on a ConversionResult and page batch to extract VLM predictions from document pages', 'run ApiVlmModel.process_images with a batch of images and prompts to return VlmPrediction results via threaded concurrency', 'review ApiVlmModel.__init__ to verify it raises OperationNotAllowed when remote services are disabled but model is enabled', 'summarize ApiVlmModel.process_images which converts numpy arrays to PIL images and calls remote VLM API with streaming or non-streaming fallback', 'create a HuggingFaceTransformersVlmModel instance with enabled flag, artifacts path, accelerator options, and VLM options', 'run VLM inference on a batch of pages by calling the model with a conversion result and page iterable', 'run batched VLM inference on a list of images and prompts yielding VlmPrediction objects', "build a formatted prompt for a document page using the model's prompt formulation method", 'load a HuggingFace transformers VLM model with device selection, quantization, and flash attention support', 'create an instance of HuggingFaceMlxModel to run MLX-based vision-language model inference on document pages', 'run the HuggingFaceMlxModel __call__ method to process a batch of document pages and attach VLM predictions', 'run the process_images method to generate VLM predictions from raw images and prompts using the MLX model', 'test HuggingFaceMlxModel __init__ to validate mlx-vlm import and model artifact path resolution', "review the process_images method's custom stopping criteria support for GenerationStopper and stop string handling", 'create a vllm vlm model instance to process document pages with vision-language inference', 'run vllm vlm inference on a batch of document pages to generate text predictions', 'process a batch of images with prompts through vllm and yield vlm predictions', 'build vllm sampling parameters with temperature, max tokens, and stop strings for generation', 'configure vllm engine with model path, device, quantization, and parallelism settings']
```

Usage

```
{'create_vllm_vlm_model': 'create a vllm vlm model instance to process document pages with vision-language inference', 'run_vlm_inference': 'run vllm vlm inference on a batch of document pages to generate text predictions', 'process_vlm_images': 'process a batch of images with prompts through vllm and yield vlm predictions', 'build_vllm_sampling_params': 'build vllm sampling parameters with temperature, max tokens, and stop strings for generation', 'configure_vllm_engine': 'configure vllm engine with model path, device, quantization, and parallelism settings'}
```

