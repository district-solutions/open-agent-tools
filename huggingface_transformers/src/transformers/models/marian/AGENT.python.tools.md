# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/marian/convert_marian_tatoeba_to_pytorch.py

Prompts

```
['convert Tatoeba-Challenge models to huggingface format with opus-mt naming', 'write a model card with metadata and markdown for a converted Marian translation model', 'resolve language codes between alpha3 and alpha2 formats for multilingual translation pairs', 'parse YAML metadata from a Tatoeba model directory and merge model type info', 'run the CLI to convert specified Tatoeba model IDs to PyTorch huggingface format', 'convert a Marian MT model from marian checkpoint format to a Hugging Face PyTorch MarianMTModel', 'find a pretrained Helsinki-NLP opus-mt translation model for a given source and target language pair', 'write a Hugging Face model card with metadata and readme from an OPUS-MT model directory', 'convert all sentencepiece-based OPUS-MT models from a registry directory to Hugging Face format', 'load an OPUS-MT model state dictionary and configuration to inspect weights and create a MarianConfig', 'build a MarianMTModel pipeline that translates text from a source language to a target language', 'create a MarianModel forward pass that encodes input text and decodes with provided decoder input ids', 'test MarianForCausalLM forward pass with input ids and optional labels for causal language modeling', 'run MarianMTModel.generate() to produce translated sequences from encoder input ids', 'refactor MarianAttention to use configurable scaling factor and support flash attention implementations', 'build a MarianTokenizer instance from source and target SentencePiece models with separate vocabularies for translation', 'tokenize source and target text sequences into token ids using MarianTokenizer for machine translation', 'decode token ids back into readable strings using MarianTokenizer with optional source or target tokenizer', 'save MarianTokenizer vocabulary and SentencePiece model files to a specified directory', 'get a mask identifying special tokens like eos and pad in a token id sequence for MarianTokenizer']
```

Usage

```
{'convert_models_tatoeba': 'convert Tatoeba-Challenge models to huggingface format with opus-mt naming', 'write_model_card': 'write a model card with metadata and markdown for a converted Marian translation model', 'resolve_lang_code': 'resolve language codes between alpha3 and alpha2 formats for multilingual translation pairs', 'parse_metadata': 'parse YAML metadata from a Tatoeba model directory and merge model type info', 'run_cli_convert': 'run the CLI to convert specified Tatoeba model IDs to PyTorch huggingface format'}
```

## File: huggingface_transformers/src/transformers/models/marian/convert_marian_to_pytorch.py

Prompts

```
['convert Tatoeba-Challenge models to huggingface format with opus-mt naming', 'write a model card with metadata and markdown for a converted Marian translation model', 'resolve language codes between alpha3 and alpha2 formats for multilingual translation pairs', 'parse YAML metadata from a Tatoeba model directory and merge model type info', 'run the CLI to convert specified Tatoeba model IDs to PyTorch huggingface format', 'convert a Marian MT model from marian checkpoint format to a Hugging Face PyTorch MarianMTModel', 'find a pretrained Helsinki-NLP opus-mt translation model for a given source and target language pair', 'write a Hugging Face model card with metadata and readme from an OPUS-MT model directory', 'convert all sentencepiece-based OPUS-MT models from a registry directory to Hugging Face format', 'load an OPUS-MT model state dictionary and configuration to inspect weights and create a MarianConfig', 'build a MarianMTModel pipeline that translates text from a source language to a target language', 'create a MarianModel forward pass that encodes input text and decodes with provided decoder input ids', 'test MarianForCausalLM forward pass with input ids and optional labels for causal language modeling', 'run MarianMTModel.generate() to produce translated sequences from encoder input ids', 'refactor MarianAttention to use configurable scaling factor and support flash attention implementations', 'build a MarianTokenizer instance from source and target SentencePiece models with separate vocabularies for translation', 'tokenize source and target text sequences into token ids using MarianTokenizer for machine translation', 'decode token ids back into readable strings using MarianTokenizer with optional source or target tokenizer', 'save MarianTokenizer vocabulary and SentencePiece model files to a specified directory', 'get a mask identifying special tokens like eos and pad in a token id sequence for MarianTokenizer']
```

Usage

```
{'convert_marian_model_to_pytorch': 'convert a Marian MT model from marian checkpoint format to a Hugging Face PyTorch MarianMTModel', 'find_pretrained_translation_model': 'find a pretrained Helsinki-NLP opus-mt translation model for a given source and target language pair', 'write_marian_model_card': 'write a Hugging Face model card with metadata and readme from an OPUS-MT model directory', 'convert_all_sentencepiece_models': 'convert all sentencepiece-based OPUS-MT models from a registry directory to Hugging Face format', 'load_opus_state_dict': 'load an OPUS-MT model state dictionary and configuration to inspect weights and create a MarianConfig'}
```

