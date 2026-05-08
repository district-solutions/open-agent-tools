# Agent Python Tools

- repo: facebookresearch/fairseq
- repo_uri: https://github.com/facebookresearch/fairseq

## File: facebookresearch_fairseq/examples/emotion_conversion/preprocess/build_translation_manifests.py

Prompts

```
['build parallel TSV and KM emotion translation manifests from EMOV dataset files for fairseq training', 'run fairseq-preprocess on denoising data for a specific emotion language with multilingual denoising task', 'run fairseq-preprocess on translation data converting source emotion to target emotion language pairs', 'deduplicate consecutive repeated tokens in a space-separated keyword sequence string', 'load and validate paired TSV and KM manifest files returning root path and line contents', 'run the CLI tool to generate denoising, translation, hifigan, and fairseq manifests from km and tsv files', 'run verify_dict_size to check if a km file vocabulary size matches a fairseq dict file', 'run verify_files_exist to check if a list of Path objects all exist on disk', 'run run_cmd to execute a shell command via subprocess and capture its output', 'refactor the main function to support additional km files or custom output directory naming', 'run the extract_f0 script to extract fundamental frequency from WAV files using pYAAPT', 'run the extract_f0 script with interpolation enabled to extract smoothed F0 values', 'run the extract_f0 script with a custom number of parallel worker processes', 'extract fundamental frequency from a WAV audio file and save as numpy array', 'process a TSV file of WAV paths in parallel to extract F0 for each audio file', 'run the script to split TSV and KM files into train, valid, and test sets by utterance ID', 'run the train_val_test_split function to partition TSV and KM lines into train, validation, and test subsets', 'create train, validation, and test TSV and KM split files from a paired TSV and KM input', 'refactor the train_val_test_split function to support custom split ratios or additional split sets', 'review the train_val_test_split function logic for utterance ID extraction and sklearn-based partitioning']
```

Usage

```
{'build_emotion_translation_manifests': 'build parallel TSV and KM emotion translation manifests from EMOV dataset files for fairseq training', 'run_denoising_preprocess': 'run fairseq-preprocess on denoising data for a specific emotion language with multilingual denoising task', 'run_translation_preprocess': 'run fairseq-preprocess on translation data converting source emotion to target emotion language pairs', 'dedup_km_tokens': 'deduplicate consecutive repeated tokens in a space-separated keyword sequence string', 'load_tsv_km_files': 'load and validate paired TSV and KM manifest files returning root path and line contents'}
```

## File: facebookresearch_fairseq/examples/emotion_conversion/preprocess/create_core_manifest.py

Prompts

```
['build parallel TSV and KM emotion translation manifests from EMOV dataset files for fairseq training', 'run fairseq-preprocess on denoising data for a specific emotion language with multilingual denoising task', 'run fairseq-preprocess on translation data converting source emotion to target emotion language pairs', 'deduplicate consecutive repeated tokens in a space-separated keyword sequence string', 'load and validate paired TSV and KM manifest files returning root path and line contents', 'run the CLI tool to generate denoising, translation, hifigan, and fairseq manifests from km and tsv files', 'run verify_dict_size to check if a km file vocabulary size matches a fairseq dict file', 'run verify_files_exist to check if a list of Path objects all exist on disk', 'run run_cmd to execute a shell command via subprocess and capture its output', 'refactor the main function to support additional km files or custom output directory naming', 'run the extract_f0 script to extract fundamental frequency from WAV files using pYAAPT', 'run the extract_f0 script with interpolation enabled to extract smoothed F0 values', 'run the extract_f0 script with a custom number of parallel worker processes', 'extract fundamental frequency from a WAV audio file and save as numpy array', 'process a TSV file of WAV paths in parallel to extract F0 for each audio file', 'run the script to split TSV and KM files into train, valid, and test sets by utterance ID', 'run the train_val_test_split function to partition TSV and KM lines into train, validation, and test subsets', 'create train, validation, and test TSV and KM split files from a paired TSV and KM input', 'refactor the train_val_test_split function to support custom split ratios or additional split sets', 'review the train_val_test_split function logic for utterance ID extraction and sklearn-based partitioning']
```

Usage

```
{'run_create_core_manifest': 'run the CLI tool to generate denoising, translation, hifigan, and fairseq manifests from km and tsv files', 'run_verify_dict_size': 'run verify_dict_size to check if a km file vocabulary size matches a fairseq dict file', 'run_verify_files_exist': 'run verify_files_exist to check if a list of Path objects all exist on disk', 'run_run_cmd': 'run run_cmd to execute a shell command via subprocess and capture its output', 'refactor_main': 'refactor the main function to support additional km files or custom output directory naming'}
```

