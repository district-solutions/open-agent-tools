# Agent Python Tools

- repo: facebookresearch/neuraldb
- repo_uri: https://github.com/facebookresearch/neuraldb

## File: facebookresearch_neuraldb/dataset-construction/src/ndb_data/dataset_statistics.py

Prompts

```
['run the python module to compute query type and support set size statistics from a JSONL dataset file', 'run the python module to analyze boolean answer distribution across database queries in a JSONL file', 'run the python module to count and print query types from a JSONL dataset file', 'summarize the python get_bool_ans function that returns NULL TRUE or FALSE from a list of answers', 'review the python merge_type function that normalizes query type strings for dataset statistics', 'run the script to sample and filter questions from a JSONL dataset file to an output file', 'run stratified sampling of questions by type and fact count bin across database instances', 'run filtering to drop weak argmin argmax and low fact count questions from the dataset', 'run get_size_bin to classify a question into a bin based on its fact count', 'run the script to print statistics on sampled question bins types and fact counts', 'review the python get_size_bin function that bins queries by fact count into discrete size buckets', 'summarize the python module sampling logic that selects questions across strata until 90 percent of bins are empty', 'review the stratified sampling logic that selects questions across type and size bins until 75% of bins are exhausted', 'review the filtering logic that drops questions by type and fact count using probabilistic thresholds', 'run the full pipeline to sample, filter, and write a subset of questions to an output JSON file', 'run the size binning logic to categorize questions by number of facts into discrete bins', 'run the script to analyze and print question type and complexity distribution statistics from a sampled dataset', 'run the python module to filter and probabilistically drop questions by type and complexity']
```

Usage

```
{'run_dataset_statistics': 'run the python module to compute query type and support set size statistics from a JSONL dataset file', 'run_bool_answer_analysis': 'run the python module to analyze boolean answer distribution across database queries in a JSONL file', 'run_query_type_counter': 'run the python module to count and print query types from a JSONL dataset file', 'summarize_get_bool_ans': 'summarize the python get_bool_ans function that returns NULL TRUE or FALSE from a list of answers', 'review_merge_type': 'review the python merge_type function that normalizes query type strings for dataset statistics'}
```

## File: facebookresearch_neuraldb/dataset-construction/src/ndb_data/sample_questions.py

Prompts

```
['run the python module to compute query type and support set size statistics from a JSONL dataset file', 'run the python module to analyze boolean answer distribution across database queries in a JSONL file', 'run the python module to count and print query types from a JSONL dataset file', 'summarize the python get_bool_ans function that returns NULL TRUE or FALSE from a list of answers', 'review the python merge_type function that normalizes query type strings for dataset statistics', 'run the script to sample and filter questions from a JSONL dataset file to an output file', 'run stratified sampling of questions by type and fact count bin across database instances', 'run filtering to drop weak argmin argmax and low fact count questions from the dataset', 'run get_size_bin to classify a question into a bin based on its fact count', 'run the script to print statistics on sampled question bins types and fact counts', 'review the python get_size_bin function that bins queries by fact count into discrete size buckets', 'summarize the python module sampling logic that selects questions across strata until 90 percent of bins are empty', 'review the stratified sampling logic that selects questions across type and size bins until 75% of bins are exhausted', 'review the filtering logic that drops questions by type and fact count using probabilistic thresholds', 'run the full pipeline to sample, filter, and write a subset of questions to an output JSON file', 'run the size binning logic to categorize questions by number of facts into discrete bins', 'run the script to analyze and print question type and complexity distribution statistics from a sampled dataset', 'run the python module to filter and probabilistically drop questions by type and complexity']
```

Usage

```
{'run_sample_questions': 'run the script to sample and filter questions from a JSONL dataset file to an output file', 'run_stratified_sampling': 'run stratified sampling of questions by type and fact count bin across database instances', 'run_question_filtering': 'run filtering to drop weak argmin argmax and low fact count questions from the dataset', 'run_get_size_bin': 'run get_size_bin to classify a question into a bin based on its fact count', 'run_question_statistics': 'run the script to print statistics on sampled question bins types and fact counts'}
```

## File: facebookresearch_neuraldb/dataset-construction/src/ndb_data/sample_questions_100.py

Prompts

