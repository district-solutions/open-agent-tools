# Agent Python Tools

- repo: facebookresearch/parlai
- repo_uri: https://github.com/facebookresearch/parlai

## File: facebookresearch_parlai/parlai/agents/image_seq2seq/image_seq2seq.py

Prompts

```
['build an ImageSeq2seqAgent model combining a transformer generator with image encoding capabilities', 'add command line arguments for image encoder including image token and fusion type options', 'build a dictionary agent that includes image and no image special tokens', 'batchify image features in a batch by processing tensor images to the correct shape', 'load a model state dict with custom handling for missing image encoder or embedding differences', 'build an ImageSeq2seqModel with a ContextWithImageEncoder to encode images alongside text tokens', 'create a ContextWithImageEncoder that combines image features and text context via early or late fusion', 'test the encode_images method to encode a batch of image tensors into embedding space', 'review the _forward_early_fusion method that fuses image and token embeddings before transformer layers', 'refactor the _forward_late_fusion method to combine separately encoded images and context via add append or prepend']
```

Usage

```
{'build_ImageSeq2seqAgent_model': 'build an ImageSeq2seqAgent model combining a transformer generator with image encoding capabilities', 'add_cmdline_args_ImageSeq2seqAgent': 'add command line arguments for image encoder including image token and fusion type options', 'build_dictionary_ImageSeq2seqAgent': 'build a dictionary agent that includes image and no image special tokens', 'batchify_image_features_ImageSeq2seqAgent': 'batchify image features in a batch by processing tensor images to the correct shape', 'load_state_dict_ImageSeq2seqAgent': 'load a model state dict with custom handling for missing image encoder or embedding differences'}
```

## File: facebookresearch_parlai/parlai/agents/image_seq2seq/modules.py

Prompts

```
['build an ImageSeq2seqAgent model combining a transformer generator with image encoding capabilities', 'add command line arguments for image encoder including image token and fusion type options', 'build a dictionary agent that includes image and no image special tokens', 'batchify image features in a batch by processing tensor images to the correct shape', 'load a model state dict with custom handling for missing image encoder or embedding differences', 'build an ImageSeq2seqModel with a ContextWithImageEncoder to encode images alongside text tokens', 'create a ContextWithImageEncoder that combines image features and text context via early or late fusion', 'test the encode_images method to encode a batch of image tensors into embedding space', 'review the _forward_early_fusion method that fuses image and token embeddings before transformer layers', 'refactor the _forward_late_fusion method to combine separately encoded images and context via add append or prepend']
```

Usage

```
{'build_ImageSeq2seqModel': 'build an ImageSeq2seqModel with a ContextWithImageEncoder to encode images alongside text tokens', 'create_ContextWithImageEncoder': 'create a ContextWithImageEncoder that combines image features and text context via early or late fusion', 'test_encode_images': 'test the encode_images method to encode a batch of image tensors into embedding space', 'review_forward_early_fusion': 'review the _forward_early_fusion method that fuses image and token embeddings before transformer layers', 'refactor_forward_late_fusion': 'refactor the _forward_late_fusion method to combine separately encoded images and context via add append or prepend'}
```

