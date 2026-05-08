# Agent Python Tools

- repo: facebookresearch/codegen
- repo_uri: https://github.com/facebookresearch/codegen

## File: facebookresearch_codegen/codegen_sources/model/deobfuscate.py

Prompts

```
['run the deobfuscator CLI to translate obfuscated Java or Python code via stdin', 'create a Deobfuscator instance from a model checkpoint path and BPE codes path', 'deobfuscate obfuscated Java or Python source code using a pretrained encoder-decoder model', 'build an argparse parser with model path, language, BPE path, and beam size arguments', 'generate deobfuscated code candidates using beam search decoding with configurable beam size', 'run the XLM_preprocess CLI to index text data into a binary .pth file using a vocabulary file', 'run the XLM_preprocess function to read a vocab file and index text data with unknown word statistics', 'review the XLM_preprocess function that indexes text data and logs word counts and unknown word coverage', 'summarize the Dictionary.read_vocab method used to load a vocabulary file into a Dictionary object', 'summarize the Dictionary.index_data method used to index text data into a binary .pth file', 'run the codegen model training loop with causal LM, MLM, MT, and auto-encoder steps via CLI', 'run a single encoder-only transformer model training with configurable embedding dimensions, layers, and heads', 'run multi-task training combining CLM, MLM, machine translation, back-translation, deobfuscation, and self-training steps', 'run evaluation only mode to compute BLEU, computation correctness, and other metrics without training', 'translate source code from one programming language to another using a pretrained model', 'initialize a Translator with a model path and BPE codes to load encoder and decoder', 'run the CLI to translate code from a source language to a target language via stdin or file', 'translate code using beam search with configurable beam size and length penalty', 'configure the Translator to use flash or cutlass efficient attention from xformers']
```

Usage

```
{'run_deobfuscator_cli': 'run the deobfuscator CLI to translate obfuscated Java or Python code via stdin', 'create_deobfuscator_instance': 'create a Deobfuscator instance from a model checkpoint path and BPE codes path', 'deobfuscate_code': 'deobfuscate obfuscated Java or Python source code using a pretrained encoder-decoder model', 'build_argparse_parser': 'build an argparse parser with model path, language, BPE path, and beam size arguments', 'generate_beam_decoding': 'generate deobfuscated code candidates using beam search decoding with configurable beam size'}
```

## File: facebookresearch_codegen/codegen_sources/model/preprocess.py

Prompts

```
['run the deobfuscator CLI to translate obfuscated Java or Python code via stdin', 'create a Deobfuscator instance from a model checkpoint path and BPE codes path', 'deobfuscate obfuscated Java or Python source code using a pretrained encoder-decoder model', 'build an argparse parser with model path, language, BPE path, and beam size arguments', 'generate deobfuscated code candidates using beam search decoding with configurable beam size', 'run the XLM_preprocess CLI to index text data into a binary .pth file using a vocabulary file', 'run the XLM_preprocess function to read a vocab file and index text data with unknown word statistics', 'review the XLM_preprocess function that indexes text data and logs word counts and unknown word coverage', 'summarize the Dictionary.read_vocab method used to load a vocabulary file into a Dictionary object', 'summarize the Dictionary.index_data method used to index text data into a binary .pth file', 'run the codegen model training loop with causal LM, MLM, MT, and auto-encoder steps via CLI', 'run a single encoder-only transformer model training with configurable embedding dimensions, layers, and heads', 'run multi-task training combining CLM, MLM, machine translation, back-translation, deobfuscation, and self-training steps', 'run evaluation only mode to compute BLEU, computation correctness, and other metrics without training', 'translate source code from one programming language to another using a pretrained model', 'initialize a Translator with a model path and BPE codes to load encoder and decoder', 'run the CLI to translate code from a source language to a target language via stdin or file', 'translate code using beam search with configurable beam size and length penalty', 'configure the Translator to use flash or cutlass efficient attention from xformers']
```

Usage

```
{'run_XLM_preprocess_cli': 'run the XLM_preprocess CLI to index text data into a binary .pth file using a vocabulary file', 'run_XLM_preprocess_function': 'run the XLM_preprocess function to read a vocab file and index text data with unknown word statistics', 'review_XLM_preprocess': 'review the XLM_preprocess function that indexes text data and logs word counts and unknown word coverage', 'summarize_Dictionary_read_vocab': 'summarize the Dictionary.read_vocab method used to load a vocabulary file into a Dictionary object', 'summarize_Dictionary_index_data': 'summarize the Dictionary.index_data method used to index text data into a binary .pth file'}
```

