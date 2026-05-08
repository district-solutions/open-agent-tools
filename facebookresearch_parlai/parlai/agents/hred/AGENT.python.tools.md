# Agent Python Tools

- repo: facebookresearch/parlai
- repo_uri: https://github.com/facebookresearch/parlai

## File: facebookresearch_parlai/parlai/agents/hred/hred.py

Prompts

```
['build an HredAgent model with configurable hidden size, embedding size, and number of layers', 'add HRED-specific command-line arguments like hiddensize, embeddingsize, numlayers, dropout, and lookuptable to a ParlaiParser', 'batchify observations for HRED by padding context vectors and computing history lengths', 'set the text_vec field in an observation using conversation history and context vectors', 'copy pretrained embeddings into the HRED model decoder and encoder lookup tables', 'build a Hierarchical RNN encoder-decoder model with context LSTM for dialog response generation', 'create an RNN encoder that encodes utterance history using a context LSTM layer', 'create a recurrent decoder that uses dialog history encoded by the context LSTM', 'review the HredEncoder sequence_to_padding method that reshapes and pads sequences by length tensor', 'review the HredModel reorder_encoder_states method for reordering encoder states by indices']
```

Usage

```
{'build_hred_model': 'build an HredAgent model with configurable hidden size, embedding size, and number of layers', 'add_hred_cmdline_args': 'add HRED-specific command-line arguments like hiddensize, embeddingsize, numlayers, dropout, and lookuptable to a ParlaiParser', 'batchify_hred_observation': 'batchify observations for HRED by padding context vectors and computing history lengths', 'set_text_vec_hred': 'set the text_vec field in an observation using conversation history and context vectors', 'copy_embeddings_hred': 'copy pretrained embeddings into the HRED model decoder and encoder lookup tables'}
```

## File: facebookresearch_parlai/parlai/agents/hred/modules.py

Prompts

```
['build an HredAgent model with configurable hidden size, embedding size, and number of layers', 'add HRED-specific command-line arguments like hiddensize, embeddingsize, numlayers, dropout, and lookuptable to a ParlaiParser', 'batchify observations for HRED by padding context vectors and computing history lengths', 'set the text_vec field in an observation using conversation history and context vectors', 'copy pretrained embeddings into the HRED model decoder and encoder lookup tables', 'build a Hierarchical RNN encoder-decoder model with context LSTM for dialog response generation', 'create an RNN encoder that encodes utterance history using a context LSTM layer', 'create a recurrent decoder that uses dialog history encoded by the context LSTM', 'review the HredEncoder sequence_to_padding method that reshapes and pads sequences by length tensor', 'review the HredModel reorder_encoder_states method for reordering encoder states by indices']
```

Usage

```
{'build_HRED_model': 'build a Hierarchical RNN encoder-decoder model with context LSTM for dialog response generation', 'create_HredEncoder': 'create an RNN encoder that encodes utterance history using a context LSTM layer', 'create_HredDecoder': 'create a recurrent decoder that uses dialog history encoded by the context LSTM', 'review_HredEncoder_sequence_to_padding': 'review the HredEncoder sequence_to_padding method that reshapes and pads sequences by length tensor', 'review_HredModel_reorder_encoder_states': 'review the HredModel reorder_encoder_states method for reordering encoder states by indices'}
```

