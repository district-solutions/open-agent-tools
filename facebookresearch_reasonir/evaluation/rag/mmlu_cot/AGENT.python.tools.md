# Agent Python Tools

- repo: facebookresearch/reasonir
- repo_uri: https://github.com/facebookresearch/reasonir

## File: facebookresearch_reasonir/evaluation/rag/mmlu_cot/compute_accuracy.py

Prompts

```
['run the script with a directory path to compute MMLU CoT answer accuracy across JSON result files', 'extract a single letter answer A-J from model output text using the level 1 regex pattern', 'extract a single letter answer A-J from model output text using cascading regex fallback patterns', 'extract an answer from text using the Answer colon pattern as a fallback regex strategy', 'extract the last standalone letter A-J from text as a final fallback extraction method', 'run the MMLU chain-of-thought evaluation script with a specified model and selected subjects', 'run the MMLU RAG-enhanced chain-of-thought evaluation using a retrieval file and concat_k contexts', 'load a vLLM LLM instance with configurable GPU utilization and tensor parallelism', 'load and preprocess the MMLU test and validation datasets from Hugging Face', 'extract a multiple choice answer letter from model-generated text using regex patterns', 'call get_mmlu_group_subjects to extract MMLU task YAML files and return subjects grouped by category', 'review the get_mmlu_group_subjects function that parses lm_eval MMLU task YAML files into category groups', 'refactor get_mmlu_group_subjects to accept a configurable task directory path instead of a hardcoded path', 'summarize the get_mmlu_group_subjects function which maps MMLU subjects to their category groups', 'test the get_mmlu_group_subjects function to verify it correctly parses MMLU YAML task files']
```

Usage

```
{'run_compute_accuracy': 'run the script with a directory path to compute MMLU CoT answer accuracy across JSON result files', 'extract_answer_l1': 'extract a single letter answer A-J from model output text using the level 1 regex pattern', 'extract_answer_l2': 'extract a single letter answer A-J from model output text using cascading regex fallback patterns', 'extract_again': 'extract an answer from text using the Answer colon pattern as a fallback regex strategy', 'extract_final': 'extract the last standalone letter A-J from text as a final fallback extraction method'}
```

## File: facebookresearch_reasonir/evaluation/rag/mmlu_cot/evaluate_from_local_mmlu.py

Prompts

```
['run the script with a directory path to compute MMLU CoT answer accuracy across JSON result files', 'extract a single letter answer A-J from model output text using the level 1 regex pattern', 'extract a single letter answer A-J from model output text using cascading regex fallback patterns', 'extract an answer from text using the Answer colon pattern as a fallback regex strategy', 'extract the last standalone letter A-J from text as a final fallback extraction method', 'run the MMLU chain-of-thought evaluation script with a specified model and selected subjects', 'run the MMLU RAG-enhanced chain-of-thought evaluation using a retrieval file and concat_k contexts', 'load a vLLM LLM instance with configurable GPU utilization and tensor parallelism', 'load and preprocess the MMLU test and validation datasets from Hugging Face', 'extract a multiple choice answer letter from model-generated text using regex patterns', 'call get_mmlu_group_subjects to extract MMLU task YAML files and return subjects grouped by category', 'review the get_mmlu_group_subjects function that parses lm_eval MMLU task YAML files into category groups', 'refactor get_mmlu_group_subjects to accept a configurable task directory path instead of a hardcoded path', 'summarize the get_mmlu_group_subjects function which maps MMLU subjects to their category groups', 'test the get_mmlu_group_subjects function to verify it correctly parses MMLU YAML task files']
```

Usage

```
{'run_MMLU_CoT_evaluation': 'run the MMLU chain-of-thought evaluation script with a specified model and selected subjects', 'run_RAG_CoT_evaluation': 'run the MMLU RAG-enhanced chain-of-thought evaluation using a retrieval file and concat_k contexts', 'load_model_vllm': 'load a vLLM LLM instance with configurable GPU utilization and tensor parallelism', 'load_mmlu_dataset': 'load and preprocess the MMLU test and validation datasets from Hugging Face', 'extract_answer_from_text': 'extract a multiple choice answer letter from model-generated text using regex patterns'}
```

## File: facebookresearch_reasonir/evaluation/rag/mmlu_cot/extract_mmlu_group.py

Prompts

```
['run the script with a directory path to compute MMLU CoT answer accuracy across JSON result files', 'extract a single letter answer A-J from model output text using the level 1 regex pattern', 'extract a single letter answer A-J from model output text using cascading regex fallback patterns', 'extract an answer from text using the Answer colon pattern as a fallback regex strategy', 'extract the last standalone letter A-J from text as a final fallback extraction method', 'run the MMLU chain-of-thought evaluation script with a specified model and selected subjects', 'run the MMLU RAG-enhanced chain-of-thought evaluation using a retrieval file and concat_k contexts', 'load a vLLM LLM instance with configurable GPU utilization and tensor parallelism', 'load and preprocess the MMLU test and validation datasets from Hugging Face', 'extract a multiple choice answer letter from model-generated text using regex patterns', 'call get_mmlu_group_subjects to extract MMLU task YAML files and return subjects grouped by category', 'review the get_mmlu_group_subjects function that parses lm_eval MMLU task YAML files into category groups', 'refactor get_mmlu_group_subjects to accept a configurable task directory path instead of a hardcoded path', 'summarize the get_mmlu_group_subjects function which maps MMLU subjects to their category groups', 'test the get_mmlu_group_subjects function to verify it correctly parses MMLU YAML task files']
```

Usage

```
{'get_mmlu_group_subjects': 'call get_mmlu_group_subjects to extract MMLU task YAML files and return subjects grouped by category', 'review_get_mmlu_group_subjects': 'review the get_mmlu_group_subjects function that parses lm_eval MMLU task YAML files into category groups', 'refactor_get_mmlu_group_subjects': 'refactor get_mmlu_group_subjects to accept a configurable task directory path instead of a hardcoded path', 'summarize_get_mmlu_group_subjects': 'summarize the get_mmlu_group_subjects function which maps MMLU subjects to their category groups', 'test_get_mmlu_group_subjects': 'test the get_mmlu_group_subjects function to verify it correctly parses MMLU YAML task files'}
```

