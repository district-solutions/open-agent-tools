# Agent Python Tools

- repo: huggingface/data-is-better-together
- repo_uri: https://github.com/huggingface/data-is-better-together

## File: huggingface_data-is-better-together/cookbook-efforts/dpo-orpo-preference/examples/en/aya_en_dpo_gen.py

Prompts

```
['run the distilabel pipeline to generate DPO responses using Llama 3 70B and push to Hugging Face Hub', 'remove an existing Argilla feedback dataset by name to prepare for re-running the pipeline', 'predict the language of generated text using the OpenLID model and return language label and confidence score', 'combine Aya dataset targets with model-generated responses into a single generations list with source labels', 'build a distilabel pipeline with text generation, language prediction, ultrafeedback rating, and Argilla export steps', 'create a CustomPreferenceToArgilla class that extends PreferenceToArgilla to add metadata properties to Argilla feedback records', 'add float, integer, or terms metadata properties to an Argilla dataset for filtering in the UI', 'customize the rating rationale pairs by adding an improved_response text question to Argilla feedback records', 'process preference step inputs into Argilla FeedbackRecords with SHA-256 hashed instruction IDs and metadata', 'review the CustomPreferenceToArgilla process method that generates FeedbackRecords with instruction hashes and metadata fields']
```

Usage

```
{'run_dpo_pipeline': 'run the distilabel pipeline to generate DPO responses using Llama 3 70B and push to Hugging Face Hub', 'remove_argilla_dataset': 'remove an existing Argilla feedback dataset by name to prepare for re-running the pipeline', 'predict_generation_language': 'predict the language of generated text using the OpenLID model and return language label and confidence score', 'combine_aya_and_model_response': 'combine Aya dataset targets with model-generated responses into a single generations list with source labels', 'build_dpo_preference_pipeline': 'build a distilabel pipeline with text generation, language prediction, ultrafeedback rating, and Argilla export steps'}
```

## File: huggingface_data-is-better-together/cookbook-efforts/dpo-orpo-preference/examples/en/custom_preference_to_argilla.py

Prompts

```
['run the distilabel pipeline to generate DPO responses using Llama 3 70B and push to Hugging Face Hub', 'remove an existing Argilla feedback dataset by name to prepare for re-running the pipeline', 'predict the language of generated text using the OpenLID model and return language label and confidence score', 'combine Aya dataset targets with model-generated responses into a single generations list with source labels', 'build a distilabel pipeline with text generation, language prediction, ultrafeedback rating, and Argilla export steps', 'create a CustomPreferenceToArgilla class that extends PreferenceToArgilla to add metadata properties to Argilla feedback records', 'add float, integer, or terms metadata properties to an Argilla dataset for filtering in the UI', 'customize the rating rationale pairs by adding an improved_response text question to Argilla feedback records', 'process preference step inputs into Argilla FeedbackRecords with SHA-256 hashed instruction IDs and metadata', 'review the CustomPreferenceToArgilla process method that generates FeedbackRecords with instruction hashes and metadata fields']
```

Usage

```
{'create_custom_preference_to_argilla_class': 'create a CustomPreferenceToArgilla class that extends PreferenceToArgilla to add metadata properties to Argilla feedback records', 'add_metadata_properties_to_argilla_dataset': 'add float, integer, or terms metadata properties to an Argilla dataset for filtering in the UI', 'customize_rating_rationale_pairs': 'customize the rating rationale pairs by adding an improved_response text question to Argilla feedback records', 'process_preference_inputs_to_argilla_records': 'process preference step inputs into Argilla FeedbackRecords with SHA-256 hashed instruction IDs and metadata', 'review_custom_preference_to_argilla_process': 'review the CustomPreferenceToArgilla process method that generates FeedbackRecords with instruction hashes and metadata fields'}
```

