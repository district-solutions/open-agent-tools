# Agent Python Tools

- repo: facebookresearch/partnr-planner
- repo_uri: https://github.com/facebookresearch/partnr-planner

## File: facebookresearch_partnr-planner/third_party/transformers-CFG/tests/test_hf_generation/test_generation.py

Prompts

```
['test grammar-constrained text generation using IncrementalTokenRecognizer and GrammarConstrainedLogitsProcessor with multiple HuggingFace models', 'test greedy decoding to generate only digit characters constrained by a regex grammar rule', 'test grammar-constrained generation of balanced parentheses using a recursive grammar rule', 'test grammar-constrained generation of a fixed constant string like the alphabet', 'test grammar-constrained generation of unicode emoji characters with the unicode flag enabled', 'test greedy decoding with grammar constraints to generate the emoji 🤣 using IncrementalTokenRecognizer', 'run IncrementalTokenRecognizer with unicode=True to constrain generation to a specific emoji string', 'test GrammarConstrainedLogitsProcessor with a grammar rule that forces output to match a unicode emoji', 'test AutoModelForCausalLM generate with a GrammarConstrainedLogitsProcessor to enforce grammar rules during decoding', 'test AutoTokenizer batch_decode to decode generated token ids back into unicode text strings']
```

Usage

```
{'test_greedy_decoding_with_grammar_constraints': 'test grammar-constrained text generation using IncrementalTokenRecognizer and GrammarConstrainedLogitsProcessor with multiple HuggingFace models', 'test_generate_only_number': 'test greedy decoding to generate only digit characters constrained by a regex grammar rule', 'test_generate_balanced_parenthesis': 'test grammar-constrained generation of balanced parentheses using a recursive grammar rule', 'test_generate_constant': 'test grammar-constrained generation of a fixed constant string like the alphabet', 'test_generate_emoji': 'test grammar-constrained generation of unicode emoji characters with the unicode flag enabled'}
```

## File: facebookresearch_partnr-planner/third_party/transformers-CFG/tests/test_hf_generation/test_unicode_generation.py

Prompts

```
['test grammar-constrained text generation using IncrementalTokenRecognizer and GrammarConstrainedLogitsProcessor with multiple HuggingFace models', 'test greedy decoding to generate only digit characters constrained by a regex grammar rule', 'test grammar-constrained generation of balanced parentheses using a recursive grammar rule', 'test grammar-constrained generation of a fixed constant string like the alphabet', 'test grammar-constrained generation of unicode emoji characters with the unicode flag enabled', 'test greedy decoding with grammar constraints to generate the emoji 🤣 using IncrementalTokenRecognizer', 'run IncrementalTokenRecognizer with unicode=True to constrain generation to a specific emoji string', 'test GrammarConstrainedLogitsProcessor with a grammar rule that forces output to match a unicode emoji', 'test AutoModelForCausalLM generate with a GrammarConstrainedLogitsProcessor to enforce grammar rules during decoding', 'test AutoTokenizer batch_decode to decode generated token ids back into unicode text strings']
```

Usage

```
{'test_emoji_generation_with_grammar_constraint': 'test greedy decoding with grammar constraints to generate the emoji 🤣 using IncrementalTokenRecognizer', 'run_IncrementalTokenRecognizer_with_unicode': 'run IncrementalTokenRecognizer with unicode=True to constrain generation to a specific emoji string', 'test_GrammarConstrainedLogitsProcessor': 'test GrammarConstrainedLogitsProcessor with a grammar rule that forces output to match a unicode emoji', 'test_AutoModelForCausalLM_generate_with_logits_processor': 'test AutoModelForCausalLM generate with a GrammarConstrainedLogitsProcessor to enforce grammar rules during decoding', 'test_AutoTokenizer_batch_decode': 'test AutoTokenizer batch_decode to decode generated token ids back into unicode text strings'}
```

