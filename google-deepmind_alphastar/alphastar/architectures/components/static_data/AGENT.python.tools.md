# Agent Python Tools

- repo: google-deepmind/alphastar
- repo_uri: https://github.com/google-deepmind/alphastar

## File: google-deepmind_alphastar/alphastar/architectures/components/static_data/camera_masks.py

Prompts

```
['get a boolean numpy array of StarCraft II raw actions restricted to unit targets inside the camera view', 'get a boolean numpy array of StarCraft II raw actions restricted to point targets inside the camera view', 'summarize the camera_masks module which lists StarCraft II function arguments forbidden outside the camera view', 'review the list of forbidden unit-target actions like Heal, Load, and Attack that must stay within camera view', 'review the list of forbidden point-target actions like Build and Effect actions that must stay within camera view', 'create a numpy boolean array specifying the attributes of each StarCraft II unit type given the number of unit types', 'remap StarCraft II function arguments to remove redundant order IDs and return a compact lookup array', 'remap function arguments to keep only build queue relevant orders and discard train or research actions', 'create a lookup array that maps Terran addon unit types like TechLab and Reactor to their indices', 'review the Unit Attributes IntEnum defining traits like LIGHT, ARMORED, BIOLOGICAL, MECHANICAL, PSIONIC, MASSIVE, STRUCTURE, DETECTOR, SUMMONED, FLYING, ADDON, and BURROWED']
```

Usage

```
{'get_camera_restricted_unit_actions': 'get a boolean numpy array of StarCraft II raw actions restricted to unit targets inside the camera view', 'get_camera_restricted_point_actions': 'get a boolean numpy array of StarCraft II raw actions restricted to point targets inside the camera view', 'summarize_camera_masks_module': 'summarize the camera_masks module which lists StarCraft II function arguments forbidden outside the camera view', 'review_forbidden_unit_actions': 'review the list of forbidden unit-target actions like Heal, Load, and Attack that must stay within camera view', 'review_forbidden_point_actions': 'review the list of forbidden point-target actions like Build and Effect actions that must stay within camera view'}
```

## File: google-deepmind_alphastar/alphastar/architectures/components/static_data/unit_encoder_data.py

Prompts

```
['get a boolean numpy array of StarCraft II raw actions restricted to unit targets inside the camera view', 'get a boolean numpy array of StarCraft II raw actions restricted to point targets inside the camera view', 'summarize the camera_masks module which lists StarCraft II function arguments forbidden outside the camera view', 'review the list of forbidden unit-target actions like Heal, Load, and Attack that must stay within camera view', 'review the list of forbidden point-target actions like Build and Effect actions that must stay within camera view', 'create a numpy boolean array specifying the attributes of each StarCraft II unit type given the number of unit types', 'remap StarCraft II function arguments to remove redundant order IDs and return a compact lookup array', 'remap function arguments to keep only build queue relevant orders and discard train or research actions', 'create a lookup array that maps Terran addon unit types like TechLab and Reactor to their indices', 'review the Unit Attributes IntEnum defining traits like LIGHT, ARMORED, BIOLOGICAL, MECHANICAL, PSIONIC, MASSIVE, STRUCTURE, DETECTOR, SUMMONED, FLYING, ADDON, and BURROWED']
```

Usage

```
{'get_attribute_lookup': 'create a numpy boolean array specifying the attributes of each StarCraft II unit type given the number of unit types', 'get_order_id_lookup': 'remap StarCraft II function arguments to remove redundant order IDs and return a compact lookup array', 'get_build_queue_order_id_lookup': 'remap function arguments to keep only build queue relevant orders and discard train or research actions', 'get_addon_lookup': 'create a lookup array that maps Terran addon unit types like TechLab and Reactor to their indices', 'review_UA_enum': 'review the Unit Attributes IntEnum defining traits like LIGHT, ARMORED, BIOLOGICAL, MECHANICAL, PSIONIC, MASSIVE, STRUCTURE, DETECTOR, SUMMONED, FLYING, ADDON, and BURROWED'}
```

