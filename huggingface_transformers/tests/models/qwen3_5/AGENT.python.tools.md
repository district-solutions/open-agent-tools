# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/qwen3_5/test_modeling_qwen3_5.py

Prompts

```
['test the Qwen3_5TextModelTest class attention_outputs method verifies alternating full_attention and linear_attention layers', 'test the Qwen3_5ModelTest class mismatching_num_image_tokens method validates VLM error on image count mismatch', 'test the Qwen3_5ModelTest class image_forward method verifies image tensor forward pass with grid thw tokens', 'test the Qwen3_5ModelTest class video_forward method verifies video tensor forward pass with frame timestamp tokens', 'test the Qwen3_5IntegrationTest class model_logits method validates greedy token picks match expected argmax for Qwen3.5-0.8B', 'test the Qwen3_5IntegrationTest class model_generation method validates autoregressive text generation from a prompt', 'test the Qwen3_5IntegrationTest class model_vision_generation method validates image understanding generation with processor', 'test the Qwen3_5IntegrationTest class model_video_generation method validates video description generation with processor', 'test the Qwen3_5IntegrationTest class model_video_generation_batch method validates batch video generation with identical inputs', 'test the Qwen3_5IntegrationTest class model_video_generation_batch_mixed method validates batch generation with mixed video and text-only prompts', 'test the Qwen3_5IntegrationTest class model_video_generation_batch_different_videos method validates batch generation with different video inputs']
```

Usage

```
{'test_Qwen3_5TextModel_attention_outputs': 'test the Qwen3_5TextModelTest class attention_outputs method verifies alternating full_attention and linear_attention layers', 'test_Qwen3_5Model_mismatching_num_image_tokens': 'test the Qwen3_5ModelTest class mismatching_num_image_tokens method validates VLM error on image count mismatch', 'test_Qwen3_5Model_image_forward': 'test the Qwen3_5ModelTest class image_forward method verifies image tensor forward pass with grid thw tokens', 'test_Qwen3_5Model_video_forward': 'test the Qwen3_5ModelTest class video_forward method verifies video tensor forward pass with frame timestamp tokens', 'test_Qwen3_5IntegrationTest_model_logits': 'test the Qwen3_5IntegrationTest class model_logits method validates greedy token picks match expected argmax for Qwen3.5-0.8B', 'test_Qwen3_5IntegrationTest_model_generation': 'test the Qwen3_5IntegrationTest class model_generation method validates autoregressive text generation from a prompt', 'test_Qwen3_5IntegrationTest_model_vision_generation': 'test the Qwen3_5IntegrationTest class model_vision_generation method validates image understanding generation with processor', 'test_Qwen3_5IntegrationTest_model_video_generation': 'test the Qwen3_5IntegrationTest class model_video_generation method validates video description generation with processor', 'test_Qwen3_5IntegrationTest_model_video_generation_batch': 'test the Qwen3_5IntegrationTest class model_video_generation_batch method validates batch video generation with identical inputs', 'test_Qwen3_5IntegrationTest_model_video_generation_batch_mixed': 'test the Qwen3_5IntegrationTest class model_video_generation_batch_mixed method validates batch generation with mixed video and text-only prompts', 'test_Qwen3_5IntegrationTest_model_video_generation_batch_different_videos': 'test the Qwen3_5IntegrationTest class model_video_generation_batch_different_videos method validates batch generation with different video inputs'}
```

