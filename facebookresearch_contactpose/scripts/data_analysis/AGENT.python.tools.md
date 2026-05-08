# Agent Python Tools

- repo: facebookresearch/contactpose
- repo_uri: https://github.com/facebookresearch/contactpose

## File: facebookresearch_contactpose/scripts/data_analysis/active_areas.py

Prompts

```
['run the script to discover active areas on an object surface most frequently touched by a specific finger part', 'run the script with --show to visualize active areas on a 3D mesh using Open3D', 'run the script with finger_idx 0 and part_idx 3 to find thumb tip active areas for use intent', 'run the script with finger_idx 4 to find little finger active areas for handoff intent', 'run the script with --p_nums to discover active areas for a custom range of participant numbers', 'calculate contact probability for hand mesh vertices using a contact map and KDTree spatial search', 'visualize hand contact probability as a color-coded 3D mesh using Open3D and matplotlib', 'run the script to calculate and visualize hand contact probability for specified subjects and intents', 'review the calc_hand_contact_prob function that computes mean contact probability across subjects using MANO meshes', 'review the show_hand_contact_prob function that renders a color-coded hand mesh with contact probability values']
```

Usage

```
{'run_discover_active_areas': 'run the script to discover active areas on an object surface most frequently touched by a specific finger part', 'run_show_active_areas': 'run the script with --show to visualize active areas on a 3D mesh using Open3D', 'run_discover_thumb_tip_use': 'run the script with finger_idx 0 and part_idx 3 to find thumb tip active areas for use intent', 'run_discover_little_finger_handoff': 'run the script with finger_idx 4 to find little finger active areas for handoff intent', 'run_discover_custom_participants': 'run the script with --p_nums to discover active areas for a custom range of participant numbers'}
```

## File: facebookresearch_contactpose/scripts/data_analysis/hand_contact_prob.py

Prompts

```
['run the script to discover active areas on an object surface most frequently touched by a specific finger part', 'run the script with --show to visualize active areas on a 3D mesh using Open3D', 'run the script with finger_idx 0 and part_idx 3 to find thumb tip active areas for use intent', 'run the script with finger_idx 4 to find little finger active areas for handoff intent', 'run the script with --p_nums to discover active areas for a custom range of participant numbers', 'calculate contact probability for hand mesh vertices using a contact map and KDTree spatial search', 'visualize hand contact probability as a color-coded 3D mesh using Open3D and matplotlib', 'run the script to calculate and visualize hand contact probability for specified subjects and intents', 'review the calc_hand_contact_prob function that computes mean contact probability across subjects using MANO meshes', 'review the show_hand_contact_prob function that renders a color-coded hand mesh with contact probability values']
```

Usage

```
{'calc_hand_contact_prob': 'calculate contact probability for hand mesh vertices using a contact map and KDTree spatial search', 'show_hand_contact_prob': 'visualize hand contact probability as a color-coded 3D mesh using Open3D and matplotlib', 'run_hand_contact_analysis': 'run the script to calculate and visualize hand contact probability for specified subjects and intents', 'review_calc_hand_contact_prob': 'review the calc_hand_contact_prob function that computes mean contact probability across subjects using MANO meshes', 'review_show_hand_contact_prob': 'review the show_hand_contact_prob function that renders a color-coded hand mesh with contact probability values'}
```

