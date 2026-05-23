# Agent Python Tools

- repo: facebookresearch/personal-timeline
- repo_uri: https://github.com/facebookresearch/personal-timeline

## File: facebookresearch_personal-timeline/src/qa/posttext/util/data2vectorstore.py

Prompts

```
['build a FAISS vector store from a CSV file with date and description columns using OpenAI embeddings', 'create a function that converts a DataFrame chunk with date and desc columns into a formatted string', 'run the main pipeline to read CSV chunks, create documents, and save a FAISS vector store as pickle', 'create LangChain Document objects from CSV data by reading chunks and formatting date and description fields', 'serialize a FAISS vector store to a pickle file for later retrieval and semantic search', 'run the python module to convert a CSV of episodes into a FAISS vector store pickle file', 'create a function that verbalizes episode data from a DataFrame into formatted text strings with metadata', 'refactor the verbalize function to support additional date formats beyond YYYY-MM-DD', 'review the main pipeline that reads CSV episodes, verbalizes them, embeds with OpenAI, and saves to FAISS', 'create a Setup instance and call install_metadata to generate embeddings for views catalog and store them in views_idx.csv', 'run install_views to execute create_db.sql and import views into a SQLite database named views_db.sqlite', 'build a function that verbalizes timeline episodes into formatted text with metadata for embedding storage', 'run install_data_embeddings to load timeline.json, generate OpenAI embeddings, and save a FAISS vector store to timeline.pkl', 'run the main setup script with a datasource directory argument to prepare metadata, views DB, and timeline embeddings for querying', 'run the table2text CLI to convert a CSV file into natural language text using a format template', 'run the verbalize function to apply a format template string to each row of a pandas DataFrame', 'create a list of natural language sentences from CSV data by applying a format template to each row', 'refactor the verbalize function to support additional template engines beyond Python str.format', 'summarize the main function that reads a CSV, verbalizes rows, and writes output to a text file']
```

Usage

```
{'build_faiss_vectorstore_from_csv': 'build a FAISS vector store from a CSV file with date and description columns using OpenAI embeddings', 'create_chunk_to_string': 'create a function that converts a DataFrame chunk with date and desc columns into a formatted string', 'run_main_vectorstore_pipeline': 'run the main pipeline to read CSV chunks, create documents, and save a FAISS vector store as pickle', 'create_documents_from_csv': 'create LangChain Document objects from CSV data by reading chunks and formatting date and description fields', 'serialize_vectorstore_to_pickle': 'serialize a FAISS vector store to a pickle file for later retrieval and semantic search'}
```

## File: facebookresearch_personal-timeline/src/qa/posttext/util/digital_data2vectorstore.py

Prompts

```
['build a FAISS vector store from a CSV file with date and description columns using OpenAI embeddings', 'create a function that converts a DataFrame chunk with date and desc columns into a formatted string', 'run the main pipeline to read CSV chunks, create documents, and save a FAISS vector store as pickle', 'create LangChain Document objects from CSV data by reading chunks and formatting date and description fields', 'serialize a FAISS vector store to a pickle file for later retrieval and semantic search', 'run the python module to convert a CSV of episodes into a FAISS vector store pickle file', 'create a function that verbalizes episode data from a DataFrame into formatted text strings with metadata', 'refactor the verbalize function to support additional date formats beyond YYYY-MM-DD', 'review the main pipeline that reads CSV episodes, verbalizes them, embeds with OpenAI, and saves to FAISS', 'create a Setup instance and call install_metadata to generate embeddings for views catalog and store them in views_idx.csv', 'run install_views to execute create_db.sql and import views into a SQLite database named views_db.sqlite', 'build a function that verbalizes timeline episodes into formatted text with metadata for embedding storage', 'run install_data_embeddings to load timeline.json, generate OpenAI embeddings, and save a FAISS vector store to timeline.pkl', 'run the main setup script with a datasource directory argument to prepare metadata, views DB, and timeline embeddings for querying', 'run the table2text CLI to convert a CSV file into natural language text using a format template', 'run the verbalize function to apply a format template string to each row of a pandas DataFrame', 'create a list of natural language sentences from CSV data by applying a format template to each row', 'refactor the verbalize function to support additional template engines beyond Python str.format', 'summarize the main function that reads a CSV, verbalizes rows, and writes output to a text file']
```

Usage

```
{'run_digital_data2vectorstore': 'run the python module to convert a CSV of episodes into a FAISS vector store pickle file', 'build_faiss_vectorstore_from_csv': 'build a FAISS vector store from a CSV file of timeline episodes using OpenAI embeddings', 'create_verbalize_function': 'create a function that verbalizes episode data from a DataFrame into formatted text strings with metadata', 'refactor_verbalize_date_formatting': 'refactor the verbalize function to support additional date formats beyond YYYY-MM-DD', 'review_main_pipeline': 'review the main pipeline that reads CSV episodes, verbalizes them, embeds with OpenAI, and saves to FAISS'}
```

