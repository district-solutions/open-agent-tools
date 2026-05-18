# Agent Python Tools

- repo: facebookresearch/neuraldb
- repo_uri: https://github.com/facebookresearch/neuraldb

## File: facebookresearch_neuraldb/dataset-construction/src/ndb_data/wikidata_common/kelm.py

Prompts

```
['create a KELMMongo instance to connect to the kelm MongoDB collection', 'find all documents in the kelm collection matching a given entity name', 'find documents matching an entity filtered by a list of relations', 'review the KELMMongo class and its MongoDB query methods for entity lookups', 'refactor KELMMongo find_entity_rel to support additional query filters beyond relations', 'create a python module that uses Wikidata.get_by_id_or_uri to fetch a Wikidata entity from MongoDB by its URI', 'create a python module that uses Wikidata.find_custom to query the wiki_graph collection with a custom key and list of tokens', 'create a python module that uses Wikidata.find_matching_relation to find all entities with a specific property type', 'review the Wikidata class and its MongoDB data access methods for the wiki_graph collection', 'refactor Wikidata.find_custom to support additional MongoDB query operators beyond $in', 'create a Wikipedia instance that connects to MongoDB and accesses the wiki_redirects collection', 'resolve a list of Wikipedia page titles to their redirect targets using MongoDB lookup', 'review the Wikipedia class that extends MongoDataSource to resolve wiki page redirects', 'test the resolve_redirect method by passing a list of Wikipedia titles and verifying returned targets', 'refactor resolve_redirect to use a list comprehension instead of a manual loop for appending targets']
```

Usage

```
{'create_KELMMongo_instance': 'create a KELMMongo instance to connect to the kelm MongoDB collection', 'find_entity_by_name': 'find all documents in the kelm collection matching a given entity name', 'find_entity_with_relations': 'find documents matching an entity filtered by a list of relations', 'review_KELMMongo_class': 'review the KELMMongo class and its MongoDB query methods for entity lookups', 'refactor_KELMMongo_find_entity_rel': 'refactor KELMMongo find_entity_rel to support additional query filters beyond relations'}
```

## File: facebookresearch_neuraldb/dataset-construction/src/ndb_data/wikidata_common/wikidata.py

Prompts

```
['create a KELMMongo instance to connect to the kelm MongoDB collection', 'find all documents in the kelm collection matching a given entity name', 'find documents matching an entity filtered by a list of relations', 'review the KELMMongo class and its MongoDB query methods for entity lookups', 'refactor KELMMongo find_entity_rel to support additional query filters beyond relations', 'create a python module that uses Wikidata.get_by_id_or_uri to fetch a Wikidata entity from MongoDB by its URI', 'create a python module that uses Wikidata.find_custom to query the wiki_graph collection with a custom key and list of tokens', 'create a python module that uses Wikidata.find_matching_relation to find all entities with a specific property type', 'review the Wikidata class and its MongoDB data access methods for the wiki_graph collection', 'refactor Wikidata.find_custom to support additional MongoDB query operators beyond $in', 'create a Wikipedia instance that connects to MongoDB and accesses the wiki_redirects collection', 'resolve a list of Wikipedia page titles to their redirect targets using MongoDB lookup', 'review the Wikipedia class that extends MongoDataSource to resolve wiki page redirects', 'test the resolve_redirect method by passing a list of Wikipedia titles and verifying returned targets', 'refactor resolve_redirect to use a list comprehension instead of a manual loop for appending targets']
```

Usage

```
{'get_wikidata_entity_by_uri': 'create a python module that uses Wikidata.get_by_id_or_uri to fetch a Wikidata entity from MongoDB by its URI', 'find_wikidata_custom_query': 'create a python module that uses Wikidata.find_custom to query the wiki_graph collection with a custom key and list of tokens', 'find_wikidata_matching_relation': 'create a python module that uses Wikidata.find_matching_relation to find all entities with a specific property type', 'review_Wikidata_class': 'review the Wikidata class and its MongoDB data access methods for the wiki_graph collection', 'refactor_Wikidata_find_custom': 'refactor Wikidata.find_custom to support additional MongoDB query operators beyond $in'}
```

## File: facebookresearch_neuraldb/dataset-construction/src/ndb_data/wikidata_common/wikpedia.py

Prompts

```
['create a KELMMongo instance to connect to the kelm MongoDB collection', 'find all documents in the kelm collection matching a given entity name', 'find documents matching an entity filtered by a list of relations', 'review the KELMMongo class and its MongoDB query methods for entity lookups', 'refactor KELMMongo find_entity_rel to support additional query filters beyond relations', 'create a python module that uses Wikidata.get_by_id_or_uri to fetch a Wikidata entity from MongoDB by its URI', 'create a python module that uses Wikidata.find_custom to query the wiki_graph collection with a custom key and list of tokens', 'create a python module that uses Wikidata.find_matching_relation to find all entities with a specific property type', 'review the Wikidata class and its MongoDB data access methods for the wiki_graph collection', 'refactor Wikidata.find_custom to support additional MongoDB query operators beyond $in', 'create a Wikipedia instance that connects to MongoDB and accesses the wiki_redirects collection', 'resolve a list of Wikipedia page titles to their redirect targets using MongoDB lookup', 'review the Wikipedia class that extends MongoDataSource to resolve wiki page redirects', 'test the resolve_redirect method by passing a list of Wikipedia titles and verifying returned targets', 'refactor resolve_redirect to use a list comprehension instead of a manual loop for appending targets']
```

Usage

```
{'create_wikipedia_instance': 'create a Wikipedia instance that connects to MongoDB and accesses the wiki_redirects collection', 'resolve_redirect_names': 'resolve a list of Wikipedia page titles to their redirect targets using MongoDB lookup', 'review_wikipedia_class': 'review the Wikipedia class that extends MongoDataSource to resolve wiki page redirects', 'test_resolve_redirect': 'test the resolve_redirect method by passing a list of Wikipedia titles and verifying returned targets', 'refactor_resolve_redirect': 'refactor resolve_redirect to use a list comprehension instead of a manual loop for appending targets'}
```

