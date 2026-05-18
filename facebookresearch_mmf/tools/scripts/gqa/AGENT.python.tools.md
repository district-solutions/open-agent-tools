# Agent Python Tools

- repo: facebookresearch/mmf
- repo_uri: https://github.com/facebookresearch/mmf

## File: facebookresearch_mmf/tools/scripts/gqa/convert_gqa_to_vqa.py

Prompts

```
['convert a GQA dataset directory into VQA format with image features and question-answer vocabularies', 'merge all partial GQA train question JSON files into a single train_all_questions.json file', 'extract bounding box features from GQA object HDF5 files and save as per-image numpy arrays', 'extract spatial pyramid features from GQA spatial HDF5 files and save as reshaped numpy arrays', 'parse a GQA questions JSON file into an IMDB array with tokenized questions and answer metadata', 'run the ExtractVocabulary CLI to extract vocabulary from GQA question JSON files', 'extract a sorted vocabulary from VQA question JSON files with minimum frequency filtering', 'save the extracted vocabulary words to a text file in the output directory', 'override the get_text method in a subclass to extract custom text from input files', 'tokenize question texts and count word frequencies using Counter to build vocabulary']
```

Usage

```
{'convert_gqa_to_vqa': 'convert a GQA dataset directory into VQA format with image features and question-answer vocabularies', 'merge_train_questions': 'merge all partial GQA train question JSON files into a single train_all_questions.json file', 'extract_bbox_features': 'extract bounding box features from GQA object HDF5 files and save as per-image numpy arrays', 'extract_spatial_features': 'extract spatial pyramid features from GQA spatial HDF5 files and save as reshaped numpy arrays', 'get_imdb': 'parse a GQA questions JSON file into an IMDB array with tokenized questions and answer metadata'}
```

## File: facebookresearch_mmf/tools/scripts/gqa/extract_vocabulary.py

Prompts

```
['convert a GQA dataset directory into VQA format with image features and question-answer vocabularies', 'merge all partial GQA train question JSON files into a single train_all_questions.json file', 'extract bounding box features from GQA object HDF5 files and save as per-image numpy arrays', 'extract spatial pyramid features from GQA spatial HDF5 files and save as reshaped numpy arrays', 'parse a GQA questions JSON file into an IMDB array with tokenized questions and answer metadata', 'run the ExtractVocabulary CLI to extract vocabulary from GQA question JSON files', 'extract a sorted vocabulary from VQA question JSON files with minimum frequency filtering', 'save the extracted vocabulary words to a text file in the output directory', 'override the get_text method in a subclass to extract custom text from input files', 'tokenize question texts and count word frequencies using Counter to build vocabulary']
```

Usage

```
{'run_extract_vocabulary': 'run the ExtractVocabulary CLI to extract vocabulary from GQA question JSON files', 'extract_vocabulary_from_questions': 'extract a sorted vocabulary from VQA question JSON files with minimum frequency filtering', 'save_vocabulary_to_file': 'save the extracted vocabulary words to a text file in the output directory', 'override_get_text': 'override the get_text method in a subclass to extract custom text from input files', 'tokenize_and_count_words': 'tokenize question texts and count word frequencies using Counter to build vocabulary'}
```

