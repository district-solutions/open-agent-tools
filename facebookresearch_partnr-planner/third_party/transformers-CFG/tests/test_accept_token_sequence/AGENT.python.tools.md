# Agent Python Tools

- repo: facebookresearch/partnr-planner
- repo_uri: https://github.com/facebookresearch/partnr-planner

## File: facebookresearch_partnr-planner/third_party/transformers-CFG/tests/test_accept_token_sequence/_test_accept_tokens_mixin.py

Prompts

```
['test that valid JSON strings are recognized as parsable by an IncrementalTokenRecognizer with a JSON EBNF grammar', 'test that deeply nested balanced parentheses are recognized correctly by an IncrementalTokenRecognizer with a balanced parentheses grammar', 'test that a hardcoded string literal grammar forces exact token sequences via IncrementalTokenRecognizer', 'test that emoji characters are accepted by an IncrementalTokenRecognizer using accept_token_ids with an emoji grammar', 'create a pretrained tokenizer instance from the tokenizer class using from_pretrained with use_fast option', 'run the GPT2TokenizerTest unit tests to validate GPT2 tokenizer accept token sequence behavior', 'run the setUp method of GPT2TokenizerTest to initialize the GPT2 tokenizer test fixture', 'test the GPT2TokenizerFast tokenizer class via the GPT2TokenizerTest test suite', 'test the pretrained gpt2 model name configuration in GPT2TokenizerTest', 'review the GPT2TokenizerTest class that extends TokenizerTesterMixin for GPT2 tokenizer testing', 'test LlamaTokenizerFast with saibo/llama-1B to parse valid JSON via EBNF grammar', 'test LlamaTokenizerFast with saibo/llama-1B to recognize balanced parentheses via EBNF grammar', 'test LlamaTokenizerFast with saibo/llama-1B to accept a forced token sequence via EBNF grammar', 'test LlamaTokenizerFast with saibo/llama-1B to accept emoji tokens via EBNF grammar', 'run all LlamaTokenizerTest unit tests using pytest or unittest against saibo/llama-1B', 'test the T5TokenizerTest class that validates T5 tokenizer functionality using TokenizerTesterMixin', 'test the TestT5TokenizerUnkToken class to verify unknown token handling in T5 tokenizer', 'test the test_unk_token method to verify curly braces map to unk_token_id', 'test loading a pretrained T5 tokenizer using T5TokenizerFast.from_pretrained with t5-small model', 'test encoding text to token IDs using the tokenizer.encode method for special characters']
```

Usage

```
{'test_json_parsable': 'test that valid JSON strings are recognized as parsable by an IncrementalTokenRecognizer with a JSON EBNF grammar', 'test_balanced_parentheses': 'test that deeply nested balanced parentheses are recognized correctly by an IncrementalTokenRecognizer with a balanced parentheses grammar', 'test_forcing_sequence': 'test that a hardcoded string literal grammar forces exact token sequences via IncrementalTokenRecognizer', 'test_emoji': 'test that emoji characters are accepted by an IncrementalTokenRecognizer using accept_token_ids with an emoji grammar', 'get_tokenizer': 'create a pretrained tokenizer instance from the tokenizer class using from_pretrained with use_fast option'}
```

## File: facebookresearch_partnr-planner/third_party/transformers-CFG/tests/test_accept_token_sequence/test_gpt2.py

Prompts

