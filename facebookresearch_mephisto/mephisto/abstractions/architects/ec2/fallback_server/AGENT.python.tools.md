# Agent Python Tools

- repo: facebookresearch/mephisto
- repo_uri: https://github.com/facebookresearch/mephisto

## File: facebookresearch_mephisto/mephisto/abstractions/architects/ec2/fallback_server/app.py

Prompts

```
['run the Flask fallback server on port 5000 using gevent WSGIServer', 'view access logs from the view_logs endpoint with an access_key and optional timestamp filter', 'create an access log JSON file when a non-internal host hits the main route', 'review the password-based access control using access_key.txt for the view_logs endpoint', 'refactor the main_route to handle path routing and log non-internal host access']
```

Usage

```
{'run_flask_fallback_server': 'run the Flask fallback server on port 5000 using gevent WSGIServer', 'view_access_logs': 'view access logs from the view_logs endpoint with an access_key and optional timestamp filter', 'create_access_log_entry': 'create an access log JSON file when a non-internal host hits the main route', 'review_password_auth': 'review the password-based access control using access_key.txt for the view_logs endpoint', 'refactor_main_route': 'refactor the main_route to handle path routing and log non-internal host access'}
```

