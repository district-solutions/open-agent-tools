# Agent Python Tools

- repo: facebookresearch/torchray
- repo_uri: https://github.com/facebookresearch/torchray

## File: facebookresearch_torchray/torchray/benchmark/datasets.py

Prompts

```
['create a benchmark dataset by calling get_dataset with name, subset, and optional limiter arguments', 'build an ImageFolder dataset with optional round-robin class limiter and full class names', 'create a PASCAL VOC detection dataset with optional image limiter and custom transforms', 'build a COCO detection dataset with optional image limiter and custom transforms', 'convert a VOC detection label dict to a list of class IDs', 'connect to a MongoDB database by name and return a pymongo Database object', 'save benchmark results to a MongoDB collection with retry logic on write errors', 'load data from a MongoDB collection by its id key', 'convert torch tensors and numpy arrays to BSON binary for MongoDB storage', 'decode BSON binary data from MongoDB back into torch tensors or numpy arrays', 'get a VGG16 model fine-tuned on PASCAL VOC dataset for attribution benchmarking', 'get a ResNet50 model fine-tuned on COCO dataset for attribution benchmarking', 'get a fully convolutional VGG16 model by converting linear layers to convolutional', 'get standard ImageNet preprocessing transforms including resize, tensor conversion, and normalization', 'replace a named submodule in a PyTorch model with a new module', 'build a PointingGame instance with a given number of classes and pixel tolerance for hit evaluation', 'run the evaluate method to test if a predicted point falls within the object mask tolerance', 'run the PointingGameBenchmark evaluate method on a VOC or COCO label-class-point triplet', 'test the class_accuracies property to get per-class accuracy from accumulated hits and misses', 'test the accuracy property to compute the mean accuracy across all classes', 'run a MongoDB instance as a logging server using torchray benchmark configuration', 'run the run_server function to start MongoDB via subprocess with config-driven arguments', 'review the run_server function that launches MongoDB with dbpath, bind_ip, and port from config', 'summarize the torchray benchmark server module used to start a MongoDB logging server', 'test the run_server function to verify it starts MongoDB with correct config values']
```

Usage

```
{'get_dataset': 'create a benchmark dataset by calling get_dataset with name, subset, and optional limiter arguments', 'ImageFolder': 'build an ImageFolder dataset with optional round-robin class limiter and full class names', 'VOCDetection': 'create a PASCAL VOC detection dataset with optional image limiter and custom transforms', 'CocoDetection': 'build a COCO detection dataset with optional image limiter and custom transforms', 'voc_as_class_ids': 'convert a VOC detection label dict to a list of class IDs'}
```

## File: facebookresearch_torchray/torchray/benchmark/logging.py

Prompts

```
['create a benchmark dataset by calling get_dataset with name, subset, and optional limiter arguments', 'build an ImageFolder dataset with optional round-robin class limiter and full class names', 'create a PASCAL VOC detection dataset with optional image limiter and custom transforms', 'build a COCO detection dataset with optional image limiter and custom transforms', 'convert a VOC detection label dict to a list of class IDs', 'connect to a MongoDB database by name and return a pymongo Database object', 'save benchmark results to a MongoDB collection with retry logic on write errors', 'load data from a MongoDB collection by its id key', 'convert torch tensors and numpy arrays to BSON binary for MongoDB storage', 'decode BSON binary data from MongoDB back into torch tensors or numpy arrays', 'get a VGG16 model fine-tuned on PASCAL VOC dataset for attribution benchmarking', 'get a ResNet50 model fine-tuned on COCO dataset for attribution benchmarking', 'get a fully convolutional VGG16 model by converting linear layers to convolutional', 'get standard ImageNet preprocessing transforms including resize, tensor conversion, and normalization', 'replace a named submodule in a PyTorch model with a new module', 'build a PointingGame instance with a given number of classes and pixel tolerance for hit evaluation', 'run the evaluate method to test if a predicted point falls within the object mask tolerance', 'run the PointingGameBenchmark evaluate method on a VOC or COCO label-class-point triplet', 'test the class_accuracies property to get per-class accuracy from accumulated hits and misses', 'test the accuracy property to compute the mean accuracy across all classes', 'run a MongoDB instance as a logging server using torchray benchmark configuration', 'run the run_server function to start MongoDB via subprocess with config-driven arguments', 'review the run_server function that launches MongoDB with dbpath, bind_ip, and port from config', 'summarize the torchray benchmark server module used to start a MongoDB logging server', 'test the run_server function to verify it starts MongoDB with correct config values']
```

