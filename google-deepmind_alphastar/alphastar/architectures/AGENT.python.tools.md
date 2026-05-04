# Agent Python Tools

- repo: google-deepmind/alphastar
- repo_uri: https://github.com/google-deepmind/alphastar

## File: google-deepmind_alphastar/alphastar/architectures/architectures.py

Prompts

```
['get an architecture builder by name like alphastar.lite or alphastar.full for StarCraft II model building', 'get the default config dictionary for an architecture like alphastar.lite or alphastar.full', 'check if an architecture string contains a transformer module by searching for the word transformer', 'validate that an architecture name like alphastar.dummy is one of the supported architecture names', 'list all available architecture names including alphastar.dummy alphastar.lite and alphastar.full', 'create a python subclass of Component implementing input_spec output_spec and _unroll method', 'build a BatchedComponent subclass implementing _forward to process single timesteps without state', 'build a SequentialComponent by appending multiple Components to chain their outputs together', 'review the input_spec prev_state_spec output_spec and next_state_spec properties of a Component', 'test a Component unroll method by passing StreamDict inputs and prev_state arguments', 'get the world map size from a StarCraft action spec by computing the square root of the world maximum', 'review the Argument class constants for StarCraft action argument names like FUNCTION DELAY and UNIT_TAGS', 'summarize the get_world_size function that extracts the square world map dimensions from an action spec', 'test the get_world_size function with a mock action spec containing a world maximum value', 'refactor the Argument class to use an Enum type instead of plain string class attributes']
```

Usage

```
{'get_architecture': 'get an architecture builder by name like alphastar.lite or alphastar.full for StarCraft II model building', 'get_default_config': 'get the default config dictionary for an architecture like alphastar.lite or alphastar.full', 'is_transformer_arch': 'check if an architecture string contains a transformer module by searching for the word transformer', 'check_architecture_supported': 'validate that an architecture name like alphastar.dummy is one of the supported architecture names', 'list_architecture_names': 'list all available architecture names including alphastar.dummy alphastar.lite and alphastar.full'}
```

## File: google-deepmind_alphastar/alphastar/architectures/modular.py

Prompts

```
['get an architecture builder by name like alphastar.lite or alphastar.full for StarCraft II model building', 'get the default config dictionary for an architecture like alphastar.lite or alphastar.full', 'check if an architecture string contains a transformer module by searching for the word transformer', 'validate that an architecture name like alphastar.dummy is one of the supported architecture names', 'list all available architecture names including alphastar.dummy alphastar.lite and alphastar.full', 'create a python subclass of Component implementing input_spec output_spec and _unroll method', 'build a BatchedComponent subclass implementing _forward to process single timesteps without state', 'build a SequentialComponent by appending multiple Components to chain their outputs together', 'review the input_spec prev_state_spec output_spec and next_state_spec properties of a Component', 'test a Component unroll method by passing StreamDict inputs and prev_state arguments', 'get the world map size from a StarCraft action spec by computing the square root of the world maximum', 'review the Argument class constants for StarCraft action argument names like FUNCTION DELAY and UNIT_TAGS', 'summarize the get_world_size function that extracts the square world map dimensions from an action spec', 'test the get_world_size function with a mock action spec containing a world maximum value', 'refactor the Argument class to use an Enum type instead of plain string class attributes']
```

Usage

```
{'create_component_subclass': 'create a python subclass of Component implementing input_spec output_spec and _unroll method', 'build_batched_component': 'build a BatchedComponent subclass implementing _forward to process single timesteps without state', 'chain_sequential_components': 'build a SequentialComponent by appending multiple Components to chain their outputs together', 'review_component_specs': 'review the input_spec prev_state_spec output_spec and next_state_spec properties of a Component', 'test_component_unroll': 'test a Component unroll method by passing StreamDict inputs and prev_state arguments'}
```

## File: google-deepmind_alphastar/alphastar/architectures/util.py

Prompts

```
['get an architecture builder by name like alphastar.lite or alphastar.full for StarCraft II model building', 'get the default config dictionary for an architecture like alphastar.lite or alphastar.full', 'check if an architecture string contains a transformer module by searching for the word transformer', 'validate that an architecture name like alphastar.dummy is one of the supported architecture names', 'list all available architecture names including alphastar.dummy alphastar.lite and alphastar.full', 'create a python subclass of Component implementing input_spec output_spec and _unroll method', 'build a BatchedComponent subclass implementing _forward to process single timesteps without state', 'build a SequentialComponent by appending multiple Components to chain their outputs together', 'review the input_spec prev_state_spec output_spec and next_state_spec properties of a Component', 'test a Component unroll method by passing StreamDict inputs and prev_state arguments', 'get the world map size from a StarCraft action spec by computing the square root of the world maximum', 'review the Argument class constants for StarCraft action argument names like FUNCTION DELAY and UNIT_TAGS', 'summarize the get_world_size function that extracts the square world map dimensions from an action spec', 'test the get_world_size function with a mock action spec containing a world maximum value', 'refactor the Argument class to use an Enum type instead of plain string class attributes']
```

Usage

```
{'get_world_size': 'get the world map size from a StarCraft action spec by computing the square root of the world maximum', 'review_Argument': 'review the Argument class constants for StarCraft action argument names like FUNCTION DELAY and UNIT_TAGS', 'summarize_get_world_size': 'summarize the get_world_size function that extracts the square world map dimensions from an action spec', 'test_get_world_size': 'test the get_world_size function with a mock action spec containing a world maximum value', 'refactor_Argument': 'refactor the Argument class to use an Enum type instead of plain string class attributes'}
```

