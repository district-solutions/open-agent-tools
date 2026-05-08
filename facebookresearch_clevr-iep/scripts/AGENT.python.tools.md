# Agent Python Tools

- repo: facebookresearch/clevr-iep
- repo_uri: https://github.com/facebookresearch/clevr-iep

## File: facebookresearch_clevr-iep/scripts/extract_features.py

Prompts

```
['run the script to extract ResNet features from PNG images and save them to an HDF5 file', 'build a pretrained ResNet model with configurable stages for feature extraction on GPU', 'run a batch of images through normalization and the model to extract feature tensors', 'refactor build_model to support non-ResNet architectures like VGG or EfficientNet', 'summarize the main function that processes PNG images in batches and writes features to HDF5', 'run the CLEVR questions preprocessing script to encode questions and programs into an HDF5 file', 'build a vocabulary from CLEVR question JSON files using the preprocess script with --output_vocab_json', 'convert a CLEVR program list to its prefix string representation using program_to_str with mode prefix', 'convert a CLEVR program list to its postfix string representation using program_to_str with mode postfix', 'expand an existing vocabulary JSON with new words from questions using --expand_vocab with the preprocess script', 'run a baseline model on a preprocessed CLEVR dataset using h5 question and feature files', 'run a program generator and execution engine model on CLEVR visual reasoning questions', 'run inference on a single question and image pair to get a predicted answer', 'build a ResNet CNN model for extracting visual features from input images', 'run batch evaluation on a dataset and save prediction scores and probabilities to an h5 file', 'run the training script with --model_type PG to train a program generator on CLEVR-IEP data', 'run the training script with --model_type PG+EE to jointly train program generator and execution engine with reinforcement learning', 'run the training script with --model_type CNN+LSTM+SA to train a stacked attention baseline model', 'run the training script with --program_generator_start_from to resume training from an existing checkpoint file', 'run the training script with --checkpoint_every to periodically evaluate validation accuracy during training']
```

Usage

```
{'run_extract_features': 'run the script to extract ResNet features from PNG images and save them to an HDF5 file', 'build_model_resnet': 'build a pretrained ResNet model with configurable stages for feature extraction on GPU', 'run_batch_normalize': 'run a batch of images through normalization and the model to extract feature tensors', 'refactor_build_model': 'refactor build_model to support non-ResNet architectures like VGG or EfficientNet', 'summarize_main': 'summarize the main function that processes PNG images in batches and writes features to HDF5'}
```

## File: facebookresearch_clevr-iep/scripts/preprocess_questions.py

Prompts

```
['run the script to extract ResNet features from PNG images and save them to an HDF5 file', 'build a pretrained ResNet model with configurable stages for feature extraction on GPU', 'run a batch of images through normalization and the model to extract feature tensors', 'refactor build_model to support non-ResNet architectures like VGG or EfficientNet', 'summarize the main function that processes PNG images in batches and writes features to HDF5', 'run the CLEVR questions preprocessing script to encode questions and programs into an HDF5 file', 'build a vocabulary from CLEVR question JSON files using the preprocess script with --output_vocab_json', 'convert a CLEVR program list to its prefix string representation using program_to_str with mode prefix', 'convert a CLEVR program list to its postfix string representation using program_to_str with mode postfix', 'expand an existing vocabulary JSON with new words from questions using --expand_vocab with the preprocess script', 'run a baseline model on a preprocessed CLEVR dataset using h5 question and feature files', 'run a program generator and execution engine model on CLEVR visual reasoning questions', 'run inference on a single question and image pair to get a predicted answer', 'build a ResNet CNN model for extracting visual features from input images', 'run batch evaluation on a dataset and save prediction scores and probabilities to an h5 file', 'run the training script with --model_type PG to train a program generator on CLEVR-IEP data', 'run the training script with --model_type PG+EE to jointly train program generator and execution engine with reinforcement learning', 'run the training script with --model_type CNN+LSTM+SA to train a stacked attention baseline model', 'run the training script with --program_generator_start_from to resume training from an existing checkpoint file', 'run the training script with --checkpoint_every to periodically evaluate validation accuracy during training']
```

Usage

```
{'run_preprocess_questions': 'run the CLEVR questions preprocessing script to encode questions and programs into an HDF5 file', 'build_vocab_from_questions': 'build a vocabulary from CLEVR question JSON files using the preprocess script with --output_vocab_json', 'convert_program_to_prefix': 'convert a CLEVR program list to its prefix string representation using program_to_str with mode prefix', 'convert_program_to_postfix': 'convert a CLEVR program list to its postfix string representation using program_to_str with mode postfix', 'expand_existing_vocab': 'expand an existing vocabulary JSON with new words from questions using --expand_vocab with the preprocess script'}
```

