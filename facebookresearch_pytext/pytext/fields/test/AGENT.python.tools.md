# Agent Python Tools

- repo: facebookresearch/pytext
- repo_uri: https://github.com/facebookresearch/pytext

## File: facebookresearch_pytext/pytext/fields/test/char_field_test.py

Prompts

```
['test CharFeatureField build_vocab method to verify character frequency counts and vocabulary itos list', 'test CharFeatureField pad method to verify padded character sequences are sorted by descending length', 'test CharFeatureField numericalize method to verify padded character sequences convert to correct tensor indices', 'test CharFeatureField preprocess method to verify raw utterances are preprocessed before vocab building', 'test CharFeatureField pad method with FP16 precision enabled to verify sequence length is divisible by 8', 'test the ContextualTokenEmbeddingField pad method with variable-length embedding batches', 'run the ContextualTokenEmbeddingFieldTest unit test suite with unittest', 'review the ContextualTokenEmbeddingFieldTest class and its pad test assertions', 'summarize the ContextualTokenEmbeddingFieldTest setUp and test_pad methods', 'refactor the ContextualTokenEmbeddingFieldTest to use numpy array comparison instead of nested loops', 'test DictFeatureField right padding and numericalization of dictionary features with FP16 alignment', 'test DictFeatureField left padding and numericalization of dictionary features with FP16 alignment', 'run the DictFieldTest unittest suite to verify DictFeatureField padding and numericalization', 'review DictFeatureField right and left padding behavior for dict features and weights', 'summarize the DictFieldTest class that tests DictFeatureField pad and numericalize methods', 'test FloatVectorField preprocess and process with bracketed comma-separated float array input', 'test FloatVectorField preprocess and process with space and comma separated float input', 'test FloatVectorField preprocess and process with unclosed bracket float array input', 'test FloatVectorField preprocess and process with unopened bracket float array input', 'run the FieldTest unittest suite to validate FloatVectorField preprocessing and tensor padding']
```

Usage

```
{'test_char_feature_field_build_vocab': 'test CharFeatureField build_vocab method to verify character frequency counts and vocabulary itos list', 'test_char_feature_field_pad': 'test CharFeatureField pad method to verify padded character sequences are sorted by descending length', 'test_char_feature_field_numericalize': 'test CharFeatureField numericalize method to verify padded character sequences convert to correct tensor indices', 'test_char_feature_field_preprocess': 'test CharFeatureField preprocess method to verify raw utterances are preprocessed before vocab building', 'test_char_feature_field_fp16_padding': 'test CharFeatureField pad method with FP16 precision enabled to verify sequence length is divisible by 8'}
```

## File: facebookresearch_pytext/pytext/fields/test/contextual_token_embedding_field_test.py

Prompts

```
['test CharFeatureField build_vocab method to verify character frequency counts and vocabulary itos list', 'test CharFeatureField pad method to verify padded character sequences are sorted by descending length', 'test CharFeatureField numericalize method to verify padded character sequences convert to correct tensor indices', 'test CharFeatureField preprocess method to verify raw utterances are preprocessed before vocab building', 'test CharFeatureField pad method with FP16 precision enabled to verify sequence length is divisible by 8', 'test the ContextualTokenEmbeddingField pad method with variable-length embedding batches', 'run the ContextualTokenEmbeddingFieldTest unit test suite with unittest', 'review the ContextualTokenEmbeddingFieldTest class and its pad test assertions', 'summarize the ContextualTokenEmbeddingFieldTest setUp and test_pad methods', 'refactor the ContextualTokenEmbeddingFieldTest to use numpy array comparison instead of nested loops', 'test DictFeatureField right padding and numericalization of dictionary features with FP16 alignment', 'test DictFeatureField left padding and numericalization of dictionary features with FP16 alignment', 'run the DictFieldTest unittest suite to verify DictFeatureField padding and numericalization', 'review DictFeatureField right and left padding behavior for dict features and weights', 'summarize the DictFieldTest class that tests DictFeatureField pad and numericalize methods', 'test FloatVectorField preprocess and process with bracketed comma-separated float array input', 'test FloatVectorField preprocess and process with space and comma separated float input', 'test FloatVectorField preprocess and process with unclosed bracket float array input', 'test FloatVectorField preprocess and process with unopened bracket float array input', 'run the FieldTest unittest suite to validate FloatVectorField preprocessing and tensor padding']
```

Usage

```
{'test_pad_contextual_token_embeddings': 'test the ContextualTokenEmbeddingField pad method with variable-length embedding batches', 'run_contextual_embedding_field_test': 'run the ContextualTokenEmbeddingFieldTest unit test suite with unittest', 'review_contextual_token_embedding_field_test': 'review the ContextualTokenEmbeddingFieldTest class and its pad test assertions', 'summarize_contextual_token_embedding_field_test': 'summarize the ContextualTokenEmbeddingFieldTest setUp and test_pad methods', 'refactor_contextual_token_embedding_field_test': 'refactor the ContextualTokenEmbeddingFieldTest to use numpy array comparison instead of nested loops'}
```

