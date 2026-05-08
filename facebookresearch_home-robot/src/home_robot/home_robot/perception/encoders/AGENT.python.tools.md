# Agent Python Tools

- repo: facebookresearch/home-robot
- repo_uri: https://github.com/facebookresearch/home-robot

## File: facebookresearch_home-robot/src/home_robot/home_robot/perception/encoders/base_encoder.py

Prompts

```
['review the BaseImageTextEncoder abstract base class and its encode_image and encode_text stub methods', 'summarize the BaseImageTextEncoder class which defines an interface for encoding images and text', 'refactor the BaseImageTextEncoder encode_image method to accept numpy arrays or torch tensors', 'refactor the BaseImageTextEncoder encode_text method to process string input into embeddings', 'review the BaseImageTextEncoder interface that requires subclasses to implement encode_image and encode_text', 'create a ClipEncoder instance with the default ViT-B/32 model on the available device', 'encode a numpy array image into a CLIP feature vector using ClipEncoder', 'encode a text string into a CLIP feature vector using ClipEncoder', 'review the ClipEncoder class initialization to understand model version and device selection', 'refactor the ClipEncoder to support a custom device string for model loading', 'encode an image using the HomeRobotMTMEncoder to get a visual embedding vector', 'encode a text string using the HomeRobotMTMEncoder to get a text embedding vector', 'load a VC model by name from config YAML files using the load_vc function', 'test the HomeRobotMTMEncoder by encoding a random image and text string', 'tokenize text strings using the ClipTokenizerWrapper with CLIP truncation']
```

Usage

```
{'review_BaseImageTextEncoder': 'review the BaseImageTextEncoder abstract base class and its encode_image and encode_text stub methods', 'summarize_BaseImageTextEncoder': 'summarize the BaseImageTextEncoder class which defines an interface for encoding images and text', 'refactor_BaseImageTextEncoder_encode_image': 'refactor the BaseImageTextEncoder encode_image method to accept numpy arrays or torch tensors', 'refactor_BaseImageTextEncoder_encode_text': 'refactor the BaseImageTextEncoder encode_text method to process string input into embeddings', 'review_BaseImageTextEncoder_interface': 'review the BaseImageTextEncoder interface that requires subclasses to implement encode_image and encode_text'}
```

## File: facebookresearch_home-robot/src/home_robot/home_robot/perception/encoders/clip_encoder.py

Prompts

```
['review the BaseImageTextEncoder abstract base class and its encode_image and encode_text stub methods', 'summarize the BaseImageTextEncoder class which defines an interface for encoding images and text', 'refactor the BaseImageTextEncoder encode_image method to accept numpy arrays or torch tensors', 'refactor the BaseImageTextEncoder encode_text method to process string input into embeddings', 'review the BaseImageTextEncoder interface that requires subclasses to implement encode_image and encode_text', 'create a ClipEncoder instance with the default ViT-B/32 model on the available device', 'encode a numpy array image into a CLIP feature vector using ClipEncoder', 'encode a text string into a CLIP feature vector using ClipEncoder', 'review the ClipEncoder class initialization to understand model version and device selection', 'refactor the ClipEncoder to support a custom device string for model loading', 'encode an image using the HomeRobotMTMEncoder to get a visual embedding vector', 'encode a text string using the HomeRobotMTMEncoder to get a text embedding vector', 'load a VC model by name from config YAML files using the load_vc function', 'test the HomeRobotMTMEncoder by encoding a random image and text string', 'tokenize text strings using the ClipTokenizerWrapper with CLIP truncation']
```

Usage

```
{'create_clip_encoder': 'create a ClipEncoder instance with the default ViT-B/32 model on the available device', 'encode_image_clip_vector': 'encode a numpy array image into a CLIP feature vector using ClipEncoder', 'encode_text_clip_vector': 'encode a text string into a CLIP feature vector using ClipEncoder', 'review_clip_encoder_init': 'review the ClipEncoder class initialization to understand model version and device selection', 'refactor_clip_encoder_device': 'refactor the ClipEncoder to support a custom device string for model loading'}
```

## File: facebookresearch_home-robot/src/home_robot/home_robot/perception/encoders/mtm_encoder.py

Prompts

```
['review the BaseImageTextEncoder abstract base class and its encode_image and encode_text stub methods', 'summarize the BaseImageTextEncoder class which defines an interface for encoding images and text', 'refactor the BaseImageTextEncoder encode_image method to accept numpy arrays or torch tensors', 'refactor the BaseImageTextEncoder encode_text method to process string input into embeddings', 'review the BaseImageTextEncoder interface that requires subclasses to implement encode_image and encode_text', 'create a ClipEncoder instance with the default ViT-B/32 model on the available device', 'encode a numpy array image into a CLIP feature vector using ClipEncoder', 'encode a text string into a CLIP feature vector using ClipEncoder', 'review the ClipEncoder class initialization to understand model version and device selection', 'refactor the ClipEncoder to support a custom device string for model loading', 'encode an image using the HomeRobotMTMEncoder to get a visual embedding vector', 'encode a text string using the HomeRobotMTMEncoder to get a text embedding vector', 'load a VC model by name from config YAML files using the load_vc function', 'test the HomeRobotMTMEncoder by encoding a random image and text string', 'tokenize text strings using the ClipTokenizerWrapper with CLIP truncation']
```

Usage

```
{'encode_image_mtm': 'encode an image using the HomeRobotMTMEncoder to get a visual embedding vector', 'encode_text_mtm': 'encode a text string using the HomeRobotMTMEncoder to get a text embedding vector', 'load_vc_model': 'load a VC model by name from config YAML files using the load_vc function', 'test_mtm_encoder': 'test the HomeRobotMTMEncoder by encoding a random image and text string', 'tokenize_clip_texts': 'tokenize text strings using the ClipTokenizerWrapper with CLIP truncation'}
```

