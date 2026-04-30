# Agent Python Tools

- repo: pandas-dev/pandas
- repo_uri: https://github.com/pandas-dev/pandas.git

## File: pandas-dev_pandas/pandas/tseries/frequencies.py

Prompts

```
['infer the frequency string from a DatetimeIndex with regularly spaced timestamps', 'get the closest period frequency alias for an offset string like BQ or BYS', 'check if downsampling is possible between a source frequency like h and a target frequency like D', 'check if upsampling is possible between a source frequency like D and a target frequency like h', 'parse a frequency string like 2D or 3H into a DateOffset object', 'create a Holiday object to compute observance dates with custom offset and observance rules', 'build an AbstractHolidayCalendar subclass with a list of Holiday rules for recurring holidays', 'get a registered holiday calendar instance by name using get_calendar', 'test the Holiday.dates method to compute all occurrences between two dates', 'merge two holiday calendars together with precedence rules based on holiday names']
```

Usage

```
{'infer_freq_datetime_index': 'infer the frequency string from a DatetimeIndex with regularly spaced timestamps', 'get_period_alias_offset': 'get the closest period frequency alias for an offset string like BQ or BYS', 'is_subperiod_downsample': 'check if downsampling is possible between a source frequency like h and a target frequency like D', 'is_superperiod_upsample': 'check if upsampling is possible between a source frequency like D and a target frequency like h', 'to_offset_parse_frequency': 'parse a frequency string like 2D or 3H into a DateOffset object'}
```

## File: pandas-dev_pandas/pandas/tseries/holiday.py

Prompts

```
['infer the frequency string from a DatetimeIndex with regularly spaced timestamps', 'get the closest period frequency alias for an offset string like BQ or BYS', 'check if downsampling is possible between a source frequency like h and a target frequency like D', 'check if upsampling is possible between a source frequency like D and a target frequency like h', 'parse a frequency string like 2D or 3H into a DateOffset object', 'create a Holiday object to compute observance dates with custom offset and observance rules', 'build an AbstractHolidayCalendar subclass with a list of Holiday rules for recurring holidays', 'get a registered holiday calendar instance by name using get_calendar', 'test the Holiday.dates method to compute all occurrences between two dates', 'merge two holiday calendars together with precedence rules based on holiday names']
```

Usage

```
{'create_holiday_date_calculation': 'create a Holiday object to compute observance dates with custom offset and observance rules', 'build_holiday_calendar': 'build an AbstractHolidayCalendar subclass with a list of Holiday rules for recurring holidays', 'get_calendar_instance': 'get a registered holiday calendar instance by name using get_calendar', 'test_holiday_dates_range': 'test the Holiday.dates method to compute all occurrences between two dates', 'merge_holiday_calendars': 'merge two holiday calendars together with precedence rules based on holiday names'}
```

