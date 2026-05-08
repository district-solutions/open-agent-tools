# Agent Python Tools

- repo: facebookresearch/parlai
- repo_uri: https://github.com/facebookresearch/parlai

## File: facebookresearch_parlai/parlai/agents/seq2seq/modules.py

Prompts

```
['build a Seq2seq model with LSTM encoder-decoder, attention, and configurable dropout for sequence generation', 'create an RNNEncoder module with bidirectional LSTM, embedding lookup, and packed sequence support', 'create an RNNDecoder module with pre or post attention mechanisms for autoregressive decoding', 'create an AttentionLayer supporting local, concat, dot, or general attention between encoder and decoder states', 'create an OutputLayer with single or multi-softmax scoring and optional shared embedding weights', 'configure the Seq2seqAgent with concat, general, dot, or local attention mechanisms', 'train a Seq2seqAgent using TorchGeneratorAgent with greedy decoding or beam search', 'load a saved Seq2seqAgent model state dict from a file path using torch.load', 'validate an observation with text_vec to check for empty input sequences before training']
```

Usage

```
{'build_seq2seq_model': 'build a Seq2seq model with LSTM encoder-decoder, attention, and configurable dropout for sequence generation', 'create_rnn_encoder': 'create an RNNEncoder module with bidirectional LSTM, embedding lookup, and packed sequence support', 'create_rnn_decoder': 'create an RNNDecoder module with pre or post attention mechanisms for autoregressive decoding', 'create_attention_layer': 'create an AttentionLayer supporting local, concat, dot, or general attention between encoder and decoder states', 'create_output_layer': 'create an OutputLayer with single or multi-softmax scoring and optional shared embedding weights'}
```

## File: facebookresearch_parlai/parlai/agents/seq2seq/seq2seq.py

Prompts

```
['build a Seq2seq model with LSTM encoder-decoder, attention, and configurable dropout for sequence generation', 'create an RNNEncoder module with bidirectional LSTM, embedding lookup, and packed sequence support', 'create an RNNDecoder module with pre or post attention mechanisms for autoregressive decoding', 'create an AttentionLayer supporting local, concat, dot, or general attention between encoder and decoder states', 'create an OutputLayer with single or multi-softmax scoring and optional shared embedding weights', 'configure the Seq2seqAgent with concat, general, dot, or local attention mechanisms', 'train a Seq2seqAgent using TorchGeneratorAgent with greedy decoding or beam search', 'load a saved Seq2seqAgent model state dict from a file path using torch.load', 'validate an observation with text_vec to check for empty input sequences before training']
```

Usage

```
{'build_seq2seq_model': 'build a Seq2seqAgent model with configurable hidden size, embedding size, and number of layers', 'configure_seq2seq_attention': 'configure the Seq2seqAgent with concat, general, dot, or local attention mechanisms', 'train_seq2seq_agent': 'train a Seq2seqAgent using TorchGeneratorAgent with greedy decoding or beam search', 'load_seq2seq_model': 'load a saved Seq2seqAgent model state dict from a file path using torch.load', 'validate_seq2seq_observation': 'validate an observation with text_vec to check for empty input sequences before training'}
```

