# Agent Python Tools

- repo: facebookresearch/codegen
- repo_uri: https://github.com/facebookresearch/codegen

## File: facebookresearch_codegen/codegen_sources/dataloaders/transforms.py

Prompts

```
['create a CodeTokenizer to tokenize source code for a given programming language', 'build a FastBpe transform to apply byte pair encoding to tokenized code', 'create a BpeTensorizer to convert BPE subtokens into a PyTorch tensor', 'build a Composition to chain multiple transforms like tokenization and BPE together', 'create an Inverted transform to swap the apply and revert operations of any transform', 'create a Batch dataclass instance with x and y torch tensors for sequence data', 'collate a list of Batch instances into one padded Batch using Batch.collate_fn', 'optimize batch packing with BatchOptimizer to maximize tokens under a max_num_tokens limit', 'walk a directory of Python or json.gz files with CodeWalker to yield DelayedReader instances randomly', 'augment Python source code by reordering and removing top-level class and function definitions with PyAugmenter']
```

Usage

```
{'tokenize_code_with_CodeTokenizer': 'create a CodeTokenizer to tokenize source code for a given programming language', 'apply_BPE_with_FastBpe': 'build a FastBpe transform to apply byte pair encoding to tokenized code', 'convert_to_tensor_with_BpeTensorizer': 'create a BpeTensorizer to convert BPE subtokens into a PyTorch tensor', 'compose_transforms_with_Composition': 'build a Composition to chain multiple transforms like tokenization and BPE together', 'invert_transform_with_Inverted': 'create an Inverted transform to swap the apply and revert operations of any transform'}
```

## File: facebookresearch_codegen/codegen_sources/dataloaders/utils.py

Prompts

```
['create a CodeTokenizer to tokenize source code for a given programming language', 'build a FastBpe transform to apply byte pair encoding to tokenized code', 'create a BpeTensorizer to convert BPE subtokens into a PyTorch tensor', 'build a Composition to chain multiple transforms like tokenization and BPE together', 'create an Inverted transform to swap the apply and revert operations of any transform', 'create a Batch dataclass instance with x and y torch tensors for sequence data', 'collate a list of Batch instances into one padded Batch using Batch.collate_fn', 'optimize batch packing with BatchOptimizer to maximize tokens under a max_num_tokens limit', 'walk a directory of Python or json.gz files with CodeWalker to yield DelayedReader instances randomly', 'augment Python source code by reordering and removing top-level class and function definitions with PyAugmenter']
```

Usage

```
{'create_batch_tensors': 'create a Batch dataclass instance with x and y torch tensors for sequence data', 'collate_batches': 'collate a list of Batch instances into one padded Batch using Batch.collate_fn', 'optimize_batch_tokens': 'optimize batch packing with BatchOptimizer to maximize tokens under a max_num_tokens limit', 'walk_code_files': 'walk a directory of Python or json.gz files with CodeWalker to yield DelayedReader instances randomly', 'augment_python_code': 'augment Python source code by reordering and removing top-level class and function definitions with PyAugmenter'}
```

