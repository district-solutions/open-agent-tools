# Agent Python Tools

- repo: google-deepmind/gemini-robotics-sdk
- repo_uri: https://github.com/google-deepmind/gemini-robotics-sdk

## File: google-deepmind_gemini-robotics-sdk/safari_sdk/auth.py

Prompts

```
['get a discovery service resource for the robotics developer API using an API key from flags or file', 'get the API key from the api_key flag or from fixed file locations like config or opt paths', 'build a discovery resource with an API key and timeout using httplib2 and googleapiclient discovery', 'extract and return a stripped API key string from a given file path', 'configure API key resolution order using the api_key flag or fixed file paths at config and opt', 'get a system environment variable by name and return its value as a string', 'get the robot ID from the GA_ROBOT_ID environment variable', 'use the DEFAULT_ROBOT_ID_IN_SYSTEM_ENV constant to reference the GA_ROBOT_ID variable name', 'check if the GA_ROBOT_ID environment variable is set by calling get_robot_id_from_system_env', 'get any custom environment variable by passing its name to get_system_env_variable']
```

Usage

```
{'get_service': 'get a discovery service resource for the robotics developer API using an API key from flags or file', 'get_api_key': 'get the API key from the api_key flag or from fixed file locations like config or opt paths', 'build_service': 'build a discovery resource with an API key and timeout using httplib2 and googleapiclient discovery', 'extract_api_key_from_file': 'extract and return a stripped API key string from a given file path', 'configure_api_key_resolution': 'configure API key resolution order using the api_key flag or fixed file paths at config and opt'}
```

## File: google-deepmind_gemini-robotics-sdk/safari_sdk/utils.py

Prompts

```
['get a discovery service resource for the robotics developer API using an API key from flags or file', 'get the API key from the api_key flag or from fixed file locations like config or opt paths', 'build a discovery resource with an API key and timeout using httplib2 and googleapiclient discovery', 'extract and return a stripped API key string from a given file path', 'configure API key resolution order using the api_key flag or fixed file paths at config and opt', 'get a system environment variable by name and return its value as a string', 'get the robot ID from the GA_ROBOT_ID environment variable', 'use the DEFAULT_ROBOT_ID_IN_SYSTEM_ENV constant to reference the GA_ROBOT_ID variable name', 'check if the GA_ROBOT_ID environment variable is set by calling get_robot_id_from_system_env', 'get any custom environment variable by passing its name to get_system_env_variable']
```

Usage

```
{'get_system_env_variable': 'get a system environment variable by name and return its value as a string', 'get_robot_id_from_system_env': 'get the robot ID from the GA_ROBOT_ID environment variable', 'use_default_robot_id_env': 'use the DEFAULT_ROBOT_ID_IN_SYSTEM_ENV constant to reference the GA_ROBOT_ID variable name', 'check_robot_id_exists': 'check if the GA_ROBOT_ID environment variable is set by calling get_robot_id_from_system_env', 'get_custom_env_variable': 'get any custom environment variable by passing its name to get_system_env_variable'}
```