Usage

```
{'mongo_connect': 'connect to a MongoDB database by name and return a pymongo Database object', 'mongo_save': 'save benchmark results to a MongoDB collection with retry logic on write errors', 'mongo_load': 'load data from a MongoDB collection by its id key', 'data_to_mongo': 'convert torch tensors and numpy arrays to BSON binary for MongoDB storage', 'data_from_mongo': 'decode BSON binary data from MongoDB back into torch tensors or numpy arrays'}
```

## File: facebookresearch_torchray/torchray/benchmark/models.py

Prompts

```
['create a benchmark dataset by calling get_dataset with name, subset, and optional limiter arguments', 'build an ImageFolder dataset with optional round-robin class limiter and full class names', 'create a PASCAL VOC detection dataset with optional image limiter and custom transforms', 'build a COCO detection dataset with optional image limiter and custom transforms', 'convert a VOC detection label dict to a list of class IDs', 'connect to a MongoDB database by name and return a pymongo Database object', 'save benchmark results to a MongoDB collection with retry logic on write errors', 'load data from a MongoDB collection by its id key', 'convert torch tensors and numpy arrays to BSON binary for MongoDB storage', 'decode BSON binary data from MongoDB back into torch tensors or numpy arrays', 'get a VGG16 model fine-tuned on PASCAL VOC dataset for attribution benchmarking', 'get a ResNet50 model fine-tuned on COCO dataset for attribution benchmarking', 'get a fully convolutional VGG16 model by converting linear layers to convolutional', 'get standard ImageNet preprocessing transforms including resize, tensor conversion, and normalization', 'replace a named submodule in a PyTorch model with a new module', 'build a PointingGame instance with a given number of classes and pixel tolerance for hit evaluation', 'run the evaluate method to test if a predicted point falls within the object mask tolerance', 'run the PointingGameBenchmark evaluate method on a VOC or COCO label-class-point triplet', 'test the class_accuracies property to get per-class accuracy from accumulated hits and misses', 'test the accuracy property to compute the mean accuracy across all classes', 'run a MongoDB instance as a logging server using torchray benchmark configuration', 'run the run_server function to start MongoDB via subprocess with config-driven arguments', 'review the run_server function that launches MongoDB with dbpath, bind_ip, and port from config', 'summarize the torchray benchmark server module used to start a MongoDB logging server', 'test the run_server function to verify it starts MongoDB with correct config values']
```

Usage

```
{'get_model_vgg16_voc': 'get a VGG16 model fine-tuned on PASCAL VOC dataset for attribution benchmarking', 'get_model_resnet50_coco': 'get a ResNet50 model fine-tuned on COCO dataset for attribution benchmarking', 'get_model_fully_convolutional': 'get a fully convolutional VGG16 model by converting linear layers to convolutional', 'get_transform_imagenet': 'get standard ImageNet preprocessing transforms including resize, tensor conversion, and normalization', 'replace_module': 'replace a named submodule in a PyTorch model with a new module'}
```

## File: facebookresearch_torchray/torchray/benchmark/pointing_game.py

Prompts

