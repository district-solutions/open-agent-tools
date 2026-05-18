# Agent Python Tools

- repo: facebookresearch/multimodal
- repo_uri: https://github.com/facebookresearch/multimodal

## File: facebookresearch_multimodal/tests/models/coca/test_coca_model.py

Prompts

```
['build a CoCa model using coca_vit with vision patch size, vocab size, and text positions', 'create a CoCaForPretraining wrapper around a coca_vit model to compute contrastive and captioning losses', 'test the CoCa model forward pass with image and text inputs and verify MultimodalOutput', 'test the CoCa model with cascaded pooler enabled and verify image pooled output shape', 'test TorchScript compilation of the CoCa model and verify scripted output matches original', 'test the CoCaMultimodalDecoder forward pass with text and image inputs against expected output', 'test that CoCaMultimodalDecoder can be scripted with torch.jit.script and produces identical output', 'create a CoCaMultimodalDecoder with custom initialized weights for deterministic testing', 'create a tensor of text embeddings reshaped to batch size, sequence length, and embedding dim', 'create a tensor of image embeddings reshaped to batch size, image positions, and embedding dim', 'test the CoCaTextDecoder with input_ids to verify pooled and token outputs match expected values', 'test the CoCaTextEmbeddings class to verify token and CLS embeddings are computed correctly', 'test the CoCaTextDecoder build_mask method to verify attention mask generation from input_ids', 'test the CoCaTextDecoder with an explicit padding mask to verify masked decoding behavior', 'test the CoCaTextDecoder with torch.jit.script to verify TorchScript compatibility and output equivalence']
```

Usage

```
{'build_coca_vit_model': 'build a CoCa model using coca_vit with vision patch size, vocab size, and text positions', 'create_coca_for_pretraining': 'create a CoCaForPretraining wrapper around a coca_vit model to compute contrastive and captioning losses', 'test_coca_model_forward': 'test the CoCa model forward pass with image and text inputs and verify MultimodalOutput', 'test_coca_cascaded_pooler': 'test the CoCa model with cascaded pooler enabled and verify image pooled output shape', 'test_coca_scripting': 'test TorchScript compilation of the CoCa model and verify scripted output matches original'}
```

## File: facebookresearch_multimodal/tests/models/coca/test_multimodal_decoder.py

Prompts

```
['build a CoCa model using coca_vit with vision patch size, vocab size, and text positions', 'create a CoCaForPretraining wrapper around a coca_vit model to compute contrastive and captioning losses', 'test the CoCa model forward pass with image and text inputs and verify MultimodalOutput', 'test the CoCa model with cascaded pooler enabled and verify image pooled output shape', 'test TorchScript compilation of the CoCa model and verify scripted output matches original', 'test the CoCaMultimodalDecoder forward pass with text and image inputs against expected output', 'test that CoCaMultimodalDecoder can be scripted with torch.jit.script and produces identical output', 'create a CoCaMultimodalDecoder with custom initialized weights for deterministic testing', 'create a tensor of text embeddings reshaped to batch size, sequence length, and embedding dim', 'create a tensor of image embeddings reshaped to batch size, image positions, and embedding dim', 'test the CoCaTextDecoder with input_ids to verify pooled and token outputs match expected values', 'test the CoCaTextEmbeddings class to verify token and CLS embeddings are computed correctly', 'test the CoCaTextDecoder build_mask method to verify attention mask generation from input_ids', 'test the CoCaTextDecoder with an explicit padding mask to verify masked decoding behavior', 'test the CoCaTextDecoder with torch.jit.script to verify TorchScript compatibility and output equivalence']
```

Usage

```
{'test_coca_multimodal_decoder_forward': 'test the CoCaMultimodalDecoder forward pass with text and image inputs against expected output', 'test_coca_multimodal_decoder_scripting': 'test that CoCaMultimodalDecoder can be scripted with torch.jit.script and produces identical output', 'create_multimodal_decoder_fixture': 'create a CoCaMultimodalDecoder with custom initialized weights for deterministic testing', 'create_text_inputs_fixture': 'create a tensor of text embeddings reshaped to batch size, sequence length, and embedding dim', 'create_image_inputs_fixture': 'create a tensor of image embeddings reshaped to batch size, image positions, and embedding dim'}
```

## File: facebookresearch_multimodal/tests/models/coca/test_text_decoder.py

Prompts

```
['build a CoCa model using coca_vit with vision patch size, vocab size, and text positions', 'create a CoCaForPretraining wrapper around a coca_vit model to compute contrastive and captioning losses', 'test the CoCa model forward pass with image and text inputs and verify MultimodalOutput', 'test the CoCa model with cascaded pooler enabled and verify image pooled output shape', 'test TorchScript compilation of the CoCa model and verify scripted output matches original', 'test the CoCaMultimodalDecoder forward pass with text and image inputs against expected output', 'test that CoCaMultimodalDecoder can be scripted with torch.jit.script and produces identical output', 'create a CoCaMultimodalDecoder with custom initialized weights for deterministic testing', 'create a tensor of text embeddings reshaped to batch size, sequence length, and embedding dim', 'create a tensor of image embeddings reshaped to batch size, image positions, and embedding dim', 'test the CoCaTextDecoder with input_ids to verify pooled and token outputs match expected values', 'test the CoCaTextEmbeddings class to verify token and CLS embeddings are computed correctly', 'test the CoCaTextDecoder build_mask method to verify attention mask generation from input_ids', 'test the CoCaTextDecoder with an explicit padding mask to verify masked decoding behavior', 'test the CoCaTextDecoder with torch.jit.script to verify TorchScript compatibility and output equivalence']
```

Usage

```
{'test_CoCaTextDecoder': 'test the CoCaTextDecoder with input_ids to verify pooled and token outputs match expected values', 'test_CoCaTextEmbeddings': 'test the CoCaTextEmbeddings class to verify token and CLS embeddings are computed correctly', 'test_build_attention_mask': 'test the CoCaTextDecoder build_mask method to verify attention mask generation from input_ids', 'test_CoCaTextDecoder_padding_mask': 'test the CoCaTextDecoder with an explicit padding mask to verify masked decoding behavior', 'test_CoCaTextDecoder_scripting': 'test the CoCaTextDecoder with torch.jit.script to verify TorchScript compatibility and output equivalence'}
```

