# Agent Python Tools

- repo: facebookresearch/recipes
- repo_uri: https://github.com/facebookresearch/recipes

## File: facebookresearch_recipes/torchrecipes/utils/tests/test_config_utils.py

Prompts

```
['test the config_entry decorator on a static method to verify it registers correctly', 'test get_class_name_str returns the fully qualified class name for a given class', 'test get_class_config_method returns the fully qualified config method string for a class', 'test that get_class_config_method raises ValueError when config_entry is on a non-static method', 'test that get_class_config_method raises ValueError when multiple config_entry decorators exist on a class', 'test the default TrainerConf with no plugins and verify zero plugins are returned', 'test TrainerConf with ddp_find_unused_parameters_false plugin and verify DDPStrategy has find_unused_parameters set to False', 'test TrainerConf with ddp_fp16_compress plugin and verify DDPStrategy uses fp16_compress_hook', 'test TrainerConf with multiple DDP plugins merged into a single DDPStrategy with combined settings', 'test TrainerConf with ddp_fully_sharded plugin and optional precision 16 to verify DDPFullyShardedStrategy and precision plugins']
```

Usage

```
{'test_config_entry_decorator': 'test the config_entry decorator on a static method to verify it registers correctly', 'test_get_class_name_str': 'test get_class_name_str returns the fully qualified class name for a given class', 'test_get_class_config_method': 'test get_class_config_method returns the fully qualified config method string for a class', 'test_annotation_failure_non_static': 'test that get_class_config_method raises ValueError when config_entry is on a non-static method', 'test_annotation_failure_multiple_entries': 'test that get_class_config_method raises ValueError when multiple config_entry decorators exist on a class'}
```

## File: facebookresearch_recipes/torchrecipes/utils/tests/test_trainer_plugins.py

Prompts

```
['test the config_entry decorator on a static method to verify it registers correctly', 'test get_class_name_str returns the fully qualified class name for a given class', 'test get_class_config_method returns the fully qualified config method string for a class', 'test that get_class_config_method raises ValueError when config_entry is on a non-static method', 'test that get_class_config_method raises ValueError when multiple config_entry decorators exist on a class', 'test the default TrainerConf with no plugins and verify zero plugins are returned', 'test TrainerConf with ddp_find_unused_parameters_false plugin and verify DDPStrategy has find_unused_parameters set to False', 'test TrainerConf with ddp_fp16_compress plugin and verify DDPStrategy uses fp16_compress_hook', 'test TrainerConf with multiple DDP plugins merged into a single DDPStrategy with combined settings', 'test TrainerConf with ddp_fully_sharded plugin and optional precision 16 to verify DDPFullyShardedStrategy and precision plugins']
```

Usage

```
{'test_default_trainer_conf': 'test the default TrainerConf with no plugins and verify zero plugins are returned', 'test_ddp_find_unused_parameters_false': 'test TrainerConf with ddp_find_unused_parameters_false plugin and verify DDPStrategy has find_unused_parameters set to False', 'test_ddp_fp16_compress_plugin': 'test TrainerConf with ddp_fp16_compress plugin and verify DDPStrategy uses fp16_compress_hook', 'test_ddp_multiple_plugins': 'test TrainerConf with multiple DDP plugins merged into a single DDPStrategy with combined settings', 'test_ddp_fully_sharded_precision': 'test TrainerConf with ddp_fully_sharded plugin and optional precision 16 to verify DDPFullyShardedStrategy and precision plugins'}
```

