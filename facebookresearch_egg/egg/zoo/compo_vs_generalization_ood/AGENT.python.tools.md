# Agent Python Tools

- repo: facebookresearch/egg
- repo_uri: https://github.com/facebookresearch/egg

## File: facebookresearch_egg/egg/zoo/compo_vs_generalization_ood/archs.py

Prompts

```
['build a ModifSender encoder-decoder model for the communication game using given opts', 'build a ModifReceiver encoder-decoder model to decode messages back to attribute values', 'create an AttnMasked attention module that performs masked soft-retrieval of values from keys', 'create a BaseEncoder with dual embeddings and GRU for encoding input sequences', 'create a SenderDecoder with attention mechanism to generate message sequences from encoded inputs', 'run the OOD compositionality vs generalization training script with argparse CLI arguments', 'review the get_params function that parses CLI arguments for n_attributes, n_values, sender, and receiver options', 'review the get_data function that creates ordered pairs and splits them into train, uniform holdout, and generalization holdout sets', 'review the main function that sets up the SenderReceiverRnnReinforce game, DataLoaders, and Trainer with callbacks', 'refactor the main function to adjust the EarlyStopperAccuracy threshold for training convergence']
```

Usage

```
{'build_ModifSender': 'build a ModifSender encoder-decoder model for the communication game using given opts', 'build_ModifReceiver': 'build a ModifReceiver encoder-decoder model to decode messages back to attribute values', 'create_AttnMasked': 'create an AttnMasked attention module that performs masked soft-retrieval of values from keys', 'create_BaseEncoder': 'create a BaseEncoder with dual embeddings and GRU for encoding input sequences', 'create_SenderDecoder': 'create a SenderDecoder with attention mechanism to generate message sequences from encoded inputs'}
```

## File: facebookresearch_egg/egg/zoo/compo_vs_generalization_ood/train.py

Prompts

```
['build a ModifSender encoder-decoder model for the communication game using given opts', 'build a ModifReceiver encoder-decoder model to decode messages back to attribute values', 'create an AttnMasked attention module that performs masked soft-retrieval of values from keys', 'create a BaseEncoder with dual embeddings and GRU for encoding input sequences', 'create a SenderDecoder with attention mechanism to generate message sequences from encoded inputs', 'run the OOD compositionality vs generalization training script with argparse CLI arguments', 'review the get_params function that parses CLI arguments for n_attributes, n_values, sender, and receiver options', 'review the get_data function that creates ordered pairs and splits them into train, uniform holdout, and generalization holdout sets', 'review the main function that sets up the SenderReceiverRnnReinforce game, DataLoaders, and Trainer with callbacks', 'refactor the main function to adjust the EarlyStopperAccuracy threshold for training convergence']
```

Usage

```
{'run_train_compo_vs_generalization_ood': 'run the OOD compositionality vs generalization training script with argparse CLI arguments', 'review_get_params': 'review the get_params function that parses CLI arguments for n_attributes, n_values, sender, and receiver options', 'review_get_data': 'review the get_data function that creates ordered pairs and splits them into train, uniform holdout, and generalization holdout sets', 'review_main': 'review the main function that sets up the SenderReceiverRnnReinforce game, DataLoaders, and Trainer with callbacks', 'refactor_main_early_stopping': 'refactor the main function to adjust the EarlyStopperAccuracy threshold for training convergence'}
```

