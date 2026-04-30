# Agent Python Tools

- repo: huggingface/data-is-better-together
- repo_uri: https://github.com/huggingface/data-is-better-together

## File: huggingface_data-is-better-together/community-efforts/image_preferences/01_synthetic_data_generation_images.py

Prompts

```
['create an InferenceEndpointsImageLLM instance to generate images from text prompts via Hugging Face inference endpoints', 'run the ImageGeneration process method to generate images from prompts and save them as artifacts', 'build a distilabel pipeline with parallel image generation steps using SD and FLUX models', 'configure image generation parameters like width, height, guidance scale, and inference steps for the pipeline', 'push the generated image preferences dataset to the Hugging Face Hub repository', 'run the distilabel pipeline to generate 15000 synthetic image prompts and push to HuggingFace Hub', 'create a custom distilabel step that randomly assigns image style categories and subcategories to prompts', 'build a text generation step that transforms prompts into specific artistic styles like cinematic or anime', 'build a text generation step that enhances prompts with vivid details and quality-improving elements', 'build a text generation step that simplifies image descriptions by removing unnecessary words', 'run the distilabel pipeline to generate synthetic image preference data and push to Hugging Face Hub', 'create an ImageGeneration task step that generates images from text prompts using a Hugging Face inference endpoint', 'build an InferenceEndpointsImageLLM class that calls text-to-image endpoints and returns base64 encoded images', 'run text generation steps to create quality enhanced and style enhanced prompts using LLM inference endpoints', 'run the clean_dataset function to filter NSFW text and images from a HuggingFace dataset batch', 'create a pipeline using transformers to classify text and images as NSFW or safe', 'build a script that loads a dataset, filters NSFW content, and pushes the cleaned version to HuggingFace Hub', 'refactor the clean_dataset function to support custom NSFW detection models or additional image columns', 'review the clean_dataset function for its multi-fallback NSFW text classification logic and batched image processing']
```

Usage

```
{'create_InferenceEndpointsImageLLM': 'create an InferenceEndpointsImageLLM instance to generate images from text prompts via Hugging Face inference endpoints', 'run_ImageGeneration_process': 'run the ImageGeneration process method to generate images from prompts and save them as artifacts', 'build_distilabel_pipeline': 'build a distilabel pipeline with parallel image generation steps using SD and FLUX models', 'configure_image_generation_kwargs': 'configure image generation parameters like width, height, guidance scale, and inference steps for the pipeline', 'push_dataset_to_hub': 'push the generated image preferences dataset to the Hugging Face Hub repository'}
```

## File: huggingface_data-is-better-together/community-efforts/image_preferences/01_synthetic_data_generation_prompts.py

Prompts

```
['create an InferenceEndpointsImageLLM instance to generate images from text prompts via Hugging Face inference endpoints', 'run the ImageGeneration process method to generate images from prompts and save them as artifacts', 'build a distilabel pipeline with parallel image generation steps using SD and FLUX models', 'configure image generation parameters like width, height, guidance scale, and inference steps for the pipeline', 'push the generated image preferences dataset to the Hugging Face Hub repository', 'run the distilabel pipeline to generate 15000 synthetic image prompts and push to HuggingFace Hub', 'create a custom distilabel step that randomly assigns image style categories and subcategories to prompts', 'build a text generation step that transforms prompts into specific artistic styles like cinematic or anime', 'build a text generation step that enhances prompts with vivid details and quality-improving elements', 'build a text generation step that simplifies image descriptions by removing unnecessary words', 'run the distilabel pipeline to generate synthetic image preference data and push to Hugging Face Hub', 'create an ImageGeneration task step that generates images from text prompts using a Hugging Face inference endpoint', 'build an InferenceEndpointsImageLLM class that calls text-to-image endpoints and returns base64 encoded images', 'run text generation steps to create quality enhanced and style enhanced prompts using LLM inference endpoints', 'run the clean_dataset function to filter NSFW text and images from a HuggingFace dataset batch', 'create a pipeline using transformers to classify text and images as NSFW or safe', 'build a script that loads a dataset, filters NSFW content, and pushes the cleaned version to HuggingFace Hub', 'refactor the clean_dataset function to support custom NSFW detection models or additional image columns', 'review the clean_dataset function for its multi-fallback NSFW text classification logic and batched image processing']
```

Usage

```
{'run_pipeline_synthetic_prompts': 'run the distilabel pipeline to generate 15000 synthetic image prompts and push to HuggingFace Hub', 'create_category_selector_step': 'create a custom distilabel step that randomly assigns image style categories and subcategories to prompts', 'build_style_augmentation': 'build a text generation step that transforms prompts into specific artistic styles like cinematic or anime', 'build_quality_augmentation': 'build a text generation step that enhances prompts with vivid details and quality-improving elements', 'build_simplification_augmentation': 'build a text generation step that simplifies image descriptions by removing unnecessary words'}
```

