# Agent Python Tools

- repo: facebookresearch/mephisto
- repo_uri: https://github.com/facebookresearch/mephisto

## File: facebookresearch_mephisto/test/abstractions/architects/test_heroku_architect.py

Prompts

```
['test the HerokuArchitectTests class to verify server prepare and cleanup lifecycle', 'test the HerokuArchitectTests class to verify server deploy and shutdown lifecycle', 'review the HerokuArchitectTests get_architect method that instantiates a HerokuArchitect with OmegaConf args', 'review the HerokuArchitectTests server_is_prepared method that checks if the build directory exists', 'review the HerokuArchitectTests tearDown method that shuts down the server and cleans up builds', 'test the LocalArchitect class by running the LocalArchitectTests unittest suite', 'review the get_architect method that creates a LocalArchitect instance with localhost config', 'test the server_is_prepared method to check if the build directory router exists', 'test the server_is_cleaned method to verify the build directory router is removed', 'test the server_is_shutdown method to confirm the server process has stopped', 'run the MockArchitectTests unit tests to verify the mock architect interface is working properly', 'test the server_is_up method to confirm the mock architect is deployed and not shutdown']
```

Usage

```
{'test_heroku_architect_prepare_cleanup': 'test the HerokuArchitectTests class to verify server prepare and cleanup lifecycle', 'test_heroku_architect_deploy_shutdown': 'test the HerokuArchitectTests class to verify server deploy and shutdown lifecycle', 'review_HerokuArchitectTests_get_architect': 'review the HerokuArchitectTests get_architect method that instantiates a HerokuArchitect with OmegaConf args', 'review_HerokuArchitectTests_server_is_prepared': 'review the HerokuArchitectTests server_is_prepared method that checks if the build directory exists', 'review_HerokuArchitectTests_tearDown': 'review the HerokuArchitectTests tearDown method that shuts down the server and cleans up builds'}
```

## File: facebookresearch_mephisto/test/abstractions/architects/test_local_architect.py

Prompts

```
['test the HerokuArchitectTests class to verify server prepare and cleanup lifecycle', 'test the HerokuArchitectTests class to verify server deploy and shutdown lifecycle', 'review the HerokuArchitectTests get_architect method that instantiates a HerokuArchitect with OmegaConf args', 'review the HerokuArchitectTests server_is_prepared method that checks if the build directory exists', 'review the HerokuArchitectTests tearDown method that shuts down the server and cleans up builds', 'test the LocalArchitect class by running the LocalArchitectTests unittest suite', 'review the get_architect method that creates a LocalArchitect instance with localhost config', 'test the server_is_prepared method to check if the build directory router exists', 'test the server_is_cleaned method to verify the build directory router is removed', 'test the server_is_shutdown method to confirm the server process has stopped', 'run the MockArchitectTests unit tests to verify the mock architect interface is working properly', 'test the server_is_up method to confirm the mock architect is deployed and not shutdown']
```

Usage

```
{'test_local_architect': 'test the LocalArchitect class by running the LocalArchitectTests unittest suite', 'review_get_architect': 'review the get_architect method that creates a LocalArchitect instance with localhost config', 'test_server_is_prepared': 'test the server_is_prepared method to check if the build directory router exists', 'test_server_is_cleaned': 'test the server_is_cleaned method to verify the build directory router is removed', 'test_server_is_shutdown': 'test the server_is_shutdown method to confirm the server process has stopped'}
```

## File: facebookresearch_mephisto/test/abstractions/architects/test_mock_architect.py

Prompts

```
['test the HerokuArchitectTests class to verify server prepare and cleanup lifecycle', 'test the HerokuArchitectTests class to verify server deploy and shutdown lifecycle', 'review the HerokuArchitectTests get_architect method that instantiates a HerokuArchitect with OmegaConf args', 'review the HerokuArchitectTests server_is_prepared method that checks if the build directory exists', 'review the HerokuArchitectTests tearDown method that shuts down the server and cleans up builds', 'test the LocalArchitect class by running the LocalArchitectTests unittest suite', 'review the get_architect method that creates a LocalArchitect instance with localhost config', 'test the server_is_prepared method to check if the build directory router exists', 'test the server_is_cleaned method to verify the build directory router is removed', 'test the server_is_shutdown method to confirm the server process has stopped', 'run the MockArchitectTests unit tests to verify the mock architect interface is working properly', 'test the server_is_up method to confirm the mock architect is deployed and not shutdown']
```

Usage

```
{'test_mock_architect': 'run the MockArchitectTests unit tests to verify the mock architect interface is working properly', 'test_server_is_prepared': 'test the server_is_prepared method to check if the mock architect has been prepared', 'test_server_is_cleaned': 'test the server_is_cleaned method to verify the mock architect cleanup state', 'test_server_is_up': 'test the server_is_up method to confirm the mock architect is deployed and not shutdown', 'test_server_is_shutdown': 'test the server_is_shutdown method to verify the mock architect has been shut down'}
```