```
['run the python module to compute query type and support set size statistics from a JSONL dataset file', 'run the python module to analyze boolean answer distribution across database queries in a JSONL file', 'run the python module to count and print query types from a JSONL dataset file', 'summarize the python get_bool_ans function that returns NULL TRUE or FALSE from a list of answers', 'review the python merge_type function that normalizes query type strings for dataset statistics', 'run the script to sample and filter questions from a JSONL dataset file to an output file', 'run stratified sampling of questions by type and fact count bin across database instances', 'run filtering to drop weak argmin argmax and low fact count questions from the dataset', 'run get_size_bin to classify a question into a bin based on its fact count', 'run the script to print statistics on sampled question bins types and fact counts', 'review the python get_size_bin function that bins queries by fact count into discrete size buckets', 'summarize the python module sampling logic that selects questions across strata until 90 percent of bins are empty', 'review the stratified sampling logic that selects questions across type and size bins until 75% of bins are exhausted', 'review the filtering logic that drops questions by type and fact count using probabilistic thresholds', 'run the full pipeline to sample, filter, and write a subset of questions to an output JSON file', 'run the size binning logic to categorize questions by number of facts into discrete bins', 'run the script to analyze and print question type and complexity distribution statistics from a sampled dataset', 'run the python module to filter and probabilistically drop questions by type and complexity']
```

Usage

```
{'run_sample_questions': 'run the python module to sample questions from a JSON-lines dataset into an output file', 'run_stratified_sampling': 'run the python module to perform stratified sampling of questions by type and fact count bin', 'run_question_filtering': 'run the python module to filter questions by type and complexity with probabilistic drop rates', 'review_get_size_bin': 'review the python get_size_bin function that bins queries by fact count into discrete size buckets', 'summarize_sampling_logic': 'summarize the python module sampling logic that selects questions across strata until 90 percent of bins are empty'}
```

## File: facebookresearch_neuraldb/dataset-construction/src/ndb_data/sample_questions_1000.py

Prompts

```
['run the python module to compute query type and support set size statistics from a JSONL dataset file', 'run the python module to analyze boolean answer distribution across database queries in a JSONL file', 'run the python module to count and print query types from a JSONL dataset file', 'summarize the python get_bool_ans function that returns NULL TRUE or FALSE from a list of answers', 'review the python merge_type function that normalizes query type strings for dataset statistics', 'run the script to sample and filter questions from a JSONL dataset file to an output file', 'run stratified sampling of questions by type and fact count bin across database instances', 'run filtering to drop weak argmin argmax and low fact count questions from the dataset', 'run get_size_bin to classify a question into a bin based on its fact count', 'run the script to print statistics on sampled question bins types and fact counts', 'review the python get_size_bin function that bins queries by fact count into discrete size buckets', 'summarize the python module sampling logic that selects questions across strata until 90 percent of bins are empty', 'review the stratified sampling logic that selects questions across type and size bins until 75% of bins are exhausted', 'review the filtering logic that drops questions by type and fact count using probabilistic thresholds', 'run the full pipeline to sample, filter, and write a subset of questions to an output JSON file', 'run the size binning logic to categorize questions by number of facts into discrete bins', 'run the script to analyze and print question type and complexity distribution statistics from a sampled dataset', 'run the python module to filter and probabilistically drop questions by type and complexity']
```

Usage

```
{'run_sample_questions': 'run the script to sample questions from a JSON dataset file with stratified binning by query complexity', 'run_get_size_bin': 'run get_size_bin to classify a query into a size bin based on the number of facts it uses', 'review_sampling_logic': 'review the stratified sampling logic that selects questions across type and size bins until 75% of bins are exhausted', 'review_filtering_logic': 'review the filtering logic that drops questions by type and fact count using probabilistic thresholds', 'run_question_sampling_pipeline': 'run the full pipeline to sample, filter, and write a subset of questions to an output JSON file'}
```

## File: facebookresearch_neuraldb/dataset-construction/src/ndb_data/sample_questions_250.py

Prompts

```
['run the python module to compute query type and support set size statistics from a JSONL dataset file', 'run the python module to analyze boolean answer distribution across database queries in a JSONL file', 'run the python module to count and print query types from a JSONL dataset file', 'summarize the python get_bool_ans function that returns NULL TRUE or FALSE from a list of answers', 'review the python merge_type function that normalizes query type strings for dataset statistics', 'run the script to sample and filter questions from a JSONL dataset file to an output file', 'run stratified sampling of questions by type and fact count bin across database instances', 'run filtering to drop weak argmin argmax and low fact count questions from the dataset', 'run get_size_bin to classify a question into a bin based on its fact count', 'run the script to print statistics on sampled question bins types and fact counts', 'review the python get_size_bin function that bins queries by fact count into discrete size buckets', 'summarize the python module sampling logic that selects questions across strata until 90 percent of bins are empty', 'review the stratified sampling logic that selects questions across type and size bins until 75% of bins are exhausted', 'review the filtering logic that drops questions by type and fact count using probabilistic thresholds', 'run the full pipeline to sample, filter, and write a subset of questions to an output JSON file', 'run the size binning logic to categorize questions by number of facts into discrete bins', 'run the script to analyze and print question type and complexity distribution statistics from a sampled dataset', 'run the python module to filter and probabilistically drop questions by type and complexity']
```