```
['test that valid JSON strings are recognized as parsable by an IncrementalTokenRecognizer with a JSON EBNF grammar', 'test that deeply nested balanced parentheses are recognized correctly by an IncrementalTokenRecognizer with a balanced parentheses grammar', 'test that a hardcoded string literal grammar forces exact token sequences via IncrementalTokenRecognizer', 'test that emoji characters are accepted by an IncrementalTokenRecognizer using accept_token_ids with an emoji grammar', 'create a pretrained tokenizer instance from the tokenizer class using from_pretrained with use_fast option', 'run the GPT2TokenizerTest unit tests to validate GPT2 tokenizer accept token sequence behavior', 'run the setUp method of GPT2TokenizerTest to initialize the GPT2 tokenizer test fixture', 'test the GPT2TokenizerFast tokenizer class via the GPT2TokenizerTest test suite', 'test the pretrained gpt2 model name configuration in GPT2TokenizerTest', 'review the GPT2TokenizerTest class that extends TokenizerTesterMixin for GPT2 tokenizer testing', 'test LlamaTokenizerFast with saibo/llama-1B to parse valid JSON via EBNF grammar', 'test LlamaTokenizerFast with saibo/llama-1B to recognize balanced parentheses via EBNF grammar', 'test LlamaTokenizerFast with saibo/llama-1B to accept a forced token sequence via EBNF grammar', 'test LlamaTokenizerFast with saibo/llama-1B to accept emoji tokens via EBNF grammar', 'run all LlamaTokenizerTest unit tests using pytest or unittest against saibo/llama-1B', 'test the T5TokenizerTest class that validates T5 tokenizer functionality using TokenizerTesterMixin', 'test the TestT5TokenizerUnkToken class to verify unknown token handling in T5 tokenizer', 'test the test_unk_token method to verify curly braces map to unk_token_id', 'test loading a pretrained T5 tokenizer using T5TokenizerFast.from_pretrained with t5-small model', 'test encoding text to token IDs using the tokenizer.encode method for special characters']
```

Usage

```
{'test_GPT2TokenizerTest': 'run the GPT2TokenizerTest unit tests to validate GPT2 tokenizer accept token sequence behavior', 'test_GPT2TokenizerTest_setUp': 'run the setUp method of GPT2TokenizerTest to initialize the GPT2 tokenizer test fixture', 'test_GPT2TokenizerTest_tokenizer_class': 'test the GPT2TokenizerFast tokenizer class via the GPT2TokenizerTest test suite', 'test_GPT2TokenizerTest_pretrained_name': 'test the pretrained gpt2 model name configuration in GPT2TokenizerTest', 'review_GPT2TokenizerTest': 'review the GPT2TokenizerTest class that extends TokenizerTesterMixin for GPT2 tokenizer testing'}
```

## File: facebookresearch_partnr-planner/third_party/transformers-CFG/tests/test_accept_token_sequence/test_llama.py

Prompts

```
['test that valid JSON strings are recognized as parsable by an IncrementalTokenRecognizer with a JSON EBNF grammar', 'test that deeply nested balanced parentheses are recognized correctly by an IncrementalTokenRecognizer with a balanced parentheses grammar', 'test that a hardcoded string literal grammar forces exact token sequences via IncrementalTokenRecognizer', 'test that emoji characters are accepted by an IncrementalTokenRecognizer using accept_token_ids with an emoji grammar', 'create a pretrained tokenizer instance from the tokenizer class using from_pretrained with use_fast option', 'run the GPT2TokenizerTest unit tests to validate GPT2 tokenizer accept token sequence behavior', 'run the setUp method of GPT2TokenizerTest to initialize the GPT2 tokenizer test fixture', 'test the GPT2TokenizerFast tokenizer class via the GPT2TokenizerTest test suite', 'test the pretrained gpt2 model name configuration in GPT2TokenizerTest', 'review the GPT2TokenizerTest class that extends TokenizerTesterMixin for GPT2 tokenizer testing', 'test LlamaTokenizerFast with saibo/llama-1B to parse valid JSON via EBNF grammar', 'test LlamaTokenizerFast with saibo/llama-1B to recognize balanced parentheses via EBNF grammar', 'test LlamaTokenizerFast with saibo/llama-1B to accept a forced token sequence via EBNF grammar', 'test LlamaTokenizerFast with saibo/llama-1B to accept emoji tokens via EBNF grammar', 'run all LlamaTokenizerTest unit tests using pytest or unittest against saibo/llama-1B', 'test the T5TokenizerTest class that validates T5 tokenizer functionality using TokenizerTesterMixin', 'test the TestT5TokenizerUnkToken class to verify unknown token handling in T5 tokenizer', 'test the test_unk_token method to verify curly braces map to unk_token_id', 'test loading a pretrained T5 tokenizer using T5TokenizerFast.from_pretrained with t5-small model', 'test encoding text to token IDs using the tokenizer.encode method for special characters']
```

