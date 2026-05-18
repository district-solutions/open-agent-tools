# Agent Python Tools

- repo: facebookresearch/neural-rewriter
- repo_uri: https://github.com/facebookresearch/neural-rewriter

## File: facebookresearch_neural-rewriter/data_generator/jspDatagen.py

Prompts

```
['run the jsp data generator to create synthetic job shop scheduling samples as JSON files', 'run sample_job to generate a single random job with length and resource size arrays', 'generate a job shop scheduling dataset split into train, validation, and test JSON files', 'refactor sample_job to support custom resource allocation strategies beyond dominant and other categories', 'review main to understand how samples are generated, split into 80/10/10 train/val/test, and saved as JSON', 'run the python module to generate 100000 VRP samples with 20 customers and capacity 30', 'run the python module to generate VRP data with custom num_customers max_demand and capacity', 'run the python module to generate reproducible VRP data by setting a random seed', 'refactor the python sample_pos function to support configurable position ranges instead of fixed 0 to 1']
```

Usage

```
{'run_jsp_datagen': 'run the jsp data generator to create synthetic job shop scheduling samples as JSON files', 'run_sample_job': 'run sample_job to generate a single random job with length and resource size arrays', 'generate_jsp_dataset': 'generate a job shop scheduling dataset split into train, validation, and test JSON files', 'refactor_sample_job': 'refactor sample_job to support custom resource allocation strategies beyond dominant and other categories', 'review_main': 'review main to understand how samples are generated, split into 80/10/10 train/val/test, and saved as JSON'}
```

## File: facebookresearch_neural-rewriter/data_generator/vrpDatagen.py

Prompts

```
['run the jsp data generator to create synthetic job shop scheduling samples as JSON files', 'run sample_job to generate a single random job with length and resource size arrays', 'generate a job shop scheduling dataset split into train, validation, and test JSON files', 'refactor sample_job to support custom resource allocation strategies beyond dominant and other categories', 'review main to understand how samples are generated, split into 80/10/10 train/val/test, and saved as JSON', 'run the python module to generate 100000 VRP samples with 20 customers and capacity 30', 'run the python module to generate VRP data with custom num_customers max_demand and capacity', 'run the python module to generate reproducible VRP data by setting a random seed', 'refactor the python sample_pos function to support configurable position ranges instead of fixed 0 to 1']
```

Usage

```
{'run_vrp_datagen': 'run the python module to generate 100000 VRP samples with 20 customers and capacity 30', 'run_vrp_datagen_custom': 'run the python module to generate VRP data with custom num_customers max_demand and capacity', 'run_vrp_datagen_seeded': 'run the python module to generate reproducible VRP data by setting a random seed', 'review_main': 'review the python main function that generates VRP samples and splits them into train val and test sets', 'refactor_sample_pos': 'refactor the python sample_pos function to support configurable position ranges instead of fixed 0 to 1'}
```

