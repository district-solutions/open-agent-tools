# Agent Python Tools

- repo: pandas-dev/pandas
- repo_uri: https://github.com/pandas-dev/pandas.git

## File: pandas-dev_pandas/pandas/_config/config.py

Prompts

```
['create a pandas config option with a key, default value, description, and validator function', 'get or set a pandas configuration option value by dot-notation key pattern', 'test temporarily setting pandas options within a with block that restores values on exit', 'review marking a pandas config option as deprecated with a replacement key and warning message', 'build a type validator factory function for registering pandas config option value constraints', 'run detect_console_encoding to find the most capable encoding supported by the console', 'test detect_console_encoding returns a non-empty encoding string from sys.stdout.encoding, locale, or sys.getdefaultencoding', 'review the pandas config option registration for display.encoding with detect_console_encoding as default and cf.is_text validator', "summarize the display module's purpose of configuring string encoding for console output in pandas to_string calls", 'refactor detect_console_encoding to add fallback logic for edge cases where all encoding sources return ascii or None', 'test the set_locale context manager to temporarily set a locale for a code block', 'test the can_set_locale function to check if a locale string is valid on the system', 'test the get_locales function to retrieve all available system locales with an optional prefix filter', 'review the set_locale context manager and its thread-safety implications', 'summarize the get_locales function and its platform-specific behavior on Linux and Darwin']
```

Usage

```
{'create_register_option': 'create a pandas config option with a key, default value, description, and validator function', 'get_set_option': 'get or set a pandas configuration option value by dot-notation key pattern', 'test_option_context': 'test temporarily setting pandas options within a with block that restores values on exit', 'review_deprecate_option': 'review marking a pandas config option as deprecated with a replacement key and warning message', 'build_validator_factory': 'build a type validator factory function for registering pandas config option value constraints'}
```

## File: pandas-dev_pandas/pandas/_config/display.py

Prompts

```
['create a pandas config option with a key, default value, description, and validator function', 'get or set a pandas configuration option value by dot-notation key pattern', 'test temporarily setting pandas options within a with block that restores values on exit', 'review marking a pandas config option as deprecated with a replacement key and warning message', 'build a type validator factory function for registering pandas config option value constraints', 'run detect_console_encoding to find the most capable encoding supported by the console', 'test detect_console_encoding returns a non-empty encoding string from sys.stdout.encoding, locale, or sys.getdefaultencoding', 'review the pandas config option registration for display.encoding with detect_console_encoding as default and cf.is_text validator', "summarize the display module's purpose of configuring string encoding for console output in pandas to_string calls", 'refactor detect_console_encoding to add fallback logic for edge cases where all encoding sources return ascii or None', 'test the set_locale context manager to temporarily set a locale for a code block', 'test the can_set_locale function to check if a locale string is valid on the system', 'test the get_locales function to retrieve all available system locales with an optional prefix filter', 'review the set_locale context manager and its thread-safety implications', 'summarize the get_locales function and its platform-specific behavior on Linux and Darwin']
```

Usage

```
{'run_detect_console_encoding': 'run detect_console_encoding to find the most capable encoding supported by the console', 'test_detect_console_encoding': 'test detect_console_encoding returns a non-empty encoding string from sys.stdout.encoding, locale, or sys.getdefaultencoding', 'review_config_register_encoding': 'review the pandas config option registration for display.encoding with detect_console_encoding as default and cf.is_text validator', 'summarize_display_config': "summarize the display module's purpose of configuring string encoding for console output in pandas to_string calls", 'refactor_detect_console_encoding': 'refactor detect_console_encoding to add fallback logic for edge cases where all encoding sources return ascii or None'}
```

## File: pandas-dev_pandas/pandas/_config/localization.py

Prompts

```
['create a pandas config option with a key, default value, description, and validator function', 'get or set a pandas configuration option value by dot-notation key pattern', 'test temporarily setting pandas options within a with block that restores values on exit', 'review marking a pandas config option as deprecated with a replacement key and warning message', 'build a type validator factory function for registering pandas config option value constraints', 'run detect_console_encoding to find the most capable encoding supported by the console', 'test detect_console_encoding returns a non-empty encoding string from sys.stdout.encoding, locale, or sys.getdefaultencoding', 'review the pandas config option registration for display.encoding with detect_console_encoding as default and cf.is_text validator', "summarize the display module's purpose of configuring string encoding for console output in pandas to_string calls", 'refactor detect_console_encoding to add fallback logic for edge cases where all encoding sources return ascii or None', 'test the set_locale context manager to temporarily set a locale for a code block', 'test the can_set_locale function to check if a locale string is valid on the system', 'test the get_locales function to retrieve all available system locales with an optional prefix filter', 'review the set_locale context manager and its thread-safety implications', 'summarize the get_locales function and its platform-specific behavior on Linux and Darwin']
```

Usage

```
{'test_set_locale': 'test the set_locale context manager to temporarily set a locale for a code block', 'test_can_set_locale': 'test the can_set_locale function to check if a locale string is valid on the system', 'test_get_locales': 'test the get_locales function to retrieve all available system locales with an optional prefix filter', 'review_set_locale': 'review the set_locale context manager and its thread-safety implications', 'summarize_get_locales': 'summarize the get_locales function and its platform-specific behavior on Linux and Darwin'}
```

