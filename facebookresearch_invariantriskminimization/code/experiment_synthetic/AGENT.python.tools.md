# Agent Python Tools

- repo: facebookresearch/invariantriskminimization
- repo_uri: https://github.com/facebookresearch/invariantriskminimization

## File: facebookresearch_invariantriskminimization/code/experiment_synthetic/main.py

Prompts

```
['run the synthetic invariant regression experiment comparing ERM, ICP, and IRM methods across environments', 'run the synthetic experiment with a fixed random seed for reproducible results', 'run the synthetic experiment with a custom subset of methods like ERM or IRM only', 'run the synthetic experiment using a chain structural equation model with configurable dimensions and environments', 'run the synthetic experiment with heterogeneous effects and scrambled variables enabled', 'train an InvariantRiskMinimization model across multiple environments with gradient penalty regularization', 'get the learned invariant weight vector from a trained InvariantRiskMinimization model', 'run InvariantCausalPrediction to find invariant feature subsets across environments using statistical tests', 'test two residual distributions for equal mean and variance using the mean_var_test method', 'train an EmpiricalRiskMinimizer by fitting linear regression on pooled data from all environments', 'run the plot module to generate causal and non-causal error bar charts from synthetic results', 'parse a setup title string into a three-letter category code like PES or FOU', 'plot bar charts with error bars comparing model performance across experimental setups', 'generate a complete bar chart figure from experiment solution lines and save to PDF', 'review the plot module functions for parsing titles, plotting bars, and generating experiment charts', 'create a ChainEquationModel with a given dimension and optional ones, scramble, hetero, and hidden flags', 'generate synthetic data by calling a ChainEquationModel with sample count n and environment variable env', 'get the ground truth weight vector and scramble matrix from a ChainEquationModel solution', 'review the ChainEquationModel constructor to understand how wxy, wyz, scramble, and hidden weights are initialized', 'test the ChainEquationModel with hetero true versus false to compare noise distribution in generated data']
```

Usage

```
{'run_experiment_synthetic': 'run the synthetic invariant regression experiment comparing ERM, ICP, and IRM methods across environments', 'run_experiment_with_seed': 'run the synthetic experiment with a fixed random seed for reproducible results', 'run_experiment_custom_methods': 'run the synthetic experiment with a custom subset of methods like ERM or IRM only', 'run_experiment_chain_sem': 'run the synthetic experiment using a chain structural equation model with configurable dimensions and environments', 'run_experiment_heterogeneous': 'run the synthetic experiment with heterogeneous effects and scrambled variables enabled'}
```

## File: facebookresearch_invariantriskminimization/code/experiment_synthetic/models.py

Prompts

```
['run the synthetic invariant regression experiment comparing ERM, ICP, and IRM methods across environments', 'run the synthetic experiment with a fixed random seed for reproducible results', 'run the synthetic experiment with a custom subset of methods like ERM or IRM only', 'run the synthetic experiment using a chain structural equation model with configurable dimensions and environments', 'run the synthetic experiment with heterogeneous effects and scrambled variables enabled', 'train an InvariantRiskMinimization model across multiple environments with gradient penalty regularization', 'get the learned invariant weight vector from a trained InvariantRiskMinimization model', 'run InvariantCausalPrediction to find invariant feature subsets across environments using statistical tests', 'test two residual distributions for equal mean and variance using the mean_var_test method', 'train an EmpiricalRiskMinimizer by fitting linear regression on pooled data from all environments', 'run the plot module to generate causal and non-causal error bar charts from synthetic results', 'parse a setup title string into a three-letter category code like PES or FOU', 'plot bar charts with error bars comparing model performance across experimental setups', 'generate a complete bar chart figure from experiment solution lines and save to PDF', 'review the plot module functions for parsing titles, plotting bars, and generating experiment charts', 'create a ChainEquationModel with a given dimension and optional ones, scramble, hetero, and hidden flags', 'generate synthetic data by calling a ChainEquationModel with sample count n and environment variable env', 'get the ground truth weight vector and scramble matrix from a ChainEquationModel solution', 'review the ChainEquationModel constructor to understand how wxy, wyz, scramble, and hidden weights are initialized', 'test the ChainEquationModel with hetero true versus false to compare noise distribution in generated data']
```

Usage

```
{'train_IRM': 'train an InvariantRiskMinimization model across multiple environments with gradient penalty regularization', 'get_IRM_solution': 'get the learned invariant weight vector from a trained InvariantRiskMinimization model', 'run_ICP': 'run InvariantCausalPrediction to find invariant feature subsets across environments using statistical tests', 'test_mean_var': 'test two residual distributions for equal mean and variance using the mean_var_test method', 'train_ERM': 'train an EmpiricalRiskMinimizer by fitting linear regression on pooled data from all environments'}
```

