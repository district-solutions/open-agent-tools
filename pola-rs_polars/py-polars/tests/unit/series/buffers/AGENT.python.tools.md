# Agent Python Tools

- repo: pola-rs/polars
- repo_uri: https://github.com/pola-rs/polars.git

## File: pola-rs_polars/py-polars/tests/unit/series/buffers/test_from_buffer.py

Prompts

```
['test pl.Series._from_buffer reconstructs a numeric series from its buffer info', 'test pl.Series._from_buffer with UInt16 dtype reconstructs the original series', 'test pl.Series._from_buffer with a sliced boolean series and bitmask buffer', 'test pl.Series._from_buffer raises TypeError for non-physical dtypes like date', 'test pl.Series._from_buffer round-trips series via _get_buffer_info using hypothesis parametric testing', 'test pl.Series._from_buffers reconstructs a numeric series with validity buffer preserving nulls', 'test pl.Series._from_buffers reconstructs a numeric series without validity buffer when no nulls present', 'test pl.Series._from_buffers reconstructs a temporal series from its physical integer representation with validity', 'test pl.Series._from_buffers constructs a string series from data and offsets buffers with validity mask', 'test pl.Series._from_buffers constructs an enum series from integer codes with validity mask', 'test the _get_buffer_info method on a numeric polars Series and verify the primary buffer pointer is greater than zero', 'test the _get_buffer_info method on a boolean polars Series and verify buffer info for a sliced Series', 'test the _get_buffer_info method after rechunking a polars Series and verify the buffer pointer changes', 'test the _get_buffer_info method on a string polars Series and verify it raises a TypeError', 'test the _get_buffer_info method on a chunked polars Series and verify it raises a ComputeError', 'test _get_buffers returns values with no validity or offsets for a plain integer series', 'test _get_buffers extracts validity buffer for a series containing null values', 'test _get_buffers extracts values, validity, and offsets buffers for a string series', 'test _get_buffers handles sliced logical types like date with validity buffer', 'test _get_buffers preserves chunk count for validity buffer on a chunked series']
```

Usage

```
{'test_series_from_buffer': 'test pl.Series._from_buffer reconstructs a numeric series from its buffer info', 'test_series_from_buffer_numeric': 'test pl.Series._from_buffer with UInt16 dtype reconstructs the original series', 'test_series_from_buffer_sliced_bitmask': 'test pl.Series._from_buffer with a sliced boolean series and bitmask buffer', 'test_series_from_buffer_unsupported': 'test pl.Series._from_buffer raises TypeError for non-physical dtypes like date', 'test_series_from_buffer_hypothesis': 'test pl.Series._from_buffer round-trips series via _get_buffer_info using hypothesis parametric testing'}
```

## File: pola-rs_polars/py-polars/tests/unit/series/buffers/test_from_buffers.py

Prompts

```
['test pl.Series._from_buffer reconstructs a numeric series from its buffer info', 'test pl.Series._from_buffer with UInt16 dtype reconstructs the original series', 'test pl.Series._from_buffer with a sliced boolean series and bitmask buffer', 'test pl.Series._from_buffer raises TypeError for non-physical dtypes like date', 'test pl.Series._from_buffer round-trips series via _get_buffer_info using hypothesis parametric testing', 'test pl.Series._from_buffers reconstructs a numeric series with validity buffer preserving nulls', 'test pl.Series._from_buffers reconstructs a numeric series without validity buffer when no nulls present', 'test pl.Series._from_buffers reconstructs a temporal series from its physical integer representation with validity', 'test pl.Series._from_buffers constructs a string series from data and offsets buffers with validity mask', 'test pl.Series._from_buffers constructs an enum series from integer codes with validity mask', 'test the _get_buffer_info method on a numeric polars Series and verify the primary buffer pointer is greater than zero', 'test the _get_buffer_info method on a boolean polars Series and verify buffer info for a sliced Series', 'test the _get_buffer_info method after rechunking a polars Series and verify the buffer pointer changes', 'test the _get_buffer_info method on a string polars Series and verify it raises a TypeError', 'test the _get_buffer_info method on a chunked polars Series and verify it raises a ComputeError', 'test _get_buffers returns values with no validity or offsets for a plain integer series', 'test _get_buffers extracts validity buffer for a series containing null values', 'test _get_buffers extracts values, validity, and offsets buffers for a string series', 'test _get_buffers handles sliced logical types like date with validity buffer', 'test _get_buffers preserves chunk count for validity buffer on a chunked series']
```

Usage

```
{'test_series_from_buffers_numeric_with_validity': 'test pl.Series._from_buffers reconstructs a numeric series with validity buffer preserving nulls', 'test_series_from_buffers_numeric': 'test pl.Series._from_buffers reconstructs a numeric series without validity buffer when no nulls present', 'test_series_from_buffers_temporal_with_validity': 'test pl.Series._from_buffers reconstructs a temporal series from its physical integer representation with validity', 'test_series_from_buffers_string': 'test pl.Series._from_buffers constructs a string series from data and offsets buffers with validity mask', 'test_series_from_buffers_enum': 'test pl.Series._from_buffers constructs an enum series from integer codes with validity mask'}
```

