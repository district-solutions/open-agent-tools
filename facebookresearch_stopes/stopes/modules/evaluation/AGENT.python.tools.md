# Agent Python Tools

- repo: facebookresearch/stopes
- repo_uri: https://github.com/facebookresearch/stopes

## File: facebookresearch_stopes/stopes/modules/evaluation/blaser_module.py

Prompts

```
['run the BlaserEvalModule to score machine translation quality using BLASER embeddings', 'create a BlaserEvalConfig dataclass with source, MT, and reference embedding file paths', 'validate BlaserEvalModule output by checking that the score file exists on disk', 'review the BlaserEvalModule requirements method to configure GPU allocation based on config', 'summarize the BlaserEvalModule class that extends StopesModule for BLASER evaluation scoring', 'run the CompareAudiosModule to compare source and target audio pairs from a TSV file and write scores to output', 'create a CompareAudiosConfig dataclass with input file paths, output file, comparator settings, and encoder parameters', 'validate a CompareAudiosConfig to check input file presence, column type consistency, and comparator path or URL availability', 'review the CompareAudiosModule requirements method which returns GPU requirements of one GPU per node', 'test the CompareAudiosModule run method by providing a TSV input file with source and target audio column paths', 'run the GenerateMultiBleuDetokModule to generate BLEU scores for multiple checkpoints and splits', 'run fairseq generate to produce translation output from a checkpoint and binarized data', 'run multi-bleu-detok.perl script to calculate BLEU score from fairseq generate output', 'run process_output_ref_hyp_file to extract reference or hypothesis text from fairseq output', 'run get_checkpoint_files_list_from_checkpoints_dir to list checkpoint files within an epoch range', 'run the SentenceTransformersSimilarityModule to compute LaBSE embedding similarity on a bitext TSV dataset', 'process a pandas DataFrame to compute sentence transformer embeddings and cosine similarity between source and target texts', 'configure the SentenceTransformersSimilarityConfig dataclass with model name, input columns, batch size, and normalization settings', 'normalize a numpy array of embeddings using L2 normalization with configurable epsilon threshold', 'validate that the output TSV file from the similarity module exists on disk']
```

Usage

```
{'run_blaser_evaluation': 'run the BlaserEvalModule to score machine translation quality using BLASER embeddings', 'create_blaser_config': 'create a BlaserEvalConfig dataclass with source, MT, and reference embedding file paths', 'validate_blaser_output': 'validate BlaserEvalModule output by checking that the score file exists on disk', 'review_blaser_requirements': 'review the BlaserEvalModule requirements method to configure GPU allocation based on config', 'summarize_blaser_module': 'summarize the BlaserEvalModule class that extends StopesModule for BLASER evaluation scoring'}
```

## File: facebookresearch_stopes/stopes/modules/evaluation/compare_audio_module.py

Prompts

```
['run the BlaserEvalModule to score machine translation quality using BLASER embeddings', 'create a BlaserEvalConfig dataclass with source, MT, and reference embedding file paths', 'validate BlaserEvalModule output by checking that the score file exists on disk', 'review the BlaserEvalModule requirements method to configure GPU allocation based on config', 'summarize the BlaserEvalModule class that extends StopesModule for BLASER evaluation scoring', 'run the CompareAudiosModule to compare source and target audio pairs from a TSV file and write scores to output', 'create a CompareAudiosConfig dataclass with input file paths, output file, comparator settings, and encoder parameters', 'validate a CompareAudiosConfig to check input file presence, column type consistency, and comparator path or URL availability', 'review the CompareAudiosModule requirements method which returns GPU requirements of one GPU per node', 'test the CompareAudiosModule run method by providing a TSV input file with source and target audio column paths', 'run the GenerateMultiBleuDetokModule to generate BLEU scores for multiple checkpoints and splits', 'run fairseq generate to produce translation output from a checkpoint and binarized data', 'run multi-bleu-detok.perl script to calculate BLEU score from fairseq generate output', 'run process_output_ref_hyp_file to extract reference or hypothesis text from fairseq output', 'run get_checkpoint_files_list_from_checkpoints_dir to list checkpoint files within an epoch range', 'run the SentenceTransformersSimilarityModule to compute LaBSE embedding similarity on a bitext TSV dataset', 'process a pandas DataFrame to compute sentence transformer embeddings and cosine similarity between source and target texts', 'configure the SentenceTransformersSimilarityConfig dataclass with model name, input columns, batch size, and normalization settings', 'normalize a numpy array of embeddings using L2 normalization with configurable epsilon threshold', 'validate that the output TSV file from the similarity module exists on disk']
```

Usage

```
{'run_compare_audio_module': 'run the CompareAudiosModule to compare source and target audio pairs from a TSV file and write scores to output', 'create_compare_audios_config': 'create a CompareAudiosConfig dataclass with input file paths, output file, comparator settings, and encoder parameters', 'validate_inputs_config': 'validate a CompareAudiosConfig to check input file presence, column type consistency, and comparator path or URL availability', 'review_compare_audios_module_requirements': 'review the CompareAudiosModule requirements method which returns GPU requirements of one GPU per node', 'test_compare_audio_pairs': 'test the CompareAudiosModule run method by providing a TSV input file with source and target audio column paths'}
```

