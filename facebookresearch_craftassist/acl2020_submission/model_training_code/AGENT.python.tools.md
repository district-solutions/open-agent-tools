# Agent Python Tools

- repo: facebookresearch/craftassist
- repo_uri: https://github.com/facebookresearch/craftassist

## File: facebookresearch_craftassist/acl2020_submission/model_training_code/query_model.py

Prompts

```
['initialize a TTADBertModel from a saved model directory and data directory for dialogue parsing', 'parse a dialogue chat history using TTADBertModel.parse to extract structured intent trees', 'load a pretrained BERT encoder and decoder model with custom vocabulary from saved checkpoint files', 'run beam search over dialogue turns to find the best structured parse tree with NOOP filtering', 'configure a BERT decoder with custom hidden layers and vocabulary size for tree generation', 'run the CAIP encoder-decoder model training loop with configurable epochs, batch size, and learning rate', 'run validation on a trained CAIP model across templated, rephrased, prompt, and humanbot datasets', 'run the main CLI to train and evaluate a CAIP parser model with argparse configuration', 'review the train function that performs gradient clipping, backpropagation, and hard example mining', 'review the validate function that computes loss and accuracy metrics without backpropagation', 'build a grammar and vocabulary from a list of weighted tree datasets using make_full_tree', 'linearize a nested dict tree into a flat sequence of tokens and spans using tree_to_seq', 'convert a linearized token sequence back into a nested dict tree using seq_to_tree', 'apply BPE tokenization to text and linearize a tree into a sequence using tokenize_linearize', 'create a PyTorch CAIPDataset for instruction parsing that applies BPE and linearizes trees on the fly', 'build a BERT-based decoder module with highway layers for sequence and span prediction', 'build an encoder-decoder model combining a BERT encoder with a DecoderWithLoss decoder', 'run beam search to predict program synthesis trees from raw text input', 'run greedy tree prediction from raw text using the model decoder step by step', 'create a label smoothing loss module using KL-divergence for cross-entropy training']
```

Usage

```
{'init_TTADBertModel': 'initialize a TTADBertModel from a saved model directory and data directory for dialogue parsing', 'parse_dialogue_with_TTADBertModel': 'parse a dialogue chat history using TTADBertModel.parse to extract structured intent trees', 'load_pretrained_encoder_decoder': 'load a pretrained BERT encoder and decoder model with custom vocabulary from saved checkpoint files', 'beam_search_dialogue_parsing': 'run beam search over dialogue turns to find the best structured parse tree with NOOP filtering', 'configure_decoder_with_BertConfig': 'configure a BERT decoder with custom hidden layers and vocabulary size for tree generation'}
```

## File: facebookresearch_craftassist/acl2020_submission/model_training_code/train_model.py

Prompts

```
['initialize a TTADBertModel from a saved model directory and data directory for dialogue parsing', 'parse a dialogue chat history using TTADBertModel.parse to extract structured intent trees', 'load a pretrained BERT encoder and decoder model with custom vocabulary from saved checkpoint files', 'run beam search over dialogue turns to find the best structured parse tree with NOOP filtering', 'configure a BERT decoder with custom hidden layers and vocabulary size for tree generation', 'run the CAIP encoder-decoder model training loop with configurable epochs, batch size, and learning rate', 'run validation on a trained CAIP model across templated, rephrased, prompt, and humanbot datasets', 'run the main CLI to train and evaluate a CAIP parser model with argparse configuration', 'review the train function that performs gradient clipping, backpropagation, and hard example mining', 'review the validate function that computes loss and accuracy metrics without backpropagation', 'build a grammar and vocabulary from a list of weighted tree datasets using make_full_tree', 'linearize a nested dict tree into a flat sequence of tokens and spans using tree_to_seq', 'convert a linearized token sequence back into a nested dict tree using seq_to_tree', 'apply BPE tokenization to text and linearize a tree into a sequence using tokenize_linearize', 'create a PyTorch CAIPDataset for instruction parsing that applies BPE and linearizes trees on the fly', 'build a BERT-based decoder module with highway layers for sequence and span prediction', 'build an encoder-decoder model combining a BERT encoder with a DecoderWithLoss decoder', 'run beam search to predict program synthesis trees from raw text input', 'run greedy tree prediction from raw text using the model decoder step by step', 'create a label smoothing loss module using KL-divergence for cross-entropy training']
```

Usage

```
{'run_train_model': 'run the CAIP encoder-decoder model training loop with configurable epochs, batch size, and learning rate', 'run_validate_model': 'run validation on a trained CAIP model across templated, rephrased, prompt, and humanbot datasets', 'run_main_cli': 'run the main CLI to train and evaluate a CAIP parser model with argparse configuration', 'review_train_function': 'review the train function that performs gradient clipping, backpropagation, and hard example mining', 'review_validate_function': 'review the validate function that computes loss and accuracy metrics without backpropagation'}
```

