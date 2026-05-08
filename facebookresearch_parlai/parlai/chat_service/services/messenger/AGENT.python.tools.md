# Agent Python Tools

- repo: facebookresearch/parlai
- repo_uri: https://github.com/facebookresearch/parlai

## File: facebookresearch_parlai/parlai/chat_service/services/messenger/agents.py

Prompts

```
['send a message or payload to a MessengerAgent through the manager', 'trigger a typing indicator on the MessengerAgent for a given persona', 'check if a Messenger message contains an image attachment or image key', 'put incoming Messenger message data into the agent message queue', 'pull the next message from the MessengerAgent queue with optional timeout', 'send a text message to a Facebook Messenger user with optional quick replies using MessageSender', 'send an image, video, audio, or file attachment to a Facebook Messenger user via MessageSender', 'create quick reply options for a Messenger message using create_reply_option with a title and payload', 'upload an attachment to Facebook Messenger using the Attachment Upload API and get a reusable attachment ID', 'create or delete a Messenger persona with a name and profile picture URL using MessageSender', 'set up a Messenger webhook server to handle incoming Facebook messages for a ParlAI task', 'send a text message with optional quick replies to a Facebook Messenger agent by receiver ID', 'send a structured payload object to a Facebook Messenger agent with optional quick replies', 'handle incoming webhook events including new messages, delivery confirmations, and read receipts', 'run the messenger chat service by executing the run function with parsed options', 'set up and parse command line arguments for the messenger chat service using ParlaiParser', 'parse a configuration file and merge world options into the messenger service options dict', 'start the MessengerManager task and ensure it shuts down cleanly on any exception', 'review the messenger runner module that sets up args, parses config, and runs the MessengerManager', 'generate a SimpleMessengerOverworld instance from opt and agents list using the generate_world static method', 'run a parley in SimpleMessengerOverworld to mark the episode done and return the default world type', 'check if the SimpleMessengerOverworld episode is done by calling the episode_done method', 'generate an OnboardWorld instance from opt and agents list using the generate_world static method', 'shutdown the OnboardWorld by calling the shutdown method to clean up resources']
```

Usage

```
{'observe_messenger_message': 'send a message or payload to a MessengerAgent through the manager', 'observe_typing_indicator': 'trigger a typing indicator on the MessengerAgent for a given persona', 'detect_image_attempt': 'check if a Messenger message contains an image attachment or image key', 'queue_messenger_data': 'put incoming Messenger message data into the agent message queue', 'pull_agent_act': 'pull the next message from the MessengerAgent queue with optional timeout'}
```

## File: facebookresearch_parlai/parlai/chat_service/services/messenger/message_sender.py

Prompts

```
['send a message or payload to a MessengerAgent through the manager', 'trigger a typing indicator on the MessengerAgent for a given persona', 'check if a Messenger message contains an image attachment or image key', 'put incoming Messenger message data into the agent message queue', 'pull the next message from the MessengerAgent queue with optional timeout', 'send a text message to a Facebook Messenger user with optional quick replies using MessageSender', 'send an image, video, audio, or file attachment to a Facebook Messenger user via MessageSender', 'create quick reply options for a Messenger message using create_reply_option with a title and payload', 'upload an attachment to Facebook Messenger using the Attachment Upload API and get a reusable attachment ID', 'create or delete a Messenger persona with a name and profile picture URL using MessageSender', 'set up a Messenger webhook server to handle incoming Facebook messages for a ParlAI task', 'send a text message with optional quick replies to a Facebook Messenger agent by receiver ID', 'send a structured payload object to a Facebook Messenger agent with optional quick replies', 'handle incoming webhook events including new messages, delivery confirmations, and read receipts', 'run the messenger chat service by executing the run function with parsed options', 'set up and parse command line arguments for the messenger chat service using ParlaiParser', 'parse a configuration file and merge world options into the messenger service options dict', 'start the MessengerManager task and ensure it shuts down cleanly on any exception', 'review the messenger runner module that sets up args, parses config, and runs the MessengerManager', 'generate a SimpleMessengerOverworld instance from opt and agents list using the generate_world static method', 'run a parley in SimpleMessengerOverworld to mark the episode done and return the default world type', 'check if the SimpleMessengerOverworld episode is done by calling the episode_done method', 'generate an OnboardWorld instance from opt and agents list using the generate_world static method', 'shutdown the OnboardWorld by calling the shutdown method to clean up resources']
```