## File: huggingface_data-is-better-together/community-efforts/image_preferences/01_synthetic_data_generation_total.py

Prompts

```
['create an InferenceEndpointsImageLLM instance to generate images from text prompts via Hugging Face inference endpoints', 'run the ImageGeneration process method to generate images from prompts and save them as artifacts', 'build a distilabel pipeline with parallel image generation steps using SD and FLUX models', 'configure image generation parameters like width, height, guidance scale, and inference steps for the pipeline', 'push the generated image preferences dataset to the Hugging Face Hub repository', 'run the distilabel pipeline to generate 15000 synthetic image prompts and push to HuggingFace Hub', 'create a custom distilabel step that randomly assigns image style categories and subcategories to prompts', 'build a text generation step that transforms prompts into specific artistic styles like cinematic or anime', 'build a text generation step that enhances prompts with vivid details and quality-improving elements', 'build a text generation step that simplifies image descriptions by removing unnecessary words', 'run the distilabel pipeline to generate synthetic image preference data and push to Hugging Face Hub', 'create an ImageGeneration task step that generates images from text prompts using a Hugging Face inference endpoint', 'build an InferenceEndpointsImageLLM class that calls text-to-image endpoints and returns base64 encoded images', 'run text generation steps to create quality enhanced and style enhanced prompts using LLM inference endpoints', 'run the clean_dataset function to filter NSFW text and images from a HuggingFace dataset batch', 'create a pipeline using transformers to classify text and images as NSFW or safe', 'build a script that loads a dataset, filters NSFW content, and pushes the cleaned version to HuggingFace Hub', 'refactor the clean_dataset function to support custom NSFW detection models or additional image columns', 'review the clean_dataset function for its multi-fallback NSFW text classification logic and batched image processing']
```

Usage

```
{'run_pipeline_image_preferences': 'run the distilabel pipeline to generate synthetic image preference data and push to Hugging Face Hub', 'create_image_generation_task': 'create an ImageGeneration task step that generates images from text prompts using a Hugging Face inference endpoint', 'build_inference_endpoints_image_llm': 'build an InferenceEndpointsImageLLM class that calls text-to-image endpoints and returns base64 encoded images', 'create_category_selector_step': 'create a CategorySelector step that randomly assigns art style categories and subcategories to image prompts', 'run_text_generation_augmentation': 'run text generation steps to create quality enhanced and style enhanced prompts using LLM inference endpoints'}
```

## File: huggingface_data-is-better-together/community-efforts/image_preferences/02_image_prefernces_cleaned_filtered_sfw.py

Prompts

```
['create an InferenceEndpointsImageLLM instance to generate images from text prompts via Hugging Face inference endpoints', 'run the ImageGeneration process method to generate images from prompts and save them as artifacts', 'build a distilabel pipeline with parallel image generation steps using SD and FLUX models', 'configure image generation parameters like width, height, guidance scale, and inference steps for the pipeline', 'push the generated image preferences dataset to the Hugging Face Hub repository', 'run the distilabel pipeline to generate 15000 synthetic image prompts and push to HuggingFace Hub', 'create a custom distilabel step that randomly assigns image style categories and subcategories to prompts', 'build a text generation step that transforms prompts into specific artistic styles like cinematic or anime', 'build a text generation step that enhances prompts with vivid details and quality-improving elements', 'build a text generation step that simplifies image descriptions by removing unnecessary words', 'run the distilabel pipeline to generate synthetic image preference data and push to Hugging Face Hub', 'create an ImageGeneration task step that generates images from text prompts using a Hugging Face inference endpoint', 'build an InferenceEndpointsImageLLM class that calls text-to-image endpoints and returns base64 encoded images', 'run text generation steps to create quality enhanced and style enhanced prompts using LLM inference endpoints', 'run the clean_dataset function to filter NSFW text and images from a HuggingFace dataset batch', 'create a pipeline using transformers to classify text and images as NSFW or safe', 'build a script that loads a dataset, filters NSFW content, and pushes the cleaned version to HuggingFace Hub', 'refactor the clean_dataset function to support custom NSFW detection models or additional image columns', 'review the clean_dataset function for its multi-fallback NSFW text classification logic and batched image processing']
```

Usage

```
{'run_clean_dataset': 'run the clean_dataset function to filter NSFW text and images from a HuggingFace dataset batch', 'create_nsfw_filter_pipeline': 'create a pipeline using transformers to classify text and images as NSFW or safe', 'build_dataset_cleaning_script': 'build a script that loads a dataset, filters NSFW content, and pushes the cleaned version to HuggingFace Hub', 'refactor_clean_dataset': 'refactor the clean_dataset function to support custom NSFW detection models or additional image columns', 'review_clean_dataset': 'review the clean_dataset function for its multi-fallback NSFW text classification logic and batched image processing'}
```

