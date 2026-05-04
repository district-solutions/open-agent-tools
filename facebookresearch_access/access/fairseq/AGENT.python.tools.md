# Agent Python Tools

- repo: facebookresearch/access
- repo_uri: https://github.com/facebookresearch/access

## File: facebookresearch_access/access/fairseq/base.py

Prompts

```
['get a fairseq experiment directory path for a given SLURM job ID or local run', 'preprocess a dataset into fairseq format with complex to simple language translation pairs', 'train a fairseq translation model on preprocessed data with configurable architecture and hyperparameters', 'generate translations from a trained fairseq model checkpoint using beam search or sampling', 'run fairseq generation with multiple checkpoints and parse hypotheses from output files', 'run fairseq training and evaluation on a dataset with BLEU, SARI, and FKGL metrics', 'find the best preprocessor parametrization using nevergrad ScrHammersleySearch optimization on the turkcorpus validation set', 'get a preprocessed simplifier combining a fairseq model with configured preprocessors and generation kwargs', 'check that a training dataset has no lines in common with the turkcorpus validation or test sets', 'check and resolve diverse beam groups arguments by computing groups from the beam ratio']
```

Usage

```
{'get_fairseq_exp_dir': 'get a fairseq experiment directory path for a given SLURM job ID or local run', 'fairseq_preprocess': 'preprocess a dataset into fairseq format with complex to simple language translation pairs', 'fairseq_train': 'train a fairseq translation model on preprocessed data with configurable architecture and hyperparameters', 'fairseq_generate': 'generate translations from a trained fairseq model checkpoint using beam search or sampling', '_fairseq_generate': 'run fairseq generation with multiple checkpoints and parse hypotheses from output files'}
```

## File: facebookresearch_access/access/fairseq/main.py

Prompts

```
['get a fairseq experiment directory path for a given SLURM job ID or local run', 'preprocess a dataset into fairseq format with complex to simple language translation pairs', 'train a fairseq translation model on preprocessed data with configurable architecture and hyperparameters', 'generate translations from a trained fairseq model checkpoint using beam search or sampling', 'run fairseq generation with multiple checkpoints and parse hypotheses from output files', 'run fairseq training and evaluation on a dataset with BLEU, SARI, and FKGL metrics', 'find the best preprocessor parametrization using nevergrad ScrHammersleySearch optimization on the turkcorpus validation set', 'get a preprocessed simplifier combining a fairseq model with configured preprocessors and generation kwargs', 'check that a training dataset has no lines in common with the turkcorpus validation or test sets', 'check and resolve diverse beam groups arguments by computing groups from the beam ratio']
```

Usage

```
{'run_fairseq_train_and_evaluate': 'run fairseq training and evaluation on a dataset with BLEU, SARI, and FKGL metrics', 'find_best_parametrization': 'find the best preprocessor parametrization using nevergrad ScrHammersleySearch optimization on the turkcorpus validation set', 'get_simplifier': 'get a preprocessed simplifier combining a fairseq model with configured preprocessors and generation kwargs', 'check_dataset': 'check that a training dataset has no lines in common with the turkcorpus validation or test sets', 'check_and_resolve_args': 'check and resolve diverse beam groups arguments by computing groups from the beam ratio'}
```

