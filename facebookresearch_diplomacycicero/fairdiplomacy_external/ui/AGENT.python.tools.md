# Agent Python Tools

- repo: facebookresearch/diplomacycicero
- repo_uri: https://github.com/facebookresearch/diplomacy_cicero

## File: facebookresearch_diplomacycicero/fairdiplomacy_external/ui/map_renderer.py

Prompts

```
['render a pydipcc Game object into a visual map string using the external diplomacy renderer', 'render a pydipcc Game rolled back to a specific phase end and return the map string', 'render a pydipcc Game map with all orders hidden by passing hide_orders=True', 'render a pydipcc Game map with abbreviations disabled by passing incl_abbrev=False', 'review the render function that converts a pydipcc Game to a rendered map string via diplomacy.engine.renderer', 'render a pydipcc diplomacy game into navigable HTML with all phases, messages, and orders', 'render a single phase of a diplomacy game into HTML with map, messages, and orders', 'render a list of diplomacy game messages into HTML with optional annotations and timestamps', 'render a dictionary of orders by power into HTML with hover-highlighted board locations', 'normalize diplomacy messages from parlai-style or old game format into a consistent dictionary format', 'render a Diplomacy game phase map as SVG and print filtered diplomatic messages', 'view a specific game phase and filter messages by sender or recipient power', 'return a colored bold terminal string for a Diplomacy power name like ENGLAND or FRANCE', 'display the current phase map and all messages for the active Diplomacy game', 'render a past phase map and print its diplomatic messages from the game history']
```

Usage

```
{'render_game_map': 'render a pydipcc Game object into a visual map string using the external diplomacy renderer', 'render_game_at_phase': 'render a pydipcc Game rolled back to a specific phase end and return the map string', 'render_game_hide_orders': 'render a pydipcc Game map with all orders hidden by passing hide_orders=True', 'render_game_no_abbrev': 'render a pydipcc Game map with abbreviations disabled by passing incl_abbrev=False', 'review_render_function': 'review the render function that converts a pydipcc Game to a rendered map string via diplomacy.engine.renderer'}
```

## File: facebookresearch_diplomacycicero/fairdiplomacy_external/ui/render.py

Prompts

```
['render a pydipcc Game object into a visual map string using the external diplomacy renderer', 'render a pydipcc Game rolled back to a specific phase end and return the map string', 'render a pydipcc Game map with all orders hidden by passing hide_orders=True', 'render a pydipcc Game map with abbreviations disabled by passing incl_abbrev=False', 'review the render function that converts a pydipcc Game to a rendered map string via diplomacy.engine.renderer', 'render a pydipcc diplomacy game into navigable HTML with all phases, messages, and orders', 'render a single phase of a diplomacy game into HTML with map, messages, and orders', 'render a list of diplomacy game messages into HTML with optional annotations and timestamps', 'render a dictionary of orders by power into HTML with hover-highlighted board locations', 'normalize diplomacy messages from parlai-style or old game format into a consistent dictionary format', 'render a Diplomacy game phase map as SVG and print filtered diplomatic messages', 'view a specific game phase and filter messages by sender or recipient power', 'return a colored bold terminal string for a Diplomacy power name like ENGLAND or FRANCE', 'display the current phase map and all messages for the active Diplomacy game', 'render a past phase map and print its diplomatic messages from the game history']
```

Usage

```
{'render_game': 'render a pydipcc diplomacy game into navigable HTML with all phases, messages, and orders', 'render_phase': 'render a single phase of a diplomacy game into HTML with map, messages, and orders', 'render_message_list': 'render a list of diplomacy game messages into HTML with optional annotations and timestamps', 'render_orders': 'render a dictionary of orders by power into HTML with hover-highlighted board locations', 'canonize_messages': 'normalize diplomacy messages from parlai-style or old game format into a consistent dictionary format'}
```

## File: facebookresearch_diplomacycicero/fairdiplomacy_external/ui/utils.py

Prompts

```
['render a pydipcc Game object into a visual map string using the external diplomacy renderer', 'render a pydipcc Game rolled back to a specific phase end and return the map string', 'render a pydipcc Game map with all orders hidden by passing hide_orders=True', 'render a pydipcc Game map with abbreviations disabled by passing incl_abbrev=False', 'review the render function that converts a pydipcc Game to a rendered map string via diplomacy.engine.renderer', 'render a pydipcc diplomacy game into navigable HTML with all phases, messages, and orders', 'render a single phase of a diplomacy game into HTML with map, messages, and orders', 'render a list of diplomacy game messages into HTML with optional annotations and timestamps', 'render a dictionary of orders by power into HTML with hover-highlighted board locations', 'normalize diplomacy messages from parlai-style or old game format into a consistent dictionary format', 'render a Diplomacy game phase map as SVG and print filtered diplomatic messages', 'view a specific game phase and filter messages by sender or recipient power', 'return a colored bold terminal string for a Diplomacy power name like ENGLAND or FRANCE', 'display the current phase map and all messages for the active Diplomacy game', 'render a past phase map and print its diplomatic messages from the game history']
```

Usage

```
{'view_diplomacy_phase': 'render a Diplomacy game phase map as SVG and print filtered diplomatic messages', 'view_phase_with_message_filter': 'view a specific game phase and filter messages by sender or recipient power', 'color_power_string': 'return a colored bold terminal string for a Diplomacy power name like ENGLAND or FRANCE', 'render_current_phase': 'display the current phase map and all messages for the active Diplomacy game', 'view_historical_phase_messages': 'render a past phase map and print its diplomatic messages from the game history'}
```

