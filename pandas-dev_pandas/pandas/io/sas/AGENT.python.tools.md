# Agent Python Tools

- repo: pandas-dev/pandas
- repo_uri: https://github.com/pandas-dev/pandas.git

## File: pandas-dev_pandas/pandas/io/sas/sas7bdat.py

Prompts

```
['read a SAS7BDAT file into a pandas DataFrame with configurable encoding and date conversion', 'create a SAS7BDATReader instance to parse SAS7BDAT binary data files with chunked iteration support', 'convert SAS date and datetime float values to pandas datetime64 Series with Gregorian calendar correction', 'read a SAS7BDAT file in chunks by specifying chunksize for memory-efficient iterative DataFrame access', 'close a SAS7BDATReader file handle and release resources after reading', 'create a function that reads a SAS Xport file and returns a pandas DataFrame', 'read a SAS Xport file into a pandas DataFrame using pd.read_sas', 'create an XportReader instance to read a SAS Xport file incrementally with chunksize', 'read a SAS Xport file in chunks using XportReader.get_chunk and iterate over DataFrames', 'parse IBM 8-byte floating point values from SAS Xport binary data into native IEEE floats', 'read a SAS sas7bdat or xport file and return a DataFrame', 'read a SAS file in chunks by specifying chunksize for incremental iteration', 'read a SAS file incrementally using the iterator parameter to return a SASReader', 'read a SAS file with a specified encoding for text data columns', 'read a compressed SAS file by inferring compression from the file extension']
```

Usage

```
{'read_sas7bdat_file': 'read a SAS7BDAT file into a pandas DataFrame with configurable encoding and date conversion', 'create_sas7bdat_reader': 'create a SAS7BDATReader instance to parse SAS7BDAT binary data files with chunked iteration support', 'convert_sas_datetimes': 'convert SAS date and datetime float values to pandas datetime64 Series with Gregorian calendar correction', 'read_sas7bdat_chunks': 'read a SAS7BDAT file in chunks by specifying chunksize for memory-efficient iterative DataFrame access', 'close_sas7bdat_reader': 'close a SAS7BDATReader file handle and release resources after reading'}
```

## File: pandas-dev_pandas/pandas/io/sas/sas_xport.py

Prompts

```
['read a SAS7BDAT file into a pandas DataFrame with configurable encoding and date conversion', 'create a SAS7BDATReader instance to parse SAS7BDAT binary data files with chunked iteration support', 'convert SAS date and datetime float values to pandas datetime64 Series with Gregorian calendar correction', 'read a SAS7BDAT file in chunks by specifying chunksize for memory-efficient iterative DataFrame access', 'close a SAS7BDATReader file handle and release resources after reading', 'create a function that reads a SAS Xport file and returns a pandas DataFrame', 'read a SAS Xport file into a pandas DataFrame using pd.read_sas', 'create an XportReader instance to read a SAS Xport file incrementally with chunksize', 'read a SAS Xport file in chunks using XportReader.get_chunk and iterate over DataFrames', 'parse IBM 8-byte floating point values from SAS Xport binary data into native IEEE floats', 'read a SAS sas7bdat or xport file and return a DataFrame', 'read a SAS file in chunks by specifying chunksize for incremental iteration', 'read a SAS file incrementally using the iterator parameter to return a SASReader', 'read a SAS file with a specified encoding for text data columns', 'read a compressed SAS file by inferring compression from the file extension']
```

Usage

```
{'create_function_read_sas_xport': 'create a function that reads a SAS Xport file and returns a pandas DataFrame', 'read_sas_xport_file': 'read a SAS Xport file into a pandas DataFrame using pd.read_sas', 'create_xport_reader_incremental': 'create an XportReader instance to read a SAS Xport file incrementally with chunksize', 'read_xport_chunks': 'read a SAS Xport file in chunks using XportReader.get_chunk and iterate over DataFrames', 'parse_xport_floats': 'parse IBM 8-byte floating point values from SAS Xport binary data into native IEEE floats'}
```

## File: pandas-dev_pandas/pandas/io/sas/sasreader.py

Prompts

```
['read a SAS7BDAT file into a pandas DataFrame with configurable encoding and date conversion', 'create a SAS7BDATReader instance to parse SAS7BDAT binary data files with chunked iteration support', 'convert SAS date and datetime float values to pandas datetime64 Series with Gregorian calendar correction', 'read a SAS7BDAT file in chunks by specifying chunksize for memory-efficient iterative DataFrame access', 'close a SAS7BDATReader file handle and release resources after reading', 'create a function that reads a SAS Xport file and returns a pandas DataFrame', 'read a SAS Xport file into a pandas DataFrame using pd.read_sas', 'create an XportReader instance to read a SAS Xport file incrementally with chunksize', 'read a SAS Xport file in chunks using XportReader.get_chunk and iterate over DataFrames', 'parse IBM 8-byte floating point values from SAS Xport binary data into native IEEE floats', 'read a SAS sas7bdat or xport file and return a DataFrame', 'read a SAS file in chunks by specifying chunksize for incremental iteration', 'read a SAS file incrementally using the iterator parameter to return a SASReader', 'read a SAS file with a specified encoding for text data columns', 'read a compressed SAS file by inferring compression from the file extension']
```

Usage

```
{'read_sas': 'read a SAS sas7bdat or xport file and return a DataFrame', 'read_sas_chunked': 'read a SAS file in chunks by specifying chunksize for incremental iteration', 'read_sas_iterator': 'read a SAS file incrementally using the iterator parameter to return a SASReader', 'read_sas_with_encoding': 'read a SAS file with a specified encoding for text data columns', 'read_sas_with_compression': 'read a compressed SAS file by inferring compression from the file extension'}
```

