# Agent Python Tools

- repo: facebookresearch/bio-lm
- repo_uri: https://github.com/facebookresearch/bio-lm

## File: facebookresearch_bio-lm/preprocessing/preprocess_i2b2_2010_ner.py

Prompts

```
['run the i2b2 2010 NER preprocessing script with beth, partners, test, and task directory arguments', 'parse an i2b2 concept annotation string into a dictionary with type, span, and concept fields', 'build a BIO label vocabulary from concept annotation files across multiple dataset directories', 'reformat clinical text and concept files into BIO-labeled token sequences for NER training', 'review the main preprocessing pipeline that splits datasets into train, dev, and test splits', 'run the i2b2 2012 NER preprocessing script with --raw_data_dir and --task_dir arguments to generate CONLL files', 'read an i2b2 XML file and extract character-level BIO event labels from CDATA text and EVENT tags', 'merge character-level text and BIO labels into word-level sequences for NER training data', 'reprocess event labels from XML folders into train and dev CONLL-formatted text splits by patient', 'generate train dev and test CONLL files from i2b2 2012 NER raw XML data directories', 'run the CLI to preprocess i2b2 2014 NER XML files into CONLL format for train dev and test splits', 'reprocess PHI and entity labels from XML folders into train and dev CONLL text splits']
```

Usage

```
{'run_preprocess_i2b2_2010_ner': 'run the i2b2 2010 NER preprocessing script with beth, partners, test, and task directory arguments', 'process_concept': 'parse an i2b2 concept annotation string into a dictionary with type, span, and concept fields', 'build_label_vocab': 'build a BIO label vocabulary from concept annotation files across multiple dataset directories', 'reformatter': 'reformat clinical text and concept files into BIO-labeled token sequences for NER training', 'review_main': 'review the main preprocessing pipeline that splits datasets into train, dev, and test splits'}
```

## File: facebookresearch_bio-lm/preprocessing/preprocess_i2b2_2012_ner.py

Prompts

```
['run the i2b2 2010 NER preprocessing script with beth, partners, test, and task directory arguments', 'parse an i2b2 concept annotation string into a dictionary with type, span, and concept fields', 'build a BIO label vocabulary from concept annotation files across multiple dataset directories', 'reformat clinical text and concept files into BIO-labeled token sequences for NER training', 'review the main preprocessing pipeline that splits datasets into train, dev, and test splits', 'run the i2b2 2012 NER preprocessing script with --raw_data_dir and --task_dir arguments to generate CONLL files', 'read an i2b2 XML file and extract character-level BIO event labels from CDATA text and EVENT tags', 'merge character-level text and BIO labels into word-level sequences for NER training data', 'reprocess event labels from XML folders into train and dev CONLL-formatted text splits by patient', 'generate train dev and test CONLL files from i2b2 2012 NER raw XML data directories', 'run the CLI to preprocess i2b2 2014 NER XML files into CONLL format for train dev and test splits', 'reprocess PHI and entity labels from XML folders into train and dev CONLL text splits']
```

Usage

```
{'run_preprocess_i2b2_ner': 'run the i2b2 2012 NER preprocessing script with --raw_data_dir and --task_dir arguments to generate CONLL files', 'read_xml_file': 'read an i2b2 XML file and extract character-level BIO event labels from CDATA text and EVENT tags', 'merge_into_words': 'merge character-level text and BIO labels into word-level sequences for NER training data', 'reprocess_event_labels': 'reprocess event labels from XML folders into train and dev CONLL-formatted text splits by patient', 'main': 'generate train dev and test CONLL files from i2b2 2012 NER raw XML data directories'}
```

## File: facebookresearch_bio-lm/preprocessing/preprocess_i2b2_2014_ner.py

Prompts

```
['run the i2b2 2010 NER preprocessing script with beth, partners, test, and task directory arguments', 'parse an i2b2 concept annotation string into a dictionary with type, span, and concept fields', 'build a BIO label vocabulary from concept annotation files across multiple dataset directories', 'reformat clinical text and concept files into BIO-labeled token sequences for NER training', 'review the main preprocessing pipeline that splits datasets into train, dev, and test splits', 'run the i2b2 2012 NER preprocessing script with --raw_data_dir and --task_dir arguments to generate CONLL files', 'read an i2b2 XML file and extract character-level BIO event labels from CDATA text and EVENT tags', 'merge character-level text and BIO labels into word-level sequences for NER training data', 'reprocess event labels from XML folders into train and dev CONLL-formatted text splits by patient', 'generate train dev and test CONLL files from i2b2 2012 NER raw XML data directories', 'run the CLI to preprocess i2b2 2014 NER XML files into CONLL format for train dev and test splits', 'reprocess PHI and entity labels from XML folders into train and dev CONLL text splits']
```

Usage

```
{'run_preprocess_i2b2_2014_ner_cli': 'run the CLI to preprocess i2b2 2014 NER XML files into CONLL format for train dev and test splits', 'read_xml_file': 'read an i2b2 XML file and extract character-level text and BIO entity labels from tagged spans', 'merge_into_words': 'merge character-level text and labels into word-level sequences for NER tokenization', 'reprocess_phi_labels': 'reprocess PHI and entity labels from XML folders into train and dev CONLL text splits', 'main': 'run the full preprocessing pipeline to generate train dev and test CONLL files from i2b2 XML directories'}
```

