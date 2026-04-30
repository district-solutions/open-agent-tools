# Agent Python Tools

- repo: berriai/litellm
- repo_uri: https://github.com/berriai/litellm

## File: berriai_litellm/litellm/integrations/focus/serializers/base.py

Prompts

```
['review the FocusSerializer abstract base class and its serialize method', 'create a concrete subclass of FocusSerializer that implements serialize for a specific format', 'test the FocusSerializer.serialize method with a polars DataFrame', 'refactor the FocusSerializer base class to support additional serialization formats', 'summarize the FocusSerializer abstract class and its purpose in Focus export', 'create a FocusCsvSerializer instance to serialize a polars DataFrame to CSV bytes', 'build CSV bytes from a polars DataFrame using FocusCsvSerializer.serialize', 'test that FocusCsvSerializer casts Decimal columns to Float64 before CSV export', 'refactor FocusCsvSerializer.serialize to support optional compression in the CSV output', 'review the FocusCsvSerializer class and its serialize method for edge cases', 'create a FocusParquetSerializer instance to serialize polars DataFrames to parquet bytes', 'test the serialize method of FocusParquetSerializer with a polars DataFrame', 'review the FocusParquetSerializer class and its serialize method', 'refactor the serialize method to support configurable compression instead of hardcoded snappy', 'summarize the FocusParquetSerializer class and its parquet extension attribute']
```

Usage

```
{'review_FocusSerializer': 'review the FocusSerializer abstract base class and its serialize method', 'create_FocusSerializer_subclass': 'create a concrete subclass of FocusSerializer that implements serialize for a specific format', 'test_FocusSerializer_serialize': 'test the FocusSerializer.serialize method with a polars DataFrame', 'refactor_FocusSerializer': 'refactor the FocusSerializer base class to support additional serialization formats', 'summarize_FocusSerializer': 'summarize the FocusSerializer abstract class and its purpose in Focus export'}
```

## File: berriai_litellm/litellm/integrations/focus/serializers/csv.py

Prompts

```
['review the FocusSerializer abstract base class and its serialize method', 'create a concrete subclass of FocusSerializer that implements serialize for a specific format', 'test the FocusSerializer.serialize method with a polars DataFrame', 'refactor the FocusSerializer base class to support additional serialization formats', 'summarize the FocusSerializer abstract class and its purpose in Focus export', 'create a FocusCsvSerializer instance to serialize a polars DataFrame to CSV bytes', 'build CSV bytes from a polars DataFrame using FocusCsvSerializer.serialize', 'test that FocusCsvSerializer casts Decimal columns to Float64 before CSV export', 'refactor FocusCsvSerializer.serialize to support optional compression in the CSV output', 'review the FocusCsvSerializer class and its serialize method for edge cases', 'create a FocusParquetSerializer instance to serialize polars DataFrames to parquet bytes', 'test the serialize method of FocusParquetSerializer with a polars DataFrame', 'review the FocusParquetSerializer class and its serialize method', 'refactor the serialize method to support configurable compression instead of hardcoded snappy', 'summarize the FocusParquetSerializer class and its parquet extension attribute']
```

Usage

```
{'create_focus_csv_serializer': 'create a FocusCsvSerializer instance to serialize a polars DataFrame to CSV bytes', 'build_csv_from_dataframe': 'build CSV bytes from a polars DataFrame using FocusCsvSerializer.serialize', 'test_csv_decimal_casting': 'test that FocusCsvSerializer casts Decimal columns to Float64 before CSV export', 'refactor_csv_serializer': 'refactor FocusCsvSerializer.serialize to support optional compression in the CSV output', 'review_csv_serializer': 'review the FocusCsvSerializer class and its serialize method for edge cases'}
```

## File: berriai_litellm/litellm/integrations/focus/serializers/parquet.py

Prompts

```
['review the FocusSerializer abstract base class and its serialize method', 'create a concrete subclass of FocusSerializer that implements serialize for a specific format', 'test the FocusSerializer.serialize method with a polars DataFrame', 'refactor the FocusSerializer base class to support additional serialization formats', 'summarize the FocusSerializer abstract class and its purpose in Focus export', 'create a FocusCsvSerializer instance to serialize a polars DataFrame to CSV bytes', 'build CSV bytes from a polars DataFrame using FocusCsvSerializer.serialize', 'test that FocusCsvSerializer casts Decimal columns to Float64 before CSV export', 'refactor FocusCsvSerializer.serialize to support optional compression in the CSV output', 'review the FocusCsvSerializer class and its serialize method for edge cases', 'create a FocusParquetSerializer instance to serialize polars DataFrames to parquet bytes', 'test the serialize method of FocusParquetSerializer with a polars DataFrame', 'review the FocusParquetSerializer class and its serialize method', 'refactor the serialize method to support configurable compression instead of hardcoded snappy', 'summarize the FocusParquetSerializer class and its parquet extension attribute']
```

Usage

```
{'create_focus_parquet_serializer': 'create a FocusParquetSerializer instance to serialize polars DataFrames to parquet bytes', 'test_serialize_method': 'test the serialize method of FocusParquetSerializer with a polars DataFrame', 'review_focus_parquet_serializer': 'review the FocusParquetSerializer class and its serialize method', 'refactor_serialize_snappy': 'refactor the serialize method to support configurable compression instead of hardcoded snappy', 'summarize_extension_class': 'summarize the FocusParquetSerializer class and its parquet extension attribute'}
```

