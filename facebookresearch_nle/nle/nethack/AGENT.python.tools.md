# Agent Python Tools

- repo: facebookresearch/nle
- repo_uri: https://github.com/facebookresearch/nle

## File: facebookresearch_nle/nle/nethack/actions.py

Prompts

```
['use the M function to compute a Meta-modified action byte from a character or integer', 'use the C function to compute a Control-modified action byte from a character or integer', 'use the CompassDirection enum to get action bytes for the 8 compass movement directions', 'use the Command enum to get action bytes for NetHack game commands like DROP, EAT, or CAST', 'use action_id_to_type to look up the enum class and name for a given action byte value', 'create a Nethack instance with custom player name and observation keys for NetHack Learning Environment', 'step the Nethack environment with an action and return the observation tuple and done status', 'reset the Nethack game to start a new episode with optional ttyrec and wizkit items', 'render terminal characters and colors as an ANSI escape sequence string with optional cursor position', 'set the core and disp RNG seeds on the Nethack instance to control reproducibility and reseeding']
```

Usage

```
{'use_M_function': 'use the M function to compute a Meta-modified action byte from a character or integer', 'use_C_function': 'use the C function to compute a Control-modified action byte from a character or integer', 'use_CompassDirection_enum': 'use the CompassDirection enum to get action bytes for the 8 compass movement directions', 'use_Command_enum': 'use the Command enum to get action bytes for NetHack game commands like DROP, EAT, or CAST', 'use_action_id_to_type': 'use action_id_to_type to look up the enum class and name for a given action byte value'}
```

## File: facebookresearch_nle/nle/nethack/nethack.py

Prompts

```
['use the M function to compute a Meta-modified action byte from a character or integer', 'use the C function to compute a Control-modified action byte from a character or integer', 'use the CompassDirection enum to get action bytes for the 8 compass movement directions', 'use the Command enum to get action bytes for NetHack game commands like DROP, EAT, or CAST', 'use action_id_to_type to look up the enum class and name for a given action byte value', 'create a Nethack instance with custom player name and observation keys for NetHack Learning Environment', 'step the Nethack environment with an action and return the observation tuple and done status', 'reset the Nethack game to start a new episode with optional ttyrec and wizkit items', 'render terminal characters and colors as an ANSI escape sequence string with optional cursor position', 'set the core and disp RNG seeds on the Nethack instance to control reproducibility and reseeding']
```

Usage

```
{'create_Nethack_instance': 'create a Nethack instance with custom player name and observation keys for NetHack Learning Environment', 'step_Nethack_action': 'step the Nethack environment with an action and return the observation tuple and done status', 'reset_Nethack_game': 'reset the Nethack game to start a new episode with optional ttyrec and wizkit items', 'render_tty_ANSI': 'render terminal characters and colors as an ANSI escape sequence string with optional cursor position', 'set_Nethack_seeds': 'set the core and disp RNG seeds on the Nethack instance to control reproducibility and reseeding'}
```

