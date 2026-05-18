# Agent Python Tools

- repo: facebookresearch/neuraldb
- repo_uri: https://github.com/facebookresearch/neuraldb

## File: facebookresearch_neuraldb/dataset-construction/src/ndb_data/data_import/fix_sitelinks.py

Prompts

```
['run the script to convert dict sitelinks to lists in the Wikidata MongoDB collection', 'run write_updates to bulk write a batch of pymongo UpdateOne operations to the collection', 'review the write_updates function that converts batch tuples into pymongo UpdateOne bulk writes', 'refactor write_updates to accept the collection as a parameter instead of relying on a global', 'summarize the fix_sitelinks script that iterates Wikidata documents and converts dict sitelinks to lists', 'run the python module to index a bz2 Wikidata dump file into a MongoDB collection', 'create a generator that reads lines from a bz2 compressed Wikidata dump file', 'extract wikidata_id, english_name, sitelinks, properties, and claims from a Wikidata instance dict', 'parse JSON lines from a Wikidata dump and yield indexable fields for each entity', 'review the main block that batches and inserts Wikidata entities into MongoDB in groups of 5000']
```

Usage

```
{'run_fix_sitelinks': 'run the script to convert dict sitelinks to lists in the Wikidata MongoDB collection', 'run_write_updates': 'run write_updates to bulk write a batch of pymongo UpdateOne operations to the collection', 'review_write_updates': 'review the write_updates function that converts batch tuples into pymongo UpdateOne bulk writes', 'refactor_write_updates': 'refactor write_updates to accept the collection as a parameter instead of relying on a global', 'summarize_fix_sitelinks': 'summarize the fix_sitelinks script that iterates Wikidata documents and converts dict sitelinks to lists'}
```

## File: facebookresearch_neuraldb/dataset-construction/src/ndb_data/data_import/wikidata_index.py

Prompts

```
['run the script to convert dict sitelinks to lists in the Wikidata MongoDB collection', 'run write_updates to bulk write a batch of pymongo UpdateOne operations to the collection', 'review the write_updates function that converts batch tuples into pymongo UpdateOne bulk writes', 'refactor write_updates to accept the collection as a parameter instead of relying on a global', 'summarize the fix_sitelinks script that iterates Wikidata documents and converts dict sitelinks to lists', 'run the python module to index a bz2 Wikidata dump file into a MongoDB collection', 'create a generator that reads lines from a bz2 compressed Wikidata dump file', 'extract wikidata_id, english_name, sitelinks, properties, and claims from a Wikidata instance dict', 'parse JSON lines from a Wikidata dump and yield indexable fields for each entity', 'review the main block that batches and inserts Wikidata entities into MongoDB in groups of 5000']
```

Usage

```
{'run_wikidata_index': 'run the python module to index a bz2 Wikidata dump file into a MongoDB collection', 'read_dump_function': 'create a generator that reads lines from a bz2 compressed Wikidata dump file', 'get_indexable_function': 'extract wikidata_id, english_name, sitelinks, properties, and claims from a Wikidata instance dict', 'index_dump_function': 'parse JSON lines from a Wikidata dump and yield indexable fields for each entity', 'review_main_batch_insert': 'review the main block that batches and inserts Wikidata entities into MongoDB in groups of 5000'}
```

