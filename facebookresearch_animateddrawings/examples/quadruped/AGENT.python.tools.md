# Agent Python Tools

- repo: facebookresearch/animateddrawings
- repo_uri: https://github.com/facebookresearch/animateddrawings

## File: facebookresearch_animateddrawings/examples/quadruped/human_to_animal.py

Prompts

```
['convert a human skeleton YAML config to a quadruped animal skeleton with validated leg groups', 'read a human skeleton YAML file and write the converted quadruped animal config to a new YAML file', 'validate a skeleton leg group by checking segment ratios, knee angles, and bilateral symmetry', 'reconfigure a failing leg group by searching for candidate joints and applying reference leg offsets', 'calculate relative offsets of body parts from a reference point like the hip for scaling']
```

Usage

```
{'convert_human_to_animal': 'convert a human skeleton YAML config to a quadruped animal skeleton with validated leg groups', 'write_animal_config': 'read a human skeleton YAML file and write the converted quadruped animal config to a new YAML file', 'validate_leg_group': 'validate a skeleton leg group by checking segment ratios, knee angles, and bilateral symmetry', 'reconfigure_leg_group': 'reconfigure a failing leg group by searching for candidate joints and applying reference leg offsets', 'calculate_offset_and_scale': 'calculate relative offsets of body parts from a reference point like the hip for scaling'}
```

