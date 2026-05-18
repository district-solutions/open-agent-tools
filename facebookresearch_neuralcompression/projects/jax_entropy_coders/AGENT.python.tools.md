# Agent Python Tools

- repo: facebookresearch/neuralcompression
- repo_uri: https://github.com/facebookresearch/neuralcompression

## File: facebookresearch_neuralcompression/projects/jax_entropy_coders/jax_arithmetic_coder.py

Prompts

```
['encode a batch of messages into compressed byte arrays using arithmetic coding with a custom CDF function', 'decode a list of compressed byte arrays back into messages using arithmetic coding with an inverse CDF function', 'enqueue a single symbol into the compressed integer array using arithmetic coding range narrowing', 'dequeue a single symbol from the compressed integer array using arithmetic coding range decoding', 'run the JAX encoding backend to compress a message array into a bit array with a given CDF function', 'test the arithmetic coder by encoding and decoding messages using a known source distribution CDF', 'test the arithmetic coder compression size against the predicted entropy of the empirical distribution', 'test the arithmetic coder with an adaptive CDF that updates frequency counts during encoding', 'test the craystack entropy coder by encoding and decoding messages with fixed or skewed CDF distributions', 'test the bits-back ANS codec by encoding and decoding messages using latent prior and posterior CDFs']
```

Usage

```
{'encode_batch_of_messages': 'encode a batch of messages into compressed byte arrays using arithmetic coding with a custom CDF function', 'decode_batch_of_messages': 'decode a list of compressed byte arrays back into messages using arithmetic coding with an inverse CDF function', 'enqueue_single_symbol': 'enqueue a single symbol into the compressed integer array using arithmetic coding range narrowing', 'dequeue_single_symbol': 'dequeue a single symbol from the compressed integer array using arithmetic coding range decoding', 'jax_encode_backend': 'run the JAX encoding backend to compress a message array into a bit array with a given CDF function'}
```

## File: facebookresearch_neuralcompression/projects/jax_entropy_coders/test_entropy_coders.py

Prompts

```
['encode a batch of messages into compressed byte arrays using arithmetic coding with a custom CDF function', 'decode a list of compressed byte arrays back into messages using arithmetic coding with an inverse CDF function', 'enqueue a single symbol into the compressed integer array using arithmetic coding range narrowing', 'dequeue a single symbol from the compressed integer array using arithmetic coding range decoding', 'run the JAX encoding backend to compress a message array into a bit array with a given CDF function', 'test the arithmetic coder by encoding and decoding messages using a known source distribution CDF', 'test the arithmetic coder compression size against the predicted entropy of the empirical distribution', 'test the arithmetic coder with an adaptive CDF that updates frequency counts during encoding', 'test the craystack entropy coder by encoding and decoding messages with fixed or skewed CDF distributions', 'test the bits-back ANS codec by encoding and decoding messages using latent prior and posterior CDFs']
```

Usage

```
{'test_arithmetic_coder_identity': 'test the arithmetic coder by encoding and decoding messages using a known source distribution CDF', 'test_arithmetic_coder_entropy': 'test the arithmetic coder compression size against the predicted entropy of the empirical distribution', 'test_arithmetic_coder_adaptive': 'test the arithmetic coder with an adaptive CDF that updates frequency counts during encoding', 'test_craystack_coder_identity': 'test the craystack entropy coder by encoding and decoding messages with fixed or skewed CDF distributions', 'test_bitsback_ans_codec_identity': 'test the bits-back ANS codec by encoding and decoding messages using latent prior and posterior CDFs'}
```

