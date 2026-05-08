# Agent Python Tools

- repo: facebookresearch/pytouch
- repo_uri: https://github.com/facebookresearch/pytouch

## File: facebookresearch_pytouch/pytouch/sensors/base.py

Prompts

```
['create a SensorBase instance with a sensor name, data source type, and optional data path', "call the name method on a SensorBase instance to retrieve the sensor's name string", 'get the string representation of a SensorBase instance showing sensor name, data source, and data path', 'instantiate a SensorBase with DATASET data source to validate that a data path is required', 'instantiate a SensorBase with VIDEO data source to validate that a data path is required', 'create a DigitSensor instance with a data source and optional custom transform pipeline', 'build a composed torchvision transform pipeline that resizes to 64x64, converts to tensor, and normalizes', 'review the DigitSensorDefaults class with SCALES, MEANS, and STDS constants for image normalization', 'test the DigitSensor zoo_name static method that returns the string DigitSensor', 'refactor the DigitSensor constructor to accept a custom transform or use the default composed pipeline', 'create a GelsightSensor instance with a data source and optional data path', 'build a torchvision transform pipeline that resizes to 64x64 and normalizes using ImageNet stats', 'review the GelsightSensorDefaults class for default scale, mean, and standard deviation values', 'test the GelsightSensor zoo_name static method returns the string GelSightSensor', 'refactor the GelsightSensor transform method to customize resize scale or normalization parameters', 'create an OmnitactSensor instance with a data source and optional data path', 'build a torchvision transform pipeline that resizes to 64x64, converts to tensor, and normalizes', 'review the OmnitactSensorDefaults class constants for image scale, mean, and standard deviation values', 'test the OmnitactSensor zoo_name static method to verify it returns the correct sensor identifier', 'refactor the OmnitactSensor transform method to customize resize scales or normalization parameters']
```

Usage

```
{'init_sensorbase': 'create a SensorBase instance with a sensor name, data source type, and optional data path', 'sensorbase_name': "call the name method on a SensorBase instance to retrieve the sensor's name string", 'sensorbase_repr': 'get the string representation of a SensorBase instance showing sensor name, data source, and data path', 'sensorbase_validate_dataset': 'instantiate a SensorBase with DATASET data source to validate that a data path is required', 'sensorbase_validate_video': 'instantiate a SensorBase with VIDEO data source to validate that a data path is required'}
```

## File: facebookresearch_pytouch/pytouch/sensors/digit.py

Prompts

```
['create a SensorBase instance with a sensor name, data source type, and optional data path', "call the name method on a SensorBase instance to retrieve the sensor's name string", 'get the string representation of a SensorBase instance showing sensor name, data source, and data path', 'instantiate a SensorBase with DATASET data source to validate that a data path is required', 'instantiate a SensorBase with VIDEO data source to validate that a data path is required', 'create a DigitSensor instance with a data source and optional custom transform pipeline', 'build a composed torchvision transform pipeline that resizes to 64x64, converts to tensor, and normalizes', 'review the DigitSensorDefaults class with SCALES, MEANS, and STDS constants for image normalization', 'test the DigitSensor zoo_name static method that returns the string DigitSensor', 'refactor the DigitSensor constructor to accept a custom transform or use the default composed pipeline', 'create a GelsightSensor instance with a data source and optional data path', 'build a torchvision transform pipeline that resizes to 64x64 and normalizes using ImageNet stats', 'review the GelsightSensorDefaults class for default scale, mean, and standard deviation values', 'test the GelsightSensor zoo_name static method returns the string GelSightSensor', 'refactor the GelsightSensor transform method to customize resize scale or normalization parameters', 'create an OmnitactSensor instance with a data source and optional data path', 'build a torchvision transform pipeline that resizes to 64x64, converts to tensor, and normalizes', 'review the OmnitactSensorDefaults class constants for image scale, mean, and standard deviation values', 'test the OmnitactSensor zoo_name static method to verify it returns the correct sensor identifier', 'refactor the OmnitactSensor transform method to customize resize scales or normalization parameters']
```

Usage

```
{'create_DigitSensor': 'create a DigitSensor instance with a data source and optional custom transform pipeline', 'build_DigitSensor_transform': 'build a composed torchvision transform pipeline that resizes to 64x64, converts to tensor, and normalizes', 'review_DigitSensorDefaults': 'review the DigitSensorDefaults class with SCALES, MEANS, and STDS constants for image normalization', 'test_DigitSensor_zoo_name': 'test the DigitSensor zoo_name static method that returns the string DigitSensor', 'refactor_DigitSensor_init': 'refactor the DigitSensor constructor to accept a custom transform or use the default composed pipeline'}
```

