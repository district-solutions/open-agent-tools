# Agent Python Tools

- repo: google-deepmind/gamearena
- repo_uri: https://github.com/google-deepmind/game_arena

## File: google-deepmind_gamearena/game_arena/harness/games/go/game.py

Prompts

```
['convert a pyspiel Go game state into a JSON string with board grid and move info', 'add whitespace to a Go ASCII board grid string with optional symbol swapping', 'convert a Go board string into a list of coordinate dictionaries with stone symbols', 'get the action string history from a GoGameAdapter instance as a comma-separated move list', 'get a human-readable ASCII representation of the current Go game state from GoGameAdapter', 'test the Go format_state function by applying moves to a 9x9 board and verifying the JSON output', 'test the Go convert_state function by converting an ASCII board string with swap_probability set to 1.0', 'run the GoTest test suite using absltest to validate format_state and convert_state functions', 'review the GoTest test_basic method that applies five moves and asserts the resulting state dictionary', 'review the GoTest test_convert_state method that verifies ASCII board string conversion with swapped symbols']
```

Usage

```
{'format_go_state_to_json': 'convert a pyspiel Go game state into a JSON string with board grid and move info', 'convert_go_ascii_grid': 'add whitespace to a Go ASCII board grid string with optional symbol swapping', 'parse_go_board_string': 'convert a Go board string into a list of coordinate dictionaries with stone symbols', 'get_go_action_history': 'get the action string history from a GoGameAdapter instance as a comma-separated move list', 'get_go_readable_state': 'get a human-readable ASCII representation of the current Go game state from GoGameAdapter'}
```

## File: google-deepmind_gamearena/game_arena/harness/games/go/game_test.py

Prompts

```
['convert a pyspiel Go game state into a JSON string with board grid and move info', 'add whitespace to a Go ASCII board grid string with optional symbol swapping', 'convert a Go board string into a list of coordinate dictionaries with stone symbols', 'get the action string history from a GoGameAdapter instance as a comma-separated move list', 'get a human-readable ASCII representation of the current Go game state from GoGameAdapter', 'test the Go format_state function by applying moves to a 9x9 board and verifying the JSON output', 'test the Go convert_state function by converting an ASCII board string with swap_probability set to 1.0', 'run the GoTest test suite using absltest to validate format_state and convert_state functions', 'review the GoTest test_basic method that applies five moves and asserts the resulting state dictionary', 'review the GoTest test_convert_state method that verifies ASCII board string conversion with swapped symbols']
```

Usage

```
{'test_format_state': 'test the Go format_state function by applying moves to a 9x9 board and verifying the JSON output', 'test_convert_state': 'test the Go convert_state function by converting an ASCII board string with swap_probability set to 1.0', 'run_GoTest': 'run the GoTest test suite using absltest to validate format_state and convert_state functions', 'review_GoTest_test_basic': 'review the GoTest test_basic method that applies five moves and asserts the resulting state dictionary', 'review_GoTest_test_convert_state': 'review the GoTest test_convert_state method that verifies ASCII board string conversion with swapped symbols'}
```

