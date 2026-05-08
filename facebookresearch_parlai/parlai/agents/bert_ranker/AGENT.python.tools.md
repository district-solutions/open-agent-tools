# Agent Python Tools

- repo: facebookresearch/parlai
- repo_uri: https://github.com/facebookresearch/parlai

## File: facebookresearch_parlai/parlai/agents/bert_ranker/bert_dictionary.py

Prompts

```
['initialize a BertDictionaryAgent with an opt dict containing datapath for BERT tokenization', 'convert text to BERT token IDs using the BertDictionaryAgent txt2vec method', 'convert a list of BERT token IDs back to text using the vec2txt method', 'review the BertDictionaryAgent class and its BERT special token handling for CLS SEP PAD', 'summarize the BertDictionaryAgent class which wraps a Hugging Face BERT tokenizer for ParlAI', 'build a BiEncoderRankerAgent to rank candidates using BERT-based biencoder embeddings', 'create a BiEncoderModule with separate context and candidate BERT encoders', 'score candidates against context using the BiEncoderRankerAgent score_candidates method', 'encode candidate text vectors into BERT embeddings using encode_candidates', 'convert token index tensors to BERT input format with segment indices and masks', 'build a BothEncoderRankerAgent that combines a biencoder and crossencoder for two-stage ranking', 'run a training step on a batch through both the biencoder and crossencoder', 'run an evaluation step that filters candidates through biencoder then crossencoder', 'save both the biencoder and crossencoder model files to disk', 'load both the biencoder and crossencoder model files from disk', 'build a CrossEncoderRankerAgent to rank candidates using a pretrained BERT cross-encoder model', 'add command-line arguments for the CrossEncoderRankerAgent including candidate encoding and dictionary settings', 'score a batch of candidates against context text using the BERT cross-encoder model', 'build a BertWrapper model from a pretrained BERT checkpoint with configurable transformer layers', 'set and surround the text vector with CLS and SEP tokens for BERT encoding', 'add command line arguments for a BERT ranker agent including transformer layer and aggregation options', 'create a BertWrapper module that adds a transformer layer and classification layers on top of a pretrained BERT model', 'run a forward pass through the BertWrapper model with token ids, segment ids, and attention mask', 'surround a token id vector with start and end index tokens using the surround helper function', 'review the BertWrapper class and its embedding aggregation strategies including first, mean, and max pooling']
```

Usage

```
{'init_bert_dictionary_agent': 'initialize a BertDictionaryAgent with an opt dict containing datapath for BERT tokenization', 'txt2vec_tokenize_text': 'convert text to BERT token IDs using the BertDictionaryAgent txt2vec method', 'vec2txt_decode_tokens': 'convert a list of BERT token IDs back to text using the vec2txt method', 'review_bert_dictionary_agent_class': 'review the BertDictionaryAgent class and its BERT special token handling for CLS SEP PAD', 'summarize_bert_dictionary_agent': 'summarize the BertDictionaryAgent class which wraps a Hugging Face BERT tokenizer for ParlAI'}
```

## File: facebookresearch_parlai/parlai/agents/bert_ranker/bi_encoder_ranker.py

Prompts

```
['initialize a BertDictionaryAgent with an opt dict containing datapath for BERT tokenization', 'convert text to BERT token IDs using the BertDictionaryAgent txt2vec method', 'convert a list of BERT token IDs back to text using the vec2txt method', 'review the BertDictionaryAgent class and its BERT special token handling for CLS SEP PAD', 'summarize the BertDictionaryAgent class which wraps a Hugging Face BERT tokenizer for ParlAI', 'build a BiEncoderRankerAgent to rank candidates using BERT-based biencoder embeddings', 'create a BiEncoderModule with separate context and candidate BERT encoders', 'score candidates against context using the BiEncoderRankerAgent score_candidates method', 'encode candidate text vectors into BERT embeddings using encode_candidates', 'convert token index tensors to BERT input format with segment indices and masks', 'build a BothEncoderRankerAgent that combines a biencoder and crossencoder for two-stage ranking', 'run a training step on a batch through both the biencoder and crossencoder', 'run an evaluation step that filters candidates through biencoder then crossencoder', 'save both the biencoder and crossencoder model files to disk', 'load both the biencoder and crossencoder model files from disk', 'build a CrossEncoderRankerAgent to rank candidates using a pretrained BERT cross-encoder model', 'add command-line arguments for the CrossEncoderRankerAgent including candidate encoding and dictionary settings', 'score a batch of candidates against context text using the BERT cross-encoder model', 'build a BertWrapper model from a pretrained BERT checkpoint with configurable transformer layers', 'set and surround the text vector with CLS and SEP tokens for BERT encoding', 'add command line arguments for a BERT ranker agent including transformer layer and aggregation options', 'create a BertWrapper module that adds a transformer layer and classification layers on top of a pretrained BERT model', 'run a forward pass through the BertWrapper model with token ids, segment ids, and attention mask', 'surround a token id vector with start and end index tokens using the surround helper function', 'review the BertWrapper class and its embedding aggregation strategies including first, mean, and max pooling']
```

