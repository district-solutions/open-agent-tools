# Agent Python Tools

- repo: facebookresearch/openlth
- repo_uri: https://github.com/facebookresearch/open_lth

## File: facebookresearch_openlth/lottery/test/test_desc.py

Prompts

```
['test that LotteryDesc hashname is stable across hyperparameter changes', 'create a LotteryDesc with dataset, model, training, and pruning hyperparameters', 'test LotteryDesc hashname changes when setting training momentum to 0.9', 'test LotteryDesc hashname changes when disabling data augmentation', 'test LotteryDesc hashname changes when freezing batchnorm or other layers', 'run a LotteryRunner with specified replicate, levels, and description hyperparameters', 'test the TestRunner class to verify level 0 lottery ticket training produces correct mask files', 'test the TestRunner class to verify multi-level pruning produces correct sparsity at each level', 'test the TestRunner class to verify pretraining weights transfer correctly to level 0 training', 'review the Mask class load method to understand how pruning masks are persisted and retrieved']
```

Usage

```
{'test_LotteryDesc_hashname': 'test that LotteryDesc hashname is stable across hyperparameter changes', 'create_LotteryDesc_with_hparams': 'create a LotteryDesc with dataset, model, training, and pruning hyperparameters', 'test_training_hparams_momentum': 'test LotteryDesc hashname changes when setting training momentum to 0.9', 'test_dataset_hparams_augmentation': 'test LotteryDesc hashname changes when disabling data augmentation', 'test_model_hparams_frozen_layers': 'test LotteryDesc hashname changes when freezing batchnorm or other layers'}
```

## File: facebookresearch_openlth/lottery/test/test_runner.py

Prompts

```
['test that LotteryDesc hashname is stable across hyperparameter changes', 'create a LotteryDesc with dataset, model, training, and pruning hyperparameters', 'test LotteryDesc hashname changes when setting training momentum to 0.9', 'test LotteryDesc hashname changes when disabling data augmentation', 'test LotteryDesc hashname changes when freezing batchnorm or other layers', 'run a LotteryRunner with specified replicate, levels, and description hyperparameters', 'test the TestRunner class to verify level 0 lottery ticket training produces correct mask files', 'test the TestRunner class to verify multi-level pruning produces correct sparsity at each level', 'test the TestRunner class to verify pretraining weights transfer correctly to level 0 training', 'review the Mask class load method to understand how pruning masks are persisted and retrieved']
```

Usage

```
{'run_LotteryRunner': 'run a LotteryRunner with specified replicate, levels, and description hyperparameters', 'test_TestRunner_level0': 'test the TestRunner class to verify level 0 lottery ticket training produces correct mask files', 'test_TestRunner_level3': 'test the TestRunner class to verify multi-level pruning produces correct sparsity at each level', 'test_TestRunner_pretrain': 'test the TestRunner class to verify pretraining weights transfer correctly to level 0 training', 'review_Mask_load': 'review the Mask class load method to understand how pruning masks are persisted and retrieved'}
```