## File: facebookresearch_stopes/stopes/modules/evaluation/generate_multi_bleu_detok_module.py

Prompts

```
['run the BlaserEvalModule to score machine translation quality using BLASER embeddings', 'create a BlaserEvalConfig dataclass with source, MT, and reference embedding file paths', 'validate BlaserEvalModule output by checking that the score file exists on disk', 'review the BlaserEvalModule requirements method to configure GPU allocation based on config', 'summarize the BlaserEvalModule class that extends StopesModule for BLASER evaluation scoring', 'run the CompareAudiosModule to compare source and target audio pairs from a TSV file and write scores to output', 'create a CompareAudiosConfig dataclass with input file paths, output file, comparator settings, and encoder parameters', 'validate a CompareAudiosConfig to check input file presence, column type consistency, and comparator path or URL availability', 'review the CompareAudiosModule requirements method which returns GPU requirements of one GPU per node', 'test the CompareAudiosModule run method by providing a TSV input file with source and target audio column paths', 'run the GenerateMultiBleuDetokModule to generate BLEU scores for multiple checkpoints and splits', 'run fairseq generate to produce translation output from a checkpoint and binarized data', 'run multi-bleu-detok.perl script to calculate BLEU score from fairseq generate output', 'run process_output_ref_hyp_file to extract reference or hypothesis text from fairseq output', 'run get_checkpoint_files_list_from_checkpoints_dir to list checkpoint files within an epoch range', 'run the SentenceTransformersSimilarityModule to compute LaBSE embedding similarity on a bitext TSV dataset', 'process a pandas DataFrame to compute sentence transformer embeddings and cosine similarity between source and target texts', 'configure the SentenceTransformersSimilarityConfig dataclass with model name, input columns, batch size, and normalization settings', 'normalize a numpy array of embeddings using L2 normalization with configurable epsilon threshold', 'validate that the output TSV file from the similarity module exists on disk']
```

Usage

```
{'run_GenerateMultiBleuDetokModule': 'run the GenerateMultiBleuDetokModule to generate BLEU scores for multiple checkpoints and splits', 'run_fairseq_generate': 'run fairseq generate to produce translation output from a checkpoint and binarized data', 'run_multi_bleu_detok_call': 'run multi-bleu-detok.perl script to calculate BLEU score from fairseq generate output', 'run_process_output_ref_hyp_file': 'run process_output_ref_hyp_file to extract reference or hypothesis text from fairseq output', 'run_get_checkpoint_files_list_from_checkpoints_dir': 'run get_checkpoint_files_list_from_checkpoints_dir to list checkpoint files within an epoch range'}
```

## File: facebookresearch_stopes/stopes/modules/evaluation/sentence_transformers_similarity.py

Prompts

```
['run the BlaserEvalModule to score machine translation quality using BLASER embeddings', 'create a BlaserEvalConfig dataclass with source, MT, and reference embedding file paths', 'validate BlaserEvalModule output by checking that the score file exists on disk', 'review the BlaserEvalModule requirements method to configure GPU allocation based on config', 'summarize the BlaserEvalModule class that extends StopesModule for BLASER evaluation scoring', 'run the CompareAudiosModule to compare source and target audio pairs from a TSV file and write scores to output', 'create a CompareAudiosConfig dataclass with input file paths, output file, comparator settings, and encoder parameters', 'validate a CompareAudiosConfig to check input file presence, column type consistency, and comparator path or URL availability', 'review the CompareAudiosModule requirements method which returns GPU requirements of one GPU per node', 'test the CompareAudiosModule run method by providing a TSV input file with source and target audio column paths', 'run the GenerateMultiBleuDetokModule to generate BLEU scores for multiple checkpoints and splits', 'run fairseq generate to produce translation output from a checkpoint and binarized data', 'run multi-bleu-detok.perl script to calculate BLEU score from fairseq generate output', 'run process_output_ref_hyp_file to extract reference or hypothesis text from fairseq output', 'run get_checkpoint_files_list_from_checkpoints_dir to list checkpoint files within an epoch range', 'run the SentenceTransformersSimilarityModule to compute LaBSE embedding similarity on a bitext TSV dataset', 'process a pandas DataFrame to compute sentence transformer embeddings and cosine similarity between source and target texts', 'configure the SentenceTransformersSimilarityConfig dataclass with model name, input columns, batch size, and normalization settings', 'normalize a numpy array of embeddings using L2 normalization with configurable epsilon threshold', 'validate that the output TSV file from the similarity module exists on disk']
```

Usage

```
{'run_similarity_module': 'run the SentenceTransformersSimilarityModule to compute LaBSE embedding similarity on a bitext TSV dataset', 'process_dataset_embeddings': 'process a pandas DataFrame to compute sentence transformer embeddings and cosine similarity between source and target texts', 'configure_similarity_module': 'configure the SentenceTransformersSimilarityConfig dataclass with model name, input columns, batch size, and normalization settings', 'normalize_embeddings_l2': 'normalize a numpy array of embeddings using L2 normalization with configurable epsilon threshold', 'validate_similarity_output': 'validate that the output TSV file from the similarity module exists on disk'}
```