Usage

```
{'build_biencoder_ranker_agent': 'build a BiEncoderRankerAgent to rank candidates using BERT-based biencoder embeddings', 'create_biencoder_module': 'create a BiEncoderModule with separate context and candidate BERT encoders', 'score_candidates_biencoder': 'score candidates against context using the BiEncoderRankerAgent score_candidates method', 'encode_candidates_bert': 'encode candidate text vectors into BERT embeddings using encode_candidates', 'convert_to_bert_input': 'convert token index tensors to BERT input format with segment indices and masks'}
```

## File: facebookresearch_parlai/parlai/agents/bert_ranker/both_encoder_ranker.py

Prompts

```
['initialize a BertDictionaryAgent with an opt dict containing datapath for BERT tokenization', 'convert text to BERT token IDs using the BertDictionaryAgent txt2vec method', 'convert a list of BERT token IDs back to text using the vec2txt method', 'review the BertDictionaryAgent class and its BERT special token handling for CLS SEP PAD', 'summarize the BertDictionaryAgent class which wraps a Hugging Face BERT tokenizer for ParlAI', 'build a BiEncoderRankerAgent to rank candidates using BERT-based biencoder embeddings', 'create a BiEncoderModule with separate context and candidate BERT encoders', 'score candidates against context using the BiEncoderRankerAgent score_candidates method', 'encode candidate text vectors into BERT embeddings using encode_candidates', 'convert token index tensors to BERT input format with segment indices and masks', 'build a BothEncoderRankerAgent that combines a biencoder and crossencoder for two-stage ranking', 'run a training step on a batch through both the biencoder and crossencoder', 'run an evaluation step that filters candidates through biencoder then crossencoder', 'save both the biencoder and crossencoder model files to disk', 'load both the biencoder and crossencoder model files from disk', 'build a CrossEncoderRankerAgent to rank candidates using a pretrained BERT cross-encoder model', 'add command-line arguments for the CrossEncoderRankerAgent including candidate encoding and dictionary settings', 'score a batch of candidates against context text using the BERT cross-encoder model', 'build a BertWrapper model from a pretrained BERT checkpoint with configurable transformer layers', 'set and surround the text vector with CLS and SEP tokens for BERT encoding', 'add command line arguments for a BERT ranker agent including transformer layer and aggregation options', 'create a BertWrapper module that adds a transformer layer and classification layers on top of a pretrained BERT model', 'run a forward pass through the BertWrapper model with token ids, segment ids, and attention mask', 'surround a token id vector with start and end index tokens using the surround helper function', 'review the BertWrapper class and its embedding aggregation strategies including first, mean, and max pooling']
```

Usage

```
{'build_both_encoder_ranker': 'build a BothEncoderRankerAgent that combines a biencoder and crossencoder for two-stage ranking', 'run_train_step': 'run a training step on a batch through both the biencoder and crossencoder', 'run_eval_step': 'run an evaluation step that filters candidates through biencoder then crossencoder', 'save_both_encoder_model': 'save both the biencoder and crossencoder model files to disk', 'load_both_encoder_model': 'load both the biencoder and crossencoder model files from disk'}
```

## File: facebookresearch_parlai/parlai/agents/bert_ranker/cross_encoder_ranker.py

Prompts

