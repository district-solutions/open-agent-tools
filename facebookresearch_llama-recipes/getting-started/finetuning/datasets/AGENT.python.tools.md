# Agent Python Tools

- repo: facebookresearch/llama-recipes
- repo_uri: https://github.com/facebookresearch/llama-recipes.git

## File: facebookresearch_llama-recipes/getting-started/finetuning/datasets/custom_dataset.py

Prompts

```
['tokenize a dialog list with user and assistant roles into input_ids and labels for LLM fine-tuning', 'mask a target token sequence within a label list by replacing matches with -100 values', 'load the OpenAssistant oasst1 dataset, build conversation threads, and tokenize them for fine-tuning', 'build conversation threads from the oasst1 dataset by following parent-child message relationships', 'convert a flat message thread into a dialog list alternating user and assistant roles', 'tokenize a batch of multimodal dialogs with images and mask prompt headers for Llama 3 fine-tuning', 'load and split the OCRVQA dataset from HuggingFaceM4/the_cauldron for train or test use', 'create a data collator that assembles OCR VQA samples into tokenized batches with masked labels', 'get an OCRVQADataCollator instance configured with a given processor for multimodal fine-tuning', 'check if a system or user prompt header token sequence exists in a token list', 'tokenize a chat dialog using a Llama 3 tokenizer with proper label masking for system and user prompts', 'tokenize a question-answer pair with document context into a Llama 3 chat format for RAG fine-tuning', 'load a JSON dataset, split it, and tokenize all samples using raft_tokenize for Llama 3 fine-tuning', 'check if a system or user prompt header token sequence exists within a given token list', 'replace all occurrences of a target 3-token sequence with -100 ignore tokens in a label sequence']
```

Usage

```
{'tokenize_dialog_for_finetuning': 'tokenize a dialog list with user and assistant roles into input_ids and labels for LLM fine-tuning', 'mask_target_tokens_in_labels': 'mask a target token sequence within a label list by replacing matches with -100 values', 'load_oasst1_custom_dataset': 'load the OpenAssistant oasst1 dataset, build conversation threads, and tokenize them for fine-tuning', 'build_conversation_threads_from_oasst1': 'build conversation threads from the oasst1 dataset by following parent-child message relationships', 'convert_threads_to_dialog_format': 'convert a flat message thread into a dialog list alternating user and assistant roles'}
```

## File: facebookresearch_llama-recipes/getting-started/finetuning/datasets/ocrvqa_dataset.py

Prompts

```
['tokenize a dialog list with user and assistant roles into input_ids and labels for LLM fine-tuning', 'mask a target token sequence within a label list by replacing matches with -100 values', 'load the OpenAssistant oasst1 dataset, build conversation threads, and tokenize them for fine-tuning', 'build conversation threads from the oasst1 dataset by following parent-child message relationships', 'convert a flat message thread into a dialog list alternating user and assistant roles', 'tokenize a batch of multimodal dialogs with images and mask prompt headers for Llama 3 fine-tuning', 'load and split the OCRVQA dataset from HuggingFaceM4/the_cauldron for train or test use', 'create a data collator that assembles OCR VQA samples into tokenized batches with masked labels', 'get an OCRVQADataCollator instance configured with a given processor for multimodal fine-tuning', 'check if a system or user prompt header token sequence exists in a token list', 'tokenize a chat dialog using a Llama 3 tokenizer with proper label masking for system and user prompts', 'tokenize a question-answer pair with document context into a Llama 3 chat format for RAG fine-tuning', 'load a JSON dataset, split it, and tokenize all samples using raft_tokenize for Llama 3 fine-tuning', 'check if a system or user prompt header token sequence exists within a given token list', 'replace all occurrences of a target 3-token sequence with -100 ignore tokens in a label sequence']
```

Usage

```
{'tokenize_dialogs': 'tokenize a batch of multimodal dialogs with images and mask prompt headers for Llama 3 fine-tuning', 'get_custom_dataset': 'load and split the OCRVQA dataset from HuggingFaceM4/the_cauldron for train or test use', 'OCRVQADataCollator': 'create a data collator that assembles OCR VQA samples into tokenized batches with masked labels', 'get_data_collator': 'get an OCRVQADataCollator instance configured with a given processor for multimodal fine-tuning', 'check_header': 'check if a system or user prompt header token sequence exists in a token list'}
```

## File: facebookresearch_llama-recipes/getting-started/finetuning/datasets/raft_dataset.py

Prompts

```
['tokenize a dialog list with user and assistant roles into input_ids and labels for LLM fine-tuning', 'mask a target token sequence within a label list by replacing matches with -100 values', 'load the OpenAssistant oasst1 dataset, build conversation threads, and tokenize them for fine-tuning', 'build conversation threads from the oasst1 dataset by following parent-child message relationships', 'convert a flat message thread into a dialog list alternating user and assistant roles', 'tokenize a batch of multimodal dialogs with images and mask prompt headers for Llama 3 fine-tuning', 'load and split the OCRVQA dataset from HuggingFaceM4/the_cauldron for train or test use', 'create a data collator that assembles OCR VQA samples into tokenized batches with masked labels', 'get an OCRVQADataCollator instance configured with a given processor for multimodal fine-tuning', 'check if a system or user prompt header token sequence exists in a token list', 'tokenize a chat dialog using a Llama 3 tokenizer with proper label masking for system and user prompts', 'tokenize a question-answer pair with document context into a Llama 3 chat format for RAG fine-tuning', 'load a JSON dataset, split it, and tokenize all samples using raft_tokenize for Llama 3 fine-tuning', 'check if a system or user prompt header token sequence exists within a given token list', 'replace all occurrences of a target 3-token sequence with -100 ignore tokens in a label sequence']
```

Usage

```
{'tokenize_dialog_for_llama3': 'tokenize a chat dialog using a Llama 3 tokenizer with proper label masking for system and user prompts', 'raft_tokenize_qa_pair': 'tokenize a question-answer pair with document context into a Llama 3 chat format for RAG fine-tuning', 'get_custom_dataset_from_json': 'load a JSON dataset, split it, and tokenize all samples using raft_tokenize for Llama 3 fine-tuning', 'check_header_in_token_seq': 'check if a system or user prompt header token sequence exists within a given token list', 'replace_target_tokens_with_ignore': 'replace all occurrences of a target 3-token sequence with -100 ignore tokens in a label sequence'}
```