## File: facebookresearch_fairseq/examples/emotion_conversion/preprocess/extract_f0.py

Prompts

```
['build parallel TSV and KM emotion translation manifests from EMOV dataset files for fairseq training', 'run fairseq-preprocess on denoising data for a specific emotion language with multilingual denoising task', 'run fairseq-preprocess on translation data converting source emotion to target emotion language pairs', 'deduplicate consecutive repeated tokens in a space-separated keyword sequence string', 'load and validate paired TSV and KM manifest files returning root path and line contents', 'run the CLI tool to generate denoising, translation, hifigan, and fairseq manifests from km and tsv files', 'run verify_dict_size to check if a km file vocabulary size matches a fairseq dict file', 'run verify_files_exist to check if a list of Path objects all exist on disk', 'run run_cmd to execute a shell command via subprocess and capture its output', 'refactor the main function to support additional km files or custom output directory naming', 'run the extract_f0 script to extract fundamental frequency from WAV files using pYAAPT', 'run the extract_f0 script with interpolation enabled to extract smoothed F0 values', 'run the extract_f0 script with a custom number of parallel worker processes', 'extract fundamental frequency from a WAV audio file and save as numpy array', 'process a TSV file of WAV paths in parallel to extract F0 for each audio file', 'run the script to split TSV and KM files into train, valid, and test sets by utterance ID', 'run the train_val_test_split function to partition TSV and KM lines into train, validation, and test subsets', 'create train, validation, and test TSV and KM split files from a paired TSV and KM input', 'refactor the train_val_test_split function to support custom split ratios or additional split sets', 'review the train_val_test_split function logic for utterance ID extraction and sklearn-based partitioning']
```

Usage

```
{'run_extract_f0_pyaapt': 'run the extract_f0 script to extract fundamental frequency from WAV files using pYAAPT', 'run_extract_f0_interp': 'run the extract_f0 script with interpolation enabled to extract smoothed F0 values', 'run_extract_f0_workers': 'run the extract_f0 script with a custom number of parallel worker processes', 'extract_f0_function': 'extract fundamental frequency from a WAV audio file and save as numpy array', 'main_function': 'process a TSV file of WAV paths in parallel to extract F0 for each audio file'}
```

## File: facebookresearch_fairseq/examples/emotion_conversion/preprocess/split_emov_km_tsv_by_uttid.py

Prompts

```
['build parallel TSV and KM emotion translation manifests from EMOV dataset files for fairseq training', 'run fairseq-preprocess on denoising data for a specific emotion language with multilingual denoising task', 'run fairseq-preprocess on translation data converting source emotion to target emotion language pairs', 'deduplicate consecutive repeated tokens in a space-separated keyword sequence string', 'load and validate paired TSV and KM manifest files returning root path and line contents', 'run the CLI tool to generate denoising, translation, hifigan, and fairseq manifests from km and tsv files', 'run verify_dict_size to check if a km file vocabulary size matches a fairseq dict file', 'run verify_files_exist to check if a list of Path objects all exist on disk', 'run run_cmd to execute a shell command via subprocess and capture its output', 'refactor the main function to support additional km files or custom output directory naming', 'run the extract_f0 script to extract fundamental frequency from WAV files using pYAAPT', 'run the extract_f0 script with interpolation enabled to extract smoothed F0 values', 'run the extract_f0 script with a custom number of parallel worker processes', 'extract fundamental frequency from a WAV audio file and save as numpy array', 'process a TSV file of WAV paths in parallel to extract F0 for each audio file', 'run the script to split TSV and KM files into train, valid, and test sets by utterance ID', 'run the train_val_test_split function to partition TSV and KM lines into train, validation, and test subsets', 'create train, validation, and test TSV and KM split files from a paired TSV and KM input', 'refactor the train_val_test_split function to support custom split ratios or additional split sets', 'review the train_val_test_split function logic for utterance ID extraction and sklearn-based partitioning']
```

Usage

```
{'run_split_tsv_km': 'run the script to split TSV and KM files into train, valid, and test sets by utterance ID', 'run_train_val_test_split': 'run the train_val_test_split function to partition TSV and KM lines into train, validation, and test subsets', 'create_train_valid_test_sets': 'create train, validation, and test TSV and KM split files from a paired TSV and KM input', 'refactor_train_val_test_split': 'refactor the train_val_test_split function to support custom split ratios or additional split sets', 'review_train_val_test_split': 'review the train_val_test_split function logic for utterance ID extraction and sklearn-based partitioning'}
```