```
['initialize a BertDictionaryAgent with an opt dict containing datapath for BERT tokenization', 'convert text to BERT token IDs using the BertDictionaryAgent txt2vec method', 'convert a list of BERT token IDs back to text using the vec2txt method', 'review the BertDictionaryAgent class and its BERT special token handling for CLS SEP PAD', 'summarize the BertDictionaryAgent class which wraps a Hugging Face BERT tokenizer for ParlAI', 'build a BiEncoderRankerAgent to rank candidates using BERT-based biencoder embeddings', 'create a BiEncoderModule with separate context and candidate BERT encoders', 'score candidates against context using the BiEncoderRankerAgent score_candidates method', 'encode candidate text vectors into BERT embeddings using encode_candidates', 'convert token index tensors to BERT input format with segment indices and masks', 'build a BothEncoderRankerAgent that combines a biencoder and crossencoder for two-stage ranking', 'run a training step on a batch through both the biencoder and crossencoder', 'run an evaluation step that filters candidates through biencoder then crossencoder', 'save both the biencoder and crossencoder model files to disk', 'load both the biencoder and crossencoder model files from disk', 'build a CrossEncoderRankerAgent to rank candidates using a pretrained BERT cross-encoder model', 'add command-line arguments for the CrossEncoderRankerAgent including candidate encoding and dictionary settings', 'score a batch of candidates against context text using the BERT cross-encoder model', 'build a BertWrapper model from a pretrained BERT checkpoint with configurable transformer layers', 'set and surround the text vector with CLS and SEP tokens for BERT encoding', 'add command line arguments for a BERT ranker agent including transformer layer and aggregation options', 'create a BertWrapper module that adds a transformer layer and classification layers on top of a pretrained BERT model', 'run a forward pass through the BertWrapper model with token ids, segment ids, and attention mask', 'surround a token id vector with start and end index tokens using the surround helper function', 'review the BertWrapper class and its embedding aggregation strategies including first, mean, and max pooling']
```

Usage

```
{'build_cross_encoder_ranker': 'build a CrossEncoderRankerAgent to rank candidates using a pretrained BERT cross-encoder model', 'add_cmdline_args': 'add command-line arguments for the CrossEncoderRankerAgent including candidate encoding and dictionary settings', 'score_candidates': 'score a batch of candidates against context text using the BERT cross-encoder model', 'build_model': 'build a BertWrapper model from a pretrained BERT checkpoint with configurable transformer layers', 'set_text_vec': 'set and surround the text vector with CLS and SEP tokens for BERT encoding'}
```

## File: facebookresearch_parlai/parlai/agents/bert_ranker/helpers.py

Prompts

```
['initialize a BertDictionaryAgent with an opt dict containing datapath for BERT tokenization', 'convert text to BERT token IDs using the BertDictionaryAgent txt2vec method', 'convert a list of BERT token IDs back to text using the vec2txt method', 'review the BertDictionaryAgent class and its BERT special token handling for CLS SEP PAD', 'summarize the BertDictionaryAgent class which wraps a Hugging Face BERT tokenizer for ParlAI', 'build a BiEncoderRankerAgent to rank candidates using BERT-based biencoder embeddings', 'create a BiEncoderModule with separate context and candidate BERT encoders', 'score candidates against context using the BiEncoderRankerAgent score_candidates method', 'encode candidate text vectors into BERT embeddings using encode_candidates', 'convert token index tensors to BERT input format with segment indices and masks', 'build a BothEncoderRankerAgent that combines a biencoder and crossencoder for two-stage ranking', 'run a training step on a batch through both the biencoder and crossencoder', 'run an evaluation step that filters candidates through biencoder then crossencoder', 'save both the biencoder and crossencoder model files to disk', 'load both the biencoder and crossencoder model files from disk', 'build a CrossEncoderRankerAgent to rank candidates using a pretrained BERT cross-encoder model', 'add command-line arguments for the CrossEncoderRankerAgent including candidate encoding and dictionary settings', 'score a batch of candidates against context text using the BERT cross-encoder model', 'build a BertWrapper model from a pretrained BERT checkpoint with configurable transformer layers', 'set and surround the text vector with CLS and SEP tokens for BERT encoding', 'add command line arguments for a BERT ranker agent including transformer layer and aggregation options', 'create a BertWrapper module that adds a transformer layer and classification layers on top of a pretrained BERT model', 'run a forward pass through the BertWrapper model with token ids, segment ids, and attention mask', 'surround a token id vector with start and end index tokens using the surround helper function', 'review the BertWrapper class and its embedding aggregation strategies including first, mean, and max pooling']
```

Usage

```
{'add_bert_ranker_args': 'add command line arguments for a BERT ranker agent including transformer layer and aggregation options', 'create_bert_wrapper': 'create a BertWrapper module that adds a transformer layer and classification layers on top of a pretrained BERT model', 'run_bert_wrapper_forward': 'run a forward pass through the BertWrapper model with token ids, segment ids, and attention mask', 'surround_token_ids': 'surround a token id vector with start and end index tokens using the surround helper function', 'review_bert_wrapper_aggregation': 'review the BertWrapper class and its embedding aggregation strategies including first, mean, and max pooling'}
```

