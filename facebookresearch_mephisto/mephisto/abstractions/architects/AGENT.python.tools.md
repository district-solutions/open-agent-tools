# Agent Python Tools

- repo: facebookresearch/mephisto
- repo_uri: https://github.com/facebookresearch/mephisto

## File: facebookresearch_mephisto/mephisto/abstractions/architects/heroku_architect.py

Prompts

```
['deploy a task server to Heroku by initializing git, creating the app, and pushing code', 'shut down and destroy a Heroku app server that was created by the HerokuArchitect', 'prepare and compile server files into a build directory ready for Heroku deployment', 'download a file from a deployed Heroku app via the download_file endpoint', 'check if a Heroku app is still running by querying the list of active apps', 'build a LocalArchitect instance to set up and manage a local server for deploying Mephisto tasks', 'create a LocalArchitectArgs dataclass to configure hostname and port for a local architect server', 'test the get_channels method to return WebsocketChannel instances for ClientIOHandler registration', 'refactor the deploy method to support additional server types beyond node and flask', 'review the shutdown method to terminate the server process and clean up the running directory', 'create a MockServer instance on a given port and launch it in a background thread', 'send a Mephisto-bound live update packet with agent action content through the mock server', 'register a mock agent by sending a REGISTER_AGENT packet with worker name and agent details', 'submit mock unit data by sending a SUBMIT_UNIT packet with the agent id and submit data', 'get chronologically sorted received messages filtered by specific packet types from the mock server']
```

Usage

```
{'deploy_heroku_server': 'deploy a task server to Heroku by initializing git, creating the app, and pushing code', 'shutdown_heroku_server': 'shut down and destroy a Heroku app server that was created by the HerokuArchitect', 'prepare_heroku_build': 'prepare and compile server files into a build directory ready for Heroku deployment', 'download_heroku_file': 'download a file from a deployed Heroku app via the download_file endpoint', 'check_heroku_server_status': 'check if a Heroku app is still running by querying the list of active apps'}
```

## File: facebookresearch_mephisto/mephisto/abstractions/architects/local_architect.py

Prompts

```
['deploy a task server to Heroku by initializing git, creating the app, and pushing code', 'shut down and destroy a Heroku app server that was created by the HerokuArchitect', 'prepare and compile server files into a build directory ready for Heroku deployment', 'download a file from a deployed Heroku app via the download_file endpoint', 'check if a Heroku app is still running by querying the list of active apps', 'build a LocalArchitect instance to set up and manage a local server for deploying Mephisto tasks', 'create a LocalArchitectArgs dataclass to configure hostname and port for a local architect server', 'test the get_channels method to return WebsocketChannel instances for ClientIOHandler registration', 'refactor the deploy method to support additional server types beyond node and flask', 'review the shutdown method to terminate the server process and clean up the running directory', 'create a MockServer instance on a given port and launch it in a background thread', 'send a Mephisto-bound live update packet with agent action content through the mock server', 'register a mock agent by sending a REGISTER_AGENT packet with worker name and agent details', 'submit mock unit data by sending a SUBMIT_UNIT packet with the agent id and submit data', 'get chronologically sorted received messages filtered by specific packet types from the mock server']
```

Usage

```
{'build_local_architect': 'build a LocalArchitect instance to set up and manage a local server for deploying Mephisto tasks', 'create_local_architect_args': 'create a LocalArchitectArgs dataclass to configure hostname and port for a local architect server', 'test_get_channels': 'test the get_channels method to return WebsocketChannel instances for ClientIOHandler registration', 'refactor_deploy': 'refactor the deploy method to support additional server types beyond node and flask', 'review_shutdown': 'review the shutdown method to terminate the server process and clean up the running directory'}
```

## File: facebookresearch_mephisto/mephisto/abstractions/architects/mock_architect.py

Prompts

```
['deploy a task server to Heroku by initializing git, creating the app, and pushing code', 'shut down and destroy a Heroku app server that was created by the HerokuArchitect', 'prepare and compile server files into a build directory ready for Heroku deployment', 'download a file from a deployed Heroku app via the download_file endpoint', 'check if a Heroku app is still running by querying the list of active apps', 'build a LocalArchitect instance to set up and manage a local server for deploying Mephisto tasks', 'create a LocalArchitectArgs dataclass to configure hostname and port for a local architect server', 'test the get_channels method to return WebsocketChannel instances for ClientIOHandler registration', 'refactor the deploy method to support additional server types beyond node and flask', 'review the shutdown method to terminate the server process and clean up the running directory', 'create a MockServer instance on a given port and launch it in a background thread', 'send a Mephisto-bound live update packet with agent action content through the mock server', 'register a mock agent by sending a REGISTER_AGENT packet with worker name and agent details', 'submit mock unit data by sending a SUBMIT_UNIT packet with the agent id and submit data', 'get chronologically sorted received messages filtered by specific packet types from the mock server']
```

Usage

```
{'create_mock_server': 'create a MockServer instance on a given port and launch it in a background thread', 'send_mock_agent_action': 'send a Mephisto-bound live update packet with agent action content through the mock server', 'register_mock_agent': 'register a mock agent by sending a REGISTER_AGENT packet with worker name and agent details', 'submit_mock_unit': 'submit mock unit data by sending a SUBMIT_UNIT packet with the agent id and submit data', 'get_received_messages': 'get chronologically sorted received messages filtered by specific packet types from the mock server'}
```

