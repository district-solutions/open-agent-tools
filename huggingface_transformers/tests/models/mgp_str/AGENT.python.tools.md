# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/mgp_str/test_modeling_mgp_str.py

Prompts

```
['test the MgpstrForSceneTextRecognition model with config and pixel values for scene text recognition', 'test the MgpstrForSceneTextRecognition model batching equivalence with configurable tolerances', 'test the MgpstrForSceneTextRecognition model hidden states output with config and input dict', 'test the MgpstrForSceneTextRecognition model input and output embeddings retrieval', 'test MgpstrForSceneTextRecognition inference on an image from the IIIT-5k dataset', 'test the MgpstrProcessor with text and image inputs to verify it returns pixel_values and labels keys', 'test the MgpstrProcessor char_decode and batch_decode methods for character, BPE, and wordpiece predictions', 'setup a MgpstrTokenizer with a custom vocabulary file containing GO, separator, digit, and letter tokens', 'setup a MgpstrImageProcessor with resize to 128x32 pixels and normalization disabled', 'test that the MgpstrProcessor raises TypeError or ValueError when called with no inputs', 'test the MgpstrTokenizationTest class that verifies MgpstrTokenizer behavior against TokenizerTesterMixin', 'create a MgpstrTokenizer instance from a vocab file containing special tokens and character mappings', 'test the MgpstrTokenizer internal consistency by verifying tokenization, encoding, and decoding round-trips', 'test adding special tokens to MgpstrTokenizer and verify encoding and decoding behavior', 'test that MgpstrTokenizer always lower cases letters and skips add_special_tokens_do_lower_case validation']
```

Usage

```
{'test_model_mgp_str': 'test the MgpstrForSceneTextRecognition model with config and pixel values for scene text recognition', 'test_model_batching_equivalence': 'test the MgpstrForSceneTextRecognition model batching equivalence with configurable tolerances', 'test_model_hidden_states_output': 'test the MgpstrForSceneTextRecognition model hidden states output with config and input dict', 'test_model_get_set_embeddings': 'test the MgpstrForSceneTextRecognition model input and output embeddings retrieval', 'test_mgpstr_inference': 'test MgpstrForSceneTextRecognition inference on an image from the IIIT-5k dataset'}
```

## File: huggingface_transformers/tests/models/mgp_str/test_processing_mgp_str.py

Prompts

```
['test the MgpstrForSceneTextRecognition model with config and pixel values for scene text recognition', 'test the MgpstrForSceneTextRecognition model batching equivalence with configurable tolerances', 'test the MgpstrForSceneTextRecognition model hidden states output with config and input dict', 'test the MgpstrForSceneTextRecognition model input and output embeddings retrieval', 'test MgpstrForSceneTextRecognition inference on an image from the IIIT-5k dataset', 'test the MgpstrProcessor with text and image inputs to verify it returns pixel_values and labels keys', 'test the MgpstrProcessor char_decode and batch_decode methods for character, BPE, and wordpiece predictions', 'setup a MgpstrTokenizer with a custom vocabulary file containing GO, separator, digit, and letter tokens', 'setup a MgpstrImageProcessor with resize to 128x32 pixels and normalization disabled', 'test that the MgpstrProcessor raises TypeError or ValueError when called with no inputs', 'test the MgpstrTokenizationTest class that verifies MgpstrTokenizer behavior against TokenizerTesterMixin', 'create a MgpstrTokenizer instance from a vocab file containing special tokens and character mappings', 'test the MgpstrTokenizer internal consistency by verifying tokenization, encoding, and decoding round-trips', 'test adding special tokens to MgpstrTokenizer and verify encoding and decoding behavior', 'test that MgpstrTokenizer always lower cases letters and skips add_special_tokens_do_lower_case validation']
```

Usage

```
{'test_processor_multiple_inputs': 'test the MgpstrProcessor with text and image inputs to verify it returns pixel_values and labels keys', 'test_processor_decode_defaults': 'test the MgpstrProcessor char_decode and batch_decode methods for character, BPE, and wordpiece predictions', 'setup_tokenizer_vocab': 'setup a MgpstrTokenizer with a custom vocabulary file containing GO, separator, digit, and letter tokens', 'setup_image_processor': 'setup a MgpstrImageProcessor with resize to 128x32 pixels and normalization disabled', 'test_processor_no_input': 'test that the MgpstrProcessor raises TypeError or ValueError when called with no inputs'}
```

## File: huggingface_transformers/tests/models/mgp_str/test_tokenization_mgp_str.py

Prompts

```
['test the MgpstrForSceneTextRecognition model with config and pixel values for scene text recognition', 'test the MgpstrForSceneTextRecognition model batching equivalence with configurable tolerances', 'test the MgpstrForSceneTextRecognition model hidden states output with config and input dict', 'test the MgpstrForSceneTextRecognition model input and output embeddings retrieval', 'test MgpstrForSceneTextRecognition inference on an image from the IIIT-5k dataset', 'test the MgpstrProcessor with text and image inputs to verify it returns pixel_values and labels keys', 'test the MgpstrProcessor char_decode and batch_decode methods for character, BPE, and wordpiece predictions', 'setup a MgpstrTokenizer with a custom vocabulary file containing GO, separator, digit, and letter tokens', 'setup a MgpstrImageProcessor with resize to 128x32 pixels and normalization disabled', 'test that the MgpstrProcessor raises TypeError or ValueError when called with no inputs', 'test the MgpstrTokenizationTest class that verifies MgpstrTokenizer behavior against TokenizerTesterMixin', 'create a MgpstrTokenizer instance from a vocab file containing special tokens and character mappings', 'test the MgpstrTokenizer internal consistency by verifying tokenization, encoding, and decoding round-trips', 'test adding special tokens to MgpstrTokenizer and verify encoding and decoding behavior', 'test that MgpstrTokenizer always lower cases letters and skips add_special_tokens_do_lower_case validation']
```

Usage

```
{'test_MgpstrTokenizationTest': 'test the MgpstrTokenizationTest class that verifies MgpstrTokenizer behavior against TokenizerTesterMixin', 'create_tokenizer_mgp_str': 'create a MgpstrTokenizer instance from a vocab file containing special tokens and character mappings', 'test_tokenizer_internal_consistency': 'test the MgpstrTokenizer internal consistency by verifying tokenization, encoding, and decoding round-trips', 'test_tokenizer_special_tokens': 'test adding special tokens to MgpstrTokenizer and verify encoding and decoding behavior', 'test_tokenizer_lower_case': 'test that MgpstrTokenizer always lower cases letters and skips add_special_tokens_do_lower_case validation'}
```

