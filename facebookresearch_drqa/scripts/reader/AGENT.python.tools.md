# Agent Python Tools

- repo: facebookresearch/drqa
- repo_uri: https://github.com/facebookresearch/drqa

## File: facebookresearch_drqa/scripts/reader/interactive.py

Prompts

```
['run the DrQA reader model interactively with a pretrained model and GPU support', 'process a document and question to extract answer spans with ranked scores', 'run the DrQA reader with a specified tokenizer like corenlp for tokenization', 'run the DrQA reader model on CPU only without CUDA acceleration', 'print the interactive module usage banner showing available commands and signatures', 'run the SQuAD dataset preprocessing script to tokenize and annotate training data with a specified tokenizer', 'load a SQuAD JSON dataset file and extract questions, answers, and contexts into separate lists', 'tokenize input text and return words, offsets, POS tags, lemmas, and NER entities using a global tokenizer', 'process a SQuAD dataset with multiprocessing to tokenize questions and contexts with lemma, POS, and NER annotations', 'find the start and end token indices matching character offsets for an answer span in a document', 'run the DrQA reader training script to train a document reading comprehension model on SQuAD data', 'add commandline arguments for training a DrQA model including GPU, batch size, and embedding options', 'initialize a new DocReader model from scratch with a word dictionary and pretrained embeddings', 'validate the DrQA model using official SQuAD exact match and F1 score evaluation metrics', 'set default values and validate file paths for DrQA training commandline arguments']
```

Usage

```
{'run_interactive_reader': 'run the DrQA reader model interactively with a pretrained model and GPU support', 'process_document_question': 'process a document and question to extract answer spans with ranked scores', 'run_reader_with_tokenizer': 'run the DrQA reader with a specified tokenizer like corenlp for tokenization', 'run_reader_cpu_only': 'run the DrQA reader model on CPU only without CUDA acceleration', 'usage_interactive_help': 'print the interactive module usage banner showing available commands and signatures'}
```

## File: facebookresearch_drqa/scripts/reader/preprocess.py

Prompts

```
['run the DrQA reader model interactively with a pretrained model and GPU support', 'process a document and question to extract answer spans with ranked scores', 'run the DrQA reader with a specified tokenizer like corenlp for tokenization', 'run the DrQA reader model on CPU only without CUDA acceleration', 'print the interactive module usage banner showing available commands and signatures', 'run the SQuAD dataset preprocessing script to tokenize and annotate training data with a specified tokenizer', 'load a SQuAD JSON dataset file and extract questions, answers, and contexts into separate lists', 'tokenize input text and return words, offsets, POS tags, lemmas, and NER entities using a global tokenizer', 'process a SQuAD dataset with multiprocessing to tokenize questions and contexts with lemma, POS, and NER annotations', 'find the start and end token indices matching character offsets for an answer span in a document', 'run the DrQA reader training script to train a document reading comprehension model on SQuAD data', 'add commandline arguments for training a DrQA model including GPU, batch size, and embedding options', 'initialize a new DocReader model from scratch with a word dictionary and pretrained embeddings', 'validate the DrQA model using official SQuAD exact match and F1 score evaluation metrics', 'set default values and validate file paths for DrQA training commandline arguments']
```

Usage

```
{'run_preprocess_squad': 'run the SQuAD dataset preprocessing script to tokenize and annotate training data with a specified tokenizer', 'load_dataset': 'load a SQuAD JSON dataset file and extract questions, answers, and contexts into separate lists', 'tokenize_text': 'tokenize input text and return words, offsets, POS tags, lemmas, and NER entities using a global tokenizer', 'process_dataset': 'process a SQuAD dataset with multiprocessing to tokenize questions and contexts with lemma, POS, and NER annotations', 'find_answer': 'find the start and end token indices matching character offsets for an answer span in a document'}
```

## File: facebookresearch_drqa/scripts/reader/train.py

Prompts

```
['run the DrQA reader model interactively with a pretrained model and GPU support', 'process a document and question to extract answer spans with ranked scores', 'run the DrQA reader with a specified tokenizer like corenlp for tokenization', 'run the DrQA reader model on CPU only without CUDA acceleration', 'print the interactive module usage banner showing available commands and signatures', 'run the SQuAD dataset preprocessing script to tokenize and annotate training data with a specified tokenizer', 'load a SQuAD JSON dataset file and extract questions, answers, and contexts into separate lists', 'tokenize input text and return words, offsets, POS tags, lemmas, and NER entities using a global tokenizer', 'process a SQuAD dataset with multiprocessing to tokenize questions and contexts with lemma, POS, and NER annotations', 'find the start and end token indices matching character offsets for an answer span in a document', 'run the DrQA reader training script to train a document reading comprehension model on SQuAD data', 'add commandline arguments for training a DrQA model including GPU, batch size, and embedding options', 'initialize a new DocReader model from scratch with a word dictionary and pretrained embeddings', 'validate the DrQA model using official SQuAD exact match and F1 score evaluation metrics', 'set default values and validate file paths for DrQA training commandline arguments']
```

Usage

```
{'run_drqa_reader_training': 'run the DrQA reader training script to train a document reading comprehension model on SQuAD data', 'add_train_args_parser': 'add commandline arguments for training a DrQA model including GPU, batch size, and embedding options', 'init_from_scratch_model': 'initialize a new DocReader model from scratch with a word dictionary and pretrained embeddings', 'validate_official_squad': 'validate the DrQA model using official SQuAD exact match and F1 score evaluation metrics', 'set_defaults_args': 'set default values and validate file paths for DrQA training commandline arguments'}
```