## File: pola-rs_polars/py-polars/tests/unit/series/buffers/test_get_buffer_info.py

Prompts

```
['test pl.Series._from_buffer reconstructs a numeric series from its buffer info', 'test pl.Series._from_buffer with UInt16 dtype reconstructs the original series', 'test pl.Series._from_buffer with a sliced boolean series and bitmask buffer', 'test pl.Series._from_buffer raises TypeError for non-physical dtypes like date', 'test pl.Series._from_buffer round-trips series via _get_buffer_info using hypothesis parametric testing', 'test pl.Series._from_buffers reconstructs a numeric series with validity buffer preserving nulls', 'test pl.Series._from_buffers reconstructs a numeric series without validity buffer when no nulls present', 'test pl.Series._from_buffers reconstructs a temporal series from its physical integer representation with validity', 'test pl.Series._from_buffers constructs a string series from data and offsets buffers with validity mask', 'test pl.Series._from_buffers constructs an enum series from integer codes with validity mask', 'test the _get_buffer_info method on a numeric polars Series and verify the primary buffer pointer is greater than zero', 'test the _get_buffer_info method on a boolean polars Series and verify buffer info for a sliced Series', 'test the _get_buffer_info method after rechunking a polars Series and verify the buffer pointer changes', 'test the _get_buffer_info method on a string polars Series and verify it raises a TypeError', 'test the _get_buffer_info method on a chunked polars Series and verify it raises a ComputeError', 'test _get_buffers returns values with no validity or offsets for a plain integer series', 'test _get_buffers extracts validity buffer for a series containing null values', 'test _get_buffers extracts values, validity, and offsets buffers for a string series', 'test _get_buffers handles sliced logical types like date with validity buffer', 'test _get_buffers preserves chunk count for validity buffer on a chunked series']
```

Usage

```
{'test_get_buffer_info_numeric': 'test the _get_buffer_info method on a numeric polars Series and verify the primary buffer pointer is greater than zero', 'test_get_buffer_info_bool': 'test the _get_buffer_info method on a boolean polars Series and verify buffer info for a sliced Series', 'test_get_buffer_info_after_rechunk': 'test the _get_buffer_info method after rechunking a polars Series and verify the buffer pointer changes', 'test_get_buffer_info_invalid_data_type': 'test the _get_buffer_info method on a string polars Series and verify it raises a TypeError', 'test_get_buffer_info_chunked': 'test the _get_buffer_info method on a chunked polars Series and verify it raises a ComputeError'}
```

## File: pola-rs_polars/py-polars/tests/unit/series/buffers/test_get_buffers.py

Prompts

```
['test pl.Series._from_buffer reconstructs a numeric series from its buffer info', 'test pl.Series._from_buffer with UInt16 dtype reconstructs the original series', 'test pl.Series._from_buffer with a sliced boolean series and bitmask buffer', 'test pl.Series._from_buffer raises TypeError for non-physical dtypes like date', 'test pl.Series._from_buffer round-trips series via _get_buffer_info using hypothesis parametric testing', 'test pl.Series._from_buffers reconstructs a numeric series with validity buffer preserving nulls', 'test pl.Series._from_buffers reconstructs a numeric series without validity buffer when no nulls present', 'test pl.Series._from_buffers reconstructs a temporal series from its physical integer representation with validity', 'test pl.Series._from_buffers constructs a string series from data and offsets buffers with validity mask', 'test pl.Series._from_buffers constructs an enum series from integer codes with validity mask', 'test the _get_buffer_info method on a numeric polars Series and verify the primary buffer pointer is greater than zero', 'test the _get_buffer_info method on a boolean polars Series and verify buffer info for a sliced Series', 'test the _get_buffer_info method after rechunking a polars Series and verify the buffer pointer changes', 'test the _get_buffer_info method on a string polars Series and verify it raises a TypeError', 'test the _get_buffer_info method on a chunked polars Series and verify it raises a ComputeError', 'test _get_buffers returns values with no validity or offsets for a plain integer series', 'test _get_buffers extracts validity buffer for a series containing null values', 'test _get_buffers extracts values, validity, and offsets buffers for a string series', 'test _get_buffers handles sliced logical types like date with validity buffer', 'test _get_buffers preserves chunk count for validity buffer on a chunked series']
```

Usage

```
{'test_get_buffers_only_values': 'test _get_buffers returns values with no validity or offsets for a plain integer series', 'test_get_buffers_with_validity': 'test _get_buffers extracts validity buffer for a series containing null values', 'test_get_buffers_string_type': 'test _get_buffers extracts values, validity, and offsets buffers for a string series', 'test_get_buffers_logical_sliced': 'test _get_buffers handles sliced logical types like date with validity buffer', 'test_get_buffers_chunked': 'test _get_buffers preserves chunk count for validity buffer on a chunked series'}
```

