# Agent Python Tools

- repo: facebookresearch/sweetrl
- repo_uri: https://github.com/facebookresearch/sweet_rl

## File: facebookresearch_sweetrl/sweet_rl/environments/human_design_interaction_env.py

Prompts

```
['encode an image file to a base64 data URI string with optional JPEG format', 'create a HumanDesignInteractionEnv instance with an OpenAI client, human prompt, and model ID', 'reset the environment with a problem description and hidden HTML information to start a new episode', 'invoke the LLM model to evaluate agent output against a ground truth design image', 'take a step in the environment by processing agent response and rendering HTML output', 'create a HumanInteractionEnv instance with an OpenAI client, human prompt template, and model ID', 'reset the HumanInteractionEnv with a problem description and hidden information to start a new dialogue', 'step the HumanInteractionEnv with an agent response to advance the dialogue and invoke the model', 'invoke the OpenAI model to generate a human-like response based on the current dialogue history', 'get the dialogue history as a list of role and content message dictionaries']
```

Usage

```
{'encode_image_base64': 'encode an image file to a base64 data URI string with optional JPEG format', 'create_HumanDesignInteractionEnv': 'create a HumanDesignInteractionEnv instance with an OpenAI client, human prompt, and model ID', 'reset_HumanDesignInteractionEnv': 'reset the environment with a problem description and hidden HTML information to start a new episode', 'invoke_model_HumanDesignInteractionEnv': 'invoke the LLM model to evaluate agent output against a ground truth design image', 'step_HumanDesignInteractionEnv': 'take a step in the environment by processing agent response and rendering HTML output'}
```

## File: facebookresearch_sweetrl/sweet_rl/environments/human_interaction_env.py

Prompts

```
['encode an image file to a base64 data URI string with optional JPEG format', 'create a HumanDesignInteractionEnv instance with an OpenAI client, human prompt, and model ID', 'reset the environment with a problem description and hidden HTML information to start a new episode', 'invoke the LLM model to evaluate agent output against a ground truth design image', 'take a step in the environment by processing agent response and rendering HTML output', 'create a HumanInteractionEnv instance with an OpenAI client, human prompt template, and model ID', 'reset the HumanInteractionEnv with a problem description and hidden information to start a new dialogue', 'step the HumanInteractionEnv with an agent response to advance the dialogue and invoke the model', 'invoke the OpenAI model to generate a human-like response based on the current dialogue history', 'get the dialogue history as a list of role and content message dictionaries']
```

Usage

```
{'create_HumanInteractionEnv': 'create a HumanInteractionEnv instance with an OpenAI client, human prompt template, and model ID', 'reset_HumanInteractionEnv': 'reset the HumanInteractionEnv with a problem description and hidden information to start a new dialogue', 'step_HumanInteractionEnv': 'step the HumanInteractionEnv with an agent response to advance the dialogue and invoke the model', 'invoke_model_HumanInteractionEnv': 'invoke the OpenAI model to generate a human-like response based on the current dialogue history', 'get_dialogue_history_HumanInteractionEnv': 'get the dialogue history as a list of role and content message dictionaries'}
```

