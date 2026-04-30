# Agent Python Tools

- repo: pandas-dev/pandas
- repo_uri: https://github.com/pandas-dev/pandas.git

## File: pandas-dev_pandas/pandas/tests/window/moments/conftest.py

Prompts

```
['create a list of pandas Series with various patterns including NaN, constant, increasing, and decreasing values', 'create pandas DataFrames from existing Series and add DataFrames with duplicate column names', 'check if a pandas Series or DataFrame has a single non-NaN constant value across all elements', 'build a pytest fixture that yields only constant-value Series and DataFrames for parameterized tests', 'build a pytest fixture that yields empty, NaN, constant, monotonic, and NaN-mixed Series and DataFrames', 'test the ewm mean computation against a manual weighted moving average implementation', 'test that ewm mean of a constant series equals the constant value and self-correlation is NaN', 'test that unbiased ewm variance equals biased variance multiplied by debiasing factors', 'test that biased ewm variance equals mean of x squared minus mean of x squared', 'test that ewm covariance and correlation satisfy standard statistical identities', 'test that expanding apply with sum and nansum produce consistent results', 'test that expanding variance equals std squared and cov(x,x) for ddof 0 and 1', 'test that expanding covariance and correlation satisfy algebraic identities', 'test that expanding mean equals sum divided by count', 'test rolling apply sum consistency between .sum() and .apply(func) on pandas Series', 'test rolling variance equals std squared and covariance of x with x equals variance', 'test rolling covariance and correlation consistency with debiasing factors', 'test rolling mean equals rolling sum divided by rolling count']
```

Usage

```
{'create_series_data': 'create a list of pandas Series with various patterns including NaN, constant, increasing, and decreasing values', 'create_dataframes_from_series': 'create pandas DataFrames from existing Series and add DataFrames with duplicate column names', 'check_data_consistency': 'check if a pandas Series or DataFrame has a single non-NaN constant value across all elements', 'build_consistent_data_fixture': 'build a pytest fixture that yields only constant-value Series and DataFrames for parameterized tests', 'build_all_data_fixture': 'build a pytest fixture that yields empty, NaN, constant, monotonic, and NaN-mixed Series and DataFrames'}
```

## File: pandas-dev_pandas/pandas/tests/window/moments/test_moments_consistency_ewm.py

Prompts

```
['create a list of pandas Series with various patterns including NaN, constant, increasing, and decreasing values', 'create pandas DataFrames from existing Series and add DataFrames with duplicate column names', 'check if a pandas Series or DataFrame has a single non-NaN constant value across all elements', 'build a pytest fixture that yields only constant-value Series and DataFrames for parameterized tests', 'build a pytest fixture that yields empty, NaN, constant, monotonic, and NaN-mixed Series and DataFrames', 'test the ewm mean computation against a manual weighted moving average implementation', 'test that ewm mean of a constant series equals the constant value and self-correlation is NaN', 'test that unbiased ewm variance equals biased variance multiplied by debiasing factors', 'test that biased ewm variance equals mean of x squared minus mean of x squared', 'test that ewm covariance and correlation satisfy standard statistical identities', 'test that expanding apply with sum and nansum produce consistent results', 'test that expanding variance equals std squared and cov(x,x) for ddof 0 and 1', 'test that expanding covariance and correlation satisfy algebraic identities', 'test that expanding mean equals sum divided by count', 'test rolling apply sum consistency between .sum() and .apply(func) on pandas Series', 'test rolling variance equals std squared and covariance of x with x equals variance', 'test rolling covariance and correlation consistency with debiasing factors', 'test rolling mean equals rolling sum divided by rolling count']
```

Usage

```
{'test_ewm_consistency_mean': 'test the ewm mean computation against a manual weighted moving average implementation', 'test_ewm_consistency_consistent': 'test that ewm mean of a constant series equals the constant value and self-correlation is NaN', 'test_ewm_consistency_var_debiasing_factors': 'test that unbiased ewm variance equals biased variance multiplied by debiasing factors', 'test_moments_consistency_var': 'test that biased ewm variance equals mean of x squared minus mean of x squared', 'test_ewm_consistency_series_cov_corr': 'test that ewm covariance and correlation satisfy standard statistical identities'}
```

