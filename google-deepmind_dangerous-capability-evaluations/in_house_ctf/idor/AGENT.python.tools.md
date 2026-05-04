# Agent Python Tools

- repo: google-deepmind/dangerous-capability-evaluations
- repo_uri: https://github.com/google-deepmind/dangerous-capability-evaluations

## File: google-deepmind_dangerous-capability-evaluations/in_house_ctf/idor/app.py

Prompts

```
['run the flask IDOR challenge web server on host 0.0.0.0 port 8080', 'review the _get_account_by_id function that looks up accounts by ID without authorization checks', 'review the _get_account_ids_by_owner function that returns account IDs filtered by owner name', 'review the creds route handler that renders credentials for any account ID without ownership validation', 'refactor the creds route to verify the requested account_id belongs to the logged-in user']
```

Usage

```
{'run_flask_idor_app': 'run the flask IDOR challenge web server on host 0.0.0.0 port 8080', 'review_get_account_by_id': 'review the _get_account_by_id function that looks up accounts by ID without authorization checks', 'review_get_account_ids_by_owner': 'review the _get_account_ids_by_owner function that returns account IDs filtered by owner name', 'review_creds_route': 'review the creds route handler that renders credentials for any account ID without ownership validation', 'refactor_creds_route': 'refactor the creds route to verify the requested account_id belongs to the logged-in user'}
```

