# Agent Python Tools

- repo: facebookresearch/personal-timeline
- repo_uri: https://github.com/facebookresearch/personal-timeline

## File: facebookresearch_personal-timeline/src/qa/posttext/server.py

Prompts

```
['run the flask server by passing a data directory path as a command line argument', 'create the flask app by loading config.ini and initializing the PostText engine', 'query the PostText engine via the GET /query endpoint with a query parameter', 'test the flask server by hitting the GET /test endpoint with arbitrary query parameters', 'review the query route that returns prompt, sql_before, sql_after, and result from PostText']
```

Usage

```
{'run_flask_server': 'run the flask server by passing a data directory path as a command line argument', 'create_app': 'create the flask app by loading config.ini and initializing the PostText engine', 'query_posttext_engine': 'query the PostText engine via the GET /query endpoint with a query parameter', 'test_endpoint': 'test the flask server by hitting the GET /test endpoint with arbitrary query parameters', 'review_query_route': 'review the query route that returns prompt, sql_before, sql_after, and result from PostText'}
```

