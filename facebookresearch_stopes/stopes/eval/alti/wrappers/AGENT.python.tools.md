# Agent Python Tools

- repo: facebookresearch/stopes
- repo_uri: https://github.com/facebookresearch/stopes

## File: facebookresearch_stopes/stopes/eval/alti/wrappers/multilingual_transformer_wrapper.py

Prompts

```
['load a pretrained FairseqMultilingualTransformerHub model from a checkpoint directory with source and target language pairs', 'change the source and target languages on a loaded multilingual transformer model for interactive translation', 'generate beam search translations from tokenized source sentences using the multilingual transformer model', 'trace a forward pass through the model capturing layer inputs and outputs via forward hooks', 'retrieve a source-target sample from a dataset split by index with decoded tokens and tensors', 'build a FairseqTransformerHub instance from a pretrained Fairseq checkpoint directory and model file', 'run a forward pass through the transformer model capturing all layer inputs and outputs via hooks', 'compute layer-wise token attribution contributions for encoder self-attention, decoder self-attention, and cross-attention modules', 'compute the full attention rollout across encoder and decoder layers to get token-to-token attributions', 'normalize layer-wise contribution tensors using min_max, softmax, sum_one, or min_sum normalization modes', 'compute the Spearman rank correlation coefficient between two attribution vectors', 'compute normalized ranks scaled to 0-1 range for an attribution vector', 'set matplotlib rcParams for consistent figure styling with custom font sizes', 'plot a heatmap visualization of ALTI contributions with source contribution bar chart', 'visualize ALTI rollout contributions across layers with optional word-level alignment']
```

Usage

```
{'load_multilingual_transformer': 'load a pretrained FairseqMultilingualTransformerHub model from a checkpoint directory with source and target language pairs', 'change_translation_languages': 'change the source and target languages on a loaded multilingual transformer model for interactive translation', 'generate_translations': 'generate beam search translations from tokenized source sentences using the multilingual transformer model', 'trace_forward_pass': 'trace a forward pass through the model capturing layer inputs and outputs via forward hooks', 'retrieve_dataset_sample': 'retrieve a source-target sample from a dataset split by index with decoded tokens and tensors'}
```

## File: facebookresearch_stopes/stopes/eval/alti/wrappers/transformer_wrapper.py

Prompts

```
['load a pretrained FairseqMultilingualTransformerHub model from a checkpoint directory with source and target language pairs', 'change the source and target languages on a loaded multilingual transformer model for interactive translation', 'generate beam search translations from tokenized source sentences using the multilingual transformer model', 'trace a forward pass through the model capturing layer inputs and outputs via forward hooks', 'retrieve a source-target sample from a dataset split by index with decoded tokens and tensors', 'build a FairseqTransformerHub instance from a pretrained Fairseq checkpoint directory and model file', 'run a forward pass through the transformer model capturing all layer inputs and outputs via hooks', 'compute layer-wise token attribution contributions for encoder self-attention, decoder self-attention, and cross-attention modules', 'compute the full attention rollout across encoder and decoder layers to get token-to-token attributions', 'normalize layer-wise contribution tensors using min_max, softmax, sum_one, or min_sum normalization modes', 'compute the Spearman rank correlation coefficient between two attribution vectors', 'compute normalized ranks scaled to 0-1 range for an attribution vector', 'set matplotlib rcParams for consistent figure styling with custom font sizes', 'plot a heatmap visualization of ALTI contributions with source contribution bar chart', 'visualize ALTI rollout contributions across layers with optional word-level alignment']
```

Usage

```
{'build_FairseqTransformerHub_from_pretrained': 'build a FairseqTransformerHub instance from a pretrained Fairseq checkpoint directory and model file', 'run_trace_forward': 'run a forward pass through the transformer model capturing all layer inputs and outputs via hooks', 'compute_get_contributions': 'compute layer-wise token attribution contributions for encoder self-attention, decoder self-attention, and cross-attention modules', 'compute_get_contribution_rollout': 'compute the full attention rollout across encoder and decoder layers to get token-to-token attributions', 'normalize_normalize_contrib': 'normalize layer-wise contribution tensors using min_max, softmax, sum_one, or min_sum normalization modes'}
```

## File: facebookresearch_stopes/stopes/eval/alti/wrappers/utils.py

Prompts

```
['load a pretrained FairseqMultilingualTransformerHub model from a checkpoint directory with source and target language pairs', 'change the source and target languages on a loaded multilingual transformer model for interactive translation', 'generate beam search translations from tokenized source sentences using the multilingual transformer model', 'trace a forward pass through the model capturing layer inputs and outputs via forward hooks', 'retrieve a source-target sample from a dataset split by index with decoded tokens and tensors', 'build a FairseqTransformerHub instance from a pretrained Fairseq checkpoint directory and model file', 'run a forward pass through the transformer model capturing all layer inputs and outputs via hooks', 'compute layer-wise token attribution contributions for encoder self-attention, decoder self-attention, and cross-attention modules', 'compute the full attention rollout across encoder and decoder layers to get token-to-token attributions', 'normalize layer-wise contribution tensors using min_max, softmax, sum_one, or min_sum normalization modes', 'compute the Spearman rank correlation coefficient between two attribution vectors', 'compute normalized ranks scaled to 0-1 range for an attribution vector', 'set matplotlib rcParams for consistent figure styling with custom font sizes', 'plot a heatmap visualization of ALTI contributions with source contribution bar chart', 'visualize ALTI rollout contributions across layers with optional word-level alignment']
```

Usage

```
{'compute_spearman_correlation': 'compute the Spearman rank correlation coefficient between two attribution vectors', 'compute_normalized_rank': 'compute normalized ranks scaled to 0-1 range for an attribution vector', 'set_matplotlib_style': 'set matplotlib rcParams for consistent figure styling with custom font sizes', 'plot_heatmap_alti': 'plot a heatmap visualization of ALTI contributions with source contribution bar chart', 'visualize_alti': 'visualize ALTI rollout contributions across layers with optional word-level alignment'}
```

