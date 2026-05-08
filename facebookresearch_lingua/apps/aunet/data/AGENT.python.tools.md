# Agent Python Tools

- repo: facebookresearch/lingua
- repo_uri: https://github.com/facebookresearch/lingua

## File: facebookresearch_lingua/apps/aunet/data/data.py

Prompts

```
['build a dataloader from DataArgs config to load and tokenize JSONL dataset chunks asynchronously', 'initialize a prefetch state from DataArgs for resuming the dataloader at a specific rank', 'build a nested iterator dataloader that reads, tokenizes, packs, and shuffles JSONL data batches', 'pack token sequences into fixed-length chunks with sliding window views for model training', 'create an async producer-consumer iterator that prefetches data batches in a separate process', 'create a RegexPool instance with word, pretok, or punct tokenization strategies for regex-based text cutting', 'compute character-level split offsets from text using compiled regex patterns in a RegexPool', 'generate a levels mask for prefill byte sequences using RegexPool get_levels_mask_prefill', 'generate incremental levels masks for generation step bytes using RegexPool get_levels_mask_gen', 'map each character in text to its cumulative UTF-8 byte offset using map_codepoint_to_byte']
```

Usage

```
{'build_dataloader_from_args': 'build a dataloader from DataArgs config to load and tokenize JSONL dataset chunks asynchronously', 'init_dataloader_state_from_args': 'initialize a prefetch state from DataArgs for resuming the dataloader at a specific rank', 'build_dataloader': 'build a nested iterator dataloader that reads, tokenizes, packs, and shuffles JSONL data batches', 'pack_tokens': 'pack token sequences into fixed-length chunks with sliding window views for model training', 'async_iterator': 'create an async producer-consumer iterator that prefetches data batches in a separate process'}
```

## File: facebookresearch_lingua/apps/aunet/data/regex_cutting.py

Prompts

```
['build a dataloader from DataArgs config to load and tokenize JSONL dataset chunks asynchronously', 'initialize a prefetch state from DataArgs for resuming the dataloader at a specific rank', 'build a nested iterator dataloader that reads, tokenizes, packs, and shuffles JSONL data batches', 'pack token sequences into fixed-length chunks with sliding window views for model training', 'create an async producer-consumer iterator that prefetches data batches in a separate process', 'create a RegexPool instance with word, pretok, or punct tokenization strategies for regex-based text cutting', 'compute character-level split offsets from text using compiled regex patterns in a RegexPool', 'generate a levels mask for prefill byte sequences using RegexPool get_levels_mask_prefill', 'generate incremental levels masks for generation step bytes using RegexPool get_levels_mask_gen', 'map each character in text to its cumulative UTF-8 byte offset using map_codepoint_to_byte']
```

Usage

```
{'create_regexpool_with_strategy': 'create a RegexPool instance with word, pretok, or punct tokenization strategies for regex-based text cutting', 'compute_str_offsets': 'compute character-level split offsets from text using compiled regex patterns in a RegexPool', 'generate_levels_mask_prefill': 'generate a levels mask for prefill byte sequences using RegexPool get_levels_mask_prefill', 'generate_levels_mask_gen': 'generate incremental levels masks for generation step bytes using RegexPool get_levels_mask_gen', 'map_codepoints_to_byte_offsets': 'map each character in text to its cumulative UTF-8 byte offset using map_codepoint_to_byte'}
```

