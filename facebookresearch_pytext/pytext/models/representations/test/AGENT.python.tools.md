# Agent Python Tools

- repo: facebookresearch/pytext
- repo_uri: https://github.com/facebookresearch/pytext

## File: facebookresearch_pytext/pytext/models/representations/test/augmented_lstm_test.py

Prompts

```
['test the AugmentedLSTM output shapes across all config combinations of layers, dropout, highway, and bidirectional', 'test that AugmentedLSTM gradients propagate correctly without NaN or Inf values during backprop', 'test that AugmentedLSTM dropout produces different outputs on repeated forward passes when dropout is enabled', 'test the AugmentedLSTM forward pass with and without pre-initialized hidden and cell states', 'run the full AugmentedLSTM test suite covering all 16 configuration permutations via unittest', 'test the OrderedNeuronLSTM output shapes for hidden and cell states across batch, layer, and dimension axes', 'test that OrderedNeuronLSTM gradients propagate correctly without NaN or Inf values during backpropagation', 'test that OrderedNeuronLSTM dropout produces different outputs on repeated forward passes when dropout is greater than zero', 'test that OrderedNeuronLSTM produces identical outputs on repeated forward passes when dropout is set to zero', 'test OrderedNeuronLSTM across multiple layer counts and dropout rates using the test_ordered_neuron_lstm test method', 'test the SentenceEncoder by building a small encoder and calling extract_features on token tensors', 'test the SentenceEncoder forward pass by calling the encoder directly on a token tensor', 'test the SentenceEncoder TorchScript compilation and verify scripted output matches the original encoder output', 'test the TransformerRepresentation by creating it from a Config object and running embedded tokens through it', 'build TransformerLayer instances with MultiheadSelfAttention and assemble them into a Transformer with a SentenceEncoder']
```

Usage

```
{'test_augmented_lstm_shapes': 'test the AugmentedLSTM output shapes across all config combinations of layers, dropout, highway, and bidirectional', 'test_augmented_lstm_gradients': 'test that AugmentedLSTM gradients propagate correctly without NaN or Inf values during backprop', 'test_augmented_lstm_dropout': 'test that AugmentedLSTM dropout produces different outputs on repeated forward passes when dropout is enabled', 'test_augmented_lstm_with_states': 'test the AugmentedLSTM forward pass with and without pre-initialized hidden and cell states', 'run_augmented_lstm_test_suite': 'run the full AugmentedLSTM test suite covering all 16 configuration permutations via unittest'}
```

## File: facebookresearch_pytext/pytext/models/representations/test/ordered_neuron_lstm_test.py

Prompts

```
['test the AugmentedLSTM output shapes across all config combinations of layers, dropout, highway, and bidirectional', 'test that AugmentedLSTM gradients propagate correctly without NaN or Inf values during backprop', 'test that AugmentedLSTM dropout produces different outputs on repeated forward passes when dropout is enabled', 'test the AugmentedLSTM forward pass with and without pre-initialized hidden and cell states', 'run the full AugmentedLSTM test suite covering all 16 configuration permutations via unittest', 'test the OrderedNeuronLSTM output shapes for hidden and cell states across batch, layer, and dimension axes', 'test that OrderedNeuronLSTM gradients propagate correctly without NaN or Inf values during backpropagation', 'test that OrderedNeuronLSTM dropout produces different outputs on repeated forward passes when dropout is greater than zero', 'test that OrderedNeuronLSTM produces identical outputs on repeated forward passes when dropout is set to zero', 'test OrderedNeuronLSTM across multiple layer counts and dropout rates using the test_ordered_neuron_lstm test method', 'test the SentenceEncoder by building a small encoder and calling extract_features on token tensors', 'test the SentenceEncoder forward pass by calling the encoder directly on a token tensor', 'test the SentenceEncoder TorchScript compilation and verify scripted output matches the original encoder output', 'test the TransformerRepresentation by creating it from a Config object and running embedded tokens through it', 'build TransformerLayer instances with MultiheadSelfAttention and assemble them into a Transformer with a SentenceEncoder']
```

Usage

```
{'test_ordered_neuron_lstm_shapes': 'test the OrderedNeuronLSTM output shapes for hidden and cell states across batch, layer, and dimension axes', 'test_ordered_neuron_lstm_gradients': 'test that OrderedNeuronLSTM gradients propagate correctly without NaN or Inf values during backpropagation', 'test_ordered_neuron_lstm_dropout': 'test that OrderedNeuronLSTM dropout produces different outputs on repeated forward passes when dropout is greater than zero', 'test_ordered_neuron_lstm_determinism': 'test that OrderedNeuronLSTM produces identical outputs on repeated forward passes when dropout is set to zero', 'test_ordered_neuron_lstm_configurations': 'test OrderedNeuronLSTM across multiple layer counts and dropout rates using the test_ordered_neuron_lstm test method'}
```

## File: facebookresearch_pytext/pytext/models/representations/test/transformer_test.py

Prompts

```
['test the AugmentedLSTM output shapes across all config combinations of layers, dropout, highway, and bidirectional', 'test that AugmentedLSTM gradients propagate correctly without NaN or Inf values during backprop', 'test that AugmentedLSTM dropout produces different outputs on repeated forward passes when dropout is enabled', 'test the AugmentedLSTM forward pass with and without pre-initialized hidden and cell states', 'run the full AugmentedLSTM test suite covering all 16 configuration permutations via unittest', 'test the OrderedNeuronLSTM output shapes for hidden and cell states across batch, layer, and dimension axes', 'test that OrderedNeuronLSTM gradients propagate correctly without NaN or Inf values during backpropagation', 'test that OrderedNeuronLSTM dropout produces different outputs on repeated forward passes when dropout is greater than zero', 'test that OrderedNeuronLSTM produces identical outputs on repeated forward passes when dropout is set to zero', 'test OrderedNeuronLSTM across multiple layer counts and dropout rates using the test_ordered_neuron_lstm test method', 'test the SentenceEncoder by building a small encoder and calling extract_features on token tensors', 'test the SentenceEncoder forward pass by calling the encoder directly on a token tensor', 'test the SentenceEncoder TorchScript compilation and verify scripted output matches the original encoder output', 'test the TransformerRepresentation by creating it from a Config object and running embedded tokens through it', 'build TransformerLayer instances with MultiheadSelfAttention and assemble them into a Transformer with a SentenceEncoder']
```

Usage

```
{'test_sentence_encoder_extract_features': 'test the SentenceEncoder by building a small encoder and calling extract_features on token tensors', 'test_sentence_encoder_forward_pass': 'test the SentenceEncoder forward pass by calling the encoder directly on a token tensor', 'test_sentence_encoder_torchscript': 'test the SentenceEncoder TorchScript compilation and verify scripted output matches the original encoder output', 'test_transformer_representation_from_config': 'test the TransformerRepresentation by creating it from a Config object and running embedded tokens through it', 'build_transformer_layers': 'build TransformerLayer instances with MultiheadSelfAttention and assemble them into a Transformer with a SentenceEncoder'}
```