## File: facebookresearch_clevr-iep/scripts/run_model.py

Prompts

```
['run the script to extract ResNet features from PNG images and save them to an HDF5 file', 'build a pretrained ResNet model with configurable stages for feature extraction on GPU', 'run a batch of images through normalization and the model to extract feature tensors', 'refactor build_model to support non-ResNet architectures like VGG or EfficientNet', 'summarize the main function that processes PNG images in batches and writes features to HDF5', 'run the CLEVR questions preprocessing script to encode questions and programs into an HDF5 file', 'build a vocabulary from CLEVR question JSON files using the preprocess script with --output_vocab_json', 'convert a CLEVR program list to its prefix string representation using program_to_str with mode prefix', 'convert a CLEVR program list to its postfix string representation using program_to_str with mode postfix', 'expand an existing vocabulary JSON with new words from questions using --expand_vocab with the preprocess script', 'run a baseline model on a preprocessed CLEVR dataset using h5 question and feature files', 'run a program generator and execution engine model on CLEVR visual reasoning questions', 'run inference on a single question and image pair to get a predicted answer', 'build a ResNet CNN model for extracting visual features from input images', 'run batch evaluation on a dataset and save prediction scores and probabilities to an h5 file', 'run the training script with --model_type PG to train a program generator on CLEVR-IEP data', 'run the training script with --model_type PG+EE to jointly train program generator and execution engine with reinforcement learning', 'run the training script with --model_type CNN+LSTM+SA to train a stacked attention baseline model', 'run the training script with --program_generator_start_from to resume training from an existing checkpoint file', 'run the training script with --checkpoint_every to periodically evaluate validation accuracy during training']
```

Usage

```
{'run_baseline_model_on_dataset': 'run a baseline model on a preprocessed CLEVR dataset using h5 question and feature files', 'run_program_generator_with_execution_engine': 'run a program generator and execution engine model on CLEVR visual reasoning questions', 'run_single_example_inference': 'run inference on a single question and image pair to get a predicted answer', 'build_cnn_feature_extractor': 'build a ResNet CNN model for extracting visual features from input images', 'run_batch_evaluation_with_output': 'run batch evaluation on a dataset and save prediction scores and probabilities to an h5 file'}
```

## File: facebookresearch_clevr-iep/scripts/train_model.py

Prompts

```
['run the script to extract ResNet features from PNG images and save them to an HDF5 file', 'build a pretrained ResNet model with configurable stages for feature extraction on GPU', 'run a batch of images through normalization and the model to extract feature tensors', 'refactor build_model to support non-ResNet architectures like VGG or EfficientNet', 'summarize the main function that processes PNG images in batches and writes features to HDF5', 'run the CLEVR questions preprocessing script to encode questions and programs into an HDF5 file', 'build a vocabulary from CLEVR question JSON files using the preprocess script with --output_vocab_json', 'convert a CLEVR program list to its prefix string representation using program_to_str with mode prefix', 'convert a CLEVR program list to its postfix string representation using program_to_str with mode postfix', 'expand an existing vocabulary JSON with new words from questions using --expand_vocab with the preprocess script', 'run a baseline model on a preprocessed CLEVR dataset using h5 question and feature files', 'run a program generator and execution engine model on CLEVR visual reasoning questions', 'run inference on a single question and image pair to get a predicted answer', 'build a ResNet CNN model for extracting visual features from input images', 'run batch evaluation on a dataset and save prediction scores and probabilities to an h5 file', 'run the training script with --model_type PG to train a program generator on CLEVR-IEP data', 'run the training script with --model_type PG+EE to jointly train program generator and execution engine with reinforcement learning', 'run the training script with --model_type CNN+LSTM+SA to train a stacked attention baseline model', 'run the training script with --program_generator_start_from to resume training from an existing checkpoint file', 'run the training script with --checkpoint_every to periodically evaluate validation accuracy during training']
```

Usage

```
{'run_train_model_pg': 'run the training script with --model_type PG to train a program generator on CLEVR-IEP data', 'run_train_model_pg_plus_ee': 'run the training script with --model_type PG+EE to jointly train program generator and execution engine with reinforcement learning', 'run_train_model_baseline': 'run the training script with --model_type CNN+LSTM+SA to train a stacked attention baseline model', 'run_train_model_from_checkpoint': 'run the training script with --program_generator_start_from to resume training from an existing checkpoint file', 'run_train_model_check_accuracy': 'run the training script with --checkpoint_every to periodically evaluate validation accuracy during training'}
```