## File: facebookresearch_craftassist/acl2020_submission/model_training_code/utils_caip.py

Prompts

```
['initialize a TTADBertModel from a saved model directory and data directory for dialogue parsing', 'parse a dialogue chat history using TTADBertModel.parse to extract structured intent trees', 'load a pretrained BERT encoder and decoder model with custom vocabulary from saved checkpoint files', 'run beam search over dialogue turns to find the best structured parse tree with NOOP filtering', 'configure a BERT decoder with custom hidden layers and vocabulary size for tree generation', 'run the CAIP encoder-decoder model training loop with configurable epochs, batch size, and learning rate', 'run validation on a trained CAIP model across templated, rephrased, prompt, and humanbot datasets', 'run the main CLI to train and evaluate a CAIP parser model with argparse configuration', 'review the train function that performs gradient clipping, backpropagation, and hard example mining', 'review the validate function that computes loss and accuracy metrics without backpropagation', 'build a grammar and vocabulary from a list of weighted tree datasets using make_full_tree', 'linearize a nested dict tree into a flat sequence of tokens and spans using tree_to_seq', 'convert a linearized token sequence back into a nested dict tree using seq_to_tree', 'apply BPE tokenization to text and linearize a tree into a sequence using tokenize_linearize', 'create a PyTorch CAIPDataset for instruction parsing that applies BPE and linearizes trees on the fly', 'build a BERT-based decoder module with highway layers for sequence and span prediction', 'build an encoder-decoder model combining a BERT encoder with a DecoderWithLoss decoder', 'run beam search to predict program synthesis trees from raw text input', 'run greedy tree prediction from raw text using the model decoder step by step', 'create a label smoothing loss module using KL-divergence for cross-entropy training']
```

Usage

```
{'build_full_tree_grammar': 'build a grammar and vocabulary from a list of weighted tree datasets using make_full_tree', 'linearize_tree_to_sequence': 'linearize a nested dict tree into a flat sequence of tokens and spans using tree_to_seq', 'delinearize_sequence_to_tree': 'convert a linearized token sequence back into a nested dict tree using seq_to_tree', 'tokenize_and_linearize': 'apply BPE tokenization to text and linearize a tree into a sequence using tokenize_linearize', 'create_caip_dataset': 'create a PyTorch CAIPDataset for instruction parsing that applies BPE and linearizes trees on the fly'}
```

## File: facebookresearch_craftassist/acl2020_submission/model_training_code/utils_parsing.py

Prompts

```
['initialize a TTADBertModel from a saved model directory and data directory for dialogue parsing', 'parse a dialogue chat history using TTADBertModel.parse to extract structured intent trees', 'load a pretrained BERT encoder and decoder model with custom vocabulary from saved checkpoint files', 'run beam search over dialogue turns to find the best structured parse tree with NOOP filtering', 'configure a BERT decoder with custom hidden layers and vocabulary size for tree generation', 'run the CAIP encoder-decoder model training loop with configurable epochs, batch size, and learning rate', 'run validation on a trained CAIP model across templated, rephrased, prompt, and humanbot datasets', 'run the main CLI to train and evaluate a CAIP parser model with argparse configuration', 'review the train function that performs gradient clipping, backpropagation, and hard example mining', 'review the validate function that computes loss and accuracy metrics without backpropagation', 'build a grammar and vocabulary from a list of weighted tree datasets using make_full_tree', 'linearize a nested dict tree into a flat sequence of tokens and spans using tree_to_seq', 'convert a linearized token sequence back into a nested dict tree using seq_to_tree', 'apply BPE tokenization to text and linearize a tree into a sequence using tokenize_linearize', 'create a PyTorch CAIPDataset for instruction parsing that applies BPE and linearizes trees on the fly', 'build a BERT-based decoder module with highway layers for sequence and span prediction', 'build an encoder-decoder model combining a BERT encoder with a DecoderWithLoss decoder', 'run beam search to predict program synthesis trees from raw text input', 'run greedy tree prediction from raw text using the model decoder step by step', 'create a label smoothing loss module using KL-divergence for cross-entropy training']
```

Usage

```
{'build_DecoderWithLoss': 'build a BERT-based decoder module with highway layers for sequence and span prediction', 'build_EncoderDecoderWithLoss': 'build an encoder-decoder model combining a BERT encoder with a DecoderWithLoss decoder', 'run_beam_search': 'run beam search to predict program synthesis trees from raw text input', 'run_predict_tree': 'run greedy tree prediction from raw text using the model decoder step by step', 'create_LabelSmoothingLoss': 'create a label smoothing loss module using KL-divergence for cross-entropy training'}
```

