# Agent Python Tools

- repo: google-deepmind/deepmind-research
- repo_uri: https://github.com/google-deepmind/deepmind-research

## File: google-deepmind_deepmind-research/hierarchical_transformer_memory/pycolab_ballet/ballet_environment.py

Prompts

```
['run the ballet environment main function to observe dancer episodes with a 4_delay16 level', 'create a BalletEnvironment instance with a specified number of dancers, dance delay, and max steps', 'build a BalletEnvironment using simple_builder with a level name like 4_delay16 or 8_delay48', 'generate a template object image for a dancer given its color and shape name', 'reset the ballet environment to start a new episode with randomized dancers and positions', 'create a pycolab game with dancers and properties using make_game for the ballet environment', 'build a DancerSprite subclass with custom motion, color, shape, and reward value for the ballet game', 'create a PlayerSprite maze walker that moves in eight directions during the choice phase', 'use the DIRECTIONS enum to define eight-way movement actions for agents and dancers', 'access predefined dance sequences like circle_cw or zee to configure dancer motion patterns', 'test the BalletEnvironment class with reset and step actions to verify observation shapes and rewards', 'test the simple_builder function with parameterized level names like 2_delay16 and 8_delay48', 'test that env.step returns observations with correct upscaled image dimensions and dance phase strings', 'test egocentric scrolling by verifying the orange plus template appears centered in the observation', 'test that simple_builder sets max_steps to 320 or 1024 depending on the dance delay parameter']
```

Usage

```
{'run_ballet_environment': 'run the ballet environment main function to observe dancer episodes with a 4_delay16 level', 'create_ballet_environment': 'create a BalletEnvironment instance with a specified number of dancers, dance delay, and max steps', 'build_ballet_level': 'build a BalletEnvironment using simple_builder with a level name like 4_delay16 or 8_delay48', 'generate_dancer_template': 'generate a template object image for a dancer given its color and shape name', 'reset_ballet_episode': 'reset the ballet environment to start a new episode with randomized dancers and positions'}
```

## File: google-deepmind_deepmind-research/hierarchical_transformer_memory/pycolab_ballet/ballet_environment_core.py

Prompts

```
['run the ballet environment main function to observe dancer episodes with a 4_delay16 level', 'create a BalletEnvironment instance with a specified number of dancers, dance delay, and max steps', 'build a BalletEnvironment using simple_builder with a level name like 4_delay16 or 8_delay48', 'generate a template object image for a dancer given its color and shape name', 'reset the ballet environment to start a new episode with randomized dancers and positions', 'create a pycolab game with dancers and properties using make_game for the ballet environment', 'build a DancerSprite subclass with custom motion, color, shape, and reward value for the ballet game', 'create a PlayerSprite maze walker that moves in eight directions during the choice phase', 'use the DIRECTIONS enum to define eight-way movement actions for agents and dancers', 'access predefined dance sequences like circle_cw or zee to configure dancer motion patterns', 'test the BalletEnvironment class with reset and step actions to verify observation shapes and rewards', 'test the simple_builder function with parameterized level names like 2_delay16 and 8_delay48', 'test that env.step returns observations with correct upscaled image dimensions and dance phase strings', 'test egocentric scrolling by verifying the orange plus template appears centered in the observation', 'test that simple_builder sets max_steps to 320 or 1024 depending on the dance delay parameter']
```

Usage

```
{'make_game': 'create a pycolab game with dancers and properties using make_game for the ballet environment', 'DancerSprite': 'build a DancerSprite subclass with custom motion, color, shape, and reward value for the ballet game', 'PlayerSprite': 'create a PlayerSprite maze walker that moves in eight directions during the choice phase', 'DIRECTIONS': 'use the DIRECTIONS enum to define eight-way movement actions for agents and dancers', 'DANCE_SEQUENCES': 'access predefined dance sequences like circle_cw or zee to configure dancer motion patterns'}
```

## File: google-deepmind_deepmind-research/hierarchical_transformer_memory/pycolab_ballet/ballet_environment_test.py

Prompts

```
['run the ballet environment main function to observe dancer episodes with a 4_delay16 level', 'create a BalletEnvironment instance with a specified number of dancers, dance delay, and max steps', 'build a BalletEnvironment using simple_builder with a level name like 4_delay16 or 8_delay48', 'generate a template object image for a dancer given its color and shape name', 'reset the ballet environment to start a new episode with randomized dancers and positions', 'create a pycolab game with dancers and properties using make_game for the ballet environment', 'build a DancerSprite subclass with custom motion, color, shape, and reward value for the ballet game', 'create a PlayerSprite maze walker that moves in eight directions during the choice phase', 'use the DIRECTIONS enum to define eight-way movement actions for agents and dancers', 'access predefined dance sequences like circle_cw or zee to configure dancer motion patterns', 'test the BalletEnvironment class with reset and step actions to verify observation shapes and rewards', 'test the simple_builder function with parameterized level names like 2_delay16 and 8_delay48', 'test that env.step returns observations with correct upscaled image dimensions and dance phase strings', 'test egocentric scrolling by verifying the orange plus template appears centered in the observation', 'test that simple_builder sets max_steps to 320 or 1024 depending on the dance delay parameter']
```

Usage

```
{'test_BalletEnvironment_full_wrapper': 'test the BalletEnvironment class with reset and step actions to verify observation shapes and rewards', 'test_BalletEnvironment_simple_builder': 'test the simple_builder function with parameterized level names like 2_delay16 and 8_delay48', 'test_BalletEnvironment_step_observations': 'test that env.step returns observations with correct upscaled image dimensions and dance phase strings', 'test_BalletEnvironment_egocentric_scrolling': 'test egocentric scrolling by verifying the orange plus template appears centered in the observation', 'test_BalletEnvironment_max_steps': 'test that simple_builder sets max_steps to 320 or 1024 depending on the dance delay parameter'}
```

