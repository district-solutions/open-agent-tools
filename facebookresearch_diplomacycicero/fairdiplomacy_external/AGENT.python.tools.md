# Agent Python Tools

- repo: facebookresearch/diplomacycicero
- repo_uri: https://github.com/facebookresearch/diplomacy_cicero

## File: facebookresearch_diplomacycicero/fairdiplomacy_external/game_to_html.py

Prompts

```
['run the CLI tool to convert a Diplomacy game JSON file into an HTML report', 'run the CLI tool to convert a game JSON to HTML with a custom title', 'run the CLI tool to convert a game JSON to HTML with annotation config', 'run the CLI tool with --filter1 to show only one power filter instead of two', 'run the CLI tool to output the generated HTML to a custom file path', 'run the play_webdip task to play web Diplomacy using the provided configuration', 'run the main dispatcher with a task name and config to execute registered tasks', 'register a new task function using the _register decorator to add it to the TASKS registry', 'review the main entry point that handles logging, GPU detection, and task dispatch via heyhi', 'summarize the TASKS dictionary registry that maps task names to their callable functions', 'run a diplomacy bot against webdiplomacy.net using a PlayWebdipTask config', 'convert a webdiplomacy.net status JSON response into a pydipcc Game object', 'build a bot wrapper that manages agent state, messages, and orders for webdiplomacy games', 'fetch the current game status JSON from the webdiplomacy.net API for a given context', "toggle a bot's draw vote on or off for a webdiplomacy.net game"]
```

Usage

```
{'run_game_to_html_cli': 'run the CLI tool to convert a Diplomacy game JSON file into an HTML report', 'run_game_to_html_with_title': 'run the CLI tool to convert a game JSON to HTML with a custom title', 'run_game_to_html_with_annotations': 'run the CLI tool to convert a game JSON to HTML with annotation config', 'run_game_to_html_filter1': 'run the CLI tool with --filter1 to show only one power filter instead of two', 'run_game_to_html_custom_output': 'run the CLI tool to output the generated HTML to a custom file path'}
```

## File: facebookresearch_diplomacycicero/fairdiplomacy_external/run.py

Prompts

```
['run the CLI tool to convert a Diplomacy game JSON file into an HTML report', 'run the CLI tool to convert a game JSON to HTML with a custom title', 'run the CLI tool to convert a game JSON to HTML with annotation config', 'run the CLI tool with --filter1 to show only one power filter instead of two', 'run the CLI tool to output the generated HTML to a custom file path', 'run the play_webdip task to play web Diplomacy using the provided configuration', 'run the main dispatcher with a task name and config to execute registered tasks', 'register a new task function using the _register decorator to add it to the TASKS registry', 'review the main entry point that handles logging, GPU detection, and task dispatch via heyhi', 'summarize the TASKS dictionary registry that maps task names to their callable functions', 'run a diplomacy bot against webdiplomacy.net using a PlayWebdipTask config', 'convert a webdiplomacy.net status JSON response into a pydipcc Game object', 'build a bot wrapper that manages agent state, messages, and orders for webdiplomacy games', 'fetch the current game status JSON from the webdiplomacy.net API for a given context', "toggle a bot's draw vote on or off for a webdiplomacy.net game"]
```

Usage

```
{'run_play_webdip_task': 'run the play_webdip task to play web Diplomacy using the provided configuration', 'run_main_dispatcher': 'run the main dispatcher with a task name and config to execute registered tasks', 'register_new_task': 'register a new task function using the _register decorator to add it to the TASKS registry', 'review_main_entry_point': 'review the main entry point that handles logging, GPU detection, and task dispatch via heyhi', 'summarize_TASKS_registry': 'summarize the TASKS dictionary registry that maps task names to their callable functions'}
```

## File: facebookresearch_diplomacycicero/fairdiplomacy_external/webdip_api.py

Prompts

```
['run the CLI tool to convert a Diplomacy game JSON file into an HTML report', 'run the CLI tool to convert a game JSON to HTML with a custom title', 'run the CLI tool to convert a game JSON to HTML with annotation config', 'run the CLI tool with --filter1 to show only one power filter instead of two', 'run the CLI tool to output the generated HTML to a custom file path', 'run the play_webdip task to play web Diplomacy using the provided configuration', 'run the main dispatcher with a task name and config to execute registered tasks', 'register a new task function using the _register decorator to add it to the TASKS registry', 'review the main entry point that handles logging, GPU detection, and task dispatch via heyhi', 'summarize the TASKS dictionary registry that maps task names to their callable functions', 'run a diplomacy bot against webdiplomacy.net using a PlayWebdipTask config', 'convert a webdiplomacy.net status JSON response into a pydipcc Game object', 'build a bot wrapper that manages agent state, messages, and orders for webdiplomacy games', 'fetch the current game status JSON from the webdiplomacy.net API for a given context', "toggle a bot's draw vote on or off for a webdiplomacy.net game"]
```

Usage

```
{'play_webdip': 'run a diplomacy bot against webdiplomacy.net using a PlayWebdipTask config', 'webdip_state_to_game': 'convert a webdiplomacy.net status JSON response into a pydipcc Game object', 'WebdipBotWrapper': 'build a bot wrapper that manages agent state, messages, and orders for webdiplomacy games', 'get_status_json': 'fetch the current game status JSON from the webdiplomacy.net API for a given context', 'set_draw_vote': "toggle a bot's draw vote on or off for a webdiplomacy.net game"}
```

