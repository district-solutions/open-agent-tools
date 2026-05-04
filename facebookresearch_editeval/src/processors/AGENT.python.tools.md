# Agent Python Tools

- repo: facebookresearch/editeval
- repo_uri: https://github.com/facebookresearch/editeval

## File: facebookresearch_editeval/src/processors/fruit.py

Prompts

```
['parse FRUIT dataset TFRecord files into a structured dictionary with inputs, targets, and retrieved documents', 'transform FRUIT indexed input text into plain text and structured context dictionaries with Wikipedia URLs', 'transform FRUIT model output by replacing sentence indices with original text and moving citations to sentence ends', 'extract a dictionary mapping bracket indices to sentences from FRUIT formatted input context strings', 'download and process the FRUIT dataset from GCS into train, dev, and test HuggingFace DatasetDict splits', 'create a JFLEGProcessor with a raw path and call download_and_process to load the JFLEG fluency dataset', 'create an ITERProcessor with a raw path and optional task type then call download_and_process to load IteraTeR data', 'create a TMUGFMProcessor with a raw path and call download_and_process to load and filter the TMU GFM fluency dataset', 'create a PAWSProcessor with a raw path and call download_and_process to load paraphrase pairs from the PAWS dataset', 'create an ASSETProcessor with a raw path and call download_and_process to load the ASSET simplification dataset', 'preprocess a WAFER insertion example by trimming sentences and linearizing wikitext into source and target', 'linearize a single wikitext element into markdown plain or wikipedia format with optional claim replacement', 'trim incomplete sentences from the beginning or end of a text string using spaCy sentencizer', 'download and process the WAFER insertion dataset from FAIR into a HuggingFace DatasetDict', 'merge retrieved documents from one JSONL file into another matching examples by id', 'create a WNCProcessor instance with a raw data path for the WNC neutralization dataset', 'run download_and_process to download the bias corpus and build dev and test datasets', 'review the WNCProcessor init method to understand dataset name, task name, and host link configuration', 'summarize the WNCProcessor class which processes Wikipedia neutralization corpus data into HuggingFace datasets', 'test the download_and_process method to verify it correctly parses TSV files into a DatasetDict']
```

Usage

```
{'parse_FRUIT_tfrecord': 'parse FRUIT dataset TFRecord files into a structured dictionary with inputs, targets, and retrieved documents', 'transform_FRUIT_input': 'transform FRUIT indexed input text into plain text and structured context dictionaries with Wikipedia URLs', 'transform_FRUIT_output': 'transform FRUIT model output by replacing sentence indices with original text and moving citations to sentence ends', 'extract_FRUIT_sentence_dict': 'extract a dictionary mapping bracket indices to sentences from FRUIT formatted input context strings', 'download_FRUIT_dataset': 'download and process the FRUIT dataset from GCS into train, dev, and test HuggingFace DatasetDict splits'}
```

## File: facebookresearch_editeval/src/processors/huggingface_processors.py

Prompts

```
['parse FRUIT dataset TFRecord files into a structured dictionary with inputs, targets, and retrieved documents', 'transform FRUIT indexed input text into plain text and structured context dictionaries with Wikipedia URLs', 'transform FRUIT model output by replacing sentence indices with original text and moving citations to sentence ends', 'extract a dictionary mapping bracket indices to sentences from FRUIT formatted input context strings', 'download and process the FRUIT dataset from GCS into train, dev, and test HuggingFace DatasetDict splits', 'create a JFLEGProcessor with a raw path and call download_and_process to load the JFLEG fluency dataset', 'create an ITERProcessor with a raw path and optional task type then call download_and_process to load IteraTeR data', 'create a TMUGFMProcessor with a raw path and call download_and_process to load and filter the TMU GFM fluency dataset', 'create a PAWSProcessor with a raw path and call download_and_process to load paraphrase pairs from the PAWS dataset', 'create an ASSETProcessor with a raw path and call download_and_process to load the ASSET simplification dataset', 'preprocess a WAFER insertion example by trimming sentences and linearizing wikitext into source and target', 'linearize a single wikitext element into markdown plain or wikipedia format with optional claim replacement', 'trim incomplete sentences from the beginning or end of a text string using spaCy sentencizer', 'download and process the WAFER insertion dataset from FAIR into a HuggingFace DatasetDict', 'merge retrieved documents from one JSONL file into another matching examples by id', 'create a WNCProcessor instance with a raw data path for the WNC neutralization dataset', 'run download_and_process to download the bias corpus and build dev and test datasets', 'review the WNCProcessor init method to understand dataset name, task name, and host link configuration', 'summarize the WNCProcessor class which processes Wikipedia neutralization corpus data into HuggingFace datasets', 'test the download_and_process method to verify it correctly parses TSV files into a DatasetDict']
```

Usage

```
{'download_jfleg_dataset': 'create a JFLEGProcessor with a raw path and call download_and_process to load the JFLEG fluency dataset', 'download_iter_dataset': 'create an ITERProcessor with a raw path and optional task type then call download_and_process to load IteraTeR data', 'download_tmu_gfm_dataset': 'create a TMUGFMProcessor with a raw path and call download_and_process to load and filter the TMU GFM fluency dataset', 'download_paws_dataset': 'create a PAWSProcessor with a raw path and call download_and_process to load paraphrase pairs from the PAWS dataset', 'download_asset_dataset': 'create an ASSETProcessor with a raw path and call download_and_process to load the ASSET simplification dataset'}
```

