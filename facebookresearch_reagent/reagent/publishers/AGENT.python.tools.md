# Agent Python Tools

- repo: facebookresearch/reagent
- repo_uri: https://github.com/facebookresearch/reagent

## File: facebookresearch_reagent/reagent/publishers/file_system_publisher.py

Prompts

```
['create a FileSystemPublisher instance with a custom publishing file path for model storage', 'get the latest published torchscript model path for a given model manager and module name', 'publish RL training output model paths to the TinyDB file system key-value store', 'review the FileSystemPublisher class that uses TinyDB as a file-based key-value store for model paths', 'refactor the FileSystemPublisher to replace TinyDB with redis for better RASP support', 'create a subclass of ModelPublisher that implements the abstract do_publish method for a custom publishing workflow', 'implement the do_publish method in a ModelPublisher subclass to publish RL training output to a serving module', 'call the publish method on a ModelPublisher instance to publish training results with setup data and workflow IDs', 'review the ModelPublisher base class and its abstract do_publish method to understand the publishing contract', 'register a new ModelPublisher subclass using the RegistryMeta metaclass so it can be discovered in workflows', 'create a NoPublishing instance to act as a no-op model publisher in the reagent pipeline', 'run do_publish on a NoPublishing instance to skip model publishing and return success', 'test the NoPublishing class to verify it returns NoPublishingResults with success True', 'review the NoPublishing do_publish method signature and its RLTrainingOutput and workflow parameters', 'refactor the NoPublishing class to add actual publishing logic instead of returning a no-op result']
```

Usage

```
{'create_filesystem_publisher': 'create a FileSystemPublisher instance with a custom publishing file path for model storage', 'get_latest_published_model': 'get the latest published torchscript model path for a given model manager and module name', 'do_publish': 'publish RL training output model paths to the TinyDB file system key-value store', 'review_filesystem_publisher_class': 'review the FileSystemPublisher class that uses TinyDB as a file-based key-value store for model paths', 'refactor_filesystem_publisher': 'refactor the FileSystemPublisher to replace TinyDB with redis for better RASP support'}
```

## File: facebookresearch_reagent/reagent/publishers/model_publisher.py

Prompts

```
['create a FileSystemPublisher instance with a custom publishing file path for model storage', 'get the latest published torchscript model path for a given model manager and module name', 'publish RL training output model paths to the TinyDB file system key-value store', 'review the FileSystemPublisher class that uses TinyDB as a file-based key-value store for model paths', 'refactor the FileSystemPublisher to replace TinyDB with redis for better RASP support', 'create a subclass of ModelPublisher that implements the abstract do_publish method for a custom publishing workflow', 'implement the do_publish method in a ModelPublisher subclass to publish RL training output to a serving module', 'call the publish method on a ModelPublisher instance to publish training results with setup data and workflow IDs', 'review the ModelPublisher base class and its abstract do_publish method to understand the publishing contract', 'register a new ModelPublisher subclass using the RegistryMeta metaclass so it can be discovered in workflows', 'create a NoPublishing instance to act as a no-op model publisher in the reagent pipeline', 'run do_publish on a NoPublishing instance to skip model publishing and return success', 'test the NoPublishing class to verify it returns NoPublishingResults with success True', 'review the NoPublishing do_publish method signature and its RLTrainingOutput and workflow parameters', 'refactor the NoPublishing class to add actual publishing logic instead of returning a no-op result']
```

Usage

```
{'subclass_ModelPublisher': 'create a subclass of ModelPublisher that implements the abstract do_publish method for a custom publishing workflow', 'implement_do_publish': 'implement the do_publish method in a ModelPublisher subclass to publish RL training output to a serving module', 'call_publish': 'call the publish method on a ModelPublisher instance to publish training results with setup data and workflow IDs', 'review_ModelPublisher': 'review the ModelPublisher base class and its abstract do_publish method to understand the publishing contract', 'register_ModelPublisher_subclass': 'register a new ModelPublisher subclass using the RegistryMeta metaclass so it can be discovered in workflows'}
```

## File: facebookresearch_reagent/reagent/publishers/no_publishing.py

Prompts

```
['create a FileSystemPublisher instance with a custom publishing file path for model storage', 'get the latest published torchscript model path for a given model manager and module name', 'publish RL training output model paths to the TinyDB file system key-value store', 'review the FileSystemPublisher class that uses TinyDB as a file-based key-value store for model paths', 'refactor the FileSystemPublisher to replace TinyDB with redis for better RASP support', 'create a subclass of ModelPublisher that implements the abstract do_publish method for a custom publishing workflow', 'implement the do_publish method in a ModelPublisher subclass to publish RL training output to a serving module', 'call the publish method on a ModelPublisher instance to publish training results with setup data and workflow IDs', 'review the ModelPublisher base class and its abstract do_publish method to understand the publishing contract', 'register a new ModelPublisher subclass using the RegistryMeta metaclass so it can be discovered in workflows', 'create a NoPublishing instance to act as a no-op model publisher in the reagent pipeline', 'run do_publish on a NoPublishing instance to skip model publishing and return success', 'test the NoPublishing class to verify it returns NoPublishingResults with success True', 'review the NoPublishing do_publish method signature and its RLTrainingOutput and workflow parameters', 'refactor the NoPublishing class to add actual publishing logic instead of returning a no-op result']
```

Usage

```
{'create_no_publishing_publisher': 'create a NoPublishing instance to act as a no-op model publisher in the reagent pipeline', 'run_do_publish_noop': 'run do_publish on a NoPublishing instance to skip model publishing and return success', 'test_no_publishing_class': 'test the NoPublishing class to verify it returns NoPublishingResults with success True', 'review_no_publishing_do_publish': 'review the NoPublishing do_publish method signature and its RLTrainingOutput and workflow parameters', 'refactor_no_publishing_publisher': 'refactor the NoPublishing class to add actual publishing logic instead of returning a no-op result'}
```