Usage

```
{'send_messenger_text_message': 'send a text message to a Facebook Messenger user with optional quick replies using MessageSender', 'send_messenger_attachment': 'send an image, video, audio, or file attachment to a Facebook Messenger user via MessageSender', 'create_messenger_quick_replies': 'create quick reply options for a Messenger message using create_reply_option with a title and payload', 'upload_messenger_attachment': 'upload an attachment to Facebook Messenger using the Attachment Upload API and get a reusable attachment ID', 'manage_messenger_persona': 'create or delete a Messenger persona with a name and profile picture URL using MessageSender'}
```

## File: facebookresearch_parlai/parlai/chat_service/services/messenger/messenger_manager.py

Prompts

```
['send a message or payload to a MessengerAgent through the manager', 'trigger a typing indicator on the MessengerAgent for a given persona', 'check if a Messenger message contains an image attachment or image key', 'put incoming Messenger message data into the agent message queue', 'pull the next message from the MessengerAgent queue with optional timeout', 'send a text message to a Facebook Messenger user with optional quick replies using MessageSender', 'send an image, video, audio, or file attachment to a Facebook Messenger user via MessageSender', 'create quick reply options for a Messenger message using create_reply_option with a title and payload', 'upload an attachment to Facebook Messenger using the Attachment Upload API and get a reusable attachment ID', 'create or delete a Messenger persona with a name and profile picture URL using MessageSender', 'set up a Messenger webhook server to handle incoming Facebook messages for a ParlAI task', 'send a text message with optional quick replies to a Facebook Messenger agent by receiver ID', 'send a structured payload object to a Facebook Messenger agent with optional quick replies', 'handle incoming webhook events including new messages, delivery confirmations, and read receipts', 'run the messenger chat service by executing the run function with parsed options', 'set up and parse command line arguments for the messenger chat service using ParlaiParser', 'parse a configuration file and merge world options into the messenger service options dict', 'start the MessengerManager task and ensure it shuts down cleanly on any exception', 'review the messenger runner module that sets up args, parses config, and runs the MessengerManager', 'generate a SimpleMessengerOverworld instance from opt and agents list using the generate_world static method', 'run a parley in SimpleMessengerOverworld to mark the episode done and return the default world type', 'check if the SimpleMessengerOverworld episode is done by calling the episode_done method', 'generate an OnboardWorld instance from opt and agents list using the generate_world static method', 'shutdown the OnboardWorld by calling the shutdown method to clean up resources']
```

Usage

```
{'setup_messenger_webhook': 'set up a Messenger webhook server to handle incoming Facebook messages for a ParlAI task', 'send_messenger_message': 'send a text message with optional quick replies to a Facebook Messenger agent by receiver ID', 'send_messenger_payload': 'send a structured payload object to a Facebook Messenger agent with optional quick replies', 'upload_messenger_attachment': 'upload an image or file attachment to Facebook Messenger and return an attachment ID', 'handle_messenger_webhook_event': 'handle incoming webhook events including new messages, delivery confirmations, and read receipts'}
```

## File: facebookresearch_parlai/parlai/chat_service/services/messenger/run.py

Prompts