## File: facebookresearch_pytouch/pytouch/sensors/gelsight.py

Prompts

```
['create a SensorBase instance with a sensor name, data source type, and optional data path', "call the name method on a SensorBase instance to retrieve the sensor's name string", 'get the string representation of a SensorBase instance showing sensor name, data source, and data path', 'instantiate a SensorBase with DATASET data source to validate that a data path is required', 'instantiate a SensorBase with VIDEO data source to validate that a data path is required', 'create a DigitSensor instance with a data source and optional custom transform pipeline', 'build a composed torchvision transform pipeline that resizes to 64x64, converts to tensor, and normalizes', 'review the DigitSensorDefaults class with SCALES, MEANS, and STDS constants for image normalization', 'test the DigitSensor zoo_name static method that returns the string DigitSensor', 'refactor the DigitSensor constructor to accept a custom transform or use the default composed pipeline', 'create a GelsightSensor instance with a data source and optional data path', 'build a torchvision transform pipeline that resizes to 64x64 and normalizes using ImageNet stats', 'review the GelsightSensorDefaults class for default scale, mean, and standard deviation values', 'test the GelsightSensor zoo_name static method returns the string GelSightSensor', 'refactor the GelsightSensor transform method to customize resize scale or normalization parameters', 'create an OmnitactSensor instance with a data source and optional data path', 'build a torchvision transform pipeline that resizes to 64x64, converts to tensor, and normalizes', 'review the OmnitactSensorDefaults class constants for image scale, mean, and standard deviation values', 'test the OmnitactSensor zoo_name static method to verify it returns the correct sensor identifier', 'refactor the OmnitactSensor transform method to customize resize scales or normalization parameters']
```

Usage

```
{'create_gelsight_sensor': 'create a GelsightSensor instance with a data source and optional data path', 'build_gelsight_transform': 'build a torchvision transform pipeline that resizes to 64x64 and normalizes using ImageNet stats', 'review_gelsight_defaults': 'review the GelsightSensorDefaults class for default scale, mean, and standard deviation values', 'test_gelsight_zoo_name': 'test the GelsightSensor zoo_name static method returns the string GelSightSensor', 'refactor_gelsight_transform': 'refactor the GelsightSensor transform method to customize resize scale or normalization parameters'}
```

## File: facebookresearch_pytouch/pytouch/sensors/omnitact.py

Prompts

```
['create a SensorBase instance with a sensor name, data source type, and optional data path', "call the name method on a SensorBase instance to retrieve the sensor's name string", 'get the string representation of a SensorBase instance showing sensor name, data source, and data path', 'instantiate a SensorBase with DATASET data source to validate that a data path is required', 'instantiate a SensorBase with VIDEO data source to validate that a data path is required', 'create a DigitSensor instance with a data source and optional custom transform pipeline', 'build a composed torchvision transform pipeline that resizes to 64x64, converts to tensor, and normalizes', 'review the DigitSensorDefaults class with SCALES, MEANS, and STDS constants for image normalization', 'test the DigitSensor zoo_name static method that returns the string DigitSensor', 'refactor the DigitSensor constructor to accept a custom transform or use the default composed pipeline', 'create a GelsightSensor instance with a data source and optional data path', 'build a torchvision transform pipeline that resizes to 64x64 and normalizes using ImageNet stats', 'review the GelsightSensorDefaults class for default scale, mean, and standard deviation values', 'test the GelsightSensor zoo_name static method returns the string GelSightSensor', 'refactor the GelsightSensor transform method to customize resize scale or normalization parameters', 'create an OmnitactSensor instance with a data source and optional data path', 'build a torchvision transform pipeline that resizes to 64x64, converts to tensor, and normalizes', 'review the OmnitactSensorDefaults class constants for image scale, mean, and standard deviation values', 'test the OmnitactSensor zoo_name static method to verify it returns the correct sensor identifier', 'refactor the OmnitactSensor transform method to customize resize scales or normalization parameters']
```

Usage

```
{'create_omnitact_sensor': 'create an OmnitactSensor instance with a data source and optional data path', 'build_omnitact_transform': 'build a torchvision transform pipeline that resizes to 64x64, converts to tensor, and normalizes', 'review_omnitact_sensor_defaults': 'review the OmnitactSensorDefaults class constants for image scale, mean, and standard deviation values', 'test_omnitact_zoo_name': 'test the OmnitactSensor zoo_name static method to verify it returns the correct sensor identifier', 'refactor_omnitact_transform': 'refactor the OmnitactSensor transform method to customize resize scales or normalization parameters'}
```

