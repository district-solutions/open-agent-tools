# Agent Python Tools

- repo: huggingface/text-generation-inference
- repo_uri: https://github.com/huggingface/text-generation-inference.git

## File: huggingface_text-generation-inference/clients/python/tests/test_client.py

Prompts

```
['test the Client.generate method to generate text with max_new_tokens and decoder_input_details', 'test the Client.generate_stream method to stream generated text responses from the server', 'test the AsyncClient.generate method to asynchronously generate text with best_of sampling', 'test the AsyncClient.generate_stream method to asynchronously stream generated text responses', 'test NotFoundError and ValidationError exceptions when the server is unreachable or parameters are invalid', 'test parse_error returns GenerationError for a 400 status code with error_type generation', 'test parse_error returns IncompleteGenerationError for a 400 status code with error_type incomplete_generation', 'test parse_error returns OverloadedError for a 400 status code with error_type overloaded', 'test parse_error returns ValidationError for a 400 status code with error_type validation', 'test parse_error returns ShardNotReadyError, ShardTimeoutError, NotFoundError, RateLimitExceededError, or UnknownError based on status code', 'test the Parameters class validation for best_of, temperature, top_k, top_p, and other fields', 'test the Request class validation for inputs, stream, and parameters combinations', 'validate that Parameters best_of requires do_sample and rejects zero or negative values', 'validate that Parameters temperature rejects zero and negative values', 'validate that Request rejects combining stream with best_of parameters']
```

Usage

```
{'test_Client_generate': 'test the Client.generate method to generate text with max_new_tokens and decoder_input_details', 'test_Client_generate_stream': 'test the Client.generate_stream method to stream generated text responses from the server', 'test_AsyncClient_generate': 'test the AsyncClient.generate method to asynchronously generate text with best_of sampling', 'test_AsyncClient_generate_stream': 'test the AsyncClient.generate_stream method to asynchronously stream generated text responses', 'test_error_handling': 'test NotFoundError and ValidationError exceptions when the server is unreachable or parameters are invalid'}
```

## File: huggingface_text-generation-inference/clients/python/tests/test_errors.py

Prompts

```
['test the Client.generate method to generate text with max_new_tokens and decoder_input_details', 'test the Client.generate_stream method to stream generated text responses from the server', 'test the AsyncClient.generate method to asynchronously generate text with best_of sampling', 'test the AsyncClient.generate_stream method to asynchronously stream generated text responses', 'test NotFoundError and ValidationError exceptions when the server is unreachable or parameters are invalid', 'test parse_error returns GenerationError for a 400 status code with error_type generation', 'test parse_error returns IncompleteGenerationError for a 400 status code with error_type incomplete_generation', 'test parse_error returns OverloadedError for a 400 status code with error_type overloaded', 'test parse_error returns ValidationError for a 400 status code with error_type validation', 'test parse_error returns ShardNotReadyError, ShardTimeoutError, NotFoundError, RateLimitExceededError, or UnknownError based on status code', 'test the Parameters class validation for best_of, temperature, top_k, top_p, and other fields', 'test the Request class validation for inputs, stream, and parameters combinations', 'validate that Parameters best_of requires do_sample and rejects zero or negative values', 'validate that Parameters temperature rejects zero and negative values', 'validate that Request rejects combining stream with best_of parameters']
```

Usage

```
{'test_parse_error_generation': 'test parse_error returns GenerationError for a 400 status code with error_type generation', 'test_parse_error_incomplete_generation': 'test parse_error returns IncompleteGenerationError for a 400 status code with error_type incomplete_generation', 'test_parse_error_overloaded': 'test parse_error returns OverloadedError for a 400 status code with error_type overloaded', 'test_parse_error_validation': 'test parse_error returns ValidationError for a 400 status code with error_type validation', 'test_parse_error_status_mapping': 'test parse_error returns ShardNotReadyError, ShardTimeoutError, NotFoundError, RateLimitExceededError, or UnknownError based on status code'}
```

## File: huggingface_text-generation-inference/clients/python/tests/test_types.py

Prompts

```
['test the Client.generate method to generate text with max_new_tokens and decoder_input_details', 'test the Client.generate_stream method to stream generated text responses from the server', 'test the AsyncClient.generate method to asynchronously generate text with best_of sampling', 'test the AsyncClient.generate_stream method to asynchronously stream generated text responses', 'test NotFoundError and ValidationError exceptions when the server is unreachable or parameters are invalid', 'test parse_error returns GenerationError for a 400 status code with error_type generation', 'test parse_error returns IncompleteGenerationError for a 400 status code with error_type incomplete_generation', 'test parse_error returns OverloadedError for a 400 status code with error_type overloaded', 'test parse_error returns ValidationError for a 400 status code with error_type validation', 'test parse_error returns ShardNotReadyError, ShardTimeoutError, NotFoundError, RateLimitExceededError, or UnknownError based on status code', 'test the Parameters class validation for best_of, temperature, top_k, top_p, and other fields', 'test the Request class validation for inputs, stream, and parameters combinations', 'validate that Parameters best_of requires do_sample and rejects zero or negative values', 'validate that Parameters temperature rejects zero and negative values', 'validate that Request rejects combining stream with best_of parameters']
```

Usage

```
{'test_parameters_validation': 'test the Parameters class validation for best_of, temperature, top_k, top_p, and other fields', 'test_request_validation': 'test the Request class validation for inputs, stream, and parameters combinations', 'validate_parameters_best_of': 'validate that Parameters best_of requires do_sample and rejects zero or negative values', 'validate_parameters_temperature': 'validate that Parameters temperature rejects zero and negative values', 'validate_request_stream_parameters': 'validate that Request rejects combining stream with best_of parameters'}
```