```
['send a message or payload to a MessengerAgent through the manager', 'trigger a typing indicator on the MessengerAgent for a given persona', 'check if a Messenger message contains an image attachment or image key', 'put incoming Messenger message data into the agent message queue', 'pull the next message from the MessengerAgent queue with optional timeout', 'send a text message to a Facebook Messenger user with optional quick replies using MessageSender', 'send an image, video, audio, or file attachment to a Facebook Messenger user via MessageSender', 'create quick reply options for a Messenger message using create_reply_option with a title and payload', 'upload an attachment to Facebook Messenger using the Attachment Upload API and get a reusable attachment ID', 'create or delete a Messenger persona with a name and profile picture URL using MessageSender', 'set up a Messenger webhook server to handle incoming Facebook messages for a ParlAI task', 'send a text message with optional quick replies to a Facebook Messenger agent by receiver ID', 'send a structured payload object to a Facebook Messenger agent with optional quick replies', 'handle incoming webhook events including new messages, delivery confirmations, and read receipts', 'run the messenger chat service by executing the run function with parsed options', 'set up and parse command line arguments for the messenger chat service using ParlaiParser', 'parse a configuration file and merge world options into the messenger service options dict', 'start the MessengerManager task and ensure it shuts down cleanly on any exception', 'review the messenger runner module that sets up args, parses config, and runs the MessengerManager', 'generate a SimpleMessengerOverworld instance from opt and agents list using the generate_world static method', 'run a parley in SimpleMessengerOverworld to mark the episode done and return the default world type', 'check if the SimpleMessengerOverworld episode is done by calling the episode_done method', 'generate an OnboardWorld instance from opt and agents list using the generate_world static method', 'shutdown the OnboardWorld by calling the shutdown method to clean up resources']
```

Usage

```
{'run_messenger_service': 'run the messenger chat service by executing the run function with parsed options', 'setup_messenger_args': 'set up and parse command line arguments for the messenger chat service using ParlaiParser', 'parse_messenger_config': 'parse a configuration file and merge world options into the messenger service options dict', 'start_messenger_manager': 'start the MessengerManager task and ensure it shuts down cleanly on any exception', 'review_messenger_runner': 'review the messenger runner module that sets up args, parses config, and runs the MessengerManager'}
```

## File: facebookresearch_parlai/parlai/chat_service/services/messenger/worlds.py

Prompts

```
['send a message or payload to a MessengerAgent through the manager', 'trigger a typing indicator on the MessengerAgent for a given persona', 'check if a Messenger message contains an image attachment or image key', 'put incoming Messenger message data into the agent message queue', 'pull the next message from the MessengerAgent queue with optional timeout', 'send a text message to a Facebook Messenger user with optional quick replies using MessageSender', 'send an image, video, audio, or file attachment to a Facebook Messenger user via MessageSender', 'create quick reply options for a Messenger message using create_reply_option with a title and payload', 'upload an attachment to Facebook Messenger using the Attachment Upload API and get a reusable attachment ID', 'create or delete a Messenger persona with a name and profile picture URL using MessageSender', 'set up a Messenger webhook server to handle incoming Facebook messages for a ParlAI task', 'send a text message with optional quick replies to a Facebook Messenger agent by receiver ID', 'send a structured payload object to a Facebook Messenger agent with optional quick replies', 'handle incoming webhook events including new messages, delivery confirmations, and read receipts', 'run the messenger chat service by executing the run function with parsed options', 'set up and parse command line arguments for the messenger chat service using ParlaiParser', 'parse a configuration file and merge world options into the messenger service options dict', 'start the MessengerManager task and ensure it shuts down cleanly on any exception', 'review the messenger runner module that sets up args, parses config, and runs the MessengerManager', 'generate a SimpleMessengerOverworld instance from opt and agents list using the generate_world static method', 'run a parley in SimpleMessengerOverworld to mark the episode done and return the default world type', 'check if the SimpleMessengerOverworld episode is done by calling the episode_done method', 'generate an OnboardWorld instance from opt and agents list using the generate_world static method', 'shutdown the OnboardWorld by calling the shutdown method to clean up resources']
```

Usage

```
{'generate_simple_messenger_overworld': 'generate a SimpleMessengerOverworld instance from opt and agents list using the generate_world static method', 'run_simple_messenger_parley': 'run a parley in SimpleMessengerOverworld to mark the episode done and return the default world type', 'check_simple_messenger_episode_done': 'check if the SimpleMessengerOverworld episode is done by calling the episode_done method', 'generate_onboard_world': 'generate an OnboardWorld instance from opt and agents list using the generate_world static method', 'shutdown_onboard_world': 'shutdown the OnboardWorld by calling the shutdown method to clean up resources'}
```

