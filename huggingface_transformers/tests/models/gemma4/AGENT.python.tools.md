# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/gemma4/test_image_processing_gemma4.py

Prompts

```
['test the Gemma4ImageProcessingTest.test_image_processor_properties method to verify all expected attributes are present', 'test the Gemma4ImageProcessingTest.test_image_processor_defaults method to verify default parameter values match VARASP_SL280_K3', 'test the get_aspect_ratio_preserving_size function to verify resize dimension calculations match C++ source of truth', 'test the Gemma4ImageProcessingTest.test_output_keys method to verify output contains pixel_values, image_position_ids, and num_soft_tokens_per_image', 'test the Gemma4ImageProcessingTest.test_position_ids_structure method to verify image_position_ids has correct real and padding structure', 'create a Gemma4TextModelTester instance to configure and test the Gemma4 text-only causal LM model with MoE blocks', 'create a Gemma4Audio2TextModelTester instance to configure and test the Gemma4 audio-to-text conditional generation model', 'create a Gemma4Vision2TextModelTester instance to configure and test the Gemma4 vision-to-text conditional generation model', 'test that Gemma4AudioRelPositionalEncoding reads the attention context size correctly from the audio config', 'test training the Gemma4ForConditionalGeneration model with text-only samples to ensure no errors on missing multimodal inputs', 'test image understanding by running Gemma4ForConditionalGeneration on a single image with a chat prompt', 'test generating text beyond the sliding window using sdpa or eager attention with static cache', 'test the Gemma4Processor to verify image token handling with nested batch image inputs', 'test the Gemma4Processor _get_num_multimodal_tokens helper to count vision tokens for given image sizes', 'test the Gemma4Processor to ensure special vision tokens are not truncated when truncation is enabled', 'test the Gemma4Processor _compute_audio_num_tokens method to verify correct audio token counts for various sample lengths', 'test the Gemma4AudioFeatureExtractor mask to verify it matches processor token count after conv subsampling']
```

Usage

```
{'test_image_processing_properties': 'test the Gemma4ImageProcessingTest.test_image_processor_properties method to verify all expected attributes are present', 'test_image_processor_defaults': 'test the Gemma4ImageProcessingTest.test_image_processor_defaults method to verify default parameter values match VARASP_SL280_K3', 'test_aspect_ratio_preserving_resize': 'test the get_aspect_ratio_preserving_size function to verify resize dimension calculations match C++ source of truth', 'test_output_keys': 'test the Gemma4ImageProcessingTest.test_output_keys method to verify output contains pixel_values, image_position_ids, and num_soft_tokens_per_image', 'test_position_ids_structure': 'test the Gemma4ImageProcessingTest.test_position_ids_structure method to verify image_position_ids has correct real and padding structure'}
```

## File: huggingface_transformers/tests/models/gemma4/test_modeling_gemma4.py

Prompts

```
['test the Gemma4ImageProcessingTest.test_image_processor_properties method to verify all expected attributes are present', 'test the Gemma4ImageProcessingTest.test_image_processor_defaults method to verify default parameter values match VARASP_SL280_K3', 'test the get_aspect_ratio_preserving_size function to verify resize dimension calculations match C++ source of truth', 'test the Gemma4ImageProcessingTest.test_output_keys method to verify output contains pixel_values, image_position_ids, and num_soft_tokens_per_image', 'test the Gemma4ImageProcessingTest.test_position_ids_structure method to verify image_position_ids has correct real and padding structure', 'create a Gemma4TextModelTester instance to configure and test the Gemma4 text-only causal LM model with MoE blocks', 'create a Gemma4Audio2TextModelTester instance to configure and test the Gemma4 audio-to-text conditional generation model', 'create a Gemma4Vision2TextModelTester instance to configure and test the Gemma4 vision-to-text conditional generation model', 'test that Gemma4AudioRelPositionalEncoding reads the attention context size correctly from the audio config', 'test training the Gemma4ForConditionalGeneration model with text-only samples to ensure no errors on missing multimodal inputs', 'test image understanding by running Gemma4ForConditionalGeneration on a single image with a chat prompt', 'test generating text beyond the sliding window using sdpa or eager attention with static cache', 'test the Gemma4Processor to verify image token handling with nested batch image inputs', 'test the Gemma4Processor _get_num_multimodal_tokens helper to count vision tokens for given image sizes', 'test the Gemma4Processor to ensure special vision tokens are not truncated when truncation is enabled', 'test the Gemma4Processor _compute_audio_num_tokens method to verify correct audio token counts for various sample lengths', 'test the Gemma4AudioFeatureExtractor mask to verify it matches processor token count after conv subsampling']
```

