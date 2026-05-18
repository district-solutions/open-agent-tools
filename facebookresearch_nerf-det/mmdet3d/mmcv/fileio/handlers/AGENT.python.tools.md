# Agent Python Tools

- repo: facebookresearch/nerf-det
- repo_uri: https://github.com/facebookresearch/nerf-det

## File: facebookresearch_nerf-det/mmdet3d/mmcv/fileio/handlers/base.py

Prompts

```
['review the BaseFileHandler abstract class and its str_like flag for file I/O handler design', 'implement the load_from_fileobj abstract method in a subclass to parse data from a file object', 'implement the dump_to_fileobj abstract method in a subclass to write data to a file object', 'implement the dump_to_str abstract method in a subclass to serialize an object to a string', 'use load_from_path to load and parse data from a file at a given filepath', 'use JsonHandler load_from_fileobj to load and parse JSON data from a file object', 'use JsonHandler dump_to_fileobj to serialize a Python object to JSON and write it to a file', 'use JsonHandler dump_to_str to serialize a Python object including numpy arrays to a JSON string', 'review the set_default function that converts set, range, numpy arrays, and numpy generics to JSON-serializable types', 'test JsonHandler dump_to_str to serialize a dictionary containing numpy.ndarray and numpy.int32 values to JSON', 'load a pickled Python object from a file path using PickleHandler load_from_path method', 'load a pickled Python object from an open file object using PickleHandler load_from_fileobj method', 'dump a Python object to a pickle file at a given path using PickleHandler dump_to_path method', 'dump a Python object to an open file object as pickle using PickleHandler dump_to_fileobj method', 'serialize a Python object to a pickle byte string using PickleHandler dump_to_str method', 'load a YAML file from disk into a Python dictionary using YamlHandler load_from_path', 'dump a Python dictionary to a YAML file on disk using YamlHandler dump_to_path', 'serialize a Python object to a YAML string using YamlHandler dump_to_str', 'parse YAML content from an open file object using YamlHandler load_from_fileobj', 'write a Python object as YAML to an open file object using YamlHandler dump_to_fileobj']
```

Usage

```
{'review_BaseFileHandler': 'review the BaseFileHandler abstract class and its str_like flag for file I/O handler design', 'implement_load_from_fileobj': 'implement the load_from_fileobj abstract method in a subclass to parse data from a file object', 'implement_dump_to_fileobj': 'implement the dump_to_fileobj abstract method in a subclass to write data to a file object', 'implement_dump_to_str': 'implement the dump_to_str abstract method in a subclass to serialize an object to a string', 'use_load_from_path': 'use load_from_path to load and parse data from a file at a given filepath'}
```

## File: facebookresearch_nerf-det/mmdet3d/mmcv/fileio/handlers/json_handler.py

Prompts

```
['review the BaseFileHandler abstract class and its str_like flag for file I/O handler design', 'implement the load_from_fileobj abstract method in a subclass to parse data from a file object', 'implement the dump_to_fileobj abstract method in a subclass to write data to a file object', 'implement the dump_to_str abstract method in a subclass to serialize an object to a string', 'use load_from_path to load and parse data from a file at a given filepath', 'use JsonHandler load_from_fileobj to load and parse JSON data from a file object', 'use JsonHandler dump_to_fileobj to serialize a Python object to JSON and write it to a file', 'use JsonHandler dump_to_str to serialize a Python object including numpy arrays to a JSON string', 'review the set_default function that converts set, range, numpy arrays, and numpy generics to JSON-serializable types', 'test JsonHandler dump_to_str to serialize a dictionary containing numpy.ndarray and numpy.int32 values to JSON', 'load a pickled Python object from a file path using PickleHandler load_from_path method', 'load a pickled Python object from an open file object using PickleHandler load_from_fileobj method', 'dump a Python object to a pickle file at a given path using PickleHandler dump_to_path method', 'dump a Python object to an open file object as pickle using PickleHandler dump_to_fileobj method', 'serialize a Python object to a pickle byte string using PickleHandler dump_to_str method', 'load a YAML file from disk into a Python dictionary using YamlHandler load_from_path', 'dump a Python dictionary to a YAML file on disk using YamlHandler dump_to_path', 'serialize a Python object to a YAML string using YamlHandler dump_to_str', 'parse YAML content from an open file object using YamlHandler load_from_fileobj', 'write a Python object as YAML to an open file object using YamlHandler dump_to_fileobj']
```

Usage

```
{'load_json_from_file': 'use JsonHandler load_from_fileobj to load and parse JSON data from a file object', 'dump_json_to_file': 'use JsonHandler dump_to_fileobj to serialize a Python object to JSON and write it to a file', 'dump_json_to_string': 'use JsonHandler dump_to_str to serialize a Python object including numpy arrays to a JSON string', 'review_set_default': 'review the set_default function that converts set, range, numpy arrays, and numpy generics to JSON-serializable types', 'test_json_handler_numpy': 'test JsonHandler dump_to_str to serialize a dictionary containing numpy.ndarray and numpy.int32 values to JSON'}
```

