# Agent Python Tools

- repo: pola-rs/polars
- repo_uri: https://github.com/pola-rs/polars.git

## File: pola-rs_polars/py-polars/tests/unit/operations/rolling/test_map.py

Prompts

```
['test the rolling_map function applies a lambda sum over a series with window_size=2 and min_samples=1', 'test the rolling_map function handles null values in the series with window_size=3 and min_samples=3', 'test the rolling_map function combined with over() to apply rolling min within groups defined by a column', 'test the rolling_map function with numpy nansum as the function argument on a series containing NaN values', 'test the rolling_map function with custom weights applied to rolling sum and rolling std computations', 'test the rolling_sum_by function computes rolling sum over a time-based window with closed interval', 'test the rolling_var function maintains numerical stability with repeated float values', 'test the rolling_quantile function with nearest interpolation returns correct quantile values', 'test the rolling_cov and rolling_corr functions compute rolling covariance and correlation between two columns', 'test the rolling_rank function computes rolling ranks with configurable method and centering', 'test the rolling_var function on a polars Series with constant values and verify the sum is zero', 'test the rolling_std function on a polars Series with constant values and verify the sum is zero', 'create a polars Series and compute rolling variance with a specified window size and minimum samples', 'create a polars Series and compute rolling standard deviation with a specified window size and minimum samples', 'test rolling_var and rolling_std with window_size and min_samples parameters on a polars Series']
```

Usage

```
{'test_rolling_map_basic': 'test the rolling_map function applies a lambda sum over a series with window_size=2 and min_samples=1', 'test_rolling_map_with_nulls': 'test the rolling_map function handles null values in the series with window_size=3 and min_samples=3', 'test_rolling_map_over_groupby': 'test the rolling_map function combined with over() to apply rolling min within groups defined by a column', 'test_rolling_map_numpy_function': 'test the rolling_map function with numpy nansum as the function argument on a series containing NaN values', 'test_rolling_map_with_weights': 'test the rolling_map function with custom weights applied to rolling sum and rolling std computations'}
```

## File: pola-rs_polars/py-polars/tests/unit/operations/rolling/test_rolling.py

Prompts

```
['test the rolling_map function applies a lambda sum over a series with window_size=2 and min_samples=1', 'test the rolling_map function handles null values in the series with window_size=3 and min_samples=3', 'test the rolling_map function combined with over() to apply rolling min within groups defined by a column', 'test the rolling_map function with numpy nansum as the function argument on a series containing NaN values', 'test the rolling_map function with custom weights applied to rolling sum and rolling std computations', 'test the rolling_sum_by function computes rolling sum over a time-based window with closed interval', 'test the rolling_var function maintains numerical stability with repeated float values', 'test the rolling_quantile function with nearest interpolation returns correct quantile values', 'test the rolling_cov and rolling_corr functions compute rolling covariance and correlation between two columns', 'test the rolling_rank function computes rolling ranks with configurable method and centering', 'test the rolling_var function on a polars Series with constant values and verify the sum is zero', 'test the rolling_std function on a polars Series with constant values and verify the sum is zero', 'create a polars Series and compute rolling variance with a specified window size and minimum samples', 'create a polars Series and compute rolling standard deviation with a specified window size and minimum samples', 'test rolling_var and rolling_std with window_size and min_samples parameters on a polars Series']
```

Usage

```
{'test_rolling_sum_by': 'test the rolling_sum_by function computes rolling sum over a time-based window with closed interval', 'test_rolling_var_numerical_stability': 'test the rolling_var function maintains numerical stability with repeated float values', 'test_rolling_quantile_nearest': 'test the rolling_quantile function with nearest interpolation returns correct quantile values', 'test_rolling_cov_corr': 'test the rolling_cov and rolling_corr functions compute rolling covariance and correlation between two columns', 'test_rolling_rank': 'test the rolling_rank function computes rolling ranks with configurable method and centering'}
```

## File: pola-rs_polars/py-polars/tests/unit/operations/rolling/test_rolling_fixed.py

Prompts

```
['test the rolling_map function applies a lambda sum over a series with window_size=2 and min_samples=1', 'test the rolling_map function handles null values in the series with window_size=3 and min_samples=3', 'test the rolling_map function combined with over() to apply rolling min within groups defined by a column', 'test the rolling_map function with numpy nansum as the function argument on a series containing NaN values', 'test the rolling_map function with custom weights applied to rolling sum and rolling std computations', 'test the rolling_sum_by function computes rolling sum over a time-based window with closed interval', 'test the rolling_var function maintains numerical stability with repeated float values', 'test the rolling_quantile function with nearest interpolation returns correct quantile values', 'test the rolling_cov and rolling_corr functions compute rolling covariance and correlation between two columns', 'test the rolling_rank function computes rolling ranks with configurable method and centering', 'test the rolling_var function on a polars Series with constant values and verify the sum is zero', 'test the rolling_std function on a polars Series with constant values and verify the sum is zero', 'create a polars Series and compute rolling variance with a specified window size and minimum samples', 'create a polars Series and compute rolling standard deviation with a specified window size and minimum samples', 'test rolling_var and rolling_std with window_size and min_samples parameters on a polars Series']
```

Usage

```
{'test_rolling_var_stability': 'test the rolling_var function on a polars Series with constant values and verify the sum is zero', 'test_rolling_std_stability': 'test the rolling_std function on a polars Series with constant values and verify the sum is zero', 'create_series_rolling_var': 'create a polars Series and compute rolling variance with a specified window size and minimum samples', 'create_series_rolling_std': 'create a polars Series and compute rolling standard deviation with a specified window size and minimum samples', 'test_rolling_window_parameters': 'test rolling_var and rolling_std with window_size and min_samples parameters on a polars Series'}
```