Usage

```
{'test_llama_tokenizer_json_parsing': 'test LlamaTokenizerFast with saibo/llama-1B to parse valid JSON via EBNF grammar', 'test_llama_tokenizer_balanced_parens': 'test LlamaTokenizerFast with saibo/llama-1B to recognize balanced parentheses via EBNF grammar', 'test_llama_tokenizer_forced_sequence': 'test LlamaTokenizerFast with saibo/llama-1B to accept a forced token sequence via EBNF grammar', 'test_llama_tokenizer_emoji': 'test LlamaTokenizerFast with saibo/llama-1B to accept emoji tokens via EBNF grammar', 'run_llama_tokenizer_tests': 'run all LlamaTokenizerTest unit tests using pytest or unittest against saibo/llama-1B'}
```

## File: facebookresearch_partnr-planner/third_party/transformers-CFG/tests/test_accept_token_sequence/test_t5.py

Prompts

```
['test that valid JSON strings are recognized as parsable by an IncrementalTokenRecognizer with a JSON EBNF grammar', 'test that deeply nested balanced parentheses are recognized correctly by an IncrementalTokenRecognizer with a balanced parentheses grammar', 'test that a hardcoded string literal grammar forces exact token sequences via IncrementalTokenRecognizer', 'test that emoji characters are accepted by an IncrementalTokenRecognizer using accept_token_ids with an emoji grammar', 'create a pretrained tokenizer instance from the tokenizer class using from_pretrained with use_fast option', 'run the GPT2TokenizerTest unit tests to validate GPT2 tokenizer accept token sequence behavior', 'run the setUp method of GPT2TokenizerTest to initialize the GPT2 tokenizer test fixture', 'test the GPT2TokenizerFast tokenizer class via the GPT2TokenizerTest test suite', 'test the pretrained gpt2 model name configuration in GPT2TokenizerTest', 'review the GPT2TokenizerTest class that extends TokenizerTesterMixin for GPT2 tokenizer testing', 'test LlamaTokenizerFast with saibo/llama-1B to parse valid JSON via EBNF grammar', 'test LlamaTokenizerFast with saibo/llama-1B to recognize balanced parentheses via EBNF grammar', 'test LlamaTokenizerFast with saibo/llama-1B to accept a forced token sequence via EBNF grammar', 'test LlamaTokenizerFast with saibo/llama-1B to accept emoji tokens via EBNF grammar', 'run all LlamaTokenizerTest unit tests using pytest or unittest against saibo/llama-1B', 'test the T5TokenizerTest class that validates T5 tokenizer functionality using TokenizerTesterMixin', 'test the TestT5TokenizerUnkToken class to verify unknown token handling in T5 tokenizer', 'test the test_unk_token method to verify curly braces map to unk_token_id', 'test loading a pretrained T5 tokenizer using T5TokenizerFast.from_pretrained with t5-small model', 'test encoding text to token IDs using the tokenizer.encode method for special characters']
```

Usage

```
{'test_T5TokenizerTest': 'test the T5TokenizerTest class that validates T5 tokenizer functionality using TokenizerTesterMixin', 'test_TestT5TokenizerUnkToken': 'test the TestT5TokenizerUnkToken class to verify unknown token handling in T5 tokenizer', 'test_test_unk_token': 'test the test_unk_token method to verify curly braces map to unk_token_id', 'test_T5TokenizerFast_from_pretrained': 'test loading a pretrained T5 tokenizer using T5TokenizerFast.from_pretrained with t5-small model', 'test_tokenizer_encode': 'test encoding text to token IDs using the tokenizer.encode method for special characters'}
```

