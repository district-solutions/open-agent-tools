# Agent Python Tools

- repo: facebookresearch/fairseq2
- repo_uri: https://github.com/facebookresearch/fairseq2.git

## File: facebookresearch_fairseq2/tests/integration/models/test_hg_integration.py

Prompts

```
['test that load_causal_lm delegates to AutoModelForCausalLM and wraps result in HgCausalLMAdapter', 'test that load_seq2seq_lm delegates to AutoModelForSeq2SeqLM without wrapping in adapter', 'test that load_hg_tokenizer_simple calls AutoTokenizer.from_pretrained and populates vocab_info correctly', 'test that create_hg_model wraps causal LM models in HgCausalLMAdapter but leaves seq2seq unwrapped', 'test that _get_auto_model_class selects the correct Auto class based on model_type or auto-detection', 'test the LLaMA model state dict round-trip conversion using convert_to_ref_llama_state_dict and convert_llama_state_dict', 'create an LLaMA model instance using LLaMAFactory with a resolved LLaMAConfig such as llama2_7b', 'convert a fairseq2 LLaMA model state dict to the reference LLaMA checkpoint format', 'convert a reference LLaMA state dict back to the fairseq2 internal format using the model config', 'get an LLaMA model config by name such as llama2_7b using get_config with a dependency resolver', 'test loading the nllb-200_dense_distill_600m model and translating an English sentence to German', 'test the NLLB tokenizer special tokens in source and target encoding modes', 'run English to German text translation using BeamSearchSeq2SeqGenerator and TextTranslator', 'test that long input text raises ValueError and can be handled with max_source_len', 'review the NLLB tokenizer create_encoder in source mode versus target mode token output', 'test loading the s2t_transformer_mustc_st_jt_m model and verify German translation output', 'test loading the s2t_conformer_covost_st_en_de model and verify German translation output', 'test loading the s2t_conformer_covost_st_en_de_rel_pos model with relative positional encoding', 'run translation assertion by converting fbank features to text using BeamSearchSeq2SeqGenerator and SequenceToTextConverter', 'review the get_s2t_transformer_model_hub API for loading speech-to-text transformer models by name']
```

Usage

```
{'test_load_causal_lm': 'test that load_causal_lm delegates to AutoModelForCausalLM and wraps result in HgCausalLMAdapter', 'test_load_seq2seq_lm': 'test that load_seq2seq_lm delegates to AutoModelForSeq2SeqLM without wrapping in adapter', 'test_load_hg_tokenizer_simple': 'test that load_hg_tokenizer_simple calls AutoTokenizer.from_pretrained and populates vocab_info correctly', 'test_create_hg_model': 'test that create_hg_model wraps causal LM models in HgCausalLMAdapter but leaves seq2seq unwrapped', 'test_get_auto_model_class': 'test that _get_auto_model_class selects the correct Auto class based on model_type or auto-detection'}
```

## File: facebookresearch_fairseq2/tests/integration/models/test_llama.py

Prompts

```
['test that load_causal_lm delegates to AutoModelForCausalLM and wraps result in HgCausalLMAdapter', 'test that load_seq2seq_lm delegates to AutoModelForSeq2SeqLM without wrapping in adapter', 'test that load_hg_tokenizer_simple calls AutoTokenizer.from_pretrained and populates vocab_info correctly', 'test that create_hg_model wraps causal LM models in HgCausalLMAdapter but leaves seq2seq unwrapped', 'test that _get_auto_model_class selects the correct Auto class based on model_type or auto-detection', 'test the LLaMA model state dict round-trip conversion using convert_to_ref_llama_state_dict and convert_llama_state_dict', 'create an LLaMA model instance using LLaMAFactory with a resolved LLaMAConfig such as llama2_7b', 'convert a fairseq2 LLaMA model state dict to the reference LLaMA checkpoint format', 'convert a reference LLaMA state dict back to the fairseq2 internal format using the model config', 'get an LLaMA model config by name such as llama2_7b using get_config with a dependency resolver', 'test loading the nllb-200_dense_distill_600m model and translating an English sentence to German', 'test the NLLB tokenizer special tokens in source and target encoding modes', 'run English to German text translation using BeamSearchSeq2SeqGenerator and TextTranslator', 'test that long input text raises ValueError and can be handled with max_source_len', 'review the NLLB tokenizer create_encoder in source mode versus target mode token output', 'test loading the s2t_transformer_mustc_st_jt_m model and verify German translation output', 'test loading the s2t_conformer_covost_st_en_de model and verify German translation output', 'test loading the s2t_conformer_covost_st_en_de_rel_pos model with relative positional encoding', 'run translation assertion by converting fbank features to text using BeamSearchSeq2SeqGenerator and SequenceToTextConverter', 'review the get_s2t_transformer_model_hub API for loading speech-to-text transformer models by name']
```

Usage

```
{'test_convert_to_ref_checkpoint': 'test the LLaMA model state dict round-trip conversion using convert_to_ref_llama_state_dict and convert_llama_state_dict', 'create_llama_model': 'create an LLaMA model instance using LLaMAFactory with a resolved LLaMAConfig such as llama2_7b', 'convert_to_ref_llama_state_dict': 'convert a fairseq2 LLaMA model state dict to the reference LLaMA checkpoint format', 'convert_llama_state_dict': 'convert a reference LLaMA state dict back to the fairseq2 internal format using the model config', 'get_llama_config': 'get an LLaMA model config by name such as llama2_7b using get_config with a dependency resolver'}
```

