# Agent Python Tools

- repo: google-deepmind/concordia
- repo_uri: https://github.com/google-deepmind/concordia

## File: google-deepmind_concordia/examples/signaling/dial.py

Prompts

```
['run a DIAL simulation for a pair of agents with personal events, dialogue, and post-date reflections', 'create a DIAL simulation configured for a single dyad with player states and scenario type', 'get all memory text snippets from a Concordia entity as a newline-separated string', 'select a random edible from an agent inventory and queue an eating statement', 'generate a statement describing what clothing item an agent is wearing from their inventory', 'run a multi-day signaling experiment with marketplace trading and dyadic date conversations between agents', 'create a marketplace simulation config with buyer agents, sellers, and goods for a given number of rounds', 'convert a nested goods specification dictionary into a flat list of Good objects with prices and inventory', 'run a marketplace-only experiment that skips DIAL date conversations and personal events entirely', 'run a signaling experiment using subculture goods to test agent behavior with different item categories']
```

Usage

```
{'run_dyad_simulation': 'run a DIAL simulation for a pair of agents with personal events, dialogue, and post-date reflections', 'create_simulation_for_dyad': 'create a DIAL simulation configured for a single dyad with player states and scenario type', 'get_memories': 'get all memory text snippets from a Concordia entity as a newline-separated string', 'get_eating_statement': 'select a random edible from an agent inventory and queue an eating statement', 'get_wearing_statement': 'generate a statement describing what clothing item an agent is wearing from their inventory'}
```

## File: google-deepmind_concordia/examples/signaling/simulation.py

Prompts

```
['run a DIAL simulation for a pair of agents with personal events, dialogue, and post-date reflections', 'create a DIAL simulation configured for a single dyad with player states and scenario type', 'get all memory text snippets from a Concordia entity as a newline-separated string', 'select a random edible from an agent inventory and queue an eating statement', 'generate a statement describing what clothing item an agent is wearing from their inventory', 'run a multi-day signaling experiment with marketplace trading and dyadic date conversations between agents', 'create a marketplace simulation config with buyer agents, sellers, and goods for a given number of rounds', 'convert a nested goods specification dictionary into a flat list of Good objects with prices and inventory', 'run a marketplace-only experiment that skips DIAL date conversations and personal events entirely', 'run a signaling experiment using subculture goods to test agent behavior with different item categories']
```

Usage

```
{'run_experiment': 'run a multi-day signaling experiment with marketplace trading and dyadic date conversations between agents', 'get_marketplace_config': 'create a marketplace simulation config with buyer agents, sellers, and goods for a given number of rounds', 'get_all_goods_from_spec': 'convert a nested goods specification dictionary into a flat list of Good objects with prices and inventory', 'run_experiment_asocial': 'run a marketplace-only experiment that skips DIAL date conversations and personal events entirely', 'run_experiment_subculture': 'run a signaling experiment using subculture goods to test agent behavior with different item categories'}
```

