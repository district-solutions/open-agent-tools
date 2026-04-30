# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/cpmant/modeling_cpmant.py

Prompts

```
['create a CPMAnt causal language model with a language modeling head for text generation', 'build a CPMAnt transformer model with embedding layers, encoder, and segment position embeddings', 'run multi-head self-attention with query, key, value projections and relative position bias', 'test the CPMAnt encoder that stacks transformer blocks with residual connections and output layer norm', 'summarize the CPMAnt segment-aware relative position embedding with segment and distance buckets', 'build a CPMAnt tokenizer from a vocabulary file with custom special tokens for document boundaries', 'create a wordpiece tokenizer that splits tokens into subword pieces using a vocab dictionary', 'test loading a vocabulary file into an ordered dictionary mapping tokens to integer indices', 'refactor the CpmAntTokenizer _tokenize method to segment text using rjieba and wordpiece tokenization', 'review the CpmAntTokenizer _decode method that filters pad, eos, and bos tokens before decoding to string']
```

Usage

```
{'create_CpmAntForCausalLM': 'create a CPMAnt causal language model with a language modeling head for text generation', 'build_CpmAntModel': 'build a CPMAnt transformer model with embedding layers, encoder, and segment position embeddings', 'run_CpmAntAttention': 'run multi-head self-attention with query, key, value projections and relative position bias', 'test_CpmAntEncoder': 'test the CPMAnt encoder that stacks transformer blocks with residual connections and output layer norm', 'summarize_CpmAntSegmentPositionEmbedding': 'summarize the CPMAnt segment-aware relative position embedding with segment and distance buckets'}
```

## File: huggingface_transformers/src/transformers/models/cpmant/tokenization_cpmant.py

Prompts

```
['create a CPMAnt causal language model with a language modeling head for text generation', 'build a CPMAnt transformer model with embedding layers, encoder, and segment position embeddings', 'run multi-head self-attention with query, key, value projections and relative position bias', 'test the CPMAnt encoder that stacks transformer blocks with residual connections and output layer norm', 'summarize the CPMAnt segment-aware relative position embedding with segment and distance buckets', 'build a CPMAnt tokenizer from a vocabulary file with custom special tokens for document boundaries', 'create a wordpiece tokenizer that splits tokens into subword pieces using a vocab dictionary', 'test loading a vocabulary file into an ordered dictionary mapping tokens to integer indices', 'refactor the CpmAntTokenizer _tokenize method to segment text using rjieba and wordpiece tokenization', 'review the CpmAntTokenizer _decode method that filters pad, eos, and bos tokens before decoding to string']
```

Usage

```
{'build_cpmant_tokenizer': 'build a CPMAnt tokenizer from a vocabulary file with custom special tokens for document boundaries', 'create_wordpiece_tokenizer': 'create a wordpiece tokenizer that splits tokens into subword pieces using a vocab dictionary', 'test_load_vocab': 'test loading a vocabulary file into an ordered dictionary mapping tokens to integer indices', 'refactor_cpmant_tokenize': 'refactor the CpmAntTokenizer _tokenize method to segment text using rjieba and wordpiece tokenization', 'review_cpmant_decode': 'review the CpmAntTokenizer _decode method that filters pad, eos, and bos tokens before decoding to string'}
```

