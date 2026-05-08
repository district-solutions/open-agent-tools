# Agent Python Tools

- repo: facebookresearch/mephisto
- repo_uri: https://github.com/facebookresearch/mephisto

## File: facebookresearch_mephisto/mephisto/review_app/server/db_queries.py

Prompts

```
['find all units in the database filtered by a specific task_id', 'find all units in the database filtered by one or more status values', 'find all units matching both a task_id and a list of statuses', 'find all units in the database with no filters applied', 'review the find_units function that queries the units table with optional task_id and status filters', 'register all mephisto review app API URL routes on a Flask application instance', 'review the TaskExportResultsView and TaskExportResultsJsonView endpoints for exporting task results', 'review the qualifications CRUD endpoints including grant and revoke worker qualifications', 'review the units approve, reject, and soft-reject endpoints for task unit moderation', 'review the worker block and worker qualifications grant endpoints for worker management']
```

Usage

```
{'find_units_by_task_id': 'find all units in the database filtered by a specific task_id', 'find_units_by_status': 'find all units in the database filtered by one or more status values', 'find_units_by_task_and_status': 'find all units matching both a task_id and a list of statuses', 'find_all_units': 'find all units in the database with no filters applied', 'review_find_units': 'review the find_units function that queries the units table with optional task_id and status filters'}
```

## File: facebookresearch_mephisto/mephisto/review_app/server/urls.py

Prompts

```
['find all units in the database filtered by a specific task_id', 'find all units in the database filtered by one or more status values', 'find all units matching both a task_id and a list of statuses', 'find all units in the database with no filters applied', 'review the find_units function that queries the units table with optional task_id and status filters', 'register all mephisto review app API URL routes on a Flask application instance', 'review the TaskExportResultsView and TaskExportResultsJsonView endpoints for exporting task results', 'review the qualifications CRUD endpoints including grant and revoke worker qualifications', 'review the units approve, reject, and soft-reject endpoints for task unit moderation', 'review the worker block and worker qualifications grant endpoints for worker management']
```

Usage

```
{'init_urls_flask_app': 'register all mephisto review app API URL routes on a Flask application instance', 'review_task_export_results': 'review the TaskExportResultsView and TaskExportResultsJsonView endpoints for exporting task results', 'review_qualifications_api': 'review the qualifications CRUD endpoints including grant and revoke worker qualifications', 'review_units_approval_api': 'review the units approve, reject, and soft-reject endpoints for task unit moderation', 'review_worker_management_api': 'review the worker block and worker qualifications grant endpoints for worker management'}
```

