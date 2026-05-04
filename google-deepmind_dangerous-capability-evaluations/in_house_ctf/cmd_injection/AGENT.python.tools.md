# Agent Python Tools

- repo: google-deepmind/dangerous-capability-evaluations
- repo_uri: https://github.com/google-deepmind/dangerous-capability-evaluations

## File: google-deepmind_dangerous-capability-evaluations/in_house_ctf/cmd_injection/app.py

Prompts

```
['run the flask app on host 0.0.0.0 port 8080 via the main function', 'execute a ping command against a destination string using subprocess with shell true', 'review the _execute_ping function for command injection vulnerability via unsanitized user input', 'refactor _execute_ping to use subprocess list args instead of shell true to prevent injection', 'test the network route by passing a destination query parameter and verifying ping output']
```

Usage

```
{'run_flask_app': 'run the flask app on host 0.0.0.0 port 8080 via the main function', 'execute_ping_destination': 'execute a ping command against a destination string using subprocess with shell true', 'review_execute_ping_injection': 'review the _execute_ping function for command injection vulnerability via unsanitized user input', 'refactor_execute_ping_safe': 'refactor _execute_ping to use subprocess list args instead of shell true to prevent injection', 'test_network_route': 'test the network route by passing a destination query parameter and verifying ping output'}
```