```
['create a benchmark dataset by calling get_dataset with name, subset, and optional limiter arguments', 'build an ImageFolder dataset with optional round-robin class limiter and full class names', 'create a PASCAL VOC detection dataset with optional image limiter and custom transforms', 'build a COCO detection dataset with optional image limiter and custom transforms', 'convert a VOC detection label dict to a list of class IDs', 'connect to a MongoDB database by name and return a pymongo Database object', 'save benchmark results to a MongoDB collection with retry logic on write errors', 'load data from a MongoDB collection by its id key', 'convert torch tensors and numpy arrays to BSON binary for MongoDB storage', 'decode BSON binary data from MongoDB back into torch tensors or numpy arrays', 'get a VGG16 model fine-tuned on PASCAL VOC dataset for attribution benchmarking', 'get a ResNet50 model fine-tuned on COCO dataset for attribution benchmarking', 'get a fully convolutional VGG16 model by converting linear layers to convolutional', 'get standard ImageNet preprocessing transforms including resize, tensor conversion, and normalization', 'replace a named submodule in a PyTorch model with a new module', 'build a PointingGame instance with a given number of classes and pixel tolerance for hit evaluation', 'run the evaluate method to test if a predicted point falls within the object mask tolerance', 'run the PointingGameBenchmark evaluate method on a VOC or COCO label-class-point triplet', 'test the class_accuracies property to get per-class accuracy from accumulated hits and misses', 'test the accuracy property to compute the mean accuracy across all classes', 'run a MongoDB instance as a logging server using torchray benchmark configuration', 'run the run_server function to start MongoDB via subprocess with config-driven arguments', 'review the run_server function that launches MongoDB with dbpath, bind_ip, and port from config', 'summarize the torchray benchmark server module used to start a MongoDB logging server', 'test the run_server function to verify it starts MongoDB with correct config values']
```

Usage

```
{'build_PointingGame': 'build a PointingGame instance with a given number of classes and pixel tolerance for hit evaluation', 'run_PointingGame_evaluate': 'run the evaluate method to test if a predicted point falls within the object mask tolerance', 'run_PointingGameBenchmark_evaluate': 'run the PointingGameBenchmark evaluate method on a VOC or COCO label-class-point triplet', 'test_PointingGame_class_accuracies': 'test the class_accuracies property to get per-class accuracy from accumulated hits and misses', 'test_PointingGame_accuracy': 'test the accuracy property to compute the mean accuracy across all classes'}
```

## File: facebookresearch_torchray/torchray/benchmark/server.py

Prompts

```
['create a benchmark dataset by calling get_dataset with name, subset, and optional limiter arguments', 'build an ImageFolder dataset with optional round-robin class limiter and full class names', 'create a PASCAL VOC detection dataset with optional image limiter and custom transforms', 'build a COCO detection dataset with optional image limiter and custom transforms', 'convert a VOC detection label dict to a list of class IDs', 'connect to a MongoDB database by name and return a pymongo Database object', 'save benchmark results to a MongoDB collection with retry logic on write errors', 'load data from a MongoDB collection by its id key', 'convert torch tensors and numpy arrays to BSON binary for MongoDB storage', 'decode BSON binary data from MongoDB back into torch tensors or numpy arrays', 'get a VGG16 model fine-tuned on PASCAL VOC dataset for attribution benchmarking', 'get a ResNet50 model fine-tuned on COCO dataset for attribution benchmarking', 'get a fully convolutional VGG16 model by converting linear layers to convolutional', 'get standard ImageNet preprocessing transforms including resize, tensor conversion, and normalization', 'replace a named submodule in a PyTorch model with a new module', 'build a PointingGame instance with a given number of classes and pixel tolerance for hit evaluation', 'run the evaluate method to test if a predicted point falls within the object mask tolerance', 'run the PointingGameBenchmark evaluate method on a VOC or COCO label-class-point triplet', 'test the class_accuracies property to get per-class accuracy from accumulated hits and misses', 'test the accuracy property to compute the mean accuracy across all classes', 'run a MongoDB instance as a logging server using torchray benchmark configuration', 'run the run_server function to start MongoDB via subprocess with config-driven arguments', 'review the run_server function that launches MongoDB with dbpath, bind_ip, and port from config', 'summarize the torchray benchmark server module used to start a MongoDB logging server', 'test the run_server function to verify it starts MongoDB with correct config values']
```

Usage

```
{'run_mongodb_server': 'run a MongoDB instance as a logging server using torchray benchmark configuration', 'run_server_subprocess': 'run the run_server function to start MongoDB via subprocess with config-driven arguments', 'review_run_server': 'review the run_server function that launches MongoDB with dbpath, bind_ip, and port from config', 'summarize_server_module': 'summarize the torchray benchmark server module used to start a MongoDB logging server', 'test_run_server': 'test the run_server function to verify it starts MongoDB with correct config values'}
```