## File: facebookresearch_fairseq2/tests/integration/models/test_nllb.py

Prompts

```
['test that load_causal_lm delegates to AutoModelForCausalLM and wraps result in HgCausalLMAdapter', 'test that load_seq2seq_lm delegates to AutoModelForSeq2SeqLM without wrapping in adapter', 'test that load_hg_tokenizer_simple calls AutoTokenizer.from_pretrained and populates vocab_info correctly', 'test that create_hg_model wraps causal LM models in HgCausalLMAdapter but leaves seq2seq unwrapped', 'test that _get_auto_model_class selects the correct Auto class based on model_type or auto-detection', 'test the LLaMA model state dict round-trip conversion using convert_to_ref_llama_state_dict and convert_llama_state_dict', 'create an LLaMA model instance using LLaMAFactory with a resolved LLaMAConfig such as llama2_7b', 'convert a fairseq2 LLaMA model state dict to the reference LLaMA checkpoint format', 'convert a reference LLaMA state dict back to the fairseq2 internal format using the model config', 'get an LLaMA model config by name such as llama2_7b using get_config with a dependency resolver', 'test loading the nllb-200_dense_distill_600m model and translating an English sentence to German', 'test the NLLB tokenizer special tokens in source and target encoding modes', 'run English to German text translation using BeamSearchSeq2SeqGenerator and TextTranslator', 'test that long input text raises ValueError and can be handled with max_source_len', 'review the NLLB tokenizer create_encoder in source mode versus target mode token output', 'test loading the s2t_transformer_mustc_st_jt_m model and verify German translation output', 'test loading the s2t_conformer_covost_st_en_de model and verify German translation output', 'test loading the s2t_conformer_covost_st_en_de_rel_pos model with relative positional encoding', 'run translation assertion by converting fbank features to text using BeamSearchSeq2SeqGenerator and SequenceToTextConverter', 'review the get_s2t_transformer_model_hub API for loading speech-to-text transformer models by name']
```

Usage

```
{'test_load_nllb_model_and_translate': 'test loading the nllb-200_dense_distill_600m model and translating an English sentence to German', 'test_nllb_tokenizer_special_tokens': 'test the NLLB tokenizer special tokens in source and target encoding modes', 'run_text_translation_with_beam_search': 'run English to German text translation using BeamSearchSeq2SeqGenerator and TextTranslator', 'test_translation_truncation_handling': 'test that long input text raises ValueError and can be handled with max_source_len', 'review_nllb_tokenizer_encoder_modes': 'review the NLLB tokenizer create_encoder in source mode versus target mode token output'}
```

## File: facebookresearch_fairseq2/tests/integration/models/test_s2t_transformer.py

Prompts

```
['test that load_causal_lm delegates to AutoModelForCausalLM and wraps result in HgCausalLMAdapter', 'test that load_seq2seq_lm delegates to AutoModelForSeq2SeqLM without wrapping in adapter', 'test that load_hg_tokenizer_simple calls AutoTokenizer.from_pretrained and populates vocab_info correctly', 'test that create_hg_model wraps causal LM models in HgCausalLMAdapter but leaves seq2seq unwrapped', 'test that _get_auto_model_class selects the correct Auto class based on model_type or auto-detection', 'test the LLaMA model state dict round-trip conversion using convert_to_ref_llama_state_dict and convert_llama_state_dict', 'create an LLaMA model instance using LLaMAFactory with a resolved LLaMAConfig such as llama2_7b', 'convert a fairseq2 LLaMA model state dict to the reference LLaMA checkpoint format', 'convert a reference LLaMA state dict back to the fairseq2 internal format using the model config', 'get an LLaMA model config by name such as llama2_7b using get_config with a dependency resolver', 'test loading the nllb-200_dense_distill_600m model and translating an English sentence to German', 'test the NLLB tokenizer special tokens in source and target encoding modes', 'run English to German text translation using BeamSearchSeq2SeqGenerator and TextTranslator', 'test that long input text raises ValueError and can be handled with max_source_len', 'review the NLLB tokenizer create_encoder in source mode versus target mode token output', 'test loading the s2t_transformer_mustc_st_jt_m model and verify German translation output', 'test loading the s2t_conformer_covost_st_en_de model and verify German translation output', 'test loading the s2t_conformer_covost_st_en_de_rel_pos model with relative positional encoding', 'run translation assertion by converting fbank features to text using BeamSearchSeq2SeqGenerator and SequenceToTextConverter', 'review the get_s2t_transformer_model_hub API for loading speech-to-text transformer models by name']
```

Usage

```
{'test_s2t_transformer_mustc_st_jt_m': 'test loading the s2t_transformer_mustc_st_jt_m model and verify German translation output', 'test_s2t_conformer_covost_st_en_de': 'test loading the s2t_conformer_covost_st_en_de model and verify German translation output', 'test_s2t_conformer_rel_pos_covost_st_en_de': 'test loading the s2t_conformer_covost_st_en_de_rel_pos model with relative positional encoding', 'run_assert_translation': 'run translation assertion by converting fbank features to text using BeamSearchSeq2SeqGenerator and SequenceToTextConverter', 'review_get_s2t_transformer_model_hub': 'review the get_s2t_transformer_model_hub API for loading speech-to-text transformer models by name'}
```

