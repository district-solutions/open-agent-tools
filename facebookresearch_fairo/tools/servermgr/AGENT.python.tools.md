# Agent Python Tools

- repo: facebookresearch/fairo
- repo_uri: https://github.com/facebookresearch/fairo

## File: facebookresearch_fairo/tools/servermgr/app.py

Prompts

```
['run the flask app to serve the craftassist Minecraft server management endpoints on localhost', 'launch a new ECS Fargate task for a Minecraft server instance with a flat world config', 'check the progress and public IP of an ECS task by querying its network attachment and port', 'check if an ECS task instance has expired by verifying its last status against running states', 'encode a string to base64 or decode a base64 string back to plain text using helper functions', 'launch an AWS ECS Fargate task on the craftassist cluster and return its task ARN', 'describe an ECS task by ARN and return its public IP address', "run the launch script to poll a task's IP and ping its Minecraft server port", 'review the launch_task function to understand how it configures ECS Fargate networking', 'refactor the describe_task function to handle missing attachments or network interfaces gracefully', 'run the script to ping a Cuberite Minecraft server on a given host and port', 'run the script to ping the default localhost server on port 25565', 'ping a Cuberite server at a specific host and port with a configurable timeout', 'review the ping function that sends a Minecraft protocol handshake and verifies the pong response', 'summarize the HANDSHAKE_PING and PONG raw byte constants used for Minecraft protocol communication']
```

Usage

```
{'run_flask_server': 'run the flask app to serve the craftassist Minecraft server management endpoints on localhost', 'launch_ecs_instance': 'launch a new ECS Fargate task for a Minecraft server instance with a flat world config', 'check_instance_status': 'check the progress and public IP of an ECS task by querying its network attachment and port', 'check_instance_expired': 'check if an ECS task instance has expired by verifying its last status against running states', 'encode_decode_base64': 'encode a string to base64 or decode a base64 string back to plain text using helper functions'}
```

## File: facebookresearch_fairo/tools/servermgr/launch.py

Prompts

```
['run the flask app to serve the craftassist Minecraft server management endpoints on localhost', 'launch a new ECS Fargate task for a Minecraft server instance with a flat world config', 'check the progress and public IP of an ECS task by querying its network attachment and port', 'check if an ECS task instance has expired by verifying its last status against running states', 'encode a string to base64 or decode a base64 string back to plain text using helper functions', 'launch an AWS ECS Fargate task on the craftassist cluster and return its task ARN', 'describe an ECS task by ARN and return its public IP address', "run the launch script to poll a task's IP and ping its Minecraft server port", 'review the launch_task function to understand how it configures ECS Fargate networking', 'refactor the describe_task function to handle missing attachments or network interfaces gracefully', 'run the script to ping a Cuberite Minecraft server on a given host and port', 'run the script to ping the default localhost server on port 25565', 'ping a Cuberite server at a specific host and port with a configurable timeout', 'review the ping function that sends a Minecraft protocol handshake and verifies the pong response', 'summarize the HANDSHAKE_PING and PONG raw byte constants used for Minecraft protocol communication']
```

Usage

```
{'launch_ecs_task': 'launch an AWS ECS Fargate task on the craftassist cluster and return its task ARN', 'describe_ecs_task_ip': 'describe an ECS task by ARN and return its public IP address', 'run_launch_main': "run the launch script to poll a task's IP and ping its Minecraft server port", 'review_launch_task': 'review the launch_task function to understand how it configures ECS Fargate networking', 'refactor_describe_task': 'refactor the describe_task function to handle missing attachments or network interfaces gracefully'}
```

## File: facebookresearch_fairo/tools/servermgr/ping_cuberite.py

Prompts

```
['run the flask app to serve the craftassist Minecraft server management endpoints on localhost', 'launch a new ECS Fargate task for a Minecraft server instance with a flat world config', 'check the progress and public IP of an ECS task by querying its network attachment and port', 'check if an ECS task instance has expired by verifying its last status against running states', 'encode a string to base64 or decode a base64 string back to plain text using helper functions', 'launch an AWS ECS Fargate task on the craftassist cluster and return its task ARN', 'describe an ECS task by ARN and return its public IP address', "run the launch script to poll a task's IP and ping its Minecraft server port", 'review the launch_task function to understand how it configures ECS Fargate networking', 'refactor the describe_task function to handle missing attachments or network interfaces gracefully', 'run the script to ping a Cuberite Minecraft server on a given host and port', 'run the script to ping the default localhost server on port 25565', 'ping a Cuberite server at a specific host and port with a configurable timeout', 'review the ping function that sends a Minecraft protocol handshake and verifies the pong response', 'summarize the HANDSHAKE_PING and PONG raw byte constants used for Minecraft protocol communication']
```

Usage

```
{'run_ping_cuberite_server': 'run the script to ping a Cuberite Minecraft server on a given host and port', 'run_ping_default_server': 'run the script to ping the default localhost server on port 25565', 'ping_cuberite_host_port': 'ping a Cuberite server at a specific host and port with a configurable timeout', 'review_ping_function': 'review the ping function that sends a Minecraft protocol handshake and verifies the pong response', 'summarize_handshake_pong_constants': 'summarize the HANDSHAKE_PING and PONG raw byte constants used for Minecraft protocol communication'}
```