## File: facebookresearch_nerf-det/mmdet3d/mmcv/fileio/handlers/pickle_handler.py

Prompts

```
['review the BaseFileHandler abstract class and its str_like flag for file I/O handler design', 'implement the load_from_fileobj abstract method in a subclass to parse data from a file object', 'implement the dump_to_fileobj abstract method in a subclass to write data to a file object', 'implement the dump_to_str abstract method in a subclass to serialize an object to a string', 'use load_from_path to load and parse data from a file at a given filepath', 'use JsonHandler load_from_fileobj to load and parse JSON data from a file object', 'use JsonHandler dump_to_fileobj to serialize a Python object to JSON and write it to a file', 'use JsonHandler dump_to_str to serialize a Python object including numpy arrays to a JSON string', 'review the set_default function that converts set, range, numpy arrays, and numpy generics to JSON-serializable types', 'test JsonHandler dump_to_str to serialize a dictionary containing numpy.ndarray and numpy.int32 values to JSON', 'load a pickled Python object from a file path using PickleHandler load_from_path method', 'load a pickled Python object from an open file object using PickleHandler load_from_fileobj method', 'dump a Python object to a pickle file at a given path using PickleHandler dump_to_path method', 'dump a Python object to an open file object as pickle using PickleHandler dump_to_fileobj method', 'serialize a Python object to a pickle byte string using PickleHandler dump_to_str method', 'load a YAML file from disk into a Python dictionary using YamlHandler load_from_path', 'dump a Python dictionary to a YAML file on disk using YamlHandler dump_to_path', 'serialize a Python object to a YAML string using YamlHandler dump_to_str', 'parse YAML content from an open file object using YamlHandler load_from_fileobj', 'write a Python object as YAML to an open file object using YamlHandler dump_to_fileobj']
```

Usage

```
{'load_pickle_from_path': 'load a pickled Python object from a file path using PickleHandler load_from_path method', 'load_pickle_from_fileobj': 'load a pickled Python object from an open file object using PickleHandler load_from_fileobj method', 'dump_pickle_to_path': 'dump a Python object to a pickle file at a given path using PickleHandler dump_to_path method', 'dump_pickle_to_fileobj': 'dump a Python object to an open file object as pickle using PickleHandler dump_to_fileobj method', 'dump_pickle_to_str': 'serialize a Python object to a pickle byte string using PickleHandler dump_to_str method'}
```

## File: facebookresearch_nerf-det/mmdet3d/mmcv/fileio/handlers/yaml_handler.py

Prompts

```
['review the BaseFileHandler abstract class and its str_like flag for file I/O handler design', 'implement the load_from_fileobj abstract method in a subclass to parse data from a file object', 'implement the dump_to_fileobj abstract method in a subclass to write data to a file object', 'implement the dump_to_str abstract method in a subclass to serialize an object to a string', 'use load_from_path to load and parse data from a file at a given filepath', 'use JsonHandler load_from_fileobj to load and parse JSON data from a file object', 'use JsonHandler dump_to_fileobj to serialize a Python object to JSON and write it to a file', 'use JsonHandler dump_to_str to serialize a Python object including numpy arrays to a JSON string', 'review the set_default function that converts set, range, numpy arrays, and numpy generics to JSON-serializable types', 'test JsonHandler dump_to_str to serialize a dictionary containing numpy.ndarray and numpy.int32 values to JSON', 'load a pickled Python object from a file path using PickleHandler load_from_path method', 'load a pickled Python object from an open file object using PickleHandler load_from_fileobj method', 'dump a Python object to a pickle file at a given path using PickleHandler dump_to_path method', 'dump a Python object to an open file object as pickle using PickleHandler dump_to_fileobj method', 'serialize a Python object to a pickle byte string using PickleHandler dump_to_str method', 'load a YAML file from disk into a Python dictionary using YamlHandler load_from_path', 'dump a Python dictionary to a YAML file on disk using YamlHandler dump_to_path', 'serialize a Python object to a YAML string using YamlHandler dump_to_str', 'parse YAML content from an open file object using YamlHandler load_from_fileobj', 'write a Python object as YAML to an open file object using YamlHandler dump_to_fileobj']
```

Usage

```
{'load_yaml_from_file': 'load a YAML file from disk into a Python dictionary using YamlHandler load_from_path', 'dump_yaml_to_file': 'dump a Python dictionary to a YAML file on disk using YamlHandler dump_to_path', 'dump_yaml_to_string': 'serialize a Python object to a YAML string using YamlHandler dump_to_str', 'load_yaml_from_fileobj': 'parse YAML content from an open file object using YamlHandler load_from_fileobj', 'dump_yaml_to_fileobj': 'write a Python object as YAML to an open file object using YamlHandler dump_to_fileobj'}
```

