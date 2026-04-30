# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/evolla/modeling_evolla.py

Prompts

```
['create an EvollaForProteinText2Text model for protein sequence to text generation', 'build an EvollaProteinEncoder that encodes protein input IDs using SaProt embeddings and a sequence compressor resampler', 'run an EvollaModel forward pass with text input IDs, protein sequences, and optional structure and MSA features', 'create an EvollaDecoderLayer with self-attention, MLP, and optional cross-attention adapter for protein-text alignment', 'test EvollaAttention with rotary embeddings and EvollaSequenceAlignerCrossAttention for multimodal fusion', 'build an EvollaModel combining text embeddings, protein encoder, and decoder layers with cross-attention adapters', 'build an EvollaSequenceCompressorResampler that compresses protein representations using learnable latents and cross-attention', 'run EvollaForProteinText2Text generate method to produce text output conditioned on protein input sequences', 'create an EvollaProcessor instance with a protein tokenizer and text tokenizer for multimodal protein-language tasks', 'process a list of protein dictionaries with aa_seq and foldseek keys into tokenized protein input tensors', 'process a list of message lists into tokenized text input tensors using chat template and generation prompt', 'call the EvollaProcessor with proteins and messages_list to get combined protein and text tokenized inputs', 'decode tokenized protein or text outputs back to strings using the underlying tokenizers']
```

Usage

```
{'create_evolla_protein_text_model': 'create an EvollaForProteinText2Text model for protein sequence to text generation', 'build_evolla_protein_encoder': 'build an EvollaProteinEncoder that encodes protein input IDs using SaProt embeddings and a sequence compressor resampler', 'run_evolla_multimodal_forward': 'run an EvollaModel forward pass with text input IDs, protein sequences, and optional structure and MSA features', 'create_evolla_decoder_layer': 'create an EvollaDecoderLayer with self-attention, MLP, and optional cross-attention adapter for protein-text alignment', 'test_evolla_attention_mechanisms': 'test EvollaAttention with rotary embeddings and EvollaSequenceAlignerCrossAttention for multimodal fusion'}
```

## File: huggingface_transformers/src/transformers/models/evolla/modular_evolla.py

Prompts

```
['create an EvollaForProteinText2Text model for protein sequence to text generation', 'build an EvollaProteinEncoder that encodes protein input IDs using SaProt embeddings and a sequence compressor resampler', 'run an EvollaModel forward pass with text input IDs, protein sequences, and optional structure and MSA features', 'create an EvollaDecoderLayer with self-attention, MLP, and optional cross-attention adapter for protein-text alignment', 'test EvollaAttention with rotary embeddings and EvollaSequenceAlignerCrossAttention for multimodal fusion', 'build an EvollaModel combining text embeddings, protein encoder, and decoder layers with cross-attention adapters', 'build an EvollaSequenceCompressorResampler that compresses protein representations using learnable latents and cross-attention', 'run EvollaForProteinText2Text generate method to produce text output conditioned on protein input sequences', 'create an EvollaProcessor instance with a protein tokenizer and text tokenizer for multimodal protein-language tasks', 'process a list of protein dictionaries with aa_seq and foldseek keys into tokenized protein input tensors', 'process a list of message lists into tokenized text input tensors using chat template and generation prompt', 'call the EvollaProcessor with proteins and messages_list to get combined protein and text tokenized inputs', 'decode tokenized protein or text outputs back to strings using the underlying tokenizers']
```

Usage

```
{'create_evolla_protein_text_model': 'create an EvollaForProteinText2Text model for protein sequence text-to-text generation with cross-attention', 'build_evolla_protein_encoder': 'build an EvollaProteinEncoder that encodes protein sequences using SaProt and a sequence compressor resampler', 'build_evolla_model': 'build an EvollaModel combining text embeddings, protein encoder, and decoder layers with cross-attention adapters', 'build_evolla_sequence_compressor': 'build an EvollaSequenceCompressorResampler that compresses protein representations using learnable latents and cross-attention', 'run_evolla_text2text_generate': 'run EvollaForProteinText2Text generate method to produce text output conditioned on protein input sequences'}
```

## File: huggingface_transformers/src/transformers/models/evolla/processing_evolla.py

Prompts

```
['create an EvollaForProteinText2Text model for protein sequence to text generation', 'build an EvollaProteinEncoder that encodes protein input IDs using SaProt embeddings and a sequence compressor resampler', 'run an EvollaModel forward pass with text input IDs, protein sequences, and optional structure and MSA features', 'create an EvollaDecoderLayer with self-attention, MLP, and optional cross-attention adapter for protein-text alignment', 'test EvollaAttention with rotary embeddings and EvollaSequenceAlignerCrossAttention for multimodal fusion', 'build an EvollaModel combining text embeddings, protein encoder, and decoder layers with cross-attention adapters', 'build an EvollaSequenceCompressorResampler that compresses protein representations using learnable latents and cross-attention', 'run EvollaForProteinText2Text generate method to produce text output conditioned on protein input sequences', 'create an EvollaProcessor instance with a protein tokenizer and text tokenizer for multimodal protein-language tasks', 'process a list of protein dictionaries with aa_seq and foldseek keys into tokenized protein input tensors', 'process a list of message lists into tokenized text input tensors using chat template and generation prompt', 'call the EvollaProcessor with proteins and messages_list to get combined protein and text tokenized inputs', 'decode tokenized protein or text outputs back to strings using the underlying tokenizers']
```

Usage

```
{'create_evolla_processor': 'create an EvollaProcessor instance with a protein tokenizer and text tokenizer for multimodal protein-language tasks', 'process_proteins_encode': 'process a list of protein dictionaries with aa_seq and foldseek keys into tokenized protein input tensors', 'process_text_encode': 'process a list of message lists into tokenized text input tensors using chat template and generation prompt', 'call_evolla_processor': 'call the EvollaProcessor with proteins and messages_list to get combined protein and text tokenized inputs', 'decode_evolla_outputs': 'decode tokenized protein or text outputs back to strings using the underlying tokenizers'}
```