## File: facebookresearch_editeval/src/processors/wafer_insert.py

Prompts

```
['parse FRUIT dataset TFRecord files into a structured dictionary with inputs, targets, and retrieved documents', 'transform FRUIT indexed input text into plain text and structured context dictionaries with Wikipedia URLs', 'transform FRUIT model output by replacing sentence indices with original text and moving citations to sentence ends', 'extract a dictionary mapping bracket indices to sentences from FRUIT formatted input context strings', 'download and process the FRUIT dataset from GCS into train, dev, and test HuggingFace DatasetDict splits', 'create a JFLEGProcessor with a raw path and call download_and_process to load the JFLEG fluency dataset', 'create an ITERProcessor with a raw path and optional task type then call download_and_process to load IteraTeR data', 'create a TMUGFMProcessor with a raw path and call download_and_process to load and filter the TMU GFM fluency dataset', 'create a PAWSProcessor with a raw path and call download_and_process to load paraphrase pairs from the PAWS dataset', 'create an ASSETProcessor with a raw path and call download_and_process to load the ASSET simplification dataset', 'preprocess a WAFER insertion example by trimming sentences and linearizing wikitext into source and target', 'linearize a single wikitext element into markdown plain or wikipedia format with optional claim replacement', 'trim incomplete sentences from the beginning or end of a text string using spaCy sentencizer', 'download and process the WAFER insertion dataset from FAIR into a HuggingFace DatasetDict', 'merge retrieved documents from one JSONL file into another matching examples by id', 'create a WNCProcessor instance with a raw data path for the WNC neutralization dataset', 'run download_and_process to download the bias corpus and build dev and test datasets', 'review the WNCProcessor init method to understand dataset name, task name, and host link configuration', 'summarize the WNCProcessor class which processes Wikipedia neutralization corpus data into HuggingFace datasets', 'test the download_and_process method to verify it correctly parses TSV files into a DatasetDict']
```

Usage

```
{'preprocess_wafer_example': 'preprocess a WAFER insertion example by trimming sentences and linearizing wikitext into source and target', 'linearize_element_wikitext': 'linearize a single wikitext element into markdown plain or wikipedia format with optional claim replacement', 'trim_text_incomplete_sentences': 'trim incomplete sentences from the beginning or end of a text string using spaCy sentencizer', 'download_and_process_wafer_dataset': 'download and process the WAFER insertion dataset from FAIR into a HuggingFace DatasetDict', 'add_retrieved_documents_to_jsonl': 'merge retrieved documents from one JSONL file into another matching examples by id'}
```

## File: facebookresearch_editeval/src/processors/wnc.py

Prompts

```
['parse FRUIT dataset TFRecord files into a structured dictionary with inputs, targets, and retrieved documents', 'transform FRUIT indexed input text into plain text and structured context dictionaries with Wikipedia URLs', 'transform FRUIT model output by replacing sentence indices with original text and moving citations to sentence ends', 'extract a dictionary mapping bracket indices to sentences from FRUIT formatted input context strings', 'download and process the FRUIT dataset from GCS into train, dev, and test HuggingFace DatasetDict splits', 'create a JFLEGProcessor with a raw path and call download_and_process to load the JFLEG fluency dataset', 'create an ITERProcessor with a raw path and optional task type then call download_and_process to load IteraTeR data', 'create a TMUGFMProcessor with a raw path and call download_and_process to load and filter the TMU GFM fluency dataset', 'create a PAWSProcessor with a raw path and call download_and_process to load paraphrase pairs from the PAWS dataset', 'create an ASSETProcessor with a raw path and call download_and_process to load the ASSET simplification dataset', 'preprocess a WAFER insertion example by trimming sentences and linearizing wikitext into source and target', 'linearize a single wikitext element into markdown plain or wikipedia format with optional claim replacement', 'trim incomplete sentences from the beginning or end of a text string using spaCy sentencizer', 'download and process the WAFER insertion dataset from FAIR into a HuggingFace DatasetDict', 'merge retrieved documents from one JSONL file into another matching examples by id', 'create a WNCProcessor instance with a raw data path for the WNC neutralization dataset', 'run download_and_process to download the bias corpus and build dev and test datasets', 'review the WNCProcessor init method to understand dataset name, task name, and host link configuration', 'summarize the WNCProcessor class which processes Wikipedia neutralization corpus data into HuggingFace datasets', 'test the download_and_process method to verify it correctly parses TSV files into a DatasetDict']
```

Usage

```
{'create_WNCProcessor': 'create a WNCProcessor instance with a raw data path for the WNC neutralization dataset', 'run_download_and_process': 'run download_and_process to download the bias corpus and build dev and test datasets', 'review_WNCProcessor_init': 'review the WNCProcessor init method to understand dataset name, task name, and host link configuration', 'summarize_WNCProcessor': 'summarize the WNCProcessor class which processes Wikipedia neutralization corpus data into HuggingFace datasets', 'test_download_and_process': 'test the download_and_process method to verify it correctly parses TSV files into a DatasetDict'}
```