Usage

```
{'run_sample_questions': 'run the python module to sample questions from a JSON lines dataset into an output file', 'run_stratified_sampling': 'run the python module to perform stratified sampling of questions by type and fact count bins', 'run_question_filtering': 'run the python module to filter questions by type like argmin argmax bool and fact bin size', 'run_get_size_bin': 'run the python module to classify a query into a size bin based on its fact count', 'run_dataset_statistics': 'run the python module to print statistics on sampled question bins types and complexity counts'}
```

## File: facebookresearch_neuraldb/dataset-construction/src/ndb_data/sample_questions_50.py

Prompts

```
['run the python module to compute query type and support set size statistics from a JSONL dataset file', 'run the python module to analyze boolean answer distribution across database queries in a JSONL file', 'run the python module to count and print query types from a JSONL dataset file', 'summarize the python get_bool_ans function that returns NULL TRUE or FALSE from a list of answers', 'review the python merge_type function that normalizes query type strings for dataset statistics', 'run the script to sample and filter questions from a JSONL dataset file to an output file', 'run stratified sampling of questions by type and fact count bin across database instances', 'run filtering to drop weak argmin argmax and low fact count questions from the dataset', 'run get_size_bin to classify a question into a bin based on its fact count', 'run the script to print statistics on sampled question bins types and fact counts', 'review the python get_size_bin function that bins queries by fact count into discrete size buckets', 'summarize the python module sampling logic that selects questions across strata until 90 percent of bins are empty', 'review the stratified sampling logic that selects questions across type and size bins until 75% of bins are exhausted', 'review the filtering logic that drops questions by type and fact count using probabilistic thresholds', 'run the full pipeline to sample, filter, and write a subset of questions to an output JSON file', 'run the size binning logic to categorize questions by number of facts into discrete bins', 'run the script to analyze and print question type and complexity distribution statistics from a sampled dataset', 'run the python module to filter and probabilistically drop questions by type and complexity']
```

Usage

```
{'run_sample_questions': 'run the script to sample and filter questions from a JSONL dataset file to an output file', 'run_stratified_sampling': 'run stratified sampling of database questions by type and fact count bins from an input JSONL file', 'run_question_filtering': 'run the question filtering pipeline that drops weak argmin argmax and simple bool questions from a dataset', 'run_size_binning': 'run the size binning logic to categorize questions by number of facts into discrete bins', 'run_complexity_analysis': 'run the script to analyze and print question type and complexity distribution statistics from a sampled dataset'}
```

## File: facebookresearch_neuraldb/dataset-construction/src/ndb_data/sample_questions_500.py

Prompts

```
['run the python module to compute query type and support set size statistics from a JSONL dataset file', 'run the python module to analyze boolean answer distribution across database queries in a JSONL file', 'run the python module to count and print query types from a JSONL dataset file', 'summarize the python get_bool_ans function that returns NULL TRUE or FALSE from a list of answers', 'review the python merge_type function that normalizes query type strings for dataset statistics', 'run the script to sample and filter questions from a JSONL dataset file to an output file', 'run stratified sampling of questions by type and fact count bin across database instances', 'run filtering to drop weak argmin argmax and low fact count questions from the dataset', 'run get_size_bin to classify a question into a bin based on its fact count', 'run the script to print statistics on sampled question bins types and fact counts', 'review the python get_size_bin function that bins queries by fact count into discrete size buckets', 'summarize the python module sampling logic that selects questions across strata until 90 percent of bins are empty', 'review the stratified sampling logic that selects questions across type and size bins until 75% of bins are exhausted', 'review the filtering logic that drops questions by type and fact count using probabilistic thresholds', 'run the full pipeline to sample, filter, and write a subset of questions to an output JSON file', 'run the size binning logic to categorize questions by number of facts into discrete bins', 'run the script to analyze and print question type and complexity distribution statistics from a sampled dataset', 'run the python module to filter and probabilistically drop questions by type and complexity']
```

Usage

```
{'run_sample_questions': 'run the python module to sample questions from a JSONL dataset into an output file', 'run_stratified_sampling': 'run the python module to perform stratified sampling of questions by type and fact count bin', 'run_filter_questions': 'run the python module to filter and probabilistically drop questions by type and complexity', 'review_get_size_bin': 'review the python function get_size_bin that classifies queries into size bins by fact count', 'summarize_sampling_logic': 'summarize the python module sampling logic that selects questions until 75 percent of strata are empty'}
```

