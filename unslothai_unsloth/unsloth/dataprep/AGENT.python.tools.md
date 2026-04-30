# Agent Python Tools

- repo: unslothai/unsloth
- repo_uri: https://github.com/unslothai/unsloth.git

## File: unslothai_unsloth/unsloth/dataprep/raw_text.py

Prompts

```
['build a RawTextDataLoader to load text files and create tokenized datasets for causal language modeling', 'create a causal language modeling dataset from tokenized text chunks with input_ids, attention_mask, and labels', 'test the smart_chunk_text method to split text into overlapping tokenized chunks with configurable stride', 'review the TextPreprocessor clean_text method to remove unwanted characters and normalize whitespace', 'summarize the TextPreprocessor validate_dataset method to check for empty samples, repeated content, and encoding issues', 'create a SyntheticDataKit instance to load a language model with vLLM for synthetic data generation', 'build a SyntheticDataKit instance from pretrained model using from_pretrained factory method', 'run qa generation preparation that creates output directories and writes synthetic data config yaml', 'run data chunking that splits a text file into token-sized chunks based on max_seq_length', 'test the vLLM server status by checking the http://localhost:8000/metrics endpoint']
```

Usage

```
{'build_raw_text_dataset': 'build a RawTextDataLoader to load text files and create tokenized datasets for causal language modeling', 'create_causal_dataset': 'create a causal language modeling dataset from tokenized text chunks with input_ids, attention_mask, and labels', 'test_chunk_text': 'test the smart_chunk_text method to split text into overlapping tokenized chunks with configurable stride', 'review_clean_text': 'review the TextPreprocessor clean_text method to remove unwanted characters and normalize whitespace', 'summarize_validate_dataset': 'summarize the TextPreprocessor validate_dataset method to check for empty samples, repeated content, and encoding issues'}
```

## File: unslothai_unsloth/unsloth/dataprep/synthetic.py

Prompts

```
['build a RawTextDataLoader to load text files and create tokenized datasets for causal language modeling', 'create a causal language modeling dataset from tokenized text chunks with input_ids, attention_mask, and labels', 'test the smart_chunk_text method to split text into overlapping tokenized chunks with configurable stride', 'review the TextPreprocessor clean_text method to remove unwanted characters and normalize whitespace', 'summarize the TextPreprocessor validate_dataset method to check for empty samples, repeated content, and encoding issues', 'create a SyntheticDataKit instance to load a language model with vLLM for synthetic data generation', 'build a SyntheticDataKit instance from pretrained model using from_pretrained factory method', 'run qa generation preparation that creates output directories and writes synthetic data config yaml', 'run data chunking that splits a text file into token-sized chunks based on max_seq_length', 'test the vLLM server status by checking the http://localhost:8000/metrics endpoint']
```

Usage

```
{'create_SyntheticDataKit': 'create a SyntheticDataKit instance to load a language model with vLLM for synthetic data generation', 'build_SyntheticDataKit_from_pretrained': 'build a SyntheticDataKit instance from pretrained model using from_pretrained factory method', 'run_SyntheticDataKit_prepare_qa_generation': 'run qa generation preparation that creates output directories and writes synthetic data config yaml', 'run_SyntheticDataKit_chunk_data': 'run data chunking that splits a text file into token-sized chunks based on max_seq_length', 'test_SyntheticDataKit_check_vllm_status': 'test the vLLM server status by checking the http://localhost:8000/metrics endpoint'}
```

