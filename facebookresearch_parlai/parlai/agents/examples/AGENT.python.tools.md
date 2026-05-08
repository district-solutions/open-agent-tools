# Agent Python Tools

- repo: facebookresearch/parlai
- repo_uri: https://github.com/facebookresearch/parlai

## File: facebookresearch_parlai/parlai/agents/examples/seq2seq.py

Prompts

```
['train a Parlai seq2seq agent on convai2 with parlai train_model -m examples/seq2seq', 'build an Encoder module with an embedding layer and 1-layer LSTM for encoding input tokens', 'build a Decoder module with an embedding layer and 1-layer LSTM supporting incremental decoding', 'reorder encoder hidden and cell states by batch indices for beam search generation', 'reorder decoder incremental hidden and cell states by batch indices for efficient generation', 'build a bag of words ranking model using ExampleBagOfWordsModel with an embedding encoder', 'encode text vectors into embeddings using the ExampleBagOfWordsModel encode_text method', 'score candidate response vectors against context using the TraAgent score_candidates method', 'add command line arguments for the bag of words model including hidden-dim to a parser', 'review the TraAgent class which extends TorchRankerAgent with a bag of words ranking model', 'build a custom transformer encoder by subclassing TransformerEncoder and overriding the forward method', 'build a custom multi-head attention module by subclassing MultiHeadAttention and overriding the forward method', 'swap transformer encoder and decoder self-attention components using TransformerGeneratorModel.with_components', 'configure the decoder feedforward variant via the --decoder-ffn-variants command line argument', 'review the VerboseTransformerAgent to see how all transformer subcomponents are explicitly specified']
```

Usage

```
{'train_seq2seq_agent': 'train a Parlai seq2seq agent on convai2 with parlai train_model -m examples/seq2seq', 'build_encoder_lstm': 'build an Encoder module with an embedding layer and 1-layer LSTM for encoding input tokens', 'build_decoder_lstm': 'build a Decoder module with an embedding layer and 1-layer LSTM supporting incremental decoding', 'reorder_encoder_states': 'reorder encoder hidden and cell states by batch indices for beam search generation', 'reorder_decoder_incremental_state': 'reorder decoder incremental hidden and cell states by batch indices for efficient generation'}
```

## File: facebookresearch_parlai/parlai/agents/examples/tra.py

Prompts

```
['train a Parlai seq2seq agent on convai2 with parlai train_model -m examples/seq2seq', 'build an Encoder module with an embedding layer and 1-layer LSTM for encoding input tokens', 'build a Decoder module with an embedding layer and 1-layer LSTM supporting incremental decoding', 'reorder encoder hidden and cell states by batch indices for beam search generation', 'reorder decoder incremental hidden and cell states by batch indices for efficient generation', 'build a bag of words ranking model using ExampleBagOfWordsModel with an embedding encoder', 'encode text vectors into embeddings using the ExampleBagOfWordsModel encode_text method', 'score candidate response vectors against context using the TraAgent score_candidates method', 'add command line arguments for the bag of words model including hidden-dim to a parser', 'review the TraAgent class which extends TorchRankerAgent with a bag of words ranking model', 'build a custom transformer encoder by subclassing TransformerEncoder and overriding the forward method', 'build a custom multi-head attention module by subclassing MultiHeadAttention and overriding the forward method', 'swap transformer encoder and decoder self-attention components using TransformerGeneratorModel.with_components', 'configure the decoder feedforward variant via the --decoder-ffn-variants command line argument', 'review the VerboseTransformerAgent to see how all transformer subcomponents are explicitly specified']
```

Usage

```
{'build_bow_ranker_model': 'build a bag of words ranking model using ExampleBagOfWordsModel with an embedding encoder', 'encode_text_vectors': 'encode text vectors into embeddings using the ExampleBagOfWordsModel encode_text method', 'score_candidates': 'score candidate response vectors against context using the TraAgent score_candidates method', 'add_cmdline_args': 'add command line arguments for the bag of words model including hidden-dim to a parser', 'review_TraAgent': 'review the TraAgent class which extends TorchRankerAgent with a bag of words ranking model'}
```

## File: facebookresearch_parlai/parlai/agents/examples/transformer_variant.py

Prompts

```
['train a Parlai seq2seq agent on convai2 with parlai train_model -m examples/seq2seq', 'build an Encoder module with an embedding layer and 1-layer LSTM for encoding input tokens', 'build a Decoder module with an embedding layer and 1-layer LSTM supporting incremental decoding', 'reorder encoder hidden and cell states by batch indices for beam search generation', 'reorder decoder incremental hidden and cell states by batch indices for efficient generation', 'build a bag of words ranking model using ExampleBagOfWordsModel with an embedding encoder', 'encode text vectors into embeddings using the ExampleBagOfWordsModel encode_text method', 'score candidate response vectors against context using the TraAgent score_candidates method', 'add command line arguments for the bag of words model including hidden-dim to a parser', 'review the TraAgent class which extends TorchRankerAgent with a bag of words ranking model', 'build a custom transformer encoder by subclassing TransformerEncoder and overriding the forward method', 'build a custom multi-head attention module by subclassing MultiHeadAttention and overriding the forward method', 'swap transformer encoder and decoder self-attention components using TransformerGeneratorModel.with_components', 'configure the decoder feedforward variant via the --decoder-ffn-variants command line argument', 'review the VerboseTransformerAgent to see how all transformer subcomponents are explicitly specified']
```

Usage

```
{'build_custom_encoder': 'build a custom transformer encoder by subclassing TransformerEncoder and overriding the forward method', 'build_custom_attention': 'build a custom multi-head attention module by subclassing MultiHeadAttention and overriding the forward method', 'swap_transformer_components': 'swap transformer encoder and decoder self-attention components using TransformerGeneratorModel.with_components', 'configure_decoder_ffn_variant': 'configure the decoder feedforward variant via the --decoder-ffn-variants command line argument', 'review_verbose_transformer': 'review the VerboseTransformerAgent to see how all transformer subcomponents are explicitly specified'}
```

