# Agent Python Tools

- repo: facebookresearch/neuralcompression
- repo_uri: https://github.com/facebookresearch/neuralcompression

## File: facebookresearch_neuralcompression/projects/jax_entropy_coders/craystack/_backend.py

Prompts

```
['create an empty CrayCompressedMessage with a given shape and tail capacity for entropy coding', 'push symbol information onto a CrayCompressedMessage stack using CDF low and high values', 'pop symbol information from a CrayCompressedMessage stack using CDF values and precision', 'flatten a CrayCompressedMessage into a single byte array for storage or transmission', 'embed a list of compressed messages into equal-size arrays with zero-padded tails', 'build a Craystack codec from a CDF array for rANS entropy coding with configurable precision', 'build a default rANS codec from custom CDF and inverse CDF callable functions', 'build a BB-ANS codec for lossless compression with latent variables using bits back coding', 'review the CrayCodec NamedTuple class that defines push and pop operations for rANS coding', 'summarize the fixed_array_cdf_codec function that creates a codec from an N+1 length CDF array', 'build a python module to encode batched messages into compressed bytes using the rANS entropy coder with a CrayCodec', 'build a python module to decode compressed bytes back into batched messages using the rANS entropy coder with a CrayCodec', 'build a python module to append encoded messages to existing compressed buffers using the encode function with start_buffers', 'review the encode function to understand how it handles batched interleaved rANS encoding with tail capacity management', 'review the decode function to understand how it reconstructs messages from compressed bytes and returns remaining buffer data']
```

Usage

```
{'create_empty_craystack_message': 'create an empty CrayCompressedMessage with a given shape and tail capacity for entropy coding', 'push_symbols_to_craystack': 'push symbol information onto a CrayCompressedMessage stack using CDF low and high values', 'pop_symbols_from_craystack': 'pop symbol information from a CrayCompressedMessage stack using CDF values and precision', 'flatten_craymessage_to_array': 'flatten a CrayCompressedMessage into a single byte array for storage or transmission', 'convert_messages_to_embedded': 'embed a list of compressed messages into equal-size arrays with zero-padded tails'}
```

## File: facebookresearch_neuralcompression/projects/jax_entropy_coders/craystack/codecs.py

Prompts

```
['create an empty CrayCompressedMessage with a given shape and tail capacity for entropy coding', 'push symbol information onto a CrayCompressedMessage stack using CDF low and high values', 'pop symbol information from a CrayCompressedMessage stack using CDF values and precision', 'flatten a CrayCompressedMessage into a single byte array for storage or transmission', 'embed a list of compressed messages into equal-size arrays with zero-padded tails', 'build a Craystack codec from a CDF array for rANS entropy coding with configurable precision', 'build a default rANS codec from custom CDF and inverse CDF callable functions', 'build a BB-ANS codec for lossless compression with latent variables using bits back coding', 'review the CrayCodec NamedTuple class that defines push and pop operations for rANS coding', 'summarize the fixed_array_cdf_codec function that creates a codec from an N+1 length CDF array', 'build a python module to encode batched messages into compressed bytes using the rANS entropy coder with a CrayCodec', 'build a python module to decode compressed bytes back into batched messages using the rANS entropy coder with a CrayCodec', 'build a python module to append encoded messages to existing compressed buffers using the encode function with start_buffers', 'review the encode function to understand how it handles batched interleaved rANS encoding with tail capacity management', 'review the decode function to understand how it reconstructs messages from compressed bytes and returns remaining buffer data']
```

Usage

```
{'build_fixed_array_cdf_codec': 'build a Craystack codec from a CDF array for rANS entropy coding with configurable precision', 'build_default_rans_codec': 'build a default rANS codec from custom CDF and inverse CDF callable functions', 'build_bitsback_ans_codec': 'build a BB-ANS codec for lossless compression with latent variables using bits back coding', 'review_CrayCodec': 'review the CrayCodec NamedTuple class that defines push and pop operations for rANS coding', 'summarize_fixed_array_cdf_codec': 'summarize the fixed_array_cdf_codec function that creates a codec from an N+1 length CDF array'}
```

## File: facebookresearch_neuralcompression/projects/jax_entropy_coders/craystack/coder.py

Prompts

```
['create an empty CrayCompressedMessage with a given shape and tail capacity for entropy coding', 'push symbol information onto a CrayCompressedMessage stack using CDF low and high values', 'pop symbol information from a CrayCompressedMessage stack using CDF values and precision', 'flatten a CrayCompressedMessage into a single byte array for storage or transmission', 'embed a list of compressed messages into equal-size arrays with zero-padded tails', 'build a Craystack codec from a CDF array for rANS entropy coding with configurable precision', 'build a default rANS codec from custom CDF and inverse CDF callable functions', 'build a BB-ANS codec for lossless compression with latent variables using bits back coding', 'review the CrayCodec NamedTuple class that defines push and pop operations for rANS coding', 'summarize the fixed_array_cdf_codec function that creates a codec from an N+1 length CDF array', 'build a python module to encode batched messages into compressed bytes using the rANS entropy coder with a CrayCodec', 'build a python module to decode compressed bytes back into batched messages using the rANS entropy coder with a CrayCodec', 'build a python module to append encoded messages to existing compressed buffers using the encode function with start_buffers', 'review the encode function to understand how it handles batched interleaved rANS encoding with tail capacity management', 'review the decode function to understand how it reconstructs messages from compressed bytes and returns remaining buffer data']
```

Usage

```
{'encode_rANS_messages': 'build a python module to encode batched messages into compressed bytes using the rANS entropy coder with a CrayCodec', 'decode_rANS_messages': 'build a python module to decode compressed bytes back into batched messages using the rANS entropy coder with a CrayCodec', 'encode_with_existing_buffers': 'build a python module to append encoded messages to existing compressed buffers using the encode function with start_buffers', 'review_encode_function': 'review the encode function to understand how it handles batched interleaved rANS encoding with tail capacity management', 'review_decode_function': 'review the decode function to understand how it reconstructs messages from compressed bytes and returns remaining buffer data'}
```