Usage

```
{'test_Gemma4TextModelTester': 'create a Gemma4TextModelTester instance to configure and test the Gemma4 text-only causal LM model with MoE blocks', 'test_Gemma4Audio2TextModelTester': 'create a Gemma4Audio2TextModelTester instance to configure and test the Gemma4 audio-to-text conditional generation model', 'test_Gemma4Vision2TextModelTester': 'create a Gemma4Vision2TextModelTester instance to configure and test the Gemma4 vision-to-text conditional generation model', 'test_audio_rel_pos_encoding_uses_context_size_from_config': 'test that Gemma4AudioRelPositionalEncoding reads the attention context size correctly from the audio config', 'test_training': 'test training the Gemma4ForConditionalGeneration model with text-only samples to ensure no errors on missing multimodal inputs', 'test_model_with_image': 'test image understanding by running Gemma4ForConditionalGeneration on a single image with a chat prompt', 'test_generation_beyond_sliding_window': 'test generating text beyond the sliding window using sdpa or eager attention with static cache'}
```

## File: huggingface_transformers/tests/models/gemma4/test_processing_gemma4.py

Prompts

```
['test the Gemma4ImageProcessingTest.test_image_processor_properties method to verify all expected attributes are present', 'test the Gemma4ImageProcessingTest.test_image_processor_defaults method to verify default parameter values match VARASP_SL280_K3', 'test the get_aspect_ratio_preserving_size function to verify resize dimension calculations match C++ source of truth', 'test the Gemma4ImageProcessingTest.test_output_keys method to verify output contains pixel_values, image_position_ids, and num_soft_tokens_per_image', 'test the Gemma4ImageProcessingTest.test_position_ids_structure method to verify image_position_ids has correct real and padding structure', 'create a Gemma4TextModelTester instance to configure and test the Gemma4 text-only causal LM model with MoE blocks', 'create a Gemma4Audio2TextModelTester instance to configure and test the Gemma4 audio-to-text conditional generation model', 'create a Gemma4Vision2TextModelTester instance to configure and test the Gemma4 vision-to-text conditional generation model', 'test that Gemma4AudioRelPositionalEncoding reads the attention context size correctly from the audio config', 'test training the Gemma4ForConditionalGeneration model with text-only samples to ensure no errors on missing multimodal inputs', 'test image understanding by running Gemma4ForConditionalGeneration on a single image with a chat prompt', 'test generating text beyond the sliding window using sdpa or eager attention with static cache', 'test the Gemma4Processor to verify image token handling with nested batch image inputs', 'test the Gemma4Processor _get_num_multimodal_tokens helper to count vision tokens for given image sizes', 'test the Gemma4Processor to ensure special vision tokens are not truncated when truncation is enabled', 'test the Gemma4Processor _compute_audio_num_tokens method to verify correct audio token counts for various sample lengths', 'test the Gemma4AudioFeatureExtractor mask to verify it matches processor token count after conv subsampling']
```

Usage

```
{'test_gemma4_processor_image_tokens': 'test the Gemma4Processor to verify image token handling with nested batch image inputs', 'test_gemma4_processor_vision_tokens': 'test the Gemma4Processor _get_num_multimodal_tokens helper to count vision tokens for given image sizes', 'test_gemma4_processor_special_token_truncation': 'test the Gemma4Processor to ensure special vision tokens are not truncated when truncation is enabled', 'test_gemma4_audio_token_count': 'test the Gemma4Processor _compute_audio_num_tokens method to verify correct audio token counts for various sample lengths', 'test_gemma4_feature_extractor_mask': 'test the Gemma4AudioFeatureExtractor mask to verify it matches processor token count after conv subsampling'}
```

