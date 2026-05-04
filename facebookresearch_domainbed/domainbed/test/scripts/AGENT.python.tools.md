# Agent Python Tools

- repo: facebookresearch/domainbed
- repo_uri: https://github.com/facebookresearch/domainbed

## File: facebookresearch_domainbed/domainbed/test/scripts/test_collect_results.py

Prompts

```
['test the format_mean function that computes mean and standard error from a list of data points', 'test the print_table function to output a plain text formatted table with row and column labels', 'test the print_table function to output a LaTeX formatted table with booktabs styling', 'run the collect_results script with an input directory to generate domainbed results tables', 'test the collect_results end-to-end output against a ground-truth file using subprocess execution', 'create a sweep Job with train_args and an output_dir for domain generalization experiments', 'launch a list of sweep Jobs using a custom launcher function to execute training commands', 'delete launched sweep Jobs to reset their state back to NOT_LAUNCHED', 'generate a list of training argument dicts for multiple algorithms, datasets, and hyperparameter combinations', 'run the sweep CLI launch command to start domain generalization training jobs with a dummy launcher', 'test the domainbed training script end to end with RotatedMNIST dataset and 501 steps', 'run the domainbed train script via subprocess with a custom dataset and output directory', 'validate the results.jsonl output file after training to check step count and accuracy', 'validate the out.txt log file after training to confirm expected step output', 'review the TestTrain unittest class and its end-to-end training test method']
```

Usage

```
{'test_format_mean': 'test the format_mean function that computes mean and standard error from a list of data points', 'test_print_table_non_latex': 'test the print_table function to output a plain text formatted table with row and column labels', 'test_print_table_latex': 'test the print_table function to output a LaTeX formatted table with booktabs styling', 'run_collect_results_cli': 'run the collect_results script with an input directory to generate domainbed results tables', 'test_end_to_end': 'test the collect_results end-to-end output against a ground-truth file using subprocess execution'}
```

## File: facebookresearch_domainbed/domainbed/test/scripts/test_sweep.py

Prompts

```
['test the format_mean function that computes mean and standard error from a list of data points', 'test the print_table function to output a plain text formatted table with row and column labels', 'test the print_table function to output a LaTeX formatted table with booktabs styling', 'run the collect_results script with an input directory to generate domainbed results tables', 'test the collect_results end-to-end output against a ground-truth file using subprocess execution', 'create a sweep Job with train_args and an output_dir for domain generalization experiments', 'launch a list of sweep Jobs using a custom launcher function to execute training commands', 'delete launched sweep Jobs to reset their state back to NOT_LAUNCHED', 'generate a list of training argument dicts for multiple algorithms, datasets, and hyperparameter combinations', 'run the sweep CLI launch command to start domain generalization training jobs with a dummy launcher', 'test the domainbed training script end to end with RotatedMNIST dataset and 501 steps', 'run the domainbed train script via subprocess with a custom dataset and output directory', 'validate the results.jsonl output file after training to check step count and accuracy', 'validate the out.txt log file after training to confirm expected step output', 'review the TestTrain unittest class and its end-to-end training test method']
```

Usage

```
{'create_sweep_job': 'create a sweep Job with train_args and an output_dir for domain generalization experiments', 'launch_sweep_jobs': 'launch a list of sweep Jobs using a custom launcher function to execute training commands', 'delete_sweep_jobs': 'delete launched sweep Jobs to reset their state back to NOT_LAUNCHED', 'generate_sweep_args_list': 'generate a list of training argument dicts for multiple algorithms, datasets, and hyperparameter combinations', 'run_sweep_cli_launch': 'run the sweep CLI launch command to start domain generalization training jobs with a dummy launcher'}
```

## File: facebookresearch_domainbed/domainbed/test/scripts/test_train.py

Prompts

```
['test the format_mean function that computes mean and standard error from a list of data points', 'test the print_table function to output a plain text formatted table with row and column labels', 'test the print_table function to output a LaTeX formatted table with booktabs styling', 'run the collect_results script with an input directory to generate domainbed results tables', 'test the collect_results end-to-end output against a ground-truth file using subprocess execution', 'create a sweep Job with train_args and an output_dir for domain generalization experiments', 'launch a list of sweep Jobs using a custom launcher function to execute training commands', 'delete launched sweep Jobs to reset their state back to NOT_LAUNCHED', 'generate a list of training argument dicts for multiple algorithms, datasets, and hyperparameter combinations', 'run the sweep CLI launch command to start domain generalization training jobs with a dummy launcher', 'test the domainbed training script end to end with RotatedMNIST dataset and 501 steps', 'run the domainbed train script via subprocess with a custom dataset and output directory', 'validate the results.jsonl output file after training to check step count and accuracy', 'validate the out.txt log file after training to confirm expected step output', 'review the TestTrain unittest class and its end-to-end training test method']
```

Usage

```
{'test_train_end_to_end': 'test the domainbed training script end to end with RotatedMNIST dataset and 501 steps', 'run_train_subprocess': 'run the domainbed train script via subprocess with a custom dataset and output directory', 'validate_results_jsonl': 'validate the results.jsonl output file after training to check step count and accuracy', 'validate_out_txt': 'validate the out.txt log file after training to confirm expected step output', 'review_TestTrain_class': 'review the TestTrain unittest class and its end-to-end training test method'}
```

