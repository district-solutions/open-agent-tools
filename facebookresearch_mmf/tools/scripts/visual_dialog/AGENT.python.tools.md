# Agent Python Tools

- repo: facebookresearch/mmf
- repo_uri: https://github.com/facebookresearch/mmf

## File: facebookresearch_mmf/tools/scripts/visual_dialog/build_imdb.py

Prompts

```
['build an IMDB JSON file from VisDial dataset JSONs and COCO image features', 'run the IMDBBuilder CLI to build a VisDial IMDB with custom output path and dataset split', 'create a mapping from image IDs to .npy feature file paths in the COCO directory', 'tokenize VisDial questions, answers, and captions using the MMF tokenize utility', 'parse VisDial dialogs by attaching image feature paths and tokenized captions to each dialog', 'run the script to extract vocabulary from Visual Dialog JSON data files', 'run the ExtractVisdialVocabulary CLI with input_files and out_dir arguments', 'create a vocabulary file from VisDial questions, answers, and dialog captions', 'extract questions, answers, and dialog captions from VisDial JSON input files', 'refactor the get_text method to extract custom text fields from VisDial JSON']
```

Usage

```
{'build_imdb_for_visdial': 'build an IMDB JSON file from VisDial dataset JSONs and COCO image features', 'run_imdb_builder_cli': 'run the IMDBBuilder CLI to build a VisDial IMDB with custom output path and dataset split', 'create_id_to_path_mapping': 'create a mapping from image IDs to .npy feature file paths in the COCO directory', 'tokenize_visdial_sentences': 'tokenize VisDial questions, answers, and captions using the MMF tokenize utility', 'parse_dialogs_with_features': 'parse VisDial dialogs by attaching image feature paths and tokenized captions to each dialog'}
```

## File: facebookresearch_mmf/tools/scripts/visual_dialog/extract_vocabulary.py

Prompts

```
['build an IMDB JSON file from VisDial dataset JSONs and COCO image features', 'run the IMDBBuilder CLI to build a VisDial IMDB with custom output path and dataset split', 'create a mapping from image IDs to .npy feature file paths in the COCO directory', 'tokenize VisDial questions, answers, and captions using the MMF tokenize utility', 'parse VisDial dialogs by attaching image feature paths and tokenized captions to each dialog', 'run the script to extract vocabulary from Visual Dialog JSON data files', 'run the ExtractVisdialVocabulary CLI with input_files and out_dir arguments', 'create a vocabulary file from VisDial questions, answers, and dialog captions', 'extract questions, answers, and dialog captions from VisDial JSON input files', 'refactor the get_text method to extract custom text fields from VisDial JSON']
```

Usage

```
{'run_extract_visdial_vocabulary': 'run the script to extract vocabulary from Visual Dialog JSON data files', 'run_extract_vocabulary_cli': 'run the ExtractVisdialVocabulary CLI with input_files and out_dir arguments', 'create_vocabulary_from_visdial': 'create a vocabulary file from VisDial questions, answers, and dialog captions', 'extract_text_from_visdial_json': 'extract questions, answers, and dialog captions from VisDial JSON input files', 'refactor_get_text_override': 'refactor the get_text method to extract custom text fields from VisDial JSON'}
```