## File: huggingface_transformers/src/transformers/models/marian/modeling_marian.py

Prompts

```
['convert Tatoeba-Challenge models to huggingface format with opus-mt naming', 'write a model card with metadata and markdown for a converted Marian translation model', 'resolve language codes between alpha3 and alpha2 formats for multilingual translation pairs', 'parse YAML metadata from a Tatoeba model directory and merge model type info', 'run the CLI to convert specified Tatoeba model IDs to PyTorch huggingface format', 'convert a Marian MT model from marian checkpoint format to a Hugging Face PyTorch MarianMTModel', 'find a pretrained Helsinki-NLP opus-mt translation model for a given source and target language pair', 'write a Hugging Face model card with metadata and readme from an OPUS-MT model directory', 'convert all sentencepiece-based OPUS-MT models from a registry directory to Hugging Face format', 'load an OPUS-MT model state dictionary and configuration to inspect weights and create a MarianConfig', 'build a MarianMTModel pipeline that translates text from a source language to a target language', 'create a MarianModel forward pass that encodes input text and decodes with provided decoder input ids', 'test MarianForCausalLM forward pass with input ids and optional labels for causal language modeling', 'run MarianMTModel.generate() to produce translated sequences from encoder input ids', 'refactor MarianAttention to use configurable scaling factor and support flash attention implementations', 'build a MarianTokenizer instance from source and target SentencePiece models with separate vocabularies for translation', 'tokenize source and target text sequences into token ids using MarianTokenizer for machine translation', 'decode token ids back into readable strings using MarianTokenizer with optional source or target tokenizer', 'save MarianTokenizer vocabulary and SentencePiece model files to a specified directory', 'get a mask identifying special tokens like eos and pad in a token id sequence for MarianTokenizer']
```

Usage

```
{'build_marianmtmodel_translate': 'build a MarianMTModel pipeline that translates text from a source language to a target language', 'create_marianmodel_forward': 'create a MarianModel forward pass that encodes input text and decodes with provided decoder input ids', 'test_marian_for_causal_lm': 'test MarianForCausalLM forward pass with input ids and optional labels for causal language modeling', 'run_marianmtmodel_generate': 'run MarianMTModel.generate() to produce translated sequences from encoder input ids', 'refactor_marian_attention_scaling': 'refactor MarianAttention to use configurable scaling factor and support flash attention implementations'}
```

## File: huggingface_transformers/src/transformers/models/marian/tokenization_marian.py

Prompts

```
['convert Tatoeba-Challenge models to huggingface format with opus-mt naming', 'write a model card with metadata and markdown for a converted Marian translation model', 'resolve language codes between alpha3 and alpha2 formats for multilingual translation pairs', 'parse YAML metadata from a Tatoeba model directory and merge model type info', 'run the CLI to convert specified Tatoeba model IDs to PyTorch huggingface format', 'convert a Marian MT model from marian checkpoint format to a Hugging Face PyTorch MarianMTModel', 'find a pretrained Helsinki-NLP opus-mt translation model for a given source and target language pair', 'write a Hugging Face model card with metadata and readme from an OPUS-MT model directory', 'convert all sentencepiece-based OPUS-MT models from a registry directory to Hugging Face format', 'load an OPUS-MT model state dictionary and configuration to inspect weights and create a MarianConfig', 'build a MarianMTModel pipeline that translates text from a source language to a target language', 'create a MarianModel forward pass that encodes input text and decodes with provided decoder input ids', 'test MarianForCausalLM forward pass with input ids and optional labels for causal language modeling', 'run MarianMTModel.generate() to produce translated sequences from encoder input ids', 'refactor MarianAttention to use configurable scaling factor and support flash attention implementations', 'build a MarianTokenizer instance from source and target SentencePiece models with separate vocabularies for translation', 'tokenize source and target text sequences into token ids using MarianTokenizer for machine translation', 'decode token ids back into readable strings using MarianTokenizer with optional source or target tokenizer', 'save MarianTokenizer vocabulary and SentencePiece model files to a specified directory', 'get a mask identifying special tokens like eos and pad in a token id sequence for MarianTokenizer']
```

Usage

```
{'build_marian_tokenizer': 'build a MarianTokenizer instance from source and target SentencePiece models with separate vocabularies for translation', 'tokenize_text_marian': 'tokenize source and target text sequences into token ids using MarianTokenizer for machine translation', 'decode_token_ids': 'decode token ids back into readable strings using MarianTokenizer with optional source or target tokenizer', 'save_tokenizer_vocab': 'save MarianTokenizer vocabulary and SentencePiece model files to a specified directory', 'get_special_tokens_mask': 'get a mask identifying special tokens like eos and pad in a token id sequence for MarianTokenizer'}
```