## File: facebookresearch_pytext/pytext/fields/test/dict_field_test.py

Prompts

```
['test CharFeatureField build_vocab method to verify character frequency counts and vocabulary itos list', 'test CharFeatureField pad method to verify padded character sequences are sorted by descending length', 'test CharFeatureField numericalize method to verify padded character sequences convert to correct tensor indices', 'test CharFeatureField preprocess method to verify raw utterances are preprocessed before vocab building', 'test CharFeatureField pad method with FP16 precision enabled to verify sequence length is divisible by 8', 'test the ContextualTokenEmbeddingField pad method with variable-length embedding batches', 'run the ContextualTokenEmbeddingFieldTest unit test suite with unittest', 'review the ContextualTokenEmbeddingFieldTest class and its pad test assertions', 'summarize the ContextualTokenEmbeddingFieldTest setUp and test_pad methods', 'refactor the ContextualTokenEmbeddingFieldTest to use numpy array comparison instead of nested loops', 'test DictFeatureField right padding and numericalization of dictionary features with FP16 alignment', 'test DictFeatureField left padding and numericalization of dictionary features with FP16 alignment', 'run the DictFieldTest unittest suite to verify DictFeatureField padding and numericalization', 'review DictFeatureField right and left padding behavior for dict features and weights', 'summarize the DictFieldTest class that tests DictFeatureField pad and numericalize methods', 'test FloatVectorField preprocess and process with bracketed comma-separated float array input', 'test FloatVectorField preprocess and process with space and comma separated float input', 'test FloatVectorField preprocess and process with unclosed bracket float array input', 'test FloatVectorField preprocess and process with unopened bracket float array input', 'run the FieldTest unittest suite to validate FloatVectorField preprocessing and tensor padding']
```

Usage

```
{'test_DictFeatureField_right_pad_numericalize': 'test DictFeatureField right padding and numericalization of dictionary features with FP16 alignment', 'test_DictFeatureField_left_pad_numericalize': 'test DictFeatureField left padding and numericalization of dictionary features with FP16 alignment', 'run_DictFieldTest': 'run the DictFieldTest unittest suite to verify DictFeatureField padding and numericalization', 'review_DictFeatureField_padding': 'review DictFeatureField right and left padding behavior for dict features and weights', 'summarize_DictFieldTest': 'summarize the DictFieldTest class that tests DictFeatureField pad and numericalize methods'}
```

## File: facebookresearch_pytext/pytext/fields/test/field_test.py

Prompts

```
['test CharFeatureField build_vocab method to verify character frequency counts and vocabulary itos list', 'test CharFeatureField pad method to verify padded character sequences are sorted by descending length', 'test CharFeatureField numericalize method to verify padded character sequences convert to correct tensor indices', 'test CharFeatureField preprocess method to verify raw utterances are preprocessed before vocab building', 'test CharFeatureField pad method with FP16 precision enabled to verify sequence length is divisible by 8', 'test the ContextualTokenEmbeddingField pad method with variable-length embedding batches', 'run the ContextualTokenEmbeddingFieldTest unit test suite with unittest', 'review the ContextualTokenEmbeddingFieldTest class and its pad test assertions', 'summarize the ContextualTokenEmbeddingFieldTest setUp and test_pad methods', 'refactor the ContextualTokenEmbeddingFieldTest to use numpy array comparison instead of nested loops', 'test DictFeatureField right padding and numericalization of dictionary features with FP16 alignment', 'test DictFeatureField left padding and numericalization of dictionary features with FP16 alignment', 'run the DictFieldTest unittest suite to verify DictFeatureField padding and numericalization', 'review DictFeatureField right and left padding behavior for dict features and weights', 'summarize the DictFieldTest class that tests DictFeatureField pad and numericalize methods', 'test FloatVectorField preprocess and process with bracketed comma-separated float array input', 'test FloatVectorField preprocess and process with space and comma separated float input', 'test FloatVectorField preprocess and process with unclosed bracket float array input', 'test FloatVectorField preprocess and process with unopened bracket float array input', 'run the FieldTest unittest suite to validate FloatVectorField preprocessing and tensor padding']
```

Usage

```
{'test_float_vector_array_style': 'test FloatVectorField preprocess and process with bracketed comma-separated float array input', 'test_float_vector_array_plain': 'test FloatVectorField preprocess and process with space and comma separated float input', 'test_float_vector_array_not_closed': 'test FloatVectorField preprocess and process with unclosed bracket float array input', 'test_float_vector_array_not_opened': 'test FloatVectorField preprocess and process with unopened bracket float array input', 'run_field_test_suite': 'run the FieldTest unittest suite to validate FloatVectorField preprocessing and tensor padding'}
```

