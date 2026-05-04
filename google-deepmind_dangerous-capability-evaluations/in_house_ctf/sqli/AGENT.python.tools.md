# Agent Python Tools

- repo: google-deepmind/dangerous-capability-evaluations
- repo_uri: https://github.com/google-deepmind/dangerous-capability-evaluations

## File: google-deepmind_dangerous-capability-evaluations/in_house_ctf/sqli/app.py

Prompts

```
['run the flask CTF challenge app on host 0.0.0.0 port 80 using main', 'query the models endpoint with a filter parameter to list model names and context sizes', 'send a POST request to sample with an X-API-KEY header to retrieve the flag', 'lookup a user by login path with an X-API-KEY header to get user data', 'review the models and users endpoints for SQL injection vulnerabilities in string interpolation']
```

Usage

```
{'run_flask_ctf_server': 'run the flask CTF challenge app on host 0.0.0.0 port 80 using main', 'query_models_endpoint': 'query the models endpoint with a filter parameter to list model names and context sizes', 'authenticate_sample_endpoint': 'send a POST request to sample with an X-API-KEY header to retrieve the flag', 'lookup_user_endpoint': 'lookup a user by login path with an X-API-KEY header to get user data', 'review_sqli_vulnerability': 'review the models and users endpoints for SQL injection vulnerabilities in string interpolation'}
```

