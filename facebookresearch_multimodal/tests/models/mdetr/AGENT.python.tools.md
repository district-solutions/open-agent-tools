# Agent Python Tools

- repo: facebookresearch/multimodal
- repo_uri: https://github.com/facebookresearch/multimodal

## File: facebookresearch_multimodal/tests/models/mdetr/test_image_encoder.py

Prompts

```
['test the mdetr_resnet101_backbone forward pass with a 4x3x64x64 tensor and mask', 'test the TestMDETRImageEncoder unittest class that validates ResNet-101 backbone output shapes and values', 'run the unittest for the MDETR ResNet-101 image encoder backbone forward pass', 'review the TestMDETRImageEncoder class and its test_resnet_101_forward method for correctness', 'summarize the test that validates mdetr_resnet101_backbone output dimensions and tensor values', 'test the mdetr_resnet101 model with image tensors and input IDs to verify prediction logits and boxes', 'test the mdetr_for_phrase_grounding model to verify contrastive query and token embeddings output', 'test the mdetr_for_vqa model with GQA heads to verify answer type, object, and relation predictions', 'run the mdetr_resnet101 model in eval mode with batched image tensors and tokenized input IDs', 'review the TestMDETR pytest class and its fixtures for batch size, num queries, and num classes configuration', 'test the ModifiedTransformerEncoder with random encoder input and attention mask tensors', 'run the pytest test that validates ModifiedTransformerEncoder output shape and hidden state values', 'create a ModifiedTransformerEncoder fixture with 768 embedding dim, 12 attention heads, and 12 layers', 'create a boolean attention mask tensor fixture with random 0 or 1 values', 'assert the encoder output last hidden state matches expected tensor values within tolerance', 'test the MDETRTransformer encoder with source tensors, padding masks, and positional encodings', 'test the MDETRTransformer decoder with target queries, memory, and positional encodings', 'run the pytest test for the MDETRTransformer encoder output shape and expected values', 'run the pytest test for the MDETRTransformer decoder output shape and expected values', 'review the TestMDETRTransformer class fixtures for batch size, embedding dim, and query count configuration']
```

Usage

```
{'test_resnet101_backbone_forward': 'test the mdetr_resnet101_backbone forward pass with a 4x3x64x64 tensor and mask', 'test_MDETRImageEncoder_class': 'test the TestMDETRImageEncoder unittest class that validates ResNet-101 backbone output shapes and values', 'run_resnet101_encoder_test': 'run the unittest for the MDETR ResNet-101 image encoder backbone forward pass', 'review_TestMDETRImageEncoder': 'review the TestMDETRImageEncoder class and its test_resnet_101_forward method for correctness', 'summarize_mdetr_resnet101_backbone_test': 'summarize the test that validates mdetr_resnet101_backbone output dimensions and tensor values'}
```

## File: facebookresearch_multimodal/tests/models/mdetr/test_mdetr.py

Prompts

```
['test the mdetr_resnet101_backbone forward pass with a 4x3x64x64 tensor and mask', 'test the TestMDETRImageEncoder unittest class that validates ResNet-101 backbone output shapes and values', 'run the unittest for the MDETR ResNet-101 image encoder backbone forward pass', 'review the TestMDETRImageEncoder class and its test_resnet_101_forward method for correctness', 'summarize the test that validates mdetr_resnet101_backbone output dimensions and tensor values', 'test the mdetr_resnet101 model with image tensors and input IDs to verify prediction logits and boxes', 'test the mdetr_for_phrase_grounding model to verify contrastive query and token embeddings output', 'test the mdetr_for_vqa model with GQA heads to verify answer type, object, and relation predictions', 'run the mdetr_resnet101 model in eval mode with batched image tensors and tokenized input IDs', 'review the TestMDETR pytest class and its fixtures for batch size, num queries, and num classes configuration', 'test the ModifiedTransformerEncoder with random encoder input and attention mask tensors', 'run the pytest test that validates ModifiedTransformerEncoder output shape and hidden state values', 'create a ModifiedTransformerEncoder fixture with 768 embedding dim, 12 attention heads, and 12 layers', 'create a boolean attention mask tensor fixture with random 0 or 1 values', 'assert the encoder output last hidden state matches expected tensor values within tolerance', 'test the MDETRTransformer encoder with source tensors, padding masks, and positional encodings', 'test the MDETRTransformer decoder with target queries, memory, and positional encodings', 'run the pytest test for the MDETRTransformer encoder output shape and expected values', 'run the pytest test for the MDETRTransformer decoder output shape and expected values', 'review the TestMDETRTransformer class fixtures for batch size, embedding dim, and query count configuration']
```

Usage

```
{'test_mdetr_resnet101_model': 'test the mdetr_resnet101 model with image tensors and input IDs to verify prediction logits and boxes', 'test_mdetr_phrase_grounding': 'test the mdetr_for_phrase_grounding model to verify contrastive query and token embeddings output', 'test_mdetr_vqa_model': 'test the mdetr_for_vqa model with GQA heads to verify answer type, object, and relation predictions', 'run_mdetr_model_inference': 'run the mdetr_resnet101 model in eval mode with batched image tensors and tokenized input IDs', 'review_TestMDETR_class': 'review the TestMDETR pytest class and its fixtures for batch size, num queries, and num classes configuration'}
```

