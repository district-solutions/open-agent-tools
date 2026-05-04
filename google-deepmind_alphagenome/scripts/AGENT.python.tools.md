# Agent Python Tools

- repo: google-deepmind/alphagenome
- repo_uri: https://github.com/google-deepmind/alphagenome

## File: google-deepmind_alphagenome/scripts/process_gtf.py

Prompts

```
['run the script to convert a GTF file into a feather format output file', 'run generate_splice_sites to extract tissue-agnostic splice start and end sites from a GTF DataFrame', 'run generate_gtf to parse a local or remote GTF file into a pandas DataFrame with gene_id_nopatch', 'refactor generate_splice_sites to support additional splice site filtering criteria beyond tissue-agnostic extraction', 'review the main function to understand GTF to feather conversion and optional splice site generation workflow', 'test the process_gtf module by parsing a GTF file and validating the output DataFrame', 'test generate_splice_sites by verifying exon boundary start and end positions from a processed GTF DataFrame', 'run all ProcessGtfTest unit tests using absltest to validate GTF parsing and splice site generation', 'review the ProcessGtfTest class and its test_process_gtf and test_generate_splice_sites test methods', 'refactor the ProcessGtfTest class to add parameterized test cases for multiple GTF input scenarios']
```

Usage

```
{'run_process_gtf': 'run the script to convert a GTF file into a feather format output file', 'run_generate_splice_sites': 'run generate_splice_sites to extract tissue-agnostic splice start and end sites from a GTF DataFrame', 'run_generate_gtf': 'run generate_gtf to parse a local or remote GTF file into a pandas DataFrame with gene_id_nopatch', 'refactor_generate_splice_sites': 'refactor generate_splice_sites to support additional splice site filtering criteria beyond tissue-agnostic extraction', 'review_main': 'review the main function to understand GTF to feather conversion and optional splice site generation workflow'}
```

## File: google-deepmind_alphagenome/scripts/process_gtf_test.py

Prompts

```
['run the script to convert a GTF file into a feather format output file', 'run generate_splice_sites to extract tissue-agnostic splice start and end sites from a GTF DataFrame', 'run generate_gtf to parse a local or remote GTF file into a pandas DataFrame with gene_id_nopatch', 'refactor generate_splice_sites to support additional splice site filtering criteria beyond tissue-agnostic extraction', 'review the main function to understand GTF to feather conversion and optional splice site generation workflow', 'test the process_gtf module by parsing a GTF file and validating the output DataFrame', 'test generate_splice_sites by verifying exon boundary start and end positions from a processed GTF DataFrame', 'run all ProcessGtfTest unit tests using absltest to validate GTF parsing and splice site generation', 'review the ProcessGtfTest class and its test_process_gtf and test_generate_splice_sites test methods', 'refactor the ProcessGtfTest class to add parameterized test cases for multiple GTF input scenarios']
```

Usage

```
{'test_process_gtf': 'test the process_gtf module by parsing a GTF file and validating the output DataFrame', 'test_generate_splice_sites': 'test generate_splice_sites by verifying exon boundary start and end positions from a processed GTF DataFrame', 'run_process_gtf_tests': 'run all ProcessGtfTest unit tests using absltest to validate GTF parsing and splice site generation', 'review_process_gtf_test': 'review the ProcessGtfTest class and its test_process_gtf and test_generate_splice_sites test methods', 'refactor_process_gtf_test': 'refactor the ProcessGtfTest class to add parameterized test cases for multiple GTF input scenarios'}
```

