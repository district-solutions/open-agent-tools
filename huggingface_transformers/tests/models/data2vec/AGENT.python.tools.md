# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/data2vec/test_modeling_data2vec_audio.py

Prompts

```
['test the Data2VecAudioModel forward pass with config and input tensors', 'test the Data2VecAudioForCTC model CTC loss computation with sum and mean reduction', 'test the Data2VecAudioForSequenceClassification inference and training with labels', 'test the Data2VecAudioForXVector training with frozen base model and gradient computation', 'test the _compute_mask_indices utility for generating random masked spans over audio sequences', 'test the Data2VecTextModel by running create_and_check_model with prepared config and inputs', 'test Data2VecTextForCausalLM by running create_and_check_for_causal_lm with decoder config and labels', 'test Data2VecTextForMaskedLM by running create_and_check_for_masked_lm with prepared config and token labels', 'test Data2VecTextEmbeddings create_position_ids_from_input_ids to verify padding index is respected', 'run slow integration test inference with facebook/data2vec-text-base pretrained masked LM model', 'test the Data2VecVisionModel test suite including forward pass, image classification, and semantic segmentation', 'create a Data2VecVisionConfig with custom hidden_size, num_hidden_layers, and attention_heads for model testing', 'test the Data2VecVisionModel forward pass and verify output hidden state shape', 'test Data2VecVisionForImageClassification inference and verify logits shape for image classification', 'test Data2VecVisionForSemanticSegmentation inference and verify output logits shape for semantic segmentation']
```

Usage

```
{'test_data2vec_audio_model': 'test the Data2VecAudioModel forward pass with config and input tensors', 'test_data2vec_audio_ctc_loss': 'test the Data2VecAudioForCTC model CTC loss computation with sum and mean reduction', 'test_data2vec_audio_seq_classifier': 'test the Data2VecAudioForSequenceClassification inference and training with labels', 'test_data2vec_audio_xvector': 'test the Data2VecAudioForXVector training with frozen base model and gradient computation', 'test_compute_mask_indices': 'test the _compute_mask_indices utility for generating random masked spans over audio sequences'}
```

## File: huggingface_transformers/tests/models/data2vec/test_modeling_data2vec_text.py

Prompts

```
['test the Data2VecAudioModel forward pass with config and input tensors', 'test the Data2VecAudioForCTC model CTC loss computation with sum and mean reduction', 'test the Data2VecAudioForSequenceClassification inference and training with labels', 'test the Data2VecAudioForXVector training with frozen base model and gradient computation', 'test the _compute_mask_indices utility for generating random masked spans over audio sequences', 'test the Data2VecTextModel by running create_and_check_model with prepared config and inputs', 'test Data2VecTextForCausalLM by running create_and_check_for_causal_lm with decoder config and labels', 'test Data2VecTextForMaskedLM by running create_and_check_for_masked_lm with prepared config and token labels', 'test Data2VecTextEmbeddings create_position_ids_from_input_ids to verify padding index is respected', 'run slow integration test inference with facebook/data2vec-text-base pretrained masked LM model', 'test the Data2VecVisionModel test suite including forward pass, image classification, and semantic segmentation', 'create a Data2VecVisionConfig with custom hidden_size, num_hidden_layers, and attention_heads for model testing', 'test the Data2VecVisionModel forward pass and verify output hidden state shape', 'test Data2VecVisionForImageClassification inference and verify logits shape for image classification', 'test Data2VecVisionForSemanticSegmentation inference and verify output logits shape for semantic segmentation']
```

Usage

```
{'test_data2vec_text_model': 'test the Data2VecTextModel by running create_and_check_model with prepared config and inputs', 'test_data2vec_text_causal_lm': 'test Data2VecTextForCausalLM by running create_and_check_for_causal_lm with decoder config and labels', 'test_data2vec_text_masked_lm': 'test Data2VecTextForMaskedLM by running create_and_check_for_masked_lm with prepared config and token labels', 'test_data2vec_text_position_ids': 'test Data2VecTextEmbeddings create_position_ids_from_input_ids to verify padding index is respected', 'run_data2vec_text_integration': 'run slow integration test inference with facebook/data2vec-text-base pretrained masked LM model'}
```

## File: huggingface_transformers/tests/models/data2vec/test_modeling_data2vec_vision.py

Prompts

```
['test the Data2VecAudioModel forward pass with config and input tensors', 'test the Data2VecAudioForCTC model CTC loss computation with sum and mean reduction', 'test the Data2VecAudioForSequenceClassification inference and training with labels', 'test the Data2VecAudioForXVector training with frozen base model and gradient computation', 'test the _compute_mask_indices utility for generating random masked spans over audio sequences', 'test the Data2VecTextModel by running create_and_check_model with prepared config and inputs', 'test Data2VecTextForCausalLM by running create_and_check_for_causal_lm with decoder config and labels', 'test Data2VecTextForMaskedLM by running create_and_check_for_masked_lm with prepared config and token labels', 'test Data2VecTextEmbeddings create_position_ids_from_input_ids to verify padding index is respected', 'run slow integration test inference with facebook/data2vec-text-base pretrained masked LM model', 'test the Data2VecVisionModel test suite including forward pass, image classification, and semantic segmentation', 'create a Data2VecVisionConfig with custom hidden_size, num_hidden_layers, and attention_heads for model testing', 'test the Data2VecVisionModel forward pass and verify output hidden state shape', 'test Data2VecVisionForImageClassification inference and verify logits shape for image classification', 'test Data2VecVisionForSemanticSegmentation inference and verify output logits shape for semantic segmentation']
```

Usage

```
{'test_modeling_data2vec_vision': 'test the Data2VecVisionModel test suite including forward pass, image classification, and semantic segmentation', 'create_config_data2vec_vision': 'create a Data2VecVisionConfig with custom hidden_size, num_hidden_layers, and attention_heads for model testing', 'test_data2vec_vision_model': 'test the Data2VecVisionModel forward pass and verify output hidden state shape', 'test_data2vec_vision_classification': 'test Data2VecVisionForImageClassification inference and verify logits shape for image classification', 'test_data2vec_vision_segmentation': 'test Data2VecVisionForSemanticSegmentation inference and verify output logits shape for semantic segmentation'}
```

