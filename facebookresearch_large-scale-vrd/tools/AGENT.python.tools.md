# Agent Python Tools

- repo: facebookresearch/large-scale-vrd
- repo_uri: https://github.com/facebookresearch/large-scale-vrd

## File: facebookresearch_large-scale-vrd/tools/test_net_rel.py

Prompts

```
['run the test_net_rel.py CLI tool to test a VRD network model with a config file', 'test the parse_args function to parse --cfg and opts command line arguments for network testing', 'test the test function that builds a model, runs inference, and evaluates triplet detection accuracy', 'review the model_builder_rel.create call that builds a test model with train=False and split=test', 'review the evaluator_rel.Evaluator eval_im_dets_triplet_topk method used to evaluate image detection triplets during testing', 'train a Detectron network for visual relationship detection using a config file and command line options', 'parse command line arguments for training including config file path and solver options', 'create training and validation models using model_builder_rel with specified model name and split', 'save model parameters to checkpoint files at regular intervals during training iterations', 'validate the trained model by running inference and calculating triplet top-k accuracy metrics']
```

Usage

```
{'run_test_net_rel': 'run the test_net_rel.py CLI tool to test a VRD network model with a config file', 'test_parse_args': 'test the parse_args function to parse --cfg and opts command line arguments for network testing', 'test_test_function': 'test the test function that builds a model, runs inference, and evaluates triplet detection accuracy', 'review_model_builder_rel_create': 'review the model_builder_rel.create call that builds a test model with train=False and split=test', 'review_evaluator_rel_eval_im_dets_triplet_topk': 'review the evaluator_rel.Evaluator eval_im_dets_triplet_topk method used to evaluate image detection triplets during testing'}
```

## File: facebookresearch_large-scale-vrd/tools/train_net_rel.py

Prompts

```
['run the test_net_rel.py CLI tool to test a VRD network model with a config file', 'test the parse_args function to parse --cfg and opts command line arguments for network testing', 'test the test function that builds a model, runs inference, and evaluates triplet detection accuracy', 'review the model_builder_rel.create call that builds a test model with train=False and split=test', 'review the evaluator_rel.Evaluator eval_im_dets_triplet_topk method used to evaluate image detection triplets during testing', 'train a Detectron network for visual relationship detection using a config file and command line options', 'parse command line arguments for training including config file path and solver options', 'create training and validation models using model_builder_rel with specified model name and split', 'save model parameters to checkpoint files at regular intervals during training iterations', 'validate the trained model by running inference and calculating triplet top-k accuracy metrics']
```

Usage

```
{'train_detectron_network': 'train a Detectron network for visual relationship detection using a config file and command line options', 'parse_training_args': 'parse command line arguments for training including config file path and solver options', 'create_train_val_models': 'create training and validation models using model_builder_rel with specified model name and split', 'save_model_checkpoints': 'save model parameters to checkpoint files at regular intervals during training iterations', 'validate_model_accuracy': 'validate the trained model by running inference and calculating triplet top-k accuracy metrics'}
```