## File: facebookresearch_invariantriskminimization/code/experiment_synthetic/plot.py

Prompts

```
['run the synthetic invariant regression experiment comparing ERM, ICP, and IRM methods across environments', 'run the synthetic experiment with a fixed random seed for reproducible results', 'run the synthetic experiment with a custom subset of methods like ERM or IRM only', 'run the synthetic experiment using a chain structural equation model with configurable dimensions and environments', 'run the synthetic experiment with heterogeneous effects and scrambled variables enabled', 'train an InvariantRiskMinimization model across multiple environments with gradient penalty regularization', 'get the learned invariant weight vector from a trained InvariantRiskMinimization model', 'run InvariantCausalPrediction to find invariant feature subsets across environments using statistical tests', 'test two residual distributions for equal mean and variance using the mean_var_test method', 'train an EmpiricalRiskMinimizer by fitting linear regression on pooled data from all environments', 'run the plot module to generate causal and non-causal error bar charts from synthetic results', 'parse a setup title string into a three-letter category code like PES or FOU', 'plot bar charts with error bars comparing model performance across experimental setups', 'generate a complete bar chart figure from experiment solution lines and save to PDF', 'review the plot module functions for parsing titles, plotting bars, and generating experiment charts', 'create a ChainEquationModel with a given dimension and optional ones, scramble, hetero, and hidden flags', 'generate synthetic data by calling a ChainEquationModel with sample count n and environment variable env', 'get the ground truth weight vector and scramble matrix from a ChainEquationModel solution', 'review the ChainEquationModel constructor to understand how wxy, wyz, scramble, and hidden weights are initialized', 'test the ChainEquationModel with hetero true versus false to compare noise distribution in generated data']
```

Usage

```
{'run_plot_synthetic_results': 'run the plot module to generate causal and non-causal error bar charts from synthetic results', 'parse_title_parse_title': 'parse a setup title string into a three-letter category code like PES or FOU', 'plot_bars_plot_bars': 'plot bar charts with error bars comparing model performance across experimental setups', 'plot_experiment_plot_experiment': 'generate a complete bar chart figure from experiment solution lines and save to PDF', 'review_plot_module': 'review the plot module functions for parsing titles, plotting bars, and generating experiment charts'}
```

## File: facebookresearch_invariantriskminimization/code/experiment_synthetic/sem.py

Prompts

```
['run the synthetic invariant regression experiment comparing ERM, ICP, and IRM methods across environments', 'run the synthetic experiment with a fixed random seed for reproducible results', 'run the synthetic experiment with a custom subset of methods like ERM or IRM only', 'run the synthetic experiment using a chain structural equation model with configurable dimensions and environments', 'run the synthetic experiment with heterogeneous effects and scrambled variables enabled', 'train an InvariantRiskMinimization model across multiple environments with gradient penalty regularization', 'get the learned invariant weight vector from a trained InvariantRiskMinimization model', 'run InvariantCausalPrediction to find invariant feature subsets across environments using statistical tests', 'test two residual distributions for equal mean and variance using the mean_var_test method', 'train an EmpiricalRiskMinimizer by fitting linear regression on pooled data from all environments', 'run the plot module to generate causal and non-causal error bar charts from synthetic results', 'parse a setup title string into a three-letter category code like PES or FOU', 'plot bar charts with error bars comparing model performance across experimental setups', 'generate a complete bar chart figure from experiment solution lines and save to PDF', 'review the plot module functions for parsing titles, plotting bars, and generating experiment charts', 'create a ChainEquationModel with a given dimension and optional ones, scramble, hetero, and hidden flags', 'generate synthetic data by calling a ChainEquationModel with sample count n and environment variable env', 'get the ground truth weight vector and scramble matrix from a ChainEquationModel solution', 'review the ChainEquationModel constructor to understand how wxy, wyz, scramble, and hidden weights are initialized', 'test the ChainEquationModel with hetero true versus false to compare noise distribution in generated data']
```

Usage

```
{'create_ChainEquationModel': 'create a ChainEquationModel with a given dimension and optional ones, scramble, hetero, and hidden flags', 'generate_data_ChainEquationModel_call': 'generate synthetic data by calling a ChainEquationModel with sample count n and environment variable env', 'get_solution_ChainEquationModel_solution': 'get the ground truth weight vector and scramble matrix from a ChainEquationModel solution', 'review_ChainEquationModel_init': 'review the ChainEquationModel constructor to understand how wxy, wyz, scramble, and hidden weights are initialized', 'test_ChainEquationModel_hetero': 'test the ChainEquationModel with hetero true versus false to compare noise distribution in generated data'}
```

