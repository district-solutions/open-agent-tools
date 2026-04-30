# Agent Python Tools

- repo: huggingface/data-is-better-together
- repo_uri: https://github.com/huggingface/data-is-better-together

## File: huggingface_data-is-better-together/cookbook-efforts/dpo-orpo-preference/aya_dpo_gen.py

Prompts

```
['run the distilabel pipeline to generate DPO preference responses using Llama 3 and push to Hugging Face Hub', 'remove an existing Argilla feedback dataset by name to prepare for re-running the pipeline', 'create a distilabel step that predicts the language of generated text using the OpenLID model', 'build a distilabel step that combines Aya dataset targets with model generations into paired responses', 'review the DutchTextGeneration class that adds a Dutch system prompt to the TextGeneration task', 'create a CustomPreferenceToArgilla class that extends PreferenceToArgilla to add metadata properties and an improved response text question to Argilla feedback records', 'add float integer or terms metadata properties to an Argilla dataset for filtering feedback records in the UI', 'generate a SHA-256 hash of an instruction string to use as a unique identifier for Argilla feedback records', 'create an Argilla FeedbackRecord with instruction generations suggestions and metadata fields from preference step input data', 'add an optional improved response text question to the rating rationale pairs for collecting feedback improvement suggestions']
```

Usage

```
{'run_dpo_pipeline': 'run the distilabel pipeline to generate DPO preference responses using Llama 3 and push to Hugging Face Hub', 'remove_argilla_dataset': 'remove an existing Argilla feedback dataset by name to prepare for re-running the pipeline', 'create_language_predict_step': 'create a distilabel step that predicts the language of generated text using the OpenLID model', 'build_combine_aya_response_step': 'build a distilabel step that combines Aya dataset targets with model generations into paired responses', 'review_dutchtexgeneration_class': 'review the DutchTextGeneration class that adds a Dutch system prompt to the TextGeneration task'}
```

## File: huggingface_data-is-better-together/cookbook-efforts/dpo-orpo-preference/custom_preference_to_argilla.py

Prompts

```
['run the distilabel pipeline to generate DPO preference responses using Llama 3 and push to Hugging Face Hub', 'remove an existing Argilla feedback dataset by name to prepare for re-running the pipeline', 'create a distilabel step that predicts the language of generated text using the OpenLID model', 'build a distilabel step that combines Aya dataset targets with model generations into paired responses', 'review the DutchTextGeneration class that adds a Dutch system prompt to the TextGeneration task', 'create a CustomPreferenceToArgilla class that extends PreferenceToArgilla to add metadata properties and an improved response text question to Argilla feedback records', 'add float integer or terms metadata properties to an Argilla dataset for filtering feedback records in the UI', 'generate a SHA-256 hash of an instruction string to use as a unique identifier for Argilla feedback records', 'create an Argilla FeedbackRecord with instruction generations suggestions and metadata fields from preference step input data', 'add an optional improved response text question to the rating rationale pairs for collecting feedback improvement suggestions']
```

Usage

```
{'create_custom_preference_to_argilla_class': 'create a CustomPreferenceToArgilla class that extends PreferenceToArgilla to add metadata properties and an improved response text question to Argilla feedback records', 'add_metadata_properties_to_argilla_dataset': 'add float integer or terms metadata properties to an Argilla dataset for filtering feedback records in the UI', 'generate_instruction_id_hash': 'generate a SHA-256 hash of an instruction string to use as a unique identifier for Argilla feedback records', 'create_feedback_record_with_generations': 'create an Argilla FeedbackRecord with instruction generations suggestions and metadata fields from preference step input data', 'add_improved_response_question': 'add an optional improved response text question to the rating rationale pairs for collecting feedback improvement suggestions'}
```

