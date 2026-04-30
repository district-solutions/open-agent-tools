# Agent Python Tools

- repo: pandas-dev/pandas
- repo_uri: https://github.com/pandas-dev/pandas.git

## File: pandas-dev_pandas/pandas/tests/config/test_config.py

Prompts

```
['test the pandas config register_option function to register nested options with validators and docstrings', 'test the pandas config get_option function to retrieve registered option values by key', 'test the pandas config set_option function to update option values using key-value pairs or a dictionary', 'test the pandas config reset_option function to restore options to their default registered values', 'test the pandas config option_context context manager to temporarily set options with nested and decorator usage', 'test the can_set_locale function to verify it returns True for valid locales and False for invalid ones', 'test the get_locales function to retrieve available system locales and filter by prefix', 'test the set_locale context manager to verify locale changes are applied and restored correctly', 'test that can_set_locale does not leak locale state when returning False for invalid locale tuples', 'test that pd.options.display.encoding matches the system locale encoding from LC_ALL environment variable']
```

Usage

```
{'test_register_option': 'test the pandas config register_option function to register nested options with validators and docstrings', 'test_get_option': 'test the pandas config get_option function to retrieve registered option values by key', 'test_set_option': 'test the pandas config set_option function to update option values using key-value pairs or a dictionary', 'test_reset_option': 'test the pandas config reset_option function to restore options to their default registered values', 'test_option_context': 'test the pandas config option_context context manager to temporarily set options with nested and decorator usage'}
```

## File: pandas-dev_pandas/pandas/tests/config/test_localization.py

Prompts

```
['test the pandas config register_option function to register nested options with validators and docstrings', 'test the pandas config get_option function to retrieve registered option values by key', 'test the pandas config set_option function to update option values using key-value pairs or a dictionary', 'test the pandas config reset_option function to restore options to their default registered values', 'test the pandas config option_context context manager to temporarily set options with nested and decorator usage', 'test the can_set_locale function to verify it returns True for valid locales and False for invalid ones', 'test the get_locales function to retrieve available system locales and filter by prefix', 'test the set_locale context manager to verify locale changes are applied and restored correctly', 'test that can_set_locale does not leak locale state when returning False for invalid locale tuples', 'test that pd.options.display.encoding matches the system locale encoding from LC_ALL environment variable']
```

Usage

```
{'test_can_set_locale': 'test the can_set_locale function to verify it returns True for valid locales and False for invalid ones', 'test_get_locales': 'test the get_locales function to retrieve available system locales and filter by prefix', 'test_set_locale': 'test the set_locale context manager to verify locale changes are applied and restored correctly', 'test_can_set_locale_no_leak': 'test that can_set_locale does not leak locale state when returning False for invalid locale tuples', 'test_encoding_detected': 'test that pd.options.display.encoding matches the system locale encoding from LC_ALL environment variable'}
```