## File: facebookresearch_codegen/codegen_sources/model/train.py

Prompts

```
['run the deobfuscator CLI to translate obfuscated Java or Python code via stdin', 'create a Deobfuscator instance from a model checkpoint path and BPE codes path', 'deobfuscate obfuscated Java or Python source code using a pretrained encoder-decoder model', 'build an argparse parser with model path, language, BPE path, and beam size arguments', 'generate deobfuscated code candidates using beam search decoding with configurable beam size', 'run the XLM_preprocess CLI to index text data into a binary .pth file using a vocabulary file', 'run the XLM_preprocess function to read a vocab file and index text data with unknown word statistics', 'review the XLM_preprocess function that indexes text data and logs word counts and unknown word coverage', 'summarize the Dictionary.read_vocab method used to load a vocabulary file into a Dictionary object', 'summarize the Dictionary.index_data method used to index text data into a binary .pth file', 'run the codegen model training loop with causal LM, MLM, MT, and auto-encoder steps via CLI', 'run a single encoder-only transformer model training with configurable embedding dimensions, layers, and heads', 'run multi-task training combining CLM, MLM, machine translation, back-translation, deobfuscation, and self-training steps', 'run evaluation only mode to compute BLEU, computation correctness, and other metrics without training', 'translate source code from one programming language to another using a pretrained model', 'initialize a Translator with a model path and BPE codes to load encoder and decoder', 'run the CLI to translate code from a source language to a target language via stdin or file', 'translate code using beam search with configurable beam size and length penalty', 'configure the Translator to use flash or cutlass efficient attention from xformers']
```

Usage

```
{'run_codegen_training': 'run the codegen model training loop with causal LM, MLM, MT, and auto-encoder steps via CLI', 'build_argparse_parser': 'build an argparse parser with 100+ arguments for codegen model training configuration including model, data, and training params', 'run_encoder_only_training': 'run a single encoder-only transformer model training with configurable embedding dimensions, layers, and heads', 'run_multitask_training': 'run multi-task training combining CLM, MLM, machine translation, back-translation, deobfuscation, and self-training steps', 'run_evaluation_only': 'run evaluation only mode to compute BLEU, computation correctness, and other metrics without training'}
```

## File: facebookresearch_codegen/codegen_sources/model/translate.py

Prompts

```
['run the deobfuscator CLI to translate obfuscated Java or Python code via stdin', 'create a Deobfuscator instance from a model checkpoint path and BPE codes path', 'deobfuscate obfuscated Java or Python source code using a pretrained encoder-decoder model', 'build an argparse parser with model path, language, BPE path, and beam size arguments', 'generate deobfuscated code candidates using beam search decoding with configurable beam size', 'run the XLM_preprocess CLI to index text data into a binary .pth file using a vocabulary file', 'run the XLM_preprocess function to read a vocab file and index text data with unknown word statistics', 'review the XLM_preprocess function that indexes text data and logs word counts and unknown word coverage', 'summarize the Dictionary.read_vocab method used to load a vocabulary file into a Dictionary object', 'summarize the Dictionary.index_data method used to index text data into a binary .pth file', 'run the codegen model training loop with causal LM, MLM, MT, and auto-encoder steps via CLI', 'run a single encoder-only transformer model training with configurable embedding dimensions, layers, and heads', 'run multi-task training combining CLM, MLM, machine translation, back-translation, deobfuscation, and self-training steps', 'run evaluation only mode to compute BLEU, computation correctness, and other metrics without training', 'translate source code from one programming language to another using a pretrained model', 'initialize a Translator with a model path and BPE codes to load encoder and decoder', 'run the CLI to translate code from a source language to a target language via stdin or file', 'translate code using beam search with configurable beam size and length penalty', 'configure the Translator to use flash or cutlass efficient attention from xformers']
```

Usage

```
{'translate_code_between_languages': 'translate source code from one programming language to another using a pretrained model', 'initialize_translator_with_model': 'initialize a Translator with a model path and BPE codes to load encoder and decoder', 'run_translation_cli': 'run the CLI to translate code from a source language to a target language via stdin or file', 'translate_with_beam_search': 'translate code using beam search with configurable beam size and length penalty', 'configure_efficient_attention': 'configure the Translator to use flash or cutlass efficient attention from xformers'}
```