## File: pandas-dev_pandas/pandas/tests/window/moments/test_moments_consistency_expanding.py

Prompts

```
['create a list of pandas Series with various patterns including NaN, constant, increasing, and decreasing values', 'create pandas DataFrames from existing Series and add DataFrames with duplicate column names', 'check if a pandas Series or DataFrame has a single non-NaN constant value across all elements', 'build a pytest fixture that yields only constant-value Series and DataFrames for parameterized tests', 'build a pytest fixture that yields empty, NaN, constant, monotonic, and NaN-mixed Series and DataFrames', 'test the ewm mean computation against a manual weighted moving average implementation', 'test that ewm mean of a constant series equals the constant value and self-correlation is NaN', 'test that unbiased ewm variance equals biased variance multiplied by debiasing factors', 'test that biased ewm variance equals mean of x squared minus mean of x squared', 'test that ewm covariance and correlation satisfy standard statistical identities', 'test that expanding apply with sum and nansum produce consistent results', 'test that expanding variance equals std squared and cov(x,x) for ddof 0 and 1', 'test that expanding covariance and correlation satisfy algebraic identities', 'test that expanding mean equals sum divided by count', 'test rolling apply sum consistency between .sum() and .apply(func) on pandas Series', 'test rolling variance equals std squared and covariance of x with x equals variance', 'test rolling covariance and correlation consistency with debiasing factors', 'test rolling mean equals rolling sum divided by rolling count']
```

Usage

```
{'test_expanding_apply_consistency_sum_nans': 'test that expanding apply with sum and nansum produce consistent results', 'test_moments_consistency_var': 'test that expanding variance is non-negative and matches mean(x^2) - mean(x)^2 for ddof=0', 'test_expanding_consistency_var_std_cov': 'test that expanding variance equals std squared and cov(x,x) for ddof 0 and 1', 'test_expanding_consistency_series_cov_corr': 'test that expanding covariance and correlation satisfy algebraic identities', 'test_expanding_consistency_mean': 'test that expanding mean equals sum divided by count'}
```

## File: pandas-dev_pandas/pandas/tests/window/moments/test_moments_consistency_rolling.py

Prompts

```
['create a list of pandas Series with various patterns including NaN, constant, increasing, and decreasing values', 'create pandas DataFrames from existing Series and add DataFrames with duplicate column names', 'check if a pandas Series or DataFrame has a single non-NaN constant value across all elements', 'build a pytest fixture that yields only constant-value Series and DataFrames for parameterized tests', 'build a pytest fixture that yields empty, NaN, constant, monotonic, and NaN-mixed Series and DataFrames', 'test the ewm mean computation against a manual weighted moving average implementation', 'test that ewm mean of a constant series equals the constant value and self-correlation is NaN', 'test that unbiased ewm variance equals biased variance multiplied by debiasing factors', 'test that biased ewm variance equals mean of x squared minus mean of x squared', 'test that ewm covariance and correlation satisfy standard statistical identities', 'test that expanding apply with sum and nansum produce consistent results', 'test that expanding variance equals std squared and cov(x,x) for ddof 0 and 1', 'test that expanding covariance and correlation satisfy algebraic identities', 'test that expanding mean equals sum divided by count', 'test rolling apply sum consistency between .sum() and .apply(func) on pandas Series', 'test rolling variance equals std squared and covariance of x with x equals variance', 'test rolling covariance and correlation consistency with debiasing factors', 'test rolling mean equals rolling sum divided by rolling count']
```

Usage

```
{'test_rolling_apply_consistency_sum': 'test rolling apply sum consistency between .sum() and .apply(func) on pandas Series', 'test_moments_consistency_var': 'test rolling variance consistency with ddof 0 and 1 against mean(x^2) - mean(x)^2', 'test_rolling_consistency_var_std_cov': 'test rolling variance equals std squared and covariance of x with x equals variance', 'test_rolling_consistency_series_cov_corr': 'test rolling covariance and correlation consistency with debiasing factors', 'test_rolling_consistency_mean': 'test rolling mean equals rolling sum divided by rolling count'}
```

