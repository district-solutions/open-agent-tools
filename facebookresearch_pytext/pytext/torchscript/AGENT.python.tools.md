# Agent Python Tools

- repo: facebookresearch/pytext
- repo_uri: https://github.com/facebookresearch/pytext

## File: facebookresearch_pytext/pytext/torchscript/batchutils.py

Prompts

```
['create a function that flattens a batch of text tuples into a single list of strings for prediction', 'build a batch of texts sorted by token length using a ScriptTensorizer and goals config', 'create a function that flattens text and dense feature batches into paired lists for prediction', 'build a function that splits a result tensor into per-client-batch tensors using a client batch size list', 'test a batch element tuple to ensure only one of texts, multi_texts, or tokens is populated', 'build a ScriptPyTextEmbeddingModule to run inference on text batches with tensorizer and model', 'create a ScriptPyTextTwoTowerModule with separate left and right tensorizers for dual-input inference', 'test the ScriptPyTextEmbeddingModuleWithDense forward method with text and dense feature inputs', 'refactor the ScriptPyTextTriTowerModule to add custom output layer logic for three-tower models', 'review the ScriptPyTextEmbeddingModule make_prediction method for cross-request batching and destructure logic', 'pad a list of int lists to a 2D tensor and return a mask tensor for non-pad positions', 'truncate a batch of token lists to a maximum sequence length with a pad token', 'convert a batch of token strings into a 3D byte tensor with sequence lengths', 'add beginning and end of sequence tokens to each sequence in a 2D int list', 'split a UTF-8 encoded string into a list of individual character strings', 'create a ScriptVocabulary instance from a list of words with configurable special token indices', 'convert a list of words into their corresponding vocabulary indices using lookup_indices_1d', 'convert a nested list of word lists into 2D vocabulary indices using lookup_indices_2d', 'convert a 1D tensor of indices back into words using lookup_words_1d with optional filtering', 'look up a single word by its vocabulary index using the lookup_word method']
```

Usage

```
{'make_prediction_texts': 'create a function that flattens a batch of text tuples into a single list of strings for prediction', 'make_batch_texts': 'build a batch of texts sorted by token length using a ScriptTensorizer and goals config', 'make_prediction_texts_dense': 'create a function that flattens text and dense feature batches into paired lists for prediction', 'destructure_tensor': 'build a function that splits a result tensor into per-client-batch tensors using a client batch size list', 'validate_batch_element': 'test a batch element tuple to ensure only one of texts, multi_texts, or tokens is populated'}
```

## File: facebookresearch_pytext/pytext/torchscript/module.py

Prompts

```
['create a function that flattens a batch of text tuples into a single list of strings for prediction', 'build a batch of texts sorted by token length using a ScriptTensorizer and goals config', 'create a function that flattens text and dense feature batches into paired lists for prediction', 'build a function that splits a result tensor into per-client-batch tensors using a client batch size list', 'test a batch element tuple to ensure only one of texts, multi_texts, or tokens is populated', 'build a ScriptPyTextEmbeddingModule to run inference on text batches with tensorizer and model', 'create a ScriptPyTextTwoTowerModule with separate left and right tensorizers for dual-input inference', 'test the ScriptPyTextEmbeddingModuleWithDense forward method with text and dense feature inputs', 'refactor the ScriptPyTextTriTowerModule to add custom output layer logic for three-tower models', 'review the ScriptPyTextEmbeddingModule make_prediction method for cross-request batching and destructure logic', 'pad a list of int lists to a 2D tensor and return a mask tensor for non-pad positions', 'truncate a batch of token lists to a maximum sequence length with a pad token', 'convert a batch of token strings into a 3D byte tensor with sequence lengths', 'add beginning and end of sequence tokens to each sequence in a 2D int list', 'split a UTF-8 encoded string into a list of individual character strings', 'create a ScriptVocabulary instance from a list of words with configurable special token indices', 'convert a list of words into their corresponding vocabulary indices using lookup_indices_1d', 'convert a nested list of word lists into 2D vocabulary indices using lookup_indices_2d', 'convert a 1D tensor of indices back into words using lookup_words_1d with optional filtering', 'look up a single word by its vocabulary index using the lookup_word method']
```

Usage

```
{'build_embedding_module': 'build a ScriptPyTextEmbeddingModule to run inference on text batches with tensorizer and model', 'create_two_tower_module': 'create a ScriptPyTextTwoTowerModule with separate left and right tensorizers for dual-input inference', 'test_dense_embedding_module': 'test the ScriptPyTextEmbeddingModuleWithDense forward method with text and dense feature inputs', 'refactor_tritower_module': 'refactor the ScriptPyTextTriTowerModule to add custom output layer logic for three-tower models', 'review_make_prediction': 'review the ScriptPyTextEmbeddingModule make_prediction method for cross-request batching and destructure logic'}
```

