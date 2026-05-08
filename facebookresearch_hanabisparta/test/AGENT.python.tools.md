# Agent Python Tools

- repo: facebookresearch/hanabisparta
- repo_uri: https://github.com/facebookresearch/hanabi_sparta

## File: facebookresearch_hanabisparta/test/test_endgame.py

Prompts

```
['run a Hanabi game with SearchBot using start_game and end_game from hanabi_lib', "test the wait_for_my_turn function that blocks until the bot's turn using server and bot", 'start a Hanabi game with a named bot and seed via start_game returning server, bot, and thread', 'end a running Hanabi game by calling end_game with the server, bot, and thread objects', 'run the endgame test script that starts and ends two Hanabi games with SearchBot', 'start a Hanabi game and get the server, bot, and thread objects', 'make a Hanabi move using MoveType like DISCARD_CARD, PLAY_CARD, HINT_COLOR, or HINT_VALUE', "wait for the current player's turn by polling server.activePlayer() against server.whoAmI()", "get the bot's current observation and observation indices from the Hanabi game state", "get a player's hand and card IDs using server.handOfPlayer() and server.cardIdsOfHandOfPlayer()", 'start a new Hanabi game with a bot name and random seed', "wait until the bot's turn by polling server.activePlayer", 'make a hint or discard move using Move and MoveType enums', 'end the Hanabi game and clean up resources on the C side']
```

Usage

```
{'run_hanabi_game': 'run a Hanabi game with SearchBot using start_game and end_game from hanabi_lib', 'test_wait_for_my_turn': "test the wait_for_my_turn function that blocks until the bot's turn using server and bot", 'start_hanabi_game': 'start a Hanabi game with a named bot and seed via start_game returning server, bot, and thread', 'end_hanabi_game': 'end a running Hanabi game by calling end_game with the server, bot, and thread objects', 'run_endgame_test': 'run the endgame test script that starts and ends two Hanabi games with SearchBot'}
```

## File: facebookresearch_hanabisparta/test/test_file.py

Prompts

```
['run a Hanabi game with SearchBot using start_game and end_game from hanabi_lib', "test the wait_for_my_turn function that blocks until the bot's turn using server and bot", 'start a Hanabi game with a named bot and seed via start_game returning server, bot, and thread', 'end a running Hanabi game by calling end_game with the server, bot, and thread objects', 'run the endgame test script that starts and ends two Hanabi games with SearchBot', 'start a Hanabi game and get the server, bot, and thread objects', 'make a Hanabi move using MoveType like DISCARD_CARD, PLAY_CARD, HINT_COLOR, or HINT_VALUE', "wait for the current player's turn by polling server.activePlayer() against server.whoAmI()", "get the bot's current observation and observation indices from the Hanabi game state", "get a player's hand and card IDs using server.handOfPlayer() and server.cardIdsOfHandOfPlayer()", 'start a new Hanabi game with a bot name and random seed', "wait until the bot's turn by polling server.activePlayer", 'make a hint or discard move using Move and MoveType enums', 'end the Hanabi game and clean up resources on the C side']
```

Usage

```
{'run_start_game': 'start a Hanabi game and get the server, bot, and thread objects', 'run_make_move': 'make a Hanabi move using MoveType like DISCARD_CARD, PLAY_CARD, HINT_COLOR, or HINT_VALUE', 'run_wait_for_my_turn': "wait for the current player's turn by polling server.activePlayer() against server.whoAmI()", 'run_bot_obs': "get the bot's current observation and observation indices from the Hanabi game state", 'run_server_hand_info': "get a player's hand and card IDs using server.handOfPlayer() and server.cardIdsOfHandOfPlayer()"}
```

## File: facebookresearch_hanabisparta/test/test_pybot.py

Prompts

```
['run a Hanabi game with SearchBot using start_game and end_game from hanabi_lib', "test the wait_for_my_turn function that blocks until the bot's turn using server and bot", 'start a Hanabi game with a named bot and seed via start_game returning server, bot, and thread', 'end a running Hanabi game by calling end_game with the server, bot, and thread objects', 'run the endgame test script that starts and ends two Hanabi games with SearchBot', 'start a Hanabi game and get the server, bot, and thread objects', 'make a Hanabi move using MoveType like DISCARD_CARD, PLAY_CARD, HINT_COLOR, or HINT_VALUE', "wait for the current player's turn by polling server.activePlayer() against server.whoAmI()", "get the bot's current observation and observation indices from the Hanabi game state", "get a player's hand and card IDs using server.handOfPlayer() and server.cardIdsOfHandOfPlayer()", 'start a new Hanabi game with a bot name and random seed', "wait until the bot's turn by polling server.activePlayer", 'make a hint or discard move using Move and MoveType enums', 'end the Hanabi game and clean up resources on the C side']
```

Usage

```
{'run_hanabi_game': 'run a Hanabi game with TorchBot and SearchBot using hanabi_lib', 'start_game': 'start a new Hanabi game with a bot name and random seed', 'wait_for_my_turn': "wait until the bot's turn by polling server.activePlayer", 'make_move': 'make a hint or discard move using Move and MoveType enums', 'end_game': 'end the Hanabi game and clean up resources on the C side'}
```