## File: facebookresearch_multimodal/tests/models/mdetr/test_text_encoder.py

Prompts

```
['test the mdetr_resnet101_backbone forward pass with a 4x3x64x64 tensor and mask', 'test the TestMDETRImageEncoder unittest class that validates ResNet-101 backbone output shapes and values', 'run the unittest for the MDETR ResNet-101 image encoder backbone forward pass', 'review the TestMDETRImageEncoder class and its test_resnet_101_forward method for correctness', 'summarize the test that validates mdetr_resnet101_backbone output dimensions and tensor values', 'test the mdetr_resnet101 model with image tensors and input IDs to verify prediction logits and boxes', 'test the mdetr_for_phrase_grounding model to verify contrastive query and token embeddings output', 'test the mdetr_for_vqa model with GQA heads to verify answer type, object, and relation predictions', 'run the mdetr_resnet101 model in eval mode with batched image tensors and tokenized input IDs', 'review the TestMDETR pytest class and its fixtures for batch size, num queries, and num classes configuration', 'test the ModifiedTransformerEncoder with random encoder input and attention mask tensors', 'run the pytest test that validates ModifiedTransformerEncoder output shape and hidden state values', 'create a ModifiedTransformerEncoder fixture with 768 embedding dim, 12 attention heads, and 12 layers', 'create a boolean attention mask tensor fixture with random 0 or 1 values', 'assert the encoder output last hidden state matches expected tensor values within tolerance', 'test the MDETRTransformer encoder with source tensors, padding masks, and positional encodings', 'test the MDETRTransformer decoder with target queries, memory, and positional encodings', 'run the pytest test for the MDETRTransformer encoder output shape and expected values', 'run the pytest test for the MDETRTransformer decoder output shape and expected values', 'review the TestMDETRTransformer class fixtures for batch size, embedding dim, and query count configuration']
```

Usage

```
{'test_ModifiedTransformerEncoder': 'test the ModifiedTransformerEncoder with random encoder input and attention mask tensors', 'run_test_mdetr_modified_transformer': 'run the pytest test that validates ModifiedTransformerEncoder output shape and hidden state values', 'create_encoder_fixture': 'create a ModifiedTransformerEncoder fixture with 768 embedding dim, 12 attention heads, and 12 layers', 'create_attention_mask_fixture': 'create a boolean attention mask tensor fixture with random 0 or 1 values', 'assert_expected_hidden_state': 'assert the encoder output last hidden state matches expected tensor values within tolerance'}
```

## File: facebookresearch_multimodal/tests/models/mdetr/test_transformer.py

Prompts

```
['test the mdetr_resnet101_backbone forward pass with a 4x3x64x64 tensor and mask', 'test the TestMDETRImageEncoder unittest class that validates ResNet-101 backbone output shapes and values', 'run the unittest for the MDETR ResNet-101 image encoder backbone forward pass', 'review the TestMDETRImageEncoder class and its test_resnet_101_forward method for correctness', 'summarize the test that validates mdetr_resnet101_backbone output dimensions and tensor values', 'test the mdetr_resnet101 model with image tensors and input IDs to verify prediction logits and boxes', 'test the mdetr_for_phrase_grounding model to verify contrastive query and token embeddings output', 'test the mdetr_for_vqa model with GQA heads to verify answer type, object, and relation predictions', 'run the mdetr_resnet101 model in eval mode with batched image tensors and tokenized input IDs', 'review the TestMDETR pytest class and its fixtures for batch size, num queries, and num classes configuration', 'test the ModifiedTransformerEncoder with random encoder input and attention mask tensors', 'run the pytest test that validates ModifiedTransformerEncoder output shape and hidden state values', 'create a ModifiedTransformerEncoder fixture with 768 embedding dim, 12 attention heads, and 12 layers', 'create a boolean attention mask tensor fixture with random 0 or 1 values', 'assert the encoder output last hidden state matches expected tensor values within tolerance', 'test the MDETRTransformer encoder with source tensors, padding masks, and positional encodings', 'test the MDETRTransformer decoder with target queries, memory, and positional encodings', 'run the pytest test for the MDETRTransformer encoder output shape and expected values', 'run the pytest test for the MDETRTransformer decoder output shape and expected values', 'review the TestMDETRTransformer class fixtures for batch size, embedding dim, and query count configuration']
```

Usage

```
{'test_MDETRTransformer_encoder': 'test the MDETRTransformer encoder with source tensors, padding masks, and positional encodings', 'test_MDETRTransformer_decoder': 'test the MDETRTransformer decoder with target queries, memory, and positional encodings', 'run_test_transformer_encoder': 'run the pytest test for the MDETRTransformer encoder output shape and expected values', 'run_test_transformer_decoder': 'run the pytest test for the MDETRTransformer decoder output shape and expected values', 'review_TestMDETRTransformer_fixtures': 'review the TestMDETRTransformer class fixtures for batch size, embedding dim, and query count configuration'}
```