## File: facebookresearch_personal-timeline/src/qa/posttext/util/setup.py

Prompts

```
['build a FAISS vector store from a CSV file with date and description columns using OpenAI embeddings', 'create a function that converts a DataFrame chunk with date and desc columns into a formatted string', 'run the main pipeline to read CSV chunks, create documents, and save a FAISS vector store as pickle', 'create LangChain Document objects from CSV data by reading chunks and formatting date and description fields', 'serialize a FAISS vector store to a pickle file for later retrieval and semantic search', 'run the python module to convert a CSV of episodes into a FAISS vector store pickle file', 'create a function that verbalizes episode data from a DataFrame into formatted text strings with metadata', 'refactor the verbalize function to support additional date formats beyond YYYY-MM-DD', 'review the main pipeline that reads CSV episodes, verbalizes them, embeds with OpenAI, and saves to FAISS', 'create a Setup instance and call install_metadata to generate embeddings for views catalog and store them in views_idx.csv', 'run install_views to execute create_db.sql and import views into a SQLite database named views_db.sqlite', 'build a function that verbalizes timeline episodes into formatted text with metadata for embedding storage', 'run install_data_embeddings to load timeline.json, generate OpenAI embeddings, and save a FAISS vector store to timeline.pkl', 'run the main setup script with a datasource directory argument to prepare metadata, views DB, and timeline embeddings for querying', 'run the table2text CLI to convert a CSV file into natural language text using a format template', 'run the verbalize function to apply a format template string to each row of a pandas DataFrame', 'create a list of natural language sentences from CSV data by applying a format template to each row', 'refactor the verbalize function to support additional template engines beyond Python str.format', 'summarize the main function that reads a CSV, verbalizes rows, and writes output to a text file']
```

Usage

```
{'install_metadata': 'create a Setup instance and call install_metadata to generate embeddings for views catalog and store them in views_idx.csv', 'install_views': 'run install_views to execute create_db.sql and import views into a SQLite database named views_db.sqlite', 'verbalize': 'build a function that verbalizes timeline episodes into formatted text with metadata for embedding storage', 'install_data_embeddings': 'run install_data_embeddings to load timeline.json, generate OpenAI embeddings, and save a FAISS vector store to timeline.pkl', 'main_setup': 'run the main setup script with a datasource directory argument to prepare metadata, views DB, and timeline embeddings for querying'}
```

## File: facebookresearch_personal-timeline/src/qa/posttext/util/table2text.py

Prompts

```
['build a FAISS vector store from a CSV file with date and description columns using OpenAI embeddings', 'create a function that converts a DataFrame chunk with date and desc columns into a formatted string', 'run the main pipeline to read CSV chunks, create documents, and save a FAISS vector store as pickle', 'create LangChain Document objects from CSV data by reading chunks and formatting date and description fields', 'serialize a FAISS vector store to a pickle file for later retrieval and semantic search', 'run the python module to convert a CSV of episodes into a FAISS vector store pickle file', 'create a function that verbalizes episode data from a DataFrame into formatted text strings with metadata', 'refactor the verbalize function to support additional date formats beyond YYYY-MM-DD', 'review the main pipeline that reads CSV episodes, verbalizes them, embeds with OpenAI, and saves to FAISS', 'create a Setup instance and call install_metadata to generate embeddings for views catalog and store them in views_idx.csv', 'run install_views to execute create_db.sql and import views into a SQLite database named views_db.sqlite', 'build a function that verbalizes timeline episodes into formatted text with metadata for embedding storage', 'run install_data_embeddings to load timeline.json, generate OpenAI embeddings, and save a FAISS vector store to timeline.pkl', 'run the main setup script with a datasource directory argument to prepare metadata, views DB, and timeline embeddings for querying', 'run the table2text CLI to convert a CSV file into natural language text using a format template', 'run the verbalize function to apply a format template string to each row of a pandas DataFrame', 'create a list of natural language sentences from CSV data by applying a format template to each row', 'refactor the verbalize function to support additional template engines beyond Python str.format', 'summarize the main function that reads a CSV, verbalizes rows, and writes output to a text file']
```

Usage

```
{'run_table2text_cli': 'run the table2text CLI to convert a CSV file into natural language text using a format template', 'run_verbalize_function': 'run the verbalize function to apply a format template string to each row of a pandas DataFrame', 'create_verbalize_from_csv': 'create a list of natural language sentences from CSV data by applying a format template to each row', 'refactor_verbalize_function': 'refactor the verbalize function to support additional template engines beyond Python str.format', 'summarize_main_function': 'summarize the main function that reads a CSV, verbalizes rows, and writes output to a text file'}
```