## File: facebookresearch_pytext/pytext/torchscript/utils.py

Prompts

```
['create a function that flattens a batch of text tuples into a single list of strings for prediction', 'build a batch of texts sorted by token length using a ScriptTensorizer and goals config', 'create a function that flattens text and dense feature batches into paired lists for prediction', 'build a function that splits a result tensor into per-client-batch tensors using a client batch size list', 'test a batch element tuple to ensure only one of texts, multi_texts, or tokens is populated', 'build a ScriptPyTextEmbeddingModule to run inference on text batches with tensorizer and model', 'create a ScriptPyTextTwoTowerModule with separate left and right tensorizers for dual-input inference', 'test the ScriptPyTextEmbeddingModuleWithDense forward method with text and dense feature inputs', 'refactor the ScriptPyTextTriTowerModule to add custom output layer logic for three-tower models', 'review the ScriptPyTextEmbeddingModule make_prediction method for cross-request batching and destructure logic', 'pad a list of int lists to a 2D tensor and return a mask tensor for non-pad positions', 'truncate a batch of token lists to a maximum sequence length with a pad token', 'convert a batch of token strings into a 3D byte tensor with sequence lengths', 'add beginning and end of sequence tokens to each sequence in a 2D int list', 'split a UTF-8 encoded string into a list of individual character strings', 'create a ScriptVocabulary instance from a list of words with configurable special token indices', 'convert a list of words into their corresponding vocabulary indices using lookup_indices_1d', 'convert a nested list of word lists into 2D vocabulary indices using lookup_indices_2d', 'convert a 1D tensor of indices back into words using lookup_words_1d with optional filtering', 'look up a single word by its vocabulary index using the lookup_word method']
```

Usage

```
{'pad_2d_mask': 'pad a list of int lists to a 2D tensor and return a mask tensor for non-pad positions', 'truncate_tokens': 'truncate a batch of token lists to a maximum sequence length with a pad token', 'make_byte_inputs': 'convert a batch of token strings into a 3D byte tensor with sequence lengths', 'add_bos_eos_2d': 'add beginning and end of sequence tokens to each sequence in a 2D int list', 'utf8_chars': 'split a UTF-8 encoded string into a list of individual character strings'}
```

## File: facebookresearch_pytext/pytext/torchscript/vocab.py

Prompts

```
['create a function that flattens a batch of text tuples into a single list of strings for prediction', 'build a batch of texts sorted by token length using a ScriptTensorizer and goals config', 'create a function that flattens text and dense feature batches into paired lists for prediction', 'build a function that splits a result tensor into per-client-batch tensors using a client batch size list', 'test a batch element tuple to ensure only one of texts, multi_texts, or tokens is populated', 'build a ScriptPyTextEmbeddingModule to run inference on text batches with tensorizer and model', 'create a ScriptPyTextTwoTowerModule with separate left and right tensorizers for dual-input inference', 'test the ScriptPyTextEmbeddingModuleWithDense forward method with text and dense feature inputs', 'refactor the ScriptPyTextTriTowerModule to add custom output layer logic for three-tower models', 'review the ScriptPyTextEmbeddingModule make_prediction method for cross-request batching and destructure logic', 'pad a list of int lists to a 2D tensor and return a mask tensor for non-pad positions', 'truncate a batch of token lists to a maximum sequence length with a pad token', 'convert a batch of token strings into a 3D byte tensor with sequence lengths', 'add beginning and end of sequence tokens to each sequence in a 2D int list', 'split a UTF-8 encoded string into a list of individual character strings', 'create a ScriptVocabulary instance from a list of words with configurable special token indices', 'convert a list of words into their corresponding vocabulary indices using lookup_indices_1d', 'convert a nested list of word lists into 2D vocabulary indices using lookup_indices_2d', 'convert a 1D tensor of indices back into words using lookup_words_1d with optional filtering', 'look up a single word by its vocabulary index using the lookup_word method']
```

Usage

```
{'create_script_vocabulary': 'create a ScriptVocabulary instance from a list of words with configurable special token indices', 'lookup_indices_1d': 'convert a list of words into their corresponding vocabulary indices using lookup_indices_1d', 'lookup_indices_2d': 'convert a nested list of word lists into 2D vocabulary indices using lookup_indices_2d', 'lookup_words_1d': 'convert a 1D tensor of indices back into words using lookup_words_1d with optional filtering', 'lookup_word': 'look up a single word by its vocabulary index using the lookup_word method'}
```

