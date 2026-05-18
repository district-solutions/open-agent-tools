# Agent Python Tools

- repo: facebookresearch/minirts
- repo_uri: https://github.com/facebookresearch/minirts

## File: facebookresearch_minirts/tube/pytube/data_channel_manager.py

Prompts

```
['create a DataChannelManager with a list of channel objects and optional thread count', 'call get_input on the manager to collect data from channels with an optional timeout', 'call set_reply to send a detached CPU tensor reply back to a named channel', 'use the contains operator to check if a channel name exists in the manager', 'call terminate to shut down all managed channels and the thread pool executor', 'create a DataChannelManager with fast and slow xrl DataChannels for batched environment dispatch', 'create an xrl Context with DualDispatchThreads and a DataChannelManager using create_env', 'get input batches from the DataChannelManager with a max timeout in seconds', 'terminate the DataChannelManager to cleanly shut down all data channels', 'test the assert_eq function by comparing two equal values and verifying no assertion error is raised', 'test the assert_eq function by comparing unequal values and verifying an assertion error is raised', 'review the assert_eq utility function and its assertion message formatting logic', 'refactor the assert_eq function to use a custom error message via the msg parameter', 'summarize the assert_eq function which asserts equality between real and expected values with a custom message']
```

Usage

```
{'create_DataChannelManager': 'create a DataChannelManager with a list of channel objects and optional thread count', 'get_input_with_timeout': 'call get_input on the manager to collect data from channels with an optional timeout', 'set_reply_to_channel': 'call set_reply to send a detached CPU tensor reply back to a named channel', 'check_channel_membership': 'use the contains operator to check if a channel name exists in the manager', 'terminate_all_channels': 'call terminate to shut down all managed channels and the thread pool executor'}
```

## File: facebookresearch_minirts/tube/pytube/test_dc_manager.py

Prompts

```
['create a DataChannelManager with a list of channel objects and optional thread count', 'call get_input on the manager to collect data from channels with an optional timeout', 'call set_reply to send a detached CPU tensor reply back to a named channel', 'use the contains operator to check if a channel name exists in the manager', 'call terminate to shut down all managed channels and the thread pool executor', 'create a DataChannelManager with fast and slow xrl DataChannels for batched environment dispatch', 'create an xrl Context with DualDispatchThreads and a DataChannelManager using create_env', 'get input batches from the DataChannelManager with a max timeout in seconds', 'terminate the DataChannelManager to cleanly shut down all data channels', 'test the assert_eq function by comparing two equal values and verifying no assertion error is raised', 'test the assert_eq function by comparing unequal values and verifying an assertion error is raised', 'review the assert_eq utility function and its assertion message formatting logic', 'refactor the assert_eq function to use a custom error message via the msg parameter', 'summarize the assert_eq function which asserts equality between real and expected values with a custom message']
```

Usage

```
{'create_data_channel_manager': 'create a DataChannelManager with fast and slow xrl DataChannels for batched environment dispatch', 'create_env_function': 'create an xrl Context with DualDispatchThreads and a DataChannelManager using create_env', 'get_input_batches': 'get input batches from the DataChannelManager with a max timeout in seconds', 'set_reply_to_channel': 'set a reply dictionary for a specific channel key via the DataChannelManager', 'terminate_data_channel_manager': 'terminate the DataChannelManager to cleanly shut down all data channels'}
```

## File: facebookresearch_minirts/tube/pytube/utils.py

Prompts

```
['create a DataChannelManager with a list of channel objects and optional thread count', 'call get_input on the manager to collect data from channels with an optional timeout', 'call set_reply to send a detached CPU tensor reply back to a named channel', 'use the contains operator to check if a channel name exists in the manager', 'call terminate to shut down all managed channels and the thread pool executor', 'create a DataChannelManager with fast and slow xrl DataChannels for batched environment dispatch', 'create an xrl Context with DualDispatchThreads and a DataChannelManager using create_env', 'get input batches from the DataChannelManager with a max timeout in seconds', 'terminate the DataChannelManager to cleanly shut down all data channels', 'test the assert_eq function by comparing two equal values and verifying no assertion error is raised', 'test the assert_eq function by comparing unequal values and verifying an assertion error is raised', 'review the assert_eq utility function and its assertion message formatting logic', 'refactor the assert_eq function to use a custom error message via the msg parameter', 'summarize the assert_eq function which asserts equality between real and expected values with a custom message']
```

Usage

```
{'test_assert_eq': 'test the assert_eq function by comparing two equal values and verifying no assertion error is raised', 'test_assert_eq_failure': 'test the assert_eq function by comparing unequal values and verifying an assertion error is raised', 'review_assert_eq': 'review the assert_eq utility function and its assertion message formatting logic', 'refactor_assert_eq': 'refactor the assert_eq function to use a custom error message via the msg parameter', 'summarize_assert_eq': 'summarize the assert_eq function which asserts equality between real and expected values with a custom message'}
```

